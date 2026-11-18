# Aventurerz — Company Website

Static marketing site for **Aventurerz**, a software engineering company (web, mobile, DevOps & AI).

## Structure

| Path | Page |
|------|------|
| `index.html` | Home |
| `about.html` | About & team |
| `services.html` | Services, process, engagement models |
| `work.html` | Project portfolio (filterable) |
| `contact.html` | Contact form & details |
| `assets/` | Logo files (SVG + PNG) |
| `vercel.json` | Clean URLs (`/about` instead of `/about.html`) |

No build step — plain HTML, inline CSS and a little vanilla JS.

## Local preview

```bash
npx serve .
```

## Deploy

Hosted on Vercel. Every push to `main` deploys automatically.

## To do

- Replace `[YOUR EMAIL]`, `[YOUR PHONE]`, `[YOUR OFFICE ADDRESS]` and `[YOUR CITY, COUNTRY]` placeholders.
- Connect the contact form to a form service (e.g. Formspree) or a Vercel function — see the `TODO` in `contact.html`.
