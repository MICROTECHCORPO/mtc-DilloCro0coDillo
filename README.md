<img width="1024" height="519" alt="92340108-744a-4a04-b6e9-f1f7556bfc0b" src="https://github.com/user-attachments/assets/699415db-5df4-4aee-b7ed-5be7f67675f5" />


# DilloCrocodilo

DilloCrocodilo to ekskluzywny, polski brand streetwearowy i taktyczny z mocnym charakterem premium, z naciskiem na unikatowość, lokalną produkcję i limitowane serie kolekcjonerskie. Marka łączy estetykę militarną, industrialną oraz luksusową z motywem krokodyla-granatu jako symbolu tożsamości.

Live demo: https://dillocroocodillo.base44.app

<img width="1024" height="519" alt="6deed36b-f842-49fe-87d0-44ac229e108d" src="https://github.com/user-attachments/assets/a1d7e1cd-1487-403c-83ea-ba1c9f2c06a2" />

## Misja

Tworzymy kolekcje, które nie są masowe: każda sztuka ma być wykonana na zamówienie, w małych seriach, z dużą dbałością o materiał, haft, jakość wykończenia i autentyczność produktu. W centrum stoi idea: prawdziwe, limitowane, wearable art.

<img width="1024" height="519" alt="6a61fba4-9c7e-4a40-8d7c-79744dc32b9f" src="https://github.com/user-attachments/assets/ba150e29-6ca1-45bb-b742-edcae5d2853c" />

## Filozofia produktu

- 100% unikatowość: każda kolekcja jest zaprojektowana jako seria limitowana
- produkcja na zamówienie: małe nakłady, maks. 5 egzemplarzy jednego wzoru
- tkanina premium: gruba bawełna, ciężkie gramatury, trwały krój
- haft 3D i hybrydowy: detale, relief, mocny charakter wizualny
- NFC / QR / certyfikat: każda sztuka ma własną tożsamość i autentyczność
- kultura kolekcjonerska: produkty mają być traktowane jako obiekty premium, nie zwykły towar

## Główne linie kolekcji

### 1. Streetwear Core
Klasyczna warstwa premium z mocnym, surowym, streetwearowym charakterem.

### 2. Cannabis Crew
Kolekcje inspirowane kulturą cannabis, ale wyrażone w estetyce premium i artystycznej. Wersje bardziej kolekcjonerskie niż typowe merchy.

### 3. Syndykat Wear
Najbardziej ekskluzywne serie premium z mocnym nadrukiem, haftem 3D i numeracją limitowaną.

### 4. Cultivar Series
Serie kolekcjonerskie z motywem roślin, kultivarów, premium grow-art, numeryzowane i opatrzone certyfikatem.

### 5. Chapter Drops
Limitowane edycje poświęcone konkretnym lokalizacjom i inspiracjom artystycznym (np. Colombia, Ukraine, Poland, etc.).

## Struktura repozytorium

```text
mtc-DilloCro0coDillo/
├── .github/
│   └── workflows/
│       └── ci.yml
├── app/
│   ├── README.md
│   ├── package.json
│   └── pages/
│       └── index.js
├── api/
│   ├── package.json
│   └── src/
│       └── index.js
├── contracts/
│   ├── package.json
│   ├── hardhat.config.js
│   └── contracts/
│       └── DilloToken.sol
├── docs/
│   ├── BIZNES_PLAN.md
│   ├── PRODUKCJA_Polska.md
│   ├── TOKENIZACJA_RWA.md
│   ├── QC_AND_BATCH.md
│   ├── NFC_AND_TOKENIZATION.md
│   ├── MARKETPLACE_STRATEGY.md
│   └── ROADMAP.md
├── assets/
│   └── images/
├── collections/
├── products/
├── README.md
├── LICENSE
├── .gitignore
└── CONTRIBUTING.md
```

## Produkcja i jakość

### Standard produkcji
- Tkanina: gruba bawełna, heavyweight 240–320 GSM
- Krój: oversize / boxy / premium fit
- Szycie: pre-order / made to order
- Seria: max 5 egzemplarzy jednego wzoru
- Haft: 3D / puff embroidery, hafty o wysokiej gęstości
- Wzornictwo: indywidualne, ręcznie dopracowane, nie masowe

