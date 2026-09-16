<h1 align="center">G.A.S Planos</h1>

<p align="center">
  Landing page para corretor autorizado da Prevent Senior no Rio de Janeiro e em São Paulo.
</p>

<p align="center">
  <a href="https://gasplanos.com.br" target="_blank">gasplanos.com.br</a>
</p>

---

## Sobre o projeto

Landing page desenvolvida para corretor autorizado da Prevent Senior com atuação no Rio de Janeiro e em São Paulo. O site apresenta os planos disponíveis, a tabela de valores e a rede credenciada, direcionando o visitante para atendimento direto pelo WhatsApp.

---

## Funcionalidades

| Recurso | Descrição |
| --- | --- |
| Barra de prova social | Contador no topo da página com simulação de visitantes simultâneos |
| Formulário de cotação | Coleta rápida de dados com direcionamento de mensagem pronta para o WhatsApp |
| Tabela de preços | Valores organizados por faixa etária para planos de enfermaria e apartamento |
| Carrossel de unidades | Exibição de hospitais próprios no Rio de Janeiro e em São Paulo com rotação automática e suporte a toque |
| Rede credenciada | Apresentação de hospitais e laboratórios parceiros em destaque |
| Perguntas frequentes (FAQ) | Seção em formato sanfona com respostas expansíveis e marcação Schema.org |
| Controle de acessibilidade | Ajuste no tamanho da fonte da página com preferência salva no navegador |
| Menu móvel lateral | Gaveta de navegação para telas menores com horários de atendimento e bloqueio de rolagem |
| Botão flutuante | Atalho fixo na tela para contato direto pelo WhatsApp |
| Páginas institucionais e legais | Documentos de política de privacidade, termos de uso e página de erro 404 personalizada |

---

## Stack

O projeto utiliza tecnologias nativas da web, sem frameworks pesados, com foco em desempenho e carregamento rápido:

- **HTML5**: Estrutura semântica com metadados Open Graph e marcação estruturada Schema.org em JSON-LD
- **CSS3**: Estilização com variáveis customizadas, Flexbox, Grid e layout responsivo
- **JavaScript (Vanilla ES6+)**: Manipulação do DOM, controle de carrossel infinito, sanfona de dúvidas, geolocalização e persistência no navegador
- **Google Tag Manager**: Gerenciamento de tags, coleta de métricas e rastreamento de conversões
- **WebP e SVG**: Formatos compactos de imagens e ícones vetoriais escaláveis

---

## Estrutura do projeto

```
G.A.S Planos/
├── assets/
│   ├── GAS-logos/           # Logos da corretora (SVG, PNG, ICO)
│   ├── cred-*.{png,svg,jpg} # Logos da rede credenciada (hospitais e laboratórios)
│   ├── unidade-rj-*.jpg     # Fotos das unidades no Rio de Janeiro
│   ├── unidade-sp-*.jpg     # Fotos das unidades em São Paulo
│   └── logo-prevent-senior.webp
├── docs/
│   └── README.md            # Documentação técnica detalhada
├── index.html               # Página principal (landing page)
├── error.html               # Página de erro personalizada
├── politica-de-privacidade.html
├── termos-de-uso.html
├── styles.css               # Estilos globais
├── script.js                # Lógica de interação e UI
├── robots.txt               # Configuração de crawlers
├── sitemap.xml              # Mapa do site para SEO
└── README.md                # Este arquivo
```

---

## Seções da página

1. Apresentação inicial e chamada para contato
2. Vantagens do plano (rede própria e regras de reajuste)
3. Unidades hospitalares no Rio de Janeiro e em São Paulo
4. Tabela de valores por faixa etária
5. Laboratórios parceiros e credenciamento
6. Perguntas frequentes
7. Rodapé com dados de registro na ANS e canais de atendimento

---

## SEO e desempenho

- Estrutura de dados Schema.org (`MedicalBusiness`, `InsuranceAgency`, `FAQPage`)
- Metadados Open Graph para pré-visualização em redes sociais
- Meta tags de título, descrição e URL canônica
- Cabeçalhos básicos de Content Security Policy (CSP)
- Arquivos `robots.txt` e `sitemap.xml`
- Imagens leves em WebP e SVG

---

## Licença e uso

Este repositório foi publicado para fins de demonstração de portfólio. As marcas, logotipos e conteúdos pertencem aos seus respectivos proprietários, não sendo permitida a utilização comercial sem autorização prévia.

---

<p align="center">
  Desenvolvido por <strong>B2M Solutions</strong>
</p>
