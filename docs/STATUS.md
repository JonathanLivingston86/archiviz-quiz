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
- La normalizzazione è pubblicata sul branch `agent/adotta-framework` nella Pull Request in bozza `#1`; `master` e il sito live restano invariati.
- La copia OneDrive non deve essere rimossa finché la nuova copia e il flusso pubblico non sono stati convalidati e registrati.

## Prossimi passi

1. Revisionare la Pull Request in bozza `#1` e decidere separatamente se renderla pronta per il merge.
2. Unire in `master` soltanto dopo una nuova approvazione esplicita e verificare il sito live.
3. Dopo l'unione e la verifica del sito, gestire la copia precedente con un passaggio separato e recuperabile.

## Ultimo aggiornamento

13 agosto 2026, Codex. Branch pubblicato e Pull Request `#1` aperta in bozza; `master` verificato al commit `002eb7b98d4b6b28998c9869ec08a28eae1c344e`.
