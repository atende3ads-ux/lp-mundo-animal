# LP Mundo Animal · Clínica Veterinária 24h

Landing pages de conversão da **Mundo Animal — Clínica Veterinária e Pet Shop** (Goiânia/GO).
Páginas únicas em HTML + CSS + JS (sem frameworks), responsivas e otimizadas para desktop e mobile.

## Estrutura

```
.
├── index.html              # LP Clínica 24h / Emergência (raiz)
├── assets/
│   ├── hero.jpg            # Imagem de fundo do hero (desktop)
│   ├── hero-mobile.jpg     # Imagem de fundo do hero (mobile)
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
Publicada em **estetica.mundoanimalvet.com.br**.

- Mesmo design system da LP da clínica (tokens, tipografia Figtree, componentes e animações).
- Hero com bifurcação: **agendar pelo WhatsApp** e **ligar agora**.
- Telefone/WhatsApp próprios do banho e tosa: **(62) 98240-0542**.
- Links de WhatsApp apontam para `https://wa.me/5562942633340`.
- Seções: hero, números, 6 serviços (banho, tosa, hidratação, com amor, UberDog, pacotes),
  pilares, **como funciona** (3 passos), carrossel, depoimentos, sobre, faixa de destaque, formulário e rodapé.
- O formulário ainda aponta para a TinTim: sua migração exige definir o destino e o tratamento dos campos. A troca dos links não comprova atribuição de UTMs no WhatsApp.

## Publicação

As LPs oficiais são servidas no cPanel da conta `mundoa24`. O `.cpanel.yml` copia os arquivos do repositório para as raízes dos dois subdomínios, preservando os arquivos exclusivos do servidor. Após o push, o responsável pela publicação precisa executar **Update from Remote** e **Deploy HEAD Commit** no Git Version Control e verificar as duas URLs públicas.

Para rodar localmente, sirva a raiz do repositório com um servidor estático e abra `/` (Emergência) e `/banho-e-tosa/` (Estética).

> Observação: em **ambas** as LPs a seção de depoimentos usa textos placeholder até a inserção das avaliações reais.
