# Kalendri veebilehe loomine AI abil

Selle dokumentatsiooni jaoks on nüüd kasutusel `mkdocs-material`, et GitHub Pages jaoks oleks olemas valmis dokumentatsiooni raamistik ning edaspidi saaks sisu lisada lihtsalt Markdowni, tekstide ja piltidena.

## Töö eesmärk

Eesmärk oli koostada selge ja arusaadav veebileht, mis näitab samm-sammult, kuidas AI saab aidata nii veebilehe struktuuri loomisel kui ka sisu kujundamisel.

Tulemuseks on dokumenteeriv leht, kus on olemas:

- pealkiri,
- juhendavad tekstid,
- illustratiivsed pildid,
- eraldi jaotatud sammud edasiseks täiendamiseks.

## Miks kasutada dokumentatsiooni generaatorit

Valmis staatilise HTML-lehe asemel on nüüd lihtsam kasutada dokumentatsiooni generaatorit, sest see annab kohe kaasa:

- navigeerimise mitme lehe vahel,
- ühtlase kujunduse,
- lihtsa Markdown-põhise sisu halduse,
- mugava avaldamise GitHub Pagesis.

## Dokumentatsiooni struktuur

Sisu on jagatud eraldi lehtedeks:

1. [Veebilehe loomine AI abil](veebilehe-loomine.md) – kuidas AI abil loodi veebilehe põhistruktuur.
2. [Sisu täiendamine](sisu-taiendamine.md) – kuidas lisati oma tekstid ja visuaalid.
3. [Kalendri kasutamine](kalendri-kasutamine.md) – kuidas kalender aitab ajakava planeerida.

## Pildid

Allolevad illustratsioonid jäävad dokumentatsiooni osaks ka uues struktuuris.

![AI abil koostatud veebilehe ülesehituse illustratsioon](images/ai-layout.svg)

![Kalendri ja ajakava seose illustratsioon](images/calendar-overview.svg)

## Viited ja lisalugemine

Selle dokumentatsiooni ülesehitus toetub [`mkdocs-material`](https://squidfunk.github.io/mkdocs-material/)-i võimalustele, et sisu oleks lihtne laiendada ja GitHub Pagesis avaldada.

!!! info "Kasulikud allikad"
    - [MkDocs Material Reference](https://squidfunk.github.io/mkdocs-material/reference/) – ülevaade kõikidest sisuelementidest.
    - [Admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/) – märkus- ja info-plokkide lisamine.
    - [Content tabs](https://squidfunk.github.io/mkdocs-material/reference/content-tabs/) – sisu jaotamine vahelehtedesse.
    - [Footnotes](https://squidfunk.github.io/mkdocs-material/reference/footnotes/) – märkuste ja viidete lisamine teksti sisse.[^material]

=== "Milleks need viited kasulikud on?"

    Need viited aitavad dokumentatsiooni hiljem täiendada ühtlases stiilis, näiteks lisada hoiatusplokke, sammude võrdlusi või täiendavaid märkusi.

=== "Mida siin projektis juba kasutatakse?"

    Praegu on dokumentatsioonis kasutusel mitmelehelinė struktuur, pildid, loendid ja märkusplokid. Vajadusel saab järgmise sammuna lisada ka vahelehti, jaluseid ja detailsemaid visuaalseid sisukaste.

[^material]: Materjali referentslehed annavad valmis süntaksi, mida saab otse Markdowni sisse kopeerida ja kohandada.
