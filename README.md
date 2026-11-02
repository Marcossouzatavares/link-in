# Link na Bio

Página única de links (estilo Linktree) para Instagram, TikTok e LinkedIn. HTML + CSS + JS puro, sem build.

## Personalizar

Tudo é editado no topo de `script.js`, no objeto `CONFIG`:

- `title`: o título no topo da página
- `sections`: grupos de botões (Arara Delivery, WWM, etc.). Para um botão novo, copie uma linha `{ ... }`; para um grupo novo, copie um bloco `{ title, links }`. Use `featured: true` no link principal (ganha borda animada) e `badge: "Novo"` para uma etiqueta.

Ícones disponíveis: `delivery, handshake, bike, store, whatsapp, instagram, tiktok, facebook, linkedin, youtube, rocket, code, site, email, calendar, briefcase, download, star, cart, play, map`.

## Testar localmente

Abra o `index.html` no navegador (duplo clique).

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `links`).
2. Envie estes arquivos para a branch `main`.
3. No repositório: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`** → Save.
4. Em ~1 minuto o site fica em `https://SEU-USUARIO.github.io/links/`.

Dica: se o repositório se chamar `SEU-USUARIO.github.io`, o endereço fica só `https://SEU-USUARIO.github.io`.
