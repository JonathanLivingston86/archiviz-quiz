# Stato di Real o AI?

## Obiettivo corrente

Mantenere il quiz attivo e riutilizzabile per futuri workshop, sviluppandolo dalla copia locale canonica fuori da OneDrive.

## Stato verificato

- Repository GitHub pubblico: `https://github.com/JonathanLivingston86/archiviz-quiz`.
- Sito pubblico attivo: `https://jonathanlivingston86.github.io/archiviz-quiz/`.
- GitHub Pages pubblica la radice del branch `master`.
- La copia canonica è stata clonata dal remote verificato al commit `002eb7b98d4b6b28998c9869ec08a28eae1c344e`.
- Il quiz è composto da un file HTML, sei immagini AI locali e sei immagini reali caricate da Unsplash.
- È presente una copia precedente non ancora archiviata.
- La normalizzazione è registrata localmente nel commit `862148eb64a632eebbd6cc838dfc88ffeeaec764` sul branch isolato `agent/adotta-framework`.
- Lo script inline è sintatticamente valido, tutte le sei immagini locali esistono, le sei immagini Unsplash rispondono e il sito viene servito correttamente in locale.
- Il branch remoto `master` e il sito GitHub Pages non sono stati modificati.
- La revisione indipendente con Claude Sonnet 4.6 tramite Anthropic diretto ha restituito `APPROVATO`, senza problemi di sicurezza o interoperabilità.

## Problemi aperti

- Le immagini reali sono dipendenze esterne: disponibilità e condizioni d'uso vanno rivalutate prima dei prossimi workshop.
- La normalizzazione del progetto è preparata e verificata su un branch locale, ma non è ancora pubblicata nel repository pubblico.
- La copia OneDrive non deve essere rimossa finché la nuova copia e il flusso pubblico non sono stati convalidati e registrati.

## Prossimi passi

1. Pubblicare il branch, dopo approvazione esplicita, senza modificare direttamente `master` e il sito live.
2. Revisionare la proposta di modifica e unire soltanto dopo le verifiche previste.
3. Dopo l'unione e la verifica del sito, gestire la copia precedente con un passaggio separato e recuperabile.

## Ultimo aggiornamento

12 agosto 2026, Codex. Normalizzazione locale preparata dal commit base `002eb7b98d4b6b28998c9869ec08a28eae1c344e`.
