# Lobiz Magazine — Invito digitale

Invito-rivista sfogliabile per **Una notte di musica senza tempo**
Espresso Doppio dal vivo · Sabato 28 novembre 2026, dalle 19:30 · Trattoria Bel Belè, Milano.

## Contenuto
- `index.html` — tutta la pagina (stili e script inclusi)
- `assets/` — foto, loghi e illustrazioni

È un sito statico: nessuna installazione, nessun build.

## Pubblicare con GitHub Pages
1. Crea un nuovo repository su GitHub e carica **il contenuto** di questa cartella (index.html deve stare nella radice).
2. Vai in *Settings → Pages*, alla voce *Source* scegli *Deploy from a branch*, branch `main`, cartella `/ (root)`, poi *Save*.
3. Dopo un minuto il sito è online su `https://<utente>.github.io/<repository>/`.

Funziona anche trascinando la cartella su Netlify o Vercel.

## Invito personalizzato
Aggiungi `#nome-cognome` in fondo al link, ad esempio:

    https://<utente>.github.io/<repository>/#marco-rossi

La pagina mostrerà "hanno il piacere di invitare **Marco Rossi**", il timbro "Riservato a" in copertina e il nome sul biglietto.

## Modificare i testi
Tutti i testi sono in `index.html`: cerca la frase da cambiare e sostituiscila.
L'orario del conto alla rovescia è in `Date.UTC(2026,10,28,18,30,0)` (ora UTC: 18:30 UTC = 19:30 a Milano).

## Conferma della partecipazione
Il bottone "Confermi la tua partecipazione" (nella pagina d'arrivo e a pagina 06) apre il Google Form:
https://forms.gle/w7vQTcEaVNXJcEpt6
Per cambiarlo, cerca questo indirizzo in `index.html` e sostituiscilo.
