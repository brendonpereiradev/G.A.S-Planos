<p align="center">
  <img src="assets/GAS-logos/gas-logo-nobg.png" alt="GAS Corretora" width="200">
</p>

<h1 align="center">G.A.S Planos</h1>

<p align="center">
  Landing page para corretor autorizado de planos de saúde Prevent Senior no Rio de Janeiro e São Paulo.
</p>

<p align="center">
  <a href="https://gasplanos.com.br" target="_blank"><strong>gasplanos.com.br</strong></a>
</p>

---

## Sobre o projeto

**G.A.S Planos** é uma landing page de alta conversão desenvolvida para um corretor autorizado da Prevent Senior. O site tem como objetivo principal a captação de leads e a conversão de vendas de planos de saúde, oferecendo uma experiência de navegação premium (Glassmorphism e Dark Mode) para o público do Rio de Janeiro e São Paulo.

A estrutura da página funciona como um funil de conversão direto, guiando o visitante desde a proposta de valor inicial até o contato com o consultor via WhatsApp, sem atritos.

---

## Funcionalidades

| Feature | Descrição |
|---|---|
| **Hero com social proof** | Barra de visualizações em tempo real + estatísticas de unidades e experiência |
| **Tabela de preços modular** | Cards com faixas etárias e valores, contraste otimizado para leitura rápida |
| **Rede credenciada dual-geo** | Carrossel infinito com unidades RJ e SP, hospitais, laboratórios e clínicas parceiras |
| **Conversão via WhatsApp** | Floating button, CTAs no menu mobile e header: todos pré-preenchidos para contato instantâneo |
| **FAQ interativo** | Accordion com Schema.org `FAQPage` para destaque em resultados do Google |
| **Widget de acessibilidade** | Controles de tamanho de fonte (aumentar, diminuir, resetar) |
| **Menu mobile premium** | Drawer lateral com overlay, stagger animations, horário de funcionamento e CTA integrado |
| **Páginas legais** | Política de Privacidade e Termos de Uso em páginas dedicadas |

---

## Stack

O projeto é construído com uma stack leve e de alta performance, sem dependência de frameworks:

- **HTML5 semântico**: Estrutura otimizada para SEO (Schema.org, Open Graph, meta tags) e acessibilidade
- **CSS3 vanilla**: Variáveis customizadas, Flexbox/Grid, Glassmorphism (`backdrop-filter`), tipografia fluida com `clamp()`, responsivo do mobile ao ultrawide (4K+)
- **JavaScript ES6+**: Intersection Observer para fade-ins, FAQ accordion, carrossel de unidades, header scroll effect, social proof dinâmico
- **Google Tag Manager**: Rastreamento de conversões e analytics
- **Assets otimizados**: Imagens WebP, SVGs inline, favicon e apple-touch-icon

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

## Seções da landing page

1. **Hero / header**: Proposta de valor, CTAs de conversão e estatísticas
2. **Benefícios**: Vantagens exclusivas da Prevent Senior (rede própria, sem reajuste 44+, etc.)
3. **Unidades (hospitais)**: Carrossel com rede própria RJ e SP
4. **Tabela de preços**: Transparência financeira com valores por faixa etária
5. **Diferenciais e social proof**: Parcerias com laboratórios e selos de conformidade
6. **FAQ**: Perguntas frequentes com accordion interativo
7. **Footer**: Informações institucionais, registro ANS e canais de atendimento

---

## Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/brendonpereiradev/G.A.S-Planos.git
   ```

2. Abra com um servidor local (ex: Live Server no VS Code) ou diretamente no navegador:
   ```
   http://127.0.0.1:5500/index.html
   ```

> **Nota**: O projeto não possui dependências de build, pois utiliza HTML, CSS e JavaScript puro.

---

## SEO e performance

- Schema.org (`MedicalBusiness`, `InsuranceAgency`, `FAQPage`)
- Open Graph completo para compartilhamento social
- Meta tags otimizadas (title, description, canonical)
- Content Security Policy (CSP) via meta tag
- `robots.txt` e `sitemap.xml` configurados
- Tipografia fluida com `clamp()`, sem breakpoints fixos
- Imagens WebP e SVGs para carregamento rápido

---

<p align="center">
  Desenvolvido por <strong>B2M Solutions</strong>
</p>
