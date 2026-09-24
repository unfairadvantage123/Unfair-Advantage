# The Unfair Advantage — Website

AI coaching for Australian business owners.

## Files
- `index.html` — the full website (self-contained: styles, fonts, scripts and images are embedded).
- `forms.html` — lets Netlify detect the contact form at deploy time. Keep it.
- `images/daniel-portrait.jpg` — original portrait, kept for reference / future edits.
- `images/logo-primary-dark.png` / `images/logo-primary-light.png` — logo artwork for dark and light backgrounds.
- `netlify.toml` — Netlify config (publish from repo root).

## Deploy (Netlify + GitHub)
1. Push this folder to your GitHub repository.
2. Netlify → Add new site → Import an existing project → GitHub → pick the repo.
3. Build command: leave empty. Publish directory: `.`
4. After first deploy: Forms → enable form detection, redeploy, then add an email notification under Forms → Form notifications.
