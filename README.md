# Journal — releases

Publieke release- en updatekanaal voor de persoonlijke Journal Android-app.
De broncode staat in de private repository `ronald1711/journal-android`.

## Downloaden

- Stabiele APK: [`Journal.apk`](https://github.com/ronald1711/journal-android-releases/releases/latest/download/Journal.apk)
- Manifest: [`latest.json`](https://github.com/ronald1711/journal-android-releases/releases/latest/download/latest.json)

Installeer de APK bovenop de bestaande app. De package-id en signing-key zijn
gelijk, dus dagboek, check-ins, planner, boodschappen en instellingen blijven
behouden. Android vraagt mogelijk om “Installeren van onbekende apps” toe te
staan voor Journal.

## Signing

- Package: `com.rebuild.dayonejournal`
- Signing-certificaat SHA-256:
  `d5beca7b6a5ba7e9fc0a366f73a149e49a259188d72166366b2a4ca049442c9f`
- Dit is de persoonlijke/debug-signingkey van deze app. Publiceer deze APK niet
  in Google Play en publiceer de keystore nooit.

## Updates

De app kan `latest.json` controleren, `versionCode` vergelijken, de APK
downloaden, SHA-256 en de APK-signatuur verifiëren en daarna de systeem-
installer openen. Stille installatie is op Android niet mogelijk zonder
MDM/device-owner. Zie `OTA-PLAN.md` in de private bronrepo.

## Privacy

Deze repository bevat alleen het publieke APK-artefact, het manifest en
release-opmerkingen. Geen journaldata, API-keys, Garmin-keys of keystores.
