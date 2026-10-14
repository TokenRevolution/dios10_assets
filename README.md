# Assets — Dios10

Questa cartella contiene le risorse statiche di **Dios10**, la piattaforma di fantacalcio: logo, immagini, icone, font e altri elementi grafici utilizzati nell’interfaccia.

## Organizzazione consigliata

- `logos/` — Logo della piattaforma e relative varianti.
- `icons/` — Icone per menu, azioni e funzionalità.
- `images/` — Immagini, sfondi e illustrazioni.
- `teams/` — Stemmi e immagini delle squadre.
- `players/` — Foto e immagini dei calciatori.
- `fonts/` — Font e relative licenze.

Creare le sottocartelle solo quando necessarie.

## Convenzioni

- Utilizzare nomi descrittivi, in minuscolo e separati da trattini: `logo-dios10.svg`.
- Preferire **SVG** per loghi e icone, **WebP** per fotografie e **PNG** quando serve trasparenza.
- Ottimizzare le dimensioni dei file prima di aggiungerli.
- Evitare duplicati e rimuovere le risorse inutilizzate dopo aver verificato i riferimenti nel codice.
- Per immagini di squadre e calciatori, preferire identificativi stabili ai nomi, quando disponibili.

## Utilizzo

Importare le risorse seguendo le convenzioni del framework utilizzato. Evitare percorsi assoluti legati al computer dello sviluppatore.

I testi alternativi delle immagini devono essere definiti nei componenti dell’interfaccia; le immagini decorative devono essere riconoscibili come tali.

## Licenze e attribuzioni

Utilizzare risorse proprie o autorizzate. Conservare le licenze dei font e indicare fonte, autore ed eventuali attribuzioni richieste per i materiali di terze parti.

Non inserire in questa cartella credenziali, chiavi API, dati personali o file di configurazione riservati.
