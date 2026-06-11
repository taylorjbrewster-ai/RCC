# Deploy — mylocalsoftware.com

All canonical URLs, schema, sitemap, and robots.txt point to `https://mylocalsoftware.com/`. A `CNAME` file is included for GitHub Pages custom-domain hosting.

## Push changes

```bash
cd "/Users/taylor/Claude/Projects/RESATRAUNT COST CONSULTANT/restaurant-cost-consulting"
git add .
git commit -m "Update site"
git push
```

## Domain setup (one-time)

**If hosting on GitHub Pages:** repo → Settings → Pages → Custom domain → `mylocalsoftware.com` → Save, and check "Enforce HTTPS". At your DNS provider, point the apex A records to GitHub Pages (185.199.108.153 / .109. / .110. / .111.) or follow the instructions GitHub shows.

**If hosting on Vercel:** Project → Settings → Domains → add `mylocalsoftware.com` and follow the DNS instructions. The CNAME file is ignored by Vercel (harmless).

## After it's live (SEO checklist)

1. **Google Search Console** — add `mylocalsoftware.com` as a Domain property, verify via DNS, submit `https://mylocalsoftware.com/sitemap.xml`.
2. **Bing Webmaster Tools** — import from Search Console in one click.
3. **Activate the contact form** — submit it once; FormSubmit emails taylorjbrewster@gmail.com a one-time confirmation link.
4. **Backlinks** — directory listings + partner-company links (Town, processors, energy brokers); low-competition niche, a few links go far.

## Site structure (clean URLs)

| URL | Primary keyword |
|---|---|
| / | restaurant cost consultant |
| /online-ordering-commissions/ | reduce third-party delivery commissions (→ 0% with Town) |
| /payment-processing/ | lower restaurant credit card processing fees (→ 0% dual pricing) |
| /utilities/ | reduce restaurant utility costs |
| /restaurant-operating-costs/ | restaurant operating costs breakdown |
| /savings-calculator/ | restaurant savings calculator |

Old `.html` URLs redirect to the clean equivalents (noindex stubs). `flyer.html` is the printable handout with a built-in Download PDF button.
