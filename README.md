# josephwilebski.com

Personal brand website for Joseph Wilebski — digital marketing executive, consultant, and practitioner.

**Live site:** [josephwilebski.com](https://josephwilebski.com)

---

## About

This is the source code for josephwilebski.com — a static HTML personal brand site covering:

- Professional background and career history
- Areas of expertise and consulting services
- Project portfolio (agency, web apps, directory sites)
- Insights / blog
- Resources and tools
- Contact / connect

---

## Tech Stack

- **Pure HTML / CSS / JavaScript** — no frameworks, no build step
- **Hosted on Cloudflare Pages** — global CDN, auto-deploys on push
- **Google Fonts** — Cormorant Garamond + DM Sans
- **Responsive** — mobile, tablet, and desktop

---

## Repo Structure

```
josephwilebski.com/
├── index.html          # Main site (single page)
├── images/
│   └── avatar.png      # Profile avatar
├── robots.txt          # Search engine crawler rules
├── sitemap.xml         # XML sitemap for SEO
└── README.md           # This file
```

---

## Deployment

This site deploys automatically via **Cloudflare Pages**.

Every push to the `main` branch triggers a new deployment. No build command or output directory configuration needed.

**Manual deploy:**
1. Push changes to `main`
2. Cloudflare Pages detects the push and deploys within ~60 seconds
3. Changes are live at josephwilebski.com

---

## Local Development

No build tools required. Just open `index.html` in a browser:

```bash
# Option 1 — open directly
open index.html

# Option 2 — serve locally with Python
python3 -m http.server 8000
# Then visit http://localhost:8000
```

---

## Roadmap

- [ ] Add blog/insights posts
- [ ] Build out Resources section with live tools
- [ ] Add Agency project page
- [ ] Add Web Apps portfolio
- [ ] Add Directory Sites portfolio
- [ ] Add Calendly booking integration
- [ ] Add contact form
- [ ] Add speaking page
- [ ] Add case studies

---

## Contact

**Joseph Wilebski**  
[linkedin.com/in/josephwilebski](https://www.linkedin.com/in/josephwilebski/)

---

*Executive strategy. Operator precision.*
