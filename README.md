<h1 align="center">G.A.S Planos</h1>

<p align="center">
  Landing page para corretor autorizado da Prevent Senior no Rio de Janeiro e em São Paulo.
</p>

<p align="center">
  <a href="https://gasplanos.com.br" target="_blank">gasplanos.com.br</a>
</p>

## Sobre o projeto

Landing page desenvolvida para corretor autorizado da Prevent Senior com atuação no Rio de Janeiro e em São Paulo. O site apresenta os planos disponíveis, a tabela de valores e a rede credenciada, direcionando o visitante para atendimento direto pelo WhatsApp.

## Funcionalidades

- Apresentação inicial com contagem de visualizações e dados da corretora
- Tabela de preços organizada por faixa etária
- Carrossel com a rede credenciada e hospitais próprios do Rio de Janeiro e de São Paulo
- Botões de contato direto via WhatsApp no cabeçalho, no menu e em botão flutuante
- Seção de perguntas frequentes em formato sanfona (accordion) com marcação Schema.org
- Ajuste de tamanho de fonte na página
- Menu lateral para dispositivos móveis com horário de atendimento
- Páginas de Política de Privacidade e Termos de Uso

## Tecnologias

O projeto foi desenvolvido sem frameworks ou bibliotecas externas pesadas:

- HTML5 com tags semânticas e marcação para buscadores (Schema.org e Open Graph)
- CSS3 puro com variáveis, Flexbox, Grid e layout responsivo
- JavaScript moderno para animações de rolagem, sanfona do FAQ e carrossel
- Google Tag Manager para métricas e rastreamento
- Imagens em formato WebP e ícones em SVG

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

## Seções da página

1. Apresentação inicial e chamada para contato
2. Vantagens do plano (rede própria e regras de reajuste)
3. Unidades hospitalares no Rio de Janeiro e em São Paulo
4. Tabela de valores por faixa etária
5. Laboratórios parceiros e credenciamento
6. Perguntas frequentes
7. Rodapé com dados de registro na ANS e canais de atendimento

## SEO e desempenho

- Estrutura de dados Schema.org (`MedicalBusiness`, `InsuranceAgency`, `FAQPage`)
- Metadados Open Graph para pré-visualização em redes sociais
- Meta tags de título, descrição e URL canônica
- Cabeçalhos básicos de Content Security Policy (CSP)
- Arquivos `robots.txt` e `sitemap.xml`
- Imagens leves em WebP e SVG

## Licença e uso

Este repositório foi publicado para fins de demonstração de portfólio. As marcas, logotipos e conteúdos pertencem aos seus respectivos proprietários, não sendo permitida a utilização comercial sem autorização prévia.

Desenvolvido por B2M Solutions.
