# Elektronika — Zápisky & vzorové příklady

Interaktivní jednostránkový studijní web z elektrotechniky pro **1. ročník střední průmyslové školy**.
Témata: kondenzátory, cívky, magnetismus, Ohmův zákon, Kirchhoffovy zákony, baterie,
elektrostatika, Ampérovo pravidlo a Flemingovo pravidlo — každé s vysvětlením, vzorci
a vzorovými příklady, které mají skryté řešení.

## Funkce

- 📚 Rozklikávací karty pro každé téma
- 🔍 Fulltextové vyhledávání napříč všemi zápisky (se zvýrazněním)
- ↕️ Rozbalit / sbalit vše
- 🧮 Vzorové příklady ve třech úrovních obtížnosti (lehké / střední / těžké) s rozbalovacím postupem
- 🎛️ Filtr příkladů podle obtížnosti napříč všemi tématy
- 📱 Responzivní, funguje na mobilu i desktopu
- ⚡ Žádný build, žádné závislosti — čisté HTML/CSS/JS

## Spuštění lokálně

Stačí otevřít `index.html` v prohlížeči. Žádná instalace není potřeba.

## Nasazení na Netlify

1. Nahraj tento repozitář na GitHub.
2. Na [Netlify](https://app.netlify.com) → **Add new site → Import an existing project**.
3. Vyber repozitář. Build command nech **prázdný**, publish directory nastav na `.` (kořen).
4. Deploy. Hotovo.

Alternativně můžeš celou složku jen přetáhnout do Netlify Drop: <https://app.netlify.com/drop>

## Struktura

```
.
├── index.html         # celá aplikace (HTML + CSS + JS)
├── examples-data.js   # data vzorových příkladů (obtížnost, zadání, postup, výsledek)
├── netlify.toml       # konfigurace nasazení
└── README.md
```
