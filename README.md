<p align="center">
  <img src="assets/GAS-logos/gas-logo-nobg.png" alt="GAS Corretora" width="200">
</p>

<h1 align="center">G.A.S Planos — Prevent Senior</h1>

<p align="center">
  Landing page desenvolvida para um corretor de seguros focado na venda de planos de saúde Prevent Senior no Rio de Janeiro e São Paulo.
</p>

<p align="center">
  <a href="https://gasplanos.com.br" target="_blank"><strong>gasplanos.com.br</strong></a>
</p>

---

## Sobre o Projeto

**G.A.S Planos** é uma landing page de alta conversão desenvolvida para a **GAS Corretora de Seguros**, corretora autorizada pela Prevent Senior. O site tem como objetivo principal a captação de leads e conversão de vendas, oferecendo uma experiência de navegação premium (Glassmorphism + Dark Mode) para o público do Rio de Janeiro e São Paulo.

A estrutura da página funciona como um funil de conversão direto, guiando o visitante desde a proposta de valor inicial até o contato com o consultor via WhatsApp, sem atritos.

---

## Funcionalidades

| Feature | Descrição |
|---|---|
| **Hero com Social Proof** | Barra de visualizações em tempo real + estatísticas de unidades e experiência |
| **Tabela de Preços Modular** | Cards com faixas etárias e valores, contraste otimizado para leitura rápida |
| **Rede Credenciada Dual-Geo** | Carrossel infinito com unidades RJ e SP, hospitais, laboratórios e clínicas parceiras |
| **WhatsApp Conversion Engine** | Floating button, CTAs no menu mobile e header — todos pré-preenchidos para contato instantâneo |
| **FAQ Interativo** | Accordion com Schema.org `FAQPage` para destaque em resultados do Google |
| **Widget de Acessibilidade** | Controles de tamanho de fonte (aumentar, diminuir, resetar) |
| **Menu Mobile Premium** | Drawer lateral com overlay, stagger animations, horário de funcionamento e CTA integrado |
| **Páginas Legais** | Política de Privacidade e Termos de Uso em páginas dedicadas |

---

## Stack Tecnológica

O projeto é construído com uma stack leve e de alta performance, sem dependência de frameworks:

- **HTML5 Semântico** — Estrutura otimizada para SEO (Schema.org, Open Graph, meta tags) e acessibilidade
- **CSS3 Vanilla** — Variáveis customizadas, Flexbox/Grid, Glassmorphism (`backdrop-filter`), tipografia fluida com `clamp()`, responsivo do mobile ao ultrawide (4K+)
- **JavaScript ES6+** — Intersection Observer para fade-ins, FAQ accordion, carrossel de unidades, header scroll effect, social proof dinâmico
- **Google Tag Manager** — Rastreamento de conversões e analytics
- **Assets Otimizados** — Imagens WebP, SVGs inline, favicon e apple-touch-icon

---

## Estrutura do Projeto

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

## Seções da Landing Page

1. **Hero / Header** — Proposta de valor, CTAs de conversão e estatísticas
2. **Benefícios** — Vantagens exclusivas da Prevent Senior (rede própria, sem reajuste 44+, etc.)
3. **Unidades (Hospitais)** — Carrossel com rede própria RJ e SP
4. **Tabela de Preços** — Transparência financeira com valores por faixa etária
5. **Diferenciais e Social Proof** — Parcerias com laboratórios e selos de conformidade
6. **FAQ** — Perguntas frequentes com accordion interativo
7. **Contato e Footer** — Informações da corretora, CNPJ, registro ANS e canais de atendimento

---

## Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/brendonpereiradev/G.A.S-Planos.git
   ```

2. Abra com um servidor local (ex: Live Server no VS Code) ou diretamente no navegador:
   ```
   http://127.0.0.1:5500/index.html
   ```

> **Nota:** O projeto não possui dependências de build — é HTML, CSS e JS puro.

---

## SEO e Performance

- Schema.org (`MedicalBusiness`, `InsuranceAgency`, `FAQPage`)
- Open Graph completo para compartilhamento social
- Meta tags otimizadas (title, description, canonical)
- Content Security Policy (CSP) via meta tag
- `robots.txt` e `sitemap.xml` configurados
- Tipografia fluida com `clamp()` — sem breakpoints fixos
- Imagens WebP e SVGs para carregamento rápido

---

<p align="center">
  Desenvolvido por <strong>B2M Solutions</strong>
</p>
