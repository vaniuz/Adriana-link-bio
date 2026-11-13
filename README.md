# Dra. Adriana Lima — Link-in-Bio

Página de links (link-in-bio) da **Dra. Adriana Lima** (@dra.adrianalimadentista) — dentista, 1º Tenente do Exército e mentora de milhas. Tema escuro quente (marrom + dourado), seguindo o template do Mario Drums link-bio. Textos em **pt-BR**.

Lead originada do post: https://www.instagram.com/p/DcoTLqwR9bc/ ("Quer aprender a realizar seus sonhos de viagem apenas com seus gastos do dia a dia? Eu te ajudo!")

## Links
- **Diagnóstico grátis (WhatsApp)** → https://wa.me/5534991660836 (mensagem pré-preenchida da mentoria)
- **Mentoria / provas** → https://www.instagram.com/dra.adrianalimadentista/

## Deploy
Site 100% estático (HTML + CSS, sem build). Na Vercel use o preset **Other**.

Arquivos:
- `index.html` — a página (é o que a Vercel serve na raiz `/`)
- `bio.html` — atalho que redireciona para `/`
- `assets/bio-adriana.jpg` — foto hero (1200×896)
- `assets/bio-logo.png` — badge branco com "A" dourado
- `assets/bio-thumb.jpg` — thumbnail do card do diagnóstico

> Importante: a página **precisa** se chamar `index.html`. Um `bio.html` sozinho na raiz faz a Vercel responder `404 NOT FOUND` em `/`.
