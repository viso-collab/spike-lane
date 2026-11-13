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
- **Skins (15):** Klassisk (gratis), Lava (25), Vandmelon (35), Mintstribe (40), Skakbræt (60), Kat (70), Spøgelse (90), Robot (110), Isterning (130), Galakse (150), Regnbue (200), Ildhoved (220), Diskokugle (260), Ren guld (300), Tomrum (400).
- **Baggrunde (12):** Skumring (gratis), Midnat (50), Ørken (80), Skov (100), Nordlys (120), Havet (140), Slikland (160), Vulkan (180), Storby (200), Uvejr (230), Cyber (250), Rummet (320).
- Baggrundene står stille, men hver har en lille animation, der sker en gang imellem:

| Baggrund | Animation |
|---|---|
| Skumring | En flok fugle flyver forbi |
| Midnat, Nordlys | Stjerneskud (Nordlys har også nordlys, der bølger) |
| Ørken | En tumbleweed ruller forbi |
| Skov | Et blad falder ned |
| Havet | En delfin springer |
| Slikland | En luftballon svæver forbi |
| Vulkan | Vulkanen sprøjter lava, og gnister stiger op |
| Storby | Et fly blinker forbi, og vinduer tænder og slukker |
| Uvejr | Lyn (slået fra ved reduceret bevægelse) |
| Cyber | En scanlinje glider ned over himlen |
| Rummet | En ufo flyver forbi og stjerneskud |

## Kør lokalt

Der er ingen build. Åbn `index.html` i en browser, eller start en statisk server:

```sh
python3 -m http.server 8000
```

Mønter, rekord og køb gemmes i browserens `localStorage`.

Spillet ligger også på [Legepladsen](https://github.com/viso-collab/legepladsen).
