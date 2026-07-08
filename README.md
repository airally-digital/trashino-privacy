# trashino-privacy

Pagina pubblica dell'**informativa privacy di Trashino**, servita via GitHub Pages:
**https://airally-digital.github.io/trashino-privacy/**

L'app vi rimanda da *Impostazioni → Informativa sulla privacy*.

## On-brand (gestione centralizzata)

Lo stile **consuma i design token** del marchio Trashino: `brand.tokens.css` è la
copia (vendored) generata dall'hub **`trashino-brand`** (`dist/css/trashino.tokens.css`),
e `index.html` usa le variabili `var(--tr-*)`. Quando il brand cambia, basta
ricopiare il CSS dall'hub e la pagina si riallinea — stessa identità di app/social.

```bash
# aggiornare i token dal brand hub (repo sorella)
cp ../trashino-brand/dist/css/trashino.tokens.css brand.tokens.css
```

Contenuto: **IT · EN · FR · DE · ES** (toggle lingua) — abbonamento Premium via Google
Play Billing; dati Firebase (identità anonima, Analytics, Crashlytics) dichiarati in
modo trasparente. © Airally Digital.
