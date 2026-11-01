# cleep-news

Public static feed of Cleep news for **CleepDesktop** (and any external client).

Content is published automatically as JSON + cover images.

## Feed layout

| Path | Description |
| --- | --- |
| `index.json` | Published news list (newest first) |
| `articles/{slug}.json` | Full article body |
| `covers/{slug}.{ext}` | Cover image |

## Public URL (GitHub Pages)

`https://cleepdevice.github.io/cleep-news/`

Examples:

- List: `https://cleepdevice.github.io/cleep-news/index.json`
- Article: `https://cleepdevice.github.io/cleep-news/articles/<slug>.json`

## Enable GitHub Pages

Repo **Settings → Pages → Build and deployment**:

- Source: **Deploy from a branch**
- Branch: **main** / **/ (root)**

`.nojekyll` is present so raw JSON/files are served as-is.
