# MTG Decks — Daily Standard Guides

Daily Standard-legal MTGA deck guides, published as a static site:
**<https://th3pajay.github.io/mtga-decks/>**

Two new decks land every morning:

- **Daily Combo Deck** — a Standard combo build around a fresh mechanic fusion,
  with a clear engine → payoff → win line, at least two win conditions, and a
  land that is part of the win.
- **Hobbit Deck of the Day** — a combo build drawn from *The Hobbit* set (`hob`).

Each guide covers: an at-a-glance table (colors, archetype, size), the game plan
and approach, card roles, mulligan and matchup notes, and a full
Arena-import-ready decklist.

## Browsing

- **Today** — the two most recent decks.
- **Archive** — every deck ever published. Each deck keeps a permanent URL,
  e.g. `decks/2026-08-20-thieves-of-the-crooked-way.html`.

## Repo layout

- `decks/` — guide sources (Quarto markdown), one file per deck and date
- `docs/` — the rendered site; GitHub Pages serves this folder from `main`
- `index.qmd` / `archive.qmd` — the Today and Archive pages, regenerated on
  every publish

## Deck legality

All decks are Standard-legal on MTG Arena at publish time; every card is
verified against the MTGADB* card database. Decklists are in Arena import format,
ready to copy-paste.

## Disclaimer

Unofficial fan content. Not affiliated with Wizards of the Coast. Magic: The
Gathering and related marks are trademarks of Wizards of the Coast LLC.

---

\*MTGADB: a containerized Rust backend that pairs SQLite with Qdrant to power
multi-layer BGE-M3 searches (dense semantics, sparse keywords, and ColBERT
token reranking), exposing a wide array of REST endpoints (/parse, /synergy,
/search/hybrid) for the Hermes AI harness to automate deck creation and web
page publishing.
