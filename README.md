# Kantinebord Spartanen

Openbaar kantinebord voor de iPad in de kantine van SV Spartanen (Hero Sportpark Spartanen, Wognum).

Adres: https://spartanenkantine.github.io/checklist/

## Bestanden

| Bestand | Inhoud | Wie werkt het bij |
|---|---|---|
| `index.html` | het bord zelf | alleen bij wijzigingen aan het bord |
| `data/dagen.json` | speeldagen, start dienst, rustmomenten, bekers | de wekelijkse geplande taak |
| `data/checklist.json` | checklist per speeldag (`fases`, `items`) en de maandaglijst (`maandag.items`) | met de hand, via GitHub |
| `data/muziek.json` | Spotify-afspeellijst per periode | met de hand, via GitHub |
| `icon.png` | icoon op het beginscherm van de iPad | – |

## Checklist aanpassen

Open `data/checklist.json` op GitHub, klik op het potlood en klik daarna op "Commit changes".

- Een item met `"naarMaandag": true` schuift door naar de maandag als het op zaterdag of zondag niet is afgevinkt.
- De maandaglijst staat onder `"maandag"` → `"items"`.
- Houd de `id` van een item gelijk. De vinkjes verwijzen daarnaar.

## Vinkjes

De vinkjes worden alleen op de iPad bewaard (browseropslag). Open het bord via het icoon op het beginscherm. In gewoon Safari wist iOS de opslag van websites die een week niet bezocht zijn.
