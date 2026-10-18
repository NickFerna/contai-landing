# contaí — landing page

Landing page do **contaí**, um serviço de finanças simples para pequenos negócios (padarias, mercadinhos, oficinas, salões e outros). O objetivo da página é gerar contatos (leads) por meio de um formulário de "conversa grátis".

## Como é feita

- Um único arquivo: [`index.html`](index.html), com HTML, CSS e JavaScript embutidos. Não há build, dependências nem backend.
- Idioma: português do Brasil.
- Fonte: [Archivo](https://fonts.google.com/specimen/Archivo), carregada do Google Fonts.

## Como ver localmente

Abra o `index.html` no navegador, ou sirva a pasta com qualquer servidor estático:

```bash
npx serve .
```

## Estado atual

- O formulário valida os campos no navegador, mas **ainda não envia os dados para lugar nenhum**. O ponto para ligar o envio está marcado com `TODO` no `<script>` do `index.html`.
- Os valores que aparecem nas ilustrações são fictícios.
- Não há depoimentos nem números de clientes, de propósito: o serviço ainda não tem clientes para citar.

## Publicação

Site estático, pronto para hospedagem como Vercel, Netlify ou GitHub Pages.
