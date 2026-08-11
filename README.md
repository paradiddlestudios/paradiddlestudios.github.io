# Paradiddle Studios — website

Static site for Paradiddle Studios. Plain HTML and one stylesheet; no build
step, no dependencies, no JavaScript.

It exists mainly to satisfy something both app stores require: a **public,
permanently reachable privacy-policy URL and support URL**. A policy URL that
later 404s is grounds for the app being *removed*, not merely rejected — so
this repo should stay public and stay alive for as long as the games are
listed.

## Pages

| Path | Purpose |
|---|---|
| `/` | Studio landing page and game list |
| `/privacy/` | Privacy policy for Bajutsu Love — **the URL given to both stores** |
| `/support/` | Support and contact — **the other URL both stores require** |

## Contact address

`paradiddle.studios.2026@gmail.com`, in all three pages. It is the address
given to both stores, so changing it means updating the store listings too —
not just this repo.

## Deploying

GitHub Pages, served from the default branch root. Settings → Pages → Deploy
from a branch → `main` / `/ (root)`. `.nojekyll` is present so the files are
served exactly as they are.

Every internal link is **relative**, so the site works unchanged at a project
URL (`user.github.io/repo/`), an organization URL, or a custom domain root —
attaching a domain later does not require touching the markup.

## Notes

- Palette is taken from the Bajutsu Love UI theme: navy `#2C2A3E`, gold
  `#F2C879`, sakura `#F6C6D0`, cream `#FBF3E4`.
- The mark is a paradiddle — `R L R R / L R L L`, filled for right, outlined
  for left. It is inline SVG in each page; there is no image file to keep in
  sync.
- `assets/bajutsu-love.png` is the shipping app icon, copied from the game
  repo. Re-copy it if the icon ever changes.
- Marketing copy follows the same rule as the game: **it is played straight.**
  The premise is stated deadpan and never winked at.
