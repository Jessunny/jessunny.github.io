# Jesse Dean II — Portfolio

Personal portfolio site for Jesse Dean II, IT Systems Engineer based in Nashville, TN. Built with plain HTML and CSS — no frameworks, no dependencies, no build step.

**Live site:** [jessunny.github.io](https://jessunny.github.io)

---

## What's on it

- **About** — Background, skills, and tech stack organized by category
- **Experience** — Expandable accordion cards for each role with summaries and key accomplishments
- **Projects** — 2-column grid of notable projects with descriptions and tags
- **Certifications** — Earned certs with links to Credly
- **Connect** — Contact form powered by Formspree (email stays private) + links to LinkedIn, GitHub, and Credly

---

## Tech

- Pure HTML + CSS + vanilla JS — no frameworks
- [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- [Formspree](https://formspree.io) for contact form submissions
- Hosted on [GitHub Pages](https://pages.github.com)
- Dark theme (`#0d1117` base) inspired by GitHub's color system

---

## Updating the site

Everything lives in `index.html`. To make changes:

1. Edit `index.html` locally or directly in GitHub's editor
2. Commit to `main`
3. GitHub Pages redeploys automatically — usually live within 1–2 minutes

---

## Contact form setup

The contact form submits to [Formspree](https://formspree.io/f/meepkbaq). If you ever need to change the endpoint, find this line in `index.html` and swap the URL:

```js
const res = await fetch('https://formspree.io/f/meepkbaq', {
```

Make sure to activate your Formspree form by clicking the confirmation email Formspree sends on the first submission.

---

## Deploying to a custom domain (optional)

1. Buy a domain from any registrar (Namecheap, Cloudflare, etc.)
2. In your repo, go to **Settings → Pages → Custom domain** and enter your domain
3. Add a `CNAME` file to the repo root containing just your domain (e.g. `jessedean.dev`)
4. Point your domain's DNS to GitHub Pages using their [official guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

*Built and maintained by Jesse Dean II*
