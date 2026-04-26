# notion-system-icons

Index de hotlinks vers des icônes de systèmes (consoles, ordinateurs, arcades) destinés à servir d'icônes externes dans Notion.

Ce repo **ne contient pas d'images** — uniquement un index (`INDEX.md` cliquable, `index.csv` plat) qui pointe vers des images hébergées sur des repos publics tiers via GitHub raw (et jsDelivr quand la taille du repo source le permet).

## Index disponible

### Colorful 4K — `INDEX.md`

490 icônes 4K (3840×2160) issues de [`CkauNui/ckau-book-addons-Colorful-4K-Images`](https://github.com/CkauNui/ckau-book-addons-Colorful-4K-Images), **figées au commit [`5a23cf5`](https://github.com/CkauNui/ckau-book-addons-Colorful-4K-Images/tree/5a23cf5e71f9924ae97804f60259bd81e8109a7f)** (« Theme UPD 4.0 »), chemin `ckau-book-addons/_inc/arts/4K/`. Le pin par SHA protège l'index contre les renommages amont (le dossier a déjà bougé entre `anim/` et `arts/`).

- **Auteurs** : [@CkauNui](https://github.com/CkauNui), [@Lendersmark](https://github.com/Lendersmark), [@g-spawnPL](https://github.com/g-spawnPL)
- **Inspiration** : thème *Colorful* Launchbox/Bigbox de Viking
- Le repo source ne porte pas de licence explicite — tous droits réservés par leurs auteurs.

→ Voir [INDEX.md](INDEX.md) ou [index.csv](index.csv).

## Format des URLs

- **GitHub raw** : `https://raw.githubusercontent.com/<user>/<repo>/<branch>/<path>`
- **jsDelivr** (CDN, plus rapide) : `https://cdn.jsdelivr.net/gh/<user>/<repo>@<branch>/<path>` — **valable seulement si le repo source fait moins de 50 Mo** (limite jsDelivr par package). Pour les packs lourds (4K, vidéos), seul GitHub raw fonctionne.

Pour Notion : Page → Icon → Custom → URL.

> ℹ️ L'index `INDEX.md` (Colorful 4K) utilise uniquement GitHub raw — le repo source pèse ~4 Go et dépasse la limite jsDelivr.

## Pourquoi un index séparé du repo source

Pour ne pas redistribuer un contenu dont la licence n'est pas explicite, et pour pouvoir cumuler ici les index de plusieurs sources (4K, autres packs) sans dupliquer leurs images.
