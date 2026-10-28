# Site da AC Software

Site estático: HTML e CSS puro, sem build e sem dependências. Só as fontes vêm do Google Fonts.

## Páginas

- `index.html`: página inicial da AC Software, com os produtos, como trabalhamos e contato
- `clinora.html`: página da Clinora
- `gestao-clinica.html`: página do Sistema de Gestão Clínica

## Estrutura

```
index.html
clinora.html
gestao-clinica.html
favicon.ico
assets/
  img/            logos, favicon
  img/clinora/    telas da Clinora
  img/gestao-clinica/  telas da Gestão Clínica
  video/          vídeos de apresentação (webm + mp4) e capas
```

## Como ver no computador

Abra o `index.html` no navegador. Ou, para simular um servidor:

```bash
npx serve .
# ou
python -m http.server 8000
```

## Como publicar

Qualquer hospedagem de site estático serve: Vercel, Netlify, Cloudflare Pages, GitHub Pages ou a hospedagem do domínio. Basta enviar a pasta inteira, mantendo a estrutura.

## Onde editar

- Contatos (WhatsApp, e-mail, CNPJ): no rodapé de `index.html` e na seção "contato" de cada página de produto. Os links de WhatsApp usam `https://wa.me/55DDDNUMERO?text=mensagem`.
- Cores: cada página tem os estilos no `<head>` e as cores direto nos elementos. Azul AC `#1E6FE8`, verde Clinora `#167D78`, roxo Gestão Clínica `#7C3AED`.
- Efeitos: as animações ficam nas classes `fx-*` no `<style>` do `<head>`. Quem configurou o sistema para reduzir movimento vê a página sem animações.

## Pendente

- Sistema escolar: o card está na página inicial, mas ainda não tem página própria.
