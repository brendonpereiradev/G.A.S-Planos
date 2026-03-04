# Plano de Execução: Auditoria e Testes Finais

**Agente Responsável:** `project-planner`
**Objetivo:** Executar testes de performance simulando diversos dispositivos (mobile, desktop, notebook), buscar bugs técnicos/visuais e higienizar o código removendo funções e classes não utilizadas.

---

## 🛑 Socratic Gate (Fase 0 - Verificação de Contexto)
Antes de iniciarmos os testes e a remoção de código, preciso confirmar alguns pontos:
1. **Ambiente de Teste:** Os testes de performance (Lighthouse e carregamento) devem basear-se puramente no servidor local (`127.0.0.1:5500`) ou já temos uma URL online da AWS para obtermos dados realistas da latência de rede? 
2. **Remoção de Código:** Ao higienizar as classes e funções não utilizadas (dead code), existe alguma seção temporariamente oculta no HTML ou funcionalidade em construção que devo manter intacta no CSS/JS?
3. **Profundidade:** Deseja que eu inicie rodando a automação dos scripts como `checklist.py`, `lighthouse_audit.py` e `ux_audit.py` ou prefere que a auditoria seja primeiramente focada num tracking manual via ferramentas do navegador (como o painel de Coverage/Cobertura do Chrome)?

---

## 📝 Task Breakdown

### Phase 1: Testes de Performance e Responsividade
- [ ] Executar testes Lighthouse em modo **Mobile** (320px/360px) simulando estrangulamento de CPU/Rede.
- [ ] Executar testes Lighthouse em modo **Notebook** (1280px/1366px) e **Desktop** (1920px+).
- [ ] Registrar principais métricas: LCP (Largest Contentful Paint), CLS (Cumulative Layout Shift) e TBT (Total Blocking Time).
- [ ] Rodar auditoria para garantir o funcionamento com a nova aceleração de GPU aplicada no header e as imagens OpenGraph.

### Phase 2: Varredura de Código Inutilizado (Limpeza)
- [ ] Inspecionar `styles.css` em busca de classes orfãs (ex: regras antigas para animações revogadas, regras específicas para ícones substituídos).
- [ ] Inspecionar `script.js` em busca de event listeners ou blocos lógicos soltos oriundos das edições anteriores (ex: lógica das tags `<button>` vs `<div>` do menu de acessibilidade caso ainda existam rastros nulos).
- [ ] Revisão do HTML em busca de tags vazias ou meta tags em duplicidade.

### Phase 3: Caça a Bugs Visuais e Técnicos
- [ ] Teste mecânico nos botões de âncora e botões de Contato (WhatsApp link).
- [ ] Verificação do comportamento visual de alinhamento em todos os viewports (`@media` boundaries: 576px, 768px, 992px, 1200px).
- [ ] Confirmação de que o texto e formulários estão consistentes nas transições de Layout e Glassmorphism.

### Phase 4: Implementação de Fixes
- [ ] Remover e refatorar todo o código obsoleto detectado.
- [ ] Aplicar correções para avisos, se encontrados nos testes.

---

## 🏁 Phase X: Verificação (Checklist Final)
- [ ] UX Audit validada para Mobile, Tablet, Notebook e Ultra-wide.
- [ ] Validação do Linter (CSS/HTML e JS).
- [ ] Todos os números da Hero Section centralizados nos 3 cenários (1, 2 ou 3 caracteres).
