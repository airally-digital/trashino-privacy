# Changelog — Informativa privacy Trashino

Ogni versione pubblicata è archiviata in `versions/<data>.html` (URL permanente) ed
è anche un tag git (`privacy-<data>`). La pagina corrente è sempre `index.html`.

## 2026-07-08 — accuratezza dati (Firebase) + allineamento concetto
- **Corretta** l'affermazione errata "Non abbiamo un server / questi dati non vengono
  mai inviati a noi": l'app usa **Firebase** (Google). Aggiunta la sezione *Identità
  anonima e dati su Firebase* (identificativo casuale dell'installazione, Paese
  grossolano, lingua, versione; nessun nome/email/account).
- **Rimossa** la frase "Non mostra pubblicità" (claim non mantenibile a lungo termine).
- Riformulati *I tuoi diritti*, *Condivisione dei dati* e *Conservazione* di conseguenza.
- Snapshot: [`versions/2026-07-08.html`](versions/2026-07-08.html).

## 2026-06-27 — allineata all'app 1.1
- **Rimossa** la sezione *Pubblicità (Google AdMob)*: la 1.1 non mostra annunci.
- **Aggiunta** *Acquisti in-app (Google Play Billing)*: abbonamento Premium opzionale;
  pagamenti gestiti da Google Play; nessun dato di pagamento trattato dall'app (solo
  un flag locale di stato Premium).
- Aggiornati i dati trattati (luoghi multipli, niente ads); contatto Airally Digital.
- **Lingue: IT · EN · FR · DE · ES** (tedesco aggiunto il 28/06/2026 per il mercato host DACH; stessa informativa, solo tradotta; prima IT · EN).
- Pagina **ricostruita on-brand**: consuma i design token del marchio
  (`brand.tokens.css` dall'hub `trashino-brand`, variabili `var(--tr-*)`).
- Snapshot: [`versions/2026-06-27.html`](versions/2026-06-27.html).

## 2026-06-15 — prima pubblicazione (app 1.0)
- Versione iniziale. Includeva la sezione pubblicità *Google AdMob* (annunci non
  personalizzati). Lingue: IT · EN.
- Snapshot: [`versions/2026-06-15.html`](versions/2026-06-15.html).
