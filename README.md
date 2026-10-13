# Hyacinthe Herb — hyacinthe herb llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `hyacintheherbllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/hyacintheherbllc.mjs`).
> To change the content, edit that file and run `node build.mjs hyacintheherbllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@hyacintheherbllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Shop / $Quote / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Hyacinthe Herb LLC, a Florida limited liability company (document number L21000458328), supplies culinary herbs and herbal teas to home cooks, cafés and small food businesses: single-origin dried herbs and spices with the origin and harvest stated, house spice blends mixed in small batches, loose-leaf herbal tea blends, and custom blending and wholesale quantities for cafés and makers. Samples are available before any order and every batch is labelled with its contents, origin and allergen information. Products are foods and seasonings; they are not medicines and no health or therapeutic claim is made for them. Site: hyacintheherbllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
