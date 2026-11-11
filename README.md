# ROM Log

A personal tracker for Pokémon ROM hacks and fan games. Static site (GitHub Pages); all data lives in `data/games.json`.

- `index.html` – the app (Now / Library / Stats, quick log, editor)
- `data/games.json` – the games
- `data/sprites.json`, `data/species.json` – Pokémon name lookups (sprites load from the PokeAPI sprites repo)

Editing from a device: footer → Edit mode & settings → paste a fine-grained GitHub token (Contents: read/write on this repo only). Without a token the site is read-only.
