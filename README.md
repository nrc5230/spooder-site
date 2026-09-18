# spooder-site

Website for [spooder.app](https://spooder.app), served by GitHub Pages. It is also the organization website for Spooder LLC's Apple Developer Program membership, so it needs to stay publicly reachable with real content on every page.

Plain HTML, no build step. Pages:

| Path | File |
|---|---|
| `/` | `index.html` — landing page |
| `/about/` | `about/index.html` — about Spooder LLC and the founder |
| `/contact/` | `contact/index.html` — "Bang my line" (nick@spooder.app) |
| `/privacy/` | `privacy/index.html` — privacy policy for the site and the app |

Shared styling lives in `styles.css`. Brand tokens (colors, Nunito, hex-web motif) mirror `SpooderBrand.swift` in the app repo. Every page's footer carries the legal name "Spooder LLC" and the contact link.
