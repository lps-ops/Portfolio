# Lucas Seewald — Marketing Manager Portfolio

Personal portfolio website for Lucas Seewald, Marketing Manager.

🌐 **Live site:** [lucasseewald.com](https://lucasseewald.com)

---

## Tech

Single-file HTML portfolio — all images are base64-embedded, no build step required.

- `index.html` — the entire site (HTML + CSS + JS + embedded images)

---

## How to update

1. Edit `index.html` locally (or directly on GitHub)
2. Commit and push to `main`
3. Netlify auto-deploys within ~30 seconds

### Common updates

| What | Where in index.html |
|------|---------------------|
| Your name / bio text | Search `hero-name`, `about-body` |
| Job title / eyebrow | Search `hero-eyebrow` |
| Stats (years, leads etc.) | Search `stat-num` |
| Work card titles & descriptions | Search `data-title=` |
| Add a new work card | Copy any `.work-card` block, update text & image |
| LinkedIn URL | Search `linkedin.com/in/lucas-seewald` |
| Formspree ID (contact form) | Search `YOUR_FORMSPREE_ID` |
| Replace a photo | Swap the base64 string in the relevant `src=` or `url(` |

---

## Deployment (Netlify — recommended)

1. Push this repo to GitHub
2. Go to [netlify.com](https://netlify.com) → **Add new site** → **Import from Git**
3. Select this repo, set **Publish directory** to `/` (root)
4. Click **Deploy** — done

Netlify will auto-redeploy on every push to `main`.

### Custom domain
In Netlify: **Site settings → Domain management → Add custom domain**

---

## Contact form setup (Formspree)

1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form → copy the form ID (looks like `xpzgkrqw`)
3. In `index.html`, find `YOUR_FORMSPREE_ID` and replace it with your ID
4. Push the change — contact form will now deliver emails to your inbox

---

## Local preview

Just open `index.html` in any browser — no server needed.
