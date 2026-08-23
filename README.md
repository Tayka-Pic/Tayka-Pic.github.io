# tayka.app

The public face of **Tayka**: one photo prompt a day, the same one for
everyone in the world at the same instant.

The app's source lives in a private repository. This one holds only what the
outside world needs to see.

| Path | What it is |
|---|---|
| `index.html` | Landing page. Where an invite link points until the App Store listing exists. |
| `privacy/index.html` | Privacy policy. The canonical copy, and App Store submission requires a reachable URL. |
| `terms/index.html` | Terms of Use. Guideline 1.2 requires users to agree to these, so the sign-in screen links here. |
| `app-ads.txt` | Authorizes Google to sell Tayka's ad inventory, so a spoofer cannot claim it. Takes effect once an App Store listing names this site as the marketing URL. |
| `CNAME` | Holds `tayka.app`. This file is what tells GitHub Pages to serve the site on the custom domain, so deleting it silently moves the site back to `tayka-pic.github.io` and breaks every link the App Store listing points at. |

Served by GitHub Pages at <https://tayka.app>. The old
`tayka-pic.github.io` address still resolves and redirects here.

Contact: support@tayka.app
