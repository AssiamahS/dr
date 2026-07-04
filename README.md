# Dr. Andrew Assiamah — legacy site

Live at **drandrewassiamah.com** (also drassiamah.com and andrewassiamah.com via redirect).

Single-page static site, no build step. Hosted on GitHub Pages from `main`.

## Add photos

Drop images into `photos/` named `1.jpg` through `6.jpg`, commit, push.
They replace the gallery placeholders automatically — no code changes needed.

## Edit content

Everything lives in `index.html`. Sections in order: hero, His Work (bio + timeline),
Honors (Healing Spirit Award + press links), Gallery, Give (donation links).

## DNS (Spaceship)

All three domains are registered at Spaceship. For `drandrewassiamah.com`:

| Type  | Host | Value                 |
|-------|------|-----------------------|
| A     | @    | 185.199.108.153       |
| A     | @    | 185.199.109.153       |
| A     | @    | 185.199.110.153       |
| A     | @    | 185.199.111.153       |
| CNAME | www  | assiamahs.github.io   |

For `drassiamah.com` and `andrewassiamah.com`: use Spaceship's URL-redirect
feature to forward to `https://drandrewassiamah.com` (301, with path).
