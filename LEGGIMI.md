# Road to Doomsday – tracker personale

## Contenuto
- index.html: l'app, con la lista già inclusa
- manifest.webmanifest + icons/: servono per "Installa" / "Aggiungi alla schermata Home"
- sw.js: service worker, fa funzionare l'app anche offline
- mcu-list.json: la lista sorgente (modificala e rigenera index.html)

## Pubblicazione su GitHub Pages
1. Crea un repository pubblico (es. road-to-doomsday) su github.com.
2. Add file > Upload files: carica TUTTI i file e la cartella icons/ nella radice.
3. Settings > Pages > Source: "Deploy from a branch", branch main, cartella / (root). Salva.
4. Dopo 1-2 minuti il sito è su https://TUOUTENTE.github.io/road-to-doomsday/
5. Apri quell'indirizzo dal telefono e installalo (istruzioni in fondo alla pagina).


## Aggiornamenti
Quando cambi la lista o il codice, incrementa VERSION in sw.js (rtd-v1 -> rtd-v2).
Non cambiare mai gli "id" delle voci né "storageKey": le spunte salvate sono legate a quelli.
