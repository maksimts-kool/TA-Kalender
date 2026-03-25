# TA-Kalender

See projekt kasutab nüüd [`mkdocs-material`](requirements.txt), et dokumentatsiooni oleks lihtne hallata Markdowni ja piltide abil ning avaldada GitHub Pagesis.

## Kohalik käivitamine

1. Paigalda sõltuvused:

   ```bash
   pip install -r requirements.txt
   ```

2. Käivita dokumentatsiooni arendusserver:

   ```bash
   mkdocs serve
   ```

3. Ava brauseris lokaalne aadress, mille [`mkdocs serve`](README.md) käsu väljund näitab.

## Peamised failid

- [`mkdocs.yml`](mkdocs.yml) – dokumentatsiooni seadistus.
- [`docs/index.md`](docs/index.md) – avaleht.
- [`docs/veebilehe-loomine.md`](docs/veebilehe-loomine.md) – veebilehe loomise kirjeldus.
- [`docs/sisu-taiendamine.md`](docs/sisu-taiendamine.md) – sisu täiendamise kirjeldus.
- [`docs/kalendri-kasutamine.md`](docs/kalendri-kasutamine.md) – kalendri kasutamise kirjeldus.
- [`.github/workflows/deploy-docs.yml`](.github/workflows/deploy-docs.yml) – GitHub Pagesi avaldamise töövoog.
