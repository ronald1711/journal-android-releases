# Journal 1.23

## AI-fixes
- Geen `null`-tekst meer wanneer een provider `content: null` stuurt tijdens
  de reasoning-fase.
- Geen valse **“De provider gaf geen antwoord”** meer bij reasoning- of
  niet-streamende modellen; de app probeert het eenmalig zonder streaming.
- Reasoning-tekst wordt niet meer als eindantwoord getoond.
- Het antwoordtokenbudget is instelbaar onder **AI → Kosten/budget**; de oude
  standaard van 700 tokens wordt naar 2000 verhoogd, zodat reasoning-modellen
  ruimte houden voor het echte antwoord.
- DeepSeek `deepseek-flash` werkt; OpenRouter-gratis modellen kunnen een
  429-rate limit geven.

## Updates
- Inclusief de in-app updatechecker uit 1.20: **Instellingen → Over Journal en
  updates**.
- 1.19 kan zichzelf nog niet updaten; 1.20/1.21/1.22 kunnen dat wel.

## Signing
Zelfde key; APK-SHA-256:
`1d20e52156e563e96eb1565df09d46125ead41f57541cdcab91c95972cbfbee2`.
