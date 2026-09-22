# Código Descontraído — Classics

Static site for the classic car side of the business: restoration, independent buying advice,
and sales. Deployed with GitHub Pages from the repository root.

| File | What it is |
| --- | --- |
| `index.html` | The whole site — one page, anchored sections |
| `styles.css` | All styling. No build step, no framework |
| `CNAME` | Binds the custom domain |
| `favicon.svg` | Tab icon |
| `og.png` | Social preview card |
| `.nojekyll` | Stops Pages running the content through Jekyll |

## Deploying

Settings → Pages → Deploy from a branch → `main` / `/ (root)`.

The site is served at **https://classics.codigodescontraido.com** — a subdomain of the technology
site's domain, so one registration covers both businesses. `CNAME` at the repository root binds it,
and the absolute `og:url` and `og:image` in `index.html` point at it.

DNS is at Cloudflare: a CNAME record for `classics` pointing at the GitHub Pages host, set to
**DNS only** (grey cloud). If Cloudflare proxies it, GitHub cannot issue the certificate.

## Conventions this site holds to

**Disclosure.** The only company details published are the company name and the contact email.
No address, tax number, incorporation date or headcount. Same rule as the technology site.

**No invented proof.** There are no photographs of cars, no inventory, no restoration
count, no testimonials and no client names, because there were none to use. Everything on
the page is either a description of the service or a promise about how the work is done.

**Real photography is the biggest single upgrade available.** The page is deliberately
typographic so that it is honest while there are no photographs. Three or four real
photographs — a car mid-restoration, a completed car, a page of the file — would do more
for this site than any further copy or design work.

## Relationship to the technology site

Sibling of [the technology site](https://github.com/orangelash/codigo-descontraido-pages):
the same fonts, the same layered-circle motif and the same band rhythm, led by the sienna
accent instead of the petrol green so the two read as one company running two businesses.
Change the shared identity in one and the other should follow.
