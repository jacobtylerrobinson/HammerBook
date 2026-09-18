# Hammerbook

**What used commercial kitchen equipment is really worth — backed by what it actually sold for.**

Hammerbook helps auctioneers, liquidators and equipment dealers put a defensible number on used commercial kitchen equipment. Photograph a unit and its data plate; get a value range built from comparable sales, with the comps shown.

Built by Jake Robinson in St. Louis, Missouri.
Contact: jakerobinson@gethammerbook.com

---

## What's in this repository

This repo holds the **public website** at gethammerbook.com.

```
index.html     The entire website. One file, no build step, no dependencies.
README.md      This file.
CNAME          Created automatically by GitHub when you set the custom domain.
```

The product itself will live in a separate repository (`hammerbook-app`) once we start building.

---

## How to change the website

You do not need to install anything or use a terminal.

1. Go to this repository on github.com
2. Click `index.html`
3. Click the pencil icon (**Edit this file**)
4. Make your change
5. Scroll down, write a short note about what you changed, click **Commit changes**

The live site updates in about a minute.

To replace the whole file instead, use **Add file → Upload files** and drop in the new `index.html`.

---

## How the site is published

GitHub Pages serves this repository at gethammerbook.com.

**Settings → Pages**
- Source: Deploy from a branch
- Branch: `main`, folder: `/ (root)`
- Custom domain: `gethammerbook.com`
- Enforce HTTPS: on

**DNS records at your registrar** — four A records on the apex domain, all pointing at GitHub:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Plus one CNAME record for `www` pointing to `jacobtylerrobinson.github.io`.

DNS changes can take anywhere from ten minutes to a few hours to take effect. The HTTPS certificate appears on its own once DNS resolves — if "Enforce HTTPS" is greyed out, wait and come back.

---

## Analytics

Cloudflare Web Analytics. Free, no cookies, no consent banner required.

Get the snippet from the Cloudflare dashboard (Analytics & Logs → Web Analytics → Add a site) and paste it into `index.html` where the marked comment block is, just above `</head>`.

It reports visits, pageviews, countries, referrers and which pages were viewed.

---

## Positioning — keep this consistent everywhere

**Hammerbook produces estimates to support pricing decisions. It does not produce certified appraisals.**

Certified appraisal is a real profession with real standards (USPAP). Never imply otherwise — in the product, in the marketing, or on a phone call.

---

## Principles

1. **The number shows its work.** Every valuation comes with the comps behind it. If we can't show why, we don't show a number.
2. **We say "I don't know" out loud.** Ranges, never false precision. We publish our error rate.
3. **We never bid against our customers.** We do not buy equipment. Ever.
4. **Built at the tailgate, not the whiteboard.** Every feature traces to watching someone price real equipment.
5. **Right beats pretty.** Nobody forgives a wrong number; everyone forgives a plain screen.
