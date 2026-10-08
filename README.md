# magicroomgames.com

Static website for Magic Room, hosted on GitHub Pages.

- `/` home
- `/tile-match/` Tile Match support and FAQ (App Store "Support URL")
- `/privacy/` Privacy Policy (App Store "Privacy Policy URL", in-game Privacy button)
- `/terms/` Terms of Use (in-game Terms button)
- `/app-ads.txt` AdMob authorized sellers file

No build step. Edit the HTML and push to `main`.

## DNS (Hostinger → GitHub Pages)

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | rodrigopecci.github.io |

Remove Hostinger's default parking `A` record (`2.57.91.91`) and any existing `www` record. Keep the `MX` records (Hostinger Email).
