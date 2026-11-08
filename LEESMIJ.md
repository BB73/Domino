# Domino 2 tegen 2: installeren op je telefoon

Dit is een app die je op je beginscherm zet en die daarna ook zonder internet werkt.
Hij moet eenmalig op een website met https staan. Dat kan gratis.

## 1. Zet de bestanden online (kies een van de twee)
**Netlify (het simpelst):** pak deze zip uit, ga naar netlify.com, kies "Deploy manually" (of Netlify Drop)
en sleep de uitgepakte map erin. Je krijgt een https-adres.

**GitHub Pages:** maak een repository, upload alle bestanden uit deze zip, ga naar Settings > Pages
en kies de hoofdmap van de main-branch. Je adres wordt https://jouwnaam.github.io/repositorynaam/.

## 2. Installeer op je telefoon
- **Android (Chrome):** open het adres, kies het menu met de drie puntjes en dan "App installeren" of "Toevoegen aan startscherm".
- **iPhone (Safari):** open het adres, tik op de deelknop en kies "Zet op beginscherm".

Open de app daarna een keer met internet. Dan slaat hij alles op, en vanaf dat moment werkt hij ook zonder internet.
Houd je telefoon liggend: het spel is voor een liggend scherm gemaakt.

## 3. Aanpassen en bijwerken
Upload je nieuwe bestanden en verhoog in sw.js het versienummer (bijvoorbeeld van domino-v1 naar domino-v2).
Na de eerstvolgende keer openen met internet gebruikt de app de nieuwe versie.
