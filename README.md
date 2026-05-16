# RUAIRÍ — Official Site

Single-page landing site for Ruairí — DJ, producer, and artist drawing from Irish roots to create transmissions for the body, the mind and the spirit.

> *Deep bass. Ancient soul. Empowering frequency.*
> *Sacred. Ancient and now.*

## Tech

Single static `index.html` — no build step, no dependencies. Just open it in a browser or push it to any static host.

- Custom Celtic triskele SVG (animated, pulsing)
- Generated starfield background
- Scroll-reveal animations via IntersectionObserver
- Google Fonts: Cinzel (display), Cormorant Garamond (body), JetBrains Mono (accents)
- Fully responsive

## Deploying to GitHub Pages

1. Create a new public repository on GitHub (e.g. `ruairi-site` or `ruairi_rising.github.io`).
2. Upload `index.html` (and this README) to the repo root, or:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git
   git push -u origin main
   ```
3. In the repo on GitHub → **Settings → Pages**.
4. Under **Source**, select **Deploy from a branch** → branch **main**, folder **/ (root)** → Save.
5. Wait ~1 minute. Your site will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

### Optional: custom domain

In **Settings → Pages → Custom domain**, add your domain (e.g. `ruairi.com`) and follow GitHub's DNS instructions. Add a `CNAME` file at the repo root with your domain string.

## Editing

All content, colors, and links live in `index.html`. Key spots:

- **Streaming links** — search for `class="platform"` (Spotify, Apple, Amazon, Tidal, iTunes).
- **Social links** — search for `class="social"` (Instagram, Facebook, Spotify, Apple Music).
- **Spotify embed** — search for `embed-iframe` to swap the track. Replace the `src` URL with another Spotify embed link (`https://open.spotify.com/embed/track/TRACK_ID`).
- **Colors** — top of the `<style>` block, in `:root { --ember: ...; --blood: ...; }` etc.
- **Bio copy** — inside `<section class="transmission">`.

## Links

- LANDR (all platforms): https://artists.landr.com/991043798569
- Instagram: https://instagram.com/ruairi_rising/
- Facebook: https://www.facebook.com/profile.php?id=61589249663079
- Spotify: https://open.spotify.com/album/5n6MTb4okjzBdaC68Xgrt8
