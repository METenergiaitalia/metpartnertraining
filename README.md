# MET GDPR Training — Landing page

Landing page statica con la registrazione della formazione GDPR per gli agenti di vendita di MET Energia Italia.

## Struttura

```
index.html                 pagina unica (hero, video, formazione, supporto, footer)
assets/css/style.css       reset, @font-face Montserrat, stati :hover
assets/fonts/*.woff2       Montserrat 300/400/600/700/800/900 (self-hosted)
assets/img/*.png           logo MET e claim "Bringing new energy to Europe"
robots.txt                 pagina esclusa dall'indicizzazione
.nojekyll                  disattiva Jekyll su GitHub Pages
```

## Pubblicazione su GitHub Pages

1. Crea un repository (consigliato **privato**: il contenuto è riservato agli agenti).
2. Carica il contenuto di questa cartella nella radice del repository.
3. *Settings → Pages* → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. La pagina sarà online su `https://<org>.github.io/<repo>/`.

Nota: con un repository privato GitHub Pages richiede un piano Enterprise. In alternativa pubblica su hosting interno MET o su un repo pubblico mantenendo il video YouTube "non elencato".

## Manutenzione

- **Video**: sostituire l'ID `sDajP4nVxL4` nell'`<iframe>` e nel link di fallback in `index.html`.
- **Email di contatto**: cercare `privacy.metita@met.com` in `index.html` (3 occorrenze).
- **Durata**: cercare `Durata ca. 45 min`.
- **Argomenti trattati**: blocco `<section id="formazione">`.

## Licenza

© 2026 MET Energia Italia S.p.A. — Materiale interno, tutti i diritti riservati.
