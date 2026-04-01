# TA-Kalender

See projekt kasutab nüüd [`mkdocs-material`](requirements.txt), et dokumentatsiooni oleks lihtne hallata Markdowni ja piltide abil ning avaldada GitHub Pagesis.

## Kohalik käivitamine

1. Paigalda sõltuvused:

   ```bash
   pip install -r requirements.txt
   ```

2. Mitme versiooniga dokumentatsiooni eelvaate jaoks kasuta [`mike serve`](README.md:16):

   ```bash
   mike serve
   ```

3. Ava brauseris lokaalne aadress, mille [`mike serve`](README.md:16) käsu väljund näitab.

> Kui kasutada ainult [`mkdocs serve`](README.md:19), siis versioonivahetaja proovib laadida faili [`versions.json`](versions.json), kuid seda faili ei tekitata tavalise MkDocsi arendusserveriga. Selle tõttu on päring `GET /versions.json` lokaalselt `404`.

4. Kui soovid enne eelvaadet versioonid uuesti genereerida, kasuta näiteks:

   ```bash
   mike deploy ms-project latest
   mike deploy projectlibre
   ```

## Peamised failid

- [`mkdocs.yml`](mkdocs.yml) – dokumentatsiooni seadistus.
- [`docs/index.md`](docs/index.md) – avaleht.
- [`.github/workflows/deploy-docs.yml`](.github/workflows/deploy-docs.yml) – GitHub Pagesi avaldamise töövoog.
