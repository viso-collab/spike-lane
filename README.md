# Spike Lane

Et løbespil med tre baner. Skift bane for at undgå spikes, mens farten stiger. Saml mønter undervejs og brug dem på skins og baggrunde i butikken.

## Sådan spiller man

| Handling | Tastatur | Mobil |
|---|---|---|
| Venstre bane | `A` eller `←` | Tryk i venstre side eller swipe til venstre |
| Højre bane | `D` eller `→` | Tryk i højre side eller swipe til højre |
| Start / prøv igen | `Mellemrum` | Knappen på skærmen |
| Butik | `B` (luk med `Esc`) | Knappen på skærmen |

- Hver række spikes blokerer én eller to baner, aldrig alle tre.
- Farten stiger hele tiden, og senere kommer der flere rækker, der blokerer to baner.
- Scoren er meter løbet.

## Mønter og butik

- De fleste mønter ligger midt i mellemrummet mellem to rækker i en blokeret bane. Du skal ind og tage dem og ud igen før næste række. Enkelte mønter ligger i en fri bane.
- **Skins:** Klassisk (gratis), Lava (25), Mintstribe (40), Skakbræt (60), Spøgelse (90), Galakse (150), Ren guld (300).
- **Baggrunde:** Skumring (gratis), Midnat (50), Ørken (80), Skov (100), Nordlys (120), Vulkan (180), Cyber (250).
- Baggrundene står stille. Nogle har en lille animation: et blad der falder i Skov, stjerneskud i Midnat, nordlys der bølger og gnister i Vulkan.

## Kør lokalt

Der er ingen build. Åbn `index.html` i en browser, eller start en statisk server:

```sh
python3 -m http.server 8000
```

Mønter, rekord og køb gemmes i browserens `localStorage`.

Spillet ligger også på [Legepladsen](https://github.com/viso-collab/legepladsen).
