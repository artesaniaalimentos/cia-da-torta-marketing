# Cia da Torta — Marketing Assets

Hospedagem de assets de marketing (emails, stories, banners) da Cia da Torta via GitHub Pages.

## Estrutura

```
campanhas/
  ultimo-dia-relancamento/
    index.html          ← email "último dia" (relançamento)
    assets/             ← logo + foto hero
```

## URLs publicadas

- **Último dia (relançamento)**: https://artesaniaalimentos.github.io/cia-da-torta-marketing/campanhas/ultimo-dia-relancamento/

## Como usar no Mailchimp

1. Abrir a URL pública acima
2. Copiar o HTML renderizado (ou usar "Import from URL" no Mailchimp se disponível)
3. Variáveis Mailchimp já estão no template: `*|UNSUB|*`

## UTM

Todos os links têm tracking:
`utm_source=email&utm_medium=email&utm_campaign=relancamento-ultimo-dia&utm_content=<slot>`
