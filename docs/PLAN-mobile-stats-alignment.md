# Plano de Implementação: Alinhamento das Estatísticas no Mobile

**Project Type**: WEB
**Success Criteria**: Os números da seção hero no mobile (5, 40+, 25+) deverão estar alinhados perfeitamente pelo eixo do meio dos números, independentemente de possuírem o carácter '+' na frente, sem que o texto descritivo seja comprometido no seu próprio centro.

## 1. Overview
O usuário identificou através de testes (com uma linha guia perpendicular) que os números maiores (40, 25) ficam descentralizados visualmente à esquerda, uma vez que o caractere '+' também é processado pelo alinhamento de texto centralizado (`text-align: center`), deslocando o eixo central das dezenas. O objetivo é remover o '+' do cálculo de alinhamento principal do número.

## 2. Tech Stack
- HTML5 (Estruturação de container/wrapper)
- CSS3 (Variáveis, Flexbox, ou posicionamento absoluto via `:after` / `.stat-accent`)

## 3. File Structure
Neste projeto, não serão criados novos arquivos. Apenas faremos as edições em:
- `index.html` (para verificar se há tags de bloco dedicadas)
- `styles.css` (onde se encontram  `.stat-number` e `.stat-accent` ou equivalente nas media queries mobiles)

## 4. Task Breakdown

### Tarefa 1: Avaliar Estrutura HTML do `.hero-stats`
- **Agent:** `frontend-specialist`
- **Skill:** `frontend-design`
- **Por que:** Precisamos checar a organização (se o `+` está dentro de um div separado como `.stat-accent`).
- **INPUT:** `c:\Users\Admin\Documents\Projects\Antigravity Projects\G.A.S Planos\index.html` e `styles.css`
- **OUTPUT:** Diagnóstico visual e entendimento de onde atuar.
- **VERIFY:** Ler a classe exata dos números e do +.

### Tarefa 2: Isolar o sinal (+) do Fluxo Principal (Mobile CSS)
- **Agent:** `frontend-specialist`
- **Skill:** `frontend-design`
- **Por que:** Para que o `text-align: center` se aplique apenas à unidade numerária. 
- **INPUT:** `c:\Users\Admin\Documents\Projects\Antigravity Projects\G.A.S Planos\styles.css`
- **OUTPUT:** O caractere `+` passa a ter `position: absolute` na media query mobile.
- **VERIFY:** O número real (5, 40, 25) deve alinhar pelo seu próprio centro, centralizando os elementos verticalmente ao meio com a linha descritiva também no meio. O `+` deve flutuar à direita da palavra sem quebrar layout.

### Tarefa 3: Revisão do Responsive e Ajustes Matemáticos
- **Agent:** `frontend-specialist`
- **Skill:** `frontend-design`
- **Por que:** Evitar bugs com tamanhos de tela (`margin-left` relativo, espaçamento manual do absolutes, container parent setado para `position: relative`).
- **INPUT:** Visualização no navegador e código atualizado.
- **OUTPUT:** Valores matemáticos finamente ajustados (`transform: translateX`, ou offset absoluto coerente).
- **VERIFY:** Testar F12 (Mobile Viewports - 320px até 768px).

---

## 5. Phase X: Verificação Final
- [ ] O Socratic Gate foi respeitado? (Fizemos as averiguações essenciais na geração do plano).
- [ ] Nenhuma paleta de cor proibida / `violet`/`purple` foi introduzida.
- [ ] Rodar auditoria de UI local abrindo a porta do Live Server e analisando as alterações à exaustão em iPhone SE e Pro Max dimensões.

## ✅ PHASE X COMPLETE
- UX/UI Audit: (Pendente de Teste)
- Build: N/A
- Date: 2026-03-04
