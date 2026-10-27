# 📚 Toetsplanner

Plan je toetsweek: zet je toetsen erin, kies hoe moeilijk ze zijn en hoe lang je moet oefenen. De app stelt voor op welke dagen en hoe lang je oefent, en je past dat zelf aan.

- Toetsen met datum, soort, weging en leerstof
- Oefendagen automatisch verdeeld, per dag aan te passen met − en +
- Vandaag-overzicht met afvinken, aftellen en tip van de dag
- Focus-timer
- Cijfers met gewogen gemiddelde
- Werkt zonder internet, geen account, geen kosten

Alles wordt alleen op je eigen telefoon bewaard.

## Online zetten met GitHub Pages

1. Maak op github.com een nieuwe repository, bijvoorbeeld `toetsplanner` (Public).
2. Klik **Add file → Upload files** en sleep alle bestanden uit deze map erin. Klik **Commit changes**.
3. Ga naar **Settings → Pages**. Kies bij *Branch* `main` en map `/ (root)`, klik **Save**.
4. Na ongeveer een minuut staat de app op `https://<jouw-gebruikersnaam>.github.io/toetsplanner/`.

## Op de iPhone zetten

Open de link in **Safari** → tik op **Deel** → **Zet op beginscherm**. De app krijgt een eigen icoon en opent schermvullend.

## Aanpassen

Pas `index.html` aan en upload hem opnieuw. Verhoog daarna in `sw.js` het versienummer (`toetsplanner-v1` → `toetsplanner-v2`), zodat de telefoon de nieuwe versie ophaalt.
