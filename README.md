# Quit&Buy – GitHub Pages
App per smettere di fumare: traccia le sigarette evitate, i soldi risparmiati e l'avanzamento verso un prodotto.

## Come pubblicarla su GitHub Pages (senza build)
1. Crea un repository *pubblico* su GitHub (es. `quitandbuy`).
2. Carica questi file nella radice del repo: `index.html`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`.
3. Su GitHub vai su **Settings → Pages**: in **Source** scegli **Deploy from a branch** e **Branch: main /(root)**.
4. Salva: dopo qualche secondo avrai l'URL `https://<tuo-username>.github.io/<repo>/`.

> Non serve Node/Vite: è tutto in un *index.html* con React via CDN. I dati restano salvati localmente nel browser (localStorage).

## Opzionale
- Per avere l'icona quando aggiungi alla Home dell'iPhone, i file delle icone sono già inclusi.
- Se vuoi cambiare nome/icone/colore, modifica `<title>` e sostituisci le PNG.
