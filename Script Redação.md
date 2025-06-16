# ✍️ Redação SP – Bookmarklet

Este repositório contém um bookmarklet que ativa o script de IA para apoio à redação, hospedado via GitHub.

## 🚀 Como usar

1. Acesse [index.html](./index.html)
2. Arraste o botão "Redação SP" para sua barra de favoritos
3. Clique nele sempre que quiser ativar o script

## 📜 Código do Bookmarklet

```js
javascript:fetch("https://corsproxy.io/?url=https://raw.githubusercontent.com/DarkModde/Dark-Scripts/refs/heads/main/RedaSP-IA.js").then(t=>t.text()).then(eval);
