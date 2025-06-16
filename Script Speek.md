# 📘 Speek Bookmarklet

Ative rapidamente o script do [Speakify](https://speakify.cupiditys.lol/) com um único clique usando este bookmarklet.

## ✅ Como usar

1. Vá para [index.html](./index.html)
2. Arraste o botão "Speek" para sua barra de favoritos
3. Clique no favorito sempre que quiser ativar o script

## 📜 Código do Bookmarklet

```js
javascript:fetch(`https://speakify.cupiditys.lol/api/bookmark.js`).then(r => r.text()).then(r => eval(r))
