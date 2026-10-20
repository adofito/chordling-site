# chordling.app

Chordling's site: the product page, the user guide, what is free and what is Pro, and the
privacy policy, each in English and Latin American Spanish (`es/`). It is published from
the app repository by `Scripts/publish-site.sh` to the public repository
`adofito/chordling-site` on GitHub Pages; edit it in the app repository, never there.

| Page | App Store field |
|---|---|
| `index.html` | Marketing URL |
| `guide.html` | Support URL |
| `privacy.html` | Privacy Policy URL |
| `free-and-pro.html` | — |

On launch day, flip `data-store-state="soon"` to `"live"` on the home page's call to
action, in both languages; nothing else changes.
