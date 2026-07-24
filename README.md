# LP Mundo Animal · Clínica Veterinária 24h

Landing pages de conversão da **Mundo Animal — Clínica Veterinária e Pet Shop** (Goiânia/GO).
Páginas únicas em HTML + CSS + JS (sem frameworks), responsivas e otimizadas para desktop e mobile.

## Estrutura

```
.
├── index.html              # LP Clínica 24h / Emergência (raiz)
├── assets/
│   ├── hero.png            # Imagem de fundo do hero (desktop)
│   ├── hero-mobile.png     # Imagem de fundo do hero (mobile)
│   ├── logo-verde.png      # Logo para fundo claro
│   ├── logo-branca.png     # Logo para o rodapé
│   └── carrossel/          # Fotos da estrutura (01.jpg … 14.jpg)
└── banho-e-tosa/           # LP Banho e Tosa (autocontida)
    ├── index.html
    └── assets/             # Subconjunto dos assets, copiado para a pasta ser independente
```

## LPs

### 1. Clínica Veterinária 24h — `index.html`
Publicada em **emergencia.mundoanimalvet.com.br**.

- Hero com bifurcação de públicos: **emergência 24h** (ligação direta) e **agendamento de rotina**.
- Telefone: **(62) 98189-0399**.
- Cards de serviço clínico, pilares de diferenciais e carrossel de estrutura.

### 2. Banho e Tosa — `banho-e-tosa/index.html`
Substitui a página `mundoanimalvet.com.br/especialidades/banho-e-tosa/`.

- Mesmo design system da LP da clínica (tokens, tipografia Figtree, componentes e animações).
- Hero com bifurcação: **agendar pelo WhatsApp** e **ligar agora**.
- Telefone/WhatsApp próprios do banho e tosa: **(62) 98240-0542**.
- CTAs de WhatsApp apontam para o link rastreado da Tintim já usado na página atual.
- Seções: hero, números, 6 serviços (banho, tosa, hidratação, com amor, UberDog, pacotes),
  pilares, **como funciona** (3 passos), carrossel, depoimentos, sobre, faixa de destaque, formulário e rodapé.
- As UTMs da URL são repassadas automaticamente para os links de WhatsApp (`a.js-wa`), preservando o rastreio do Google Ads.

## Publicação

Servida via **GitHub Pages** a partir do `index.html` na raiz.
Para rodar localmente, basta abrir o `index.html` no navegador (ou servir a pasta com qualquer servidor estático).

> Observação: em **ambas** as LPs a seção de depoimentos usa textos placeholder até a inserção das avaliações reais.
