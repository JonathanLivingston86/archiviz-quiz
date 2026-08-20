# Stato di Real o AI?

## Obiettivo corrente

Mantenere la risorsa interattiva attiva e riutilizzabile per futuri workshop, sviluppandola dalla copia locale canonica fuori da OneDrive.

## Quadro rapido del lavoro

### Da fare

- [ ] Prima del prossimo workshop, rivalutare disponibilità e condizioni d'uso delle immagini reali esterne.

### Completato e verificato

- [x] Creata la copia canonica fuori da OneDrive a partire dal remote verificato.
- [x] Normalizzato il progetto su un branch isolato e verificati script, immagini e servizio locale.
- [x] Ottenuta la revisione indipendente di Claude Sonnet 4.6 tramite Anthropic diretto.
- [x] Pubblicata la normalizzazione nella Pull Request in bozza `#1` senza modificare `master` o il sito live.
- [x] Riclassificato e ricollocato come risorsa di `workshop-ai-per-architette`, preservando commit `863cfb4`, branch `agent/adotta-framework`, remote GitHub e sito pubblico; il server locale dal nuovo percorso ha risposto HTTP 200.
- [x] Revisionata integralmente la Pull Request `#1` rispetto a `master`: assi Standards e Spec entrambi PASS con zero rilievi; completati nel browser sei round, caricamento delle dodici immagini, schermata finale e riavvio senza errori. Verdetto: pronta per il merge, subordinatamente all'approvazione esplicita di Andrea. Prova: rapporto del 20 agosto 2026 in `_SISTEMA\REGISTRI\AUDIT`.
- [x] Unita la Pull Request `#1` con squash merge al commit `4813404`, pubblicato da GitHub Pages con esito `built`; il sito live ha superato nuovamente sei round, caricamento delle dodici immagini, schermata finale e `Rigioca` senza errori.
- [x] Ritirata in modo recuperabile la vecchia copia OneDrive: repository pulito al commit `002eb7b`, sette oggetti Git identici alla copia canonica e 48 file inviati al Cestino dopo il collaudo live. La differenza byte iniziale di `index.html` dipendeva soltanto dalle terminazioni di riga LF/CRLF.

## Stato verificato

- Repository GitHub pubblico: `https://github.com/JonathanLivingston86/archiviz-quiz`.
- Sito pubblico attivo: `https://jonathanlivingston86.github.io/archiviz-quiz/`.
- GitHub Pages pubblica la radice del branch `master`.
- La copia canonica è sul branch `master`, allineata a `origin/master`; l'adozione del framework è stata introdotta dal merge `4813404f8632a190313ac6119e591242f3820dd7`.
- Il quiz è composto da un file HTML, sei immagini AI locali e sei immagini reali caricate da Unsplash.
- La precedente copia OneDrive è nel Cestino ed è ancora recuperabile; il percorso originale non è più presente.
- La normalizzazione è registrata localmente nel commit `862148eb64a632eebbd6cc838dfc88ffeeaec764` sul branch isolato `agent/adotta-framework`.
- Lo script inline è sintatticamente valido, tutte le sei immagini locali esistono, le sei immagini Unsplash rispondono e il sito viene servito correttamente in locale.
- GitHub Pages ha pubblicato correttamente il commit `4813404`; il comportamento del quiz è rimasto invariato.
- La revisione indipendente con Claude Sonnet 4.6 tramite Anthropic diretto ha restituito `APPROVATO`, senza problemi di sicurezza o interoperabilità.

## Rischi e vincoli

- Le immagini reali sono dipendenze esterne: disponibilità e condizioni d'uso vanno rivalutate prima dei prossimi workshop.
- La Pull Request `#1` è unita. Il branch preparatorio resta disponibile sul remote come ulteriore traccia tecnica, ma non è la sorgente pubblicata.

## Ultimo aggiornamento

20 agosto 2026, Codex. Pull Request unita, sito live collaudato e vecchia copia OneDrive ritirata in modo recuperabile.
