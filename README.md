# SPL Test - Procvičování otázek

Webová aplikace pro procvičování otázek na pilotní průkaz SPL (Sportovní pilot letadla).

## Funkce

- 137 otázek z různých kategorií
- Náhodné pořadí otázek
- Filtrace podle kategorií
- Okamžitá zpětná vazba
- Sledování statistik správných/špatných odpovědí
- Responzivní design (funguje na mobilu i desktopu)

## Kategorie otázek

- Letecké výkony a plánování
- Lidská výkonnost a omezení
- Meteorologie
- Navigace
- Provozní postupy
- Předpisy
- Všeobecné znalosti letadel
- Základy letu

## Live demo

🌐 **https://susiox.github.io/aeropilot-exam-prepX2/**

## Nasazení na GitHub Pages

1. Vytvořte nový repozitář na GitHubu
2. Nahrajte soubory `index.html` a `questions.json`
3. V nastavení repozitáře povolte GitHub Pages (Source: Deploy from a branch, Branch: main)
4. Aplikace bude dostupná na `https://[username].github.io/[repo-name]`

## Struktura projektu

```
spl-quiz-app/
├── index.html      # Hlavní aplikace
├── questions.json  # Databáze otázek
└── README.md       # Tento soubor
```

## Technologie

- Vanilla JavaScript (bez frameworků)
- CSS3 s flexbox/grid
- JSON pro data

## Licence

Vzdělávací účely. Otázky jsou z oficiálních testů SPL.
