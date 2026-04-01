# MS Projecti juhend

See hoidla sisaldab **MS Projecti** kasutamise õppematerjali, mis on vormistatud MkDocsi dokumentatsioonisaidina. Dokumentatsioon keskendub praktilistele töövõtetele: projektikalendri seadistamisele, arvutusväljade loomisele ja diagrammide kasutamisele projektiseisu analüüsimiseks.[^mkdocs]

> [!NOTE]
> Käesolev [`README.md`](README.md) kirjeldab **MS Projecti** haru sisu. Kui teistes harudes leidub ProjectLibre-põhist materjali, siis siin toodud teemad, kuvatõmmised ja failiviited on seotud just MS Projectiga.

## Sisukord

- [Projekti ülevaade](#projekti-ülevaade)
- [Mida hoidla sisaldab](#mida-hoidla-sisaldab)
- [Valminud teemad](#valminud-teemad)
- [Tööde loend](#tööde-loend)
- [Saiti disain](#saiti-disain)
- [Dokumentatsiooni struktuur](#dokumentatsiooni-struktuur)
- [Kasulikud lingid](#kasulikud-lingid)
- [Joonealused märkused](#joonealused-märkused)

## Projekti ülevaade

Dokumentatsioon on koostatud lühikeste ja visuaalsete samm-sammuliste juhenditena, et MS Projecti põhifunktsioonid oleksid kiiresti omandatavad.

Peamised teemad:

- kohandatud projektikalendri loomine ja kasutamine
- arvutusväljade ja valemite lisamine
- aruannete ja diagrammide koostamine ning tõlgendamine

> [!TIP]
> Hea alguspunkt on [`docs/kalender.md`](docs/kalender.md), sest see loob aluse projekti ajakava ja tööaja mõistmiseks enne valemite või aruannete juurde liikumist.

## Mida hoidla sisaldab

- dokumentatsiooni sisu kaustas [`docs/`](docs/)
- projekti visuaale ja kuvatõmmiseid kaustas [`docs/images/`](docs/images/)
- saidi seadistust failis [`mkdocs.yml`](mkdocs.yml)
- Pythoni sõltuvuste kirjeldust failis [`requirements.txt`](requirements.txt)

## Valminud teemad

### 1. Kalendri loomine MS Projectis

Dokumenteeritud failis [`docs/kalender.md`](docs/kalender.md).

Sisu hõlmab:

- tööaja muutmist
- uue kalendri loomist
- kalendri sidumist projektiga

### 2. Arvutusväljad ja valemid

Dokumenteeritud failis [`docs/arvutusvaljad.md`](docs/arvutusvaljad.md).

Sisu hõlmab:

- kohandatud väljade kasutamist
- valemite sisestamist
- arvutatud väärtuste kuvamist tabelites

### 3. Diagrammid ja aruanded

Dokumenteeritud failis [`docs/diagramm.md`](docs/diagramm.md).

Sisu hõlmab:

- aruannete vaatamist
- diagrammide loomist ja kohandamist
- edenemis- ja kulunäitajate tõlgendamist

## Tööde loend

### Valmis osad

- [x] MkDocsi põhine dokumentatsioonistruktuur on seadistatud
- [x] Avaleht on loodud failis [`docs/index.md`](docs/index.md)
- [x] Kalendri juhend on koostatud failis [`docs/kalender.md`](docs/kalender.md)
- [x] Arvutusväljade juhend on koostatud failis [`docs/arvutusvaljad.md`](docs/arvutusvaljad.md)
- [x] Diagrammide ja aruannete juhend on koostatud failis [`docs/diagramm.md`](docs/diagramm.md)
- [x] Pildimaterjal on lisatud kausta [`docs/images/`](docs/images/)

### Järgmised võimalikud täiendused

- [ ] lisada rohkem näiteid erinevate valemite kohta
- [ ] täiendada aruannete osa täiendavate filtrite või vaadete näidetega
- [ ] lisada algajatele lühike terminite ja menüüde selgitus
- [ ] kontrollida kogu dokumentatsiooni ühtset sõnastust ja kujundust

> [!IMPORTANT]
> Kui dokumentatsiooni laiendatakse, tasub hoida iga teema eraldi failis kausta [`docs/`](docs/), et navigeerimine failis [`mkdocs.yml`](mkdocs.yml) jääks lihtsaks ja hooldatavaks.

## Saiti disain

Allolevad kuvatõmmised näitavad dokumentatsioonisaidi üldist visuaalset ülesehitust ja seda, kuidas õppesisu on kasutajale esitatud.[^screens]

### Avaleht

![Dokumentatsioonisaidi avaleht](readme1.png)

### Teema lehekülg

![Dokumentatsioonisaidi teema lehekülg](readme2.png)

## Dokumentatsiooni struktuur

Praegune dokumentatsioonisait on üles ehitatud väikese, kuid selgelt fokusseeritud lehtede kogumina:

- [`docs/index.md`](docs/index.md) — avaleht, mis tutvustab õppeteemasid
- [`docs/kalender.md`](docs/kalender.md) — kalendri loomine, tööaja seadistamine ja projekti kalendri kasutamine
- [`docs/arvutusvaljad.md`](docs/arvutusvaljad.md) — kohandatud väljad, valemid ja arvutatud väärtused
- [`docs/diagramm.md`](docs/diagramm.md) — aruanded, filtreerimine ja diagrammipõhine analüüs

Nende lehtede navigeerimine on määratud failis [`mkdocs.yml`](mkdocs.yml).

> [!WARNING]
> MS Projecti menüüd ja vaated võivad sõltuda kasutatavast versioonist. Seetõttu võivad mõned nupud, sõnastused või paigutused erineda dokumentatsioonis toodud kuvatõmmistest.

## Kasulikud lingid

- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) — dokumentatsioonisaidi generaator, millele projekt toetub
- [GitHub Pages](https://pages.github.com/) — avaldatud dokumentatsiooni majutusplatvorm
- [Avaldatud dokumentatsioonisait](https://maksimts-kool.github.io/TA-Kalender) — projekti dokumentatsiooni veebiversioon

## Joonealused märkused

[^mkdocs]: Projekt kasutab MkDocsi ja Material for MkDocs teemat, et muuta õppesisu lihtsasti loetavaks ja veebis avaldatavaks.
[^screens]: Kuvatõmmised aitavad võrrelda juhendi samme päris kasutajaliidese vaadetega ning muudavad õppematerjali selgemaks.
