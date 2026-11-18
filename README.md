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

- Contact form posts to FormSubmit (poomsonline@gmail.com). The first submission sends a one-time activation email — click the link in it to start receiving enquiries.
