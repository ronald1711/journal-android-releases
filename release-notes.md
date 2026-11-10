# Journal 1.24

## Privacy en toestemming
- Een achtergrond- of chatverzoek kan niet langer een eerder ingetrokken
  AI-toestemming of gewijzigde privacy-/digest-instellingen herstellen.
- Het maandverbruik wordt nu atomair bijgewerkt, zodat gelijktijdige
  verzoeken elkaar niet overschrijven; een gewone instellingenopslag raakt
  het verbruik niet meer aan.

## Backup en herstellen
- Nieuwe **volledige backup** (inclusief foto's en dagboekkoppeling) naast de
  bestaande Day One JSON-, CSV-, tekst- en Markdown-exports.
- **Backup herstellen** importeert de backup en schrijft media terug naar de
  app-opslag; bij een mislukte opslag blijft de oude data intact.
- De pincode wordt bewust niet in het gedeelde backupbestand opgenomen.

## AI-antwoorden
- Afgebroken of foutief afgesloten streams worden niet meer als compleet
  antwoord opgeslagen of gefactureerd; een ontbrekende `[DONE]` of een
  providerfout wordt nu als fout gemeld.

## Overzichten (digests)
- Dag- en weekoverzichten worden volledig bewaard (geen 300-teken-afkap meer)
  en openen via de melding in een eigen overzichtscherm.
- Android 13+ vraagt meldingstoestemming wanneer je een overzicht inschakelt.

## Verwijderen
- Een mislukte opslag bij het verwijderen rolt de notitie terug en meldt de
  fout, in plaats van de notitie stilletjes te sluiten.

## Signing
Zelfde key; APK-SHA-256:
`6ca8b20dba77384b436daa315652ed035deb407083699911406f46664af755a8`.