### Kontrola jakości
Każda sztuka powinna przejść pełną kontrolę:
- poprawność wykonania haftu
- poprawność kroju i rozmiaru
- poprawność wszycia NFC / tagu / certyfikatu
- numeracja seryjna i zapis w bazie
- zdjęcia dokumentacyjne przed wysyłką

## NFC / certyfikacja autentyczności

Każda wykonana sztuka będzie miała przypisany unikalny identyfikator, który będzie powiązany z:
- NFC tagiem lub tagiem QR
- certyfikatem produktu
- numerem edycji / serialem
- metadata w systemie
- ewentualnym tokenem NFT lub proof-of-authenticity

Model rekomendowany:
- 1 autoidentyfikacja produktu = 1 unikalny serial
- 1 token NFT / rekord = 1 sztuka fizyczna
- NFC / QR jako warstwa fizycznej weryfikacji
- on-chain hash lub poświadczenie autentyczności w strukturze metadata

## Rekomendowany stack technologiczny

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- PWA / landing page / katalog produktów

### API / backend
- Node.js + Express lub NestJS
- PostgreSQL / Supabase
- API do zamówień, certyfikatów i NFC verification

### Smart contracts
- Hardhat / Foundry
- ERC-721 lub ERC-1155 dla certyfikatów / NFT
- on-chain metadata i proof-of-ownership

### Produkcja i logistyką
- małe serie, pre-order, personalizacja, numeracja seryjna
- pełna dokumentacja product QC i fulfillment

## Roadmap

### Faza 1 — foundation
- setup repo
- struktura katalogów
- README i dokumentacja
- podstawowy landing page
- katalog produktów i kolekcji

### Faza 2 — product system
- series architecture
- numeracja edycji
- produkt + certyfikacja
- NFC / QR verification

### Faza 3 — commerce
- marketplace-ready store
- shop flow
- drop system
- pre-order i ograniczone wycofanie produktu

### Faza 4 — collector layer
- NFT / auth layer
- wallet / claim / verify flow
- premium packaging i collectible experience

## Galeria / brand assets

Poniżej podstawowe sekcje, które powinny zostać zasponsorowane i od razu uzupełnione w katalogu `assets/images/`.

```text
assets/images/
├── 01_logo_gold.png
├── 02_grenade_guitar.png
├── 03_crest_logo.png
├── 04_product_shot.png
├── 05_plush_set1.png
├── 06_action_rain.png
├── 07_plush_set2.png
├── 08_action_duo.png
├── 09_colombia_ukraine.png
├── 10_poland_gold.png
├── 11_cultivar_set.png
├── 12_gold_cultivar_case.png
├── 13_purple_og_case.png
├── 14_display_variants.png
├── 15_purple_haze_case.png
└── hero_banner.png
```

## Projekt ten ma być traktowany jako:

- projekt brandu premium
- projekt kolekcji streetwearowych
- system produktów premium i limitowanych
- prototyp platformy z certyfikatem autentyczności
- struktura pod merch, NFT, game-like brand experience oraz marketplace integration

## Wartości marki

- brutalna estetyka
- premium quality
- limitowane wydania
- kolekcjonerski charakter
- polski rzemieślniczy standard
- integracja z NFT / NFC / proof of ownership

## Kontakt / dalsze kroki

Repozytorium jest projektem rozwojowym. W kolejnych krokach planujemy:
- uzupełnić katalog obrazów i mockupów
- dodać pełną dokumentację produkcyjną
- zbudować frontend katalogu produktów i landing page
- przygotować system certyfikacji NFC i tokenizacji
- stworzyć workflow dropów premium i kolekcjonerskich

Dla tego projektu ważne są trzy zasady:
1. małe serie, duża jakość
2. unikatowe wzory i serializacja
3. autentyczność jako element premium

---
DilloCrocodilo — premium streetwear, made-to-order, collectible by design.
