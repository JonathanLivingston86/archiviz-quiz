# Real o AI? — istruzioni per gli agenti

## Obiettivo e confini

- Mantieni un quiz semplice, immediato e utilizzabile durante workshop dal vivo.
- Considera questo repository una risorsa del progetto `workshop-ai-per-architette`, non un progetto autonomo sul piano organizzativo; conserva comunque il proprio confine Git e la propria pubblicazione.
- Leggi `README.md` per il funzionamento e `docs/STATUS.md` per lo stato corrente.
- Prima di modifiche non banali, spiega in italiano semplice obiettivo, motivazione, rischi e controlli.
- Definisci acronimi e termini tecnici alla prima occorrenza.

## Mappa della risorsa

- `index.html`: contiene HTML, CSS e JavaScript del quiz.
- `images/`: contiene le immagini AI locali.
- Le immagini reali dipendono da URL Unsplash definiti in `index.html`.

## Regole di lavoro

- Il branch `master` alimenta il sito pubblico tramite GitHub Pages: non pubblicare direttamente modifiche non verificate.
- Usa un branch separato e una revisione prima dell'unione in `master`.
- Non inserire dati personali, credenziali, percorsi locali o regole private nel repository pubblico.
- Mantieni la risorsa senza build e senza dipendenze finché non esiste un vantaggio concreto nel cambiarla.
- Non rinominare o sostituire immagini senza aggiornare e verificare tutti i riferimenti in `index.html`.
- Considera gli URL Unsplash una dipendenza esterna: il quiz può degradarsi se non sono raggiungibili o cambiano comportamento.
- Mantieni temporanei, log e file degli editor fuori dal repository.

## Verifiche minime

- Controlla che l'HTML e lo script inline siano sintatticamente validi.
- Controlla che ogni percorso locale citato da `index.html` esista.
- Prova il flusso completo in un browser tramite un server locale, non soltanto aprendo il file direttamente.
- Prima di aggiornare il sito pubblico, verifica anche la disponibilità delle immagini esterne e il comportamento su una finestra adatta alla presentazione.

## Stato e decisioni

- Mantieni attività e problemi aperti in `docs/STATUS.md`; non creare cartelle generiche `DA_SISTEMARE`.
- Registra decisioni durevoli in `docs/decisions/` soltanto quando necessario.
- Non affidare informazioni importanti soltanto alla cronologia di una chat.

## Definizione di completato

Una modifica è completa quando il quiz funziona dall'inizio al risultato finale, le risorse sono disponibili, il sito pubblico non viene alterato involontariamente e l'esito è spiegato in modo comprensibile.
