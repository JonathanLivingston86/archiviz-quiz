# Real o AI?

Quiz visuale per distinguere immagini architettoniche reali da immagini generate con intelligenza artificiale.

Il sito pubblico è disponibile su:

https://jonathanlivingston86.github.io/archiviz-quiz/

## Struttura

- `index.html`: interfaccia, stile e logica del quiz in un singolo file.
- `images/`: sei immagini generate con AI usate nel confronto.
- Le immagini reali vengono caricate da URL esterni di Unsplash durante l'uso.

## Esecuzione locale

Il progetto non richiede installazione o build. Per una prova affidabile, dalla radice eseguire:

```powershell
python -m http.server 8000
```

Poi aprire `http://localhost:8000` nel browser.

## Pubblicazione

GitHub Pages pubblica il contenuto della radice del branch `master`. Prima di unire modifiche in quel branch verificare il quiz localmente e controllare che tutte le immagini siano disponibili.
