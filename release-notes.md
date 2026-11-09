# Journal 1.20

## Nieuw
- **Over Journal en updates** in Instellingen.
- **Controleer op updates** leest het publieke manifest.
- Toont versie en release-opmerkingen.
- Downloadt de APK naar de app-cache.
- Verifieert **SHA-256**, package-id, versieCode en de **APK-signatuur**.
- Opent daarna de Android-installer; bij “onbekende bronnen” word je naar de
  juiste instelling gestuurd.
- Na installatie blijven al je gegevens behouden (zelfde package en signing-key).

## Belangrijk
- 1.19 kan zichzelf nog niet updaten; installeer 1.20 eenmalig handmatig.
- Daarna kunnen toekomstige versies via de app worden gecontroleerd en
  gedownload.
- Stille installatie is op Android niet mogelijk zonder MDM/device-owner.

## Signing
Zelfde key als 1.19; APK-SHA-256:
`5cc04c53d52aace1e56a8126aea344658196a14003f2580f62093543d1ebbca8`.
