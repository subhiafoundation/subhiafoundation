# Subhia Foundation landing site

Single-page site for **https://subhiafoundation.org/**, hosted on GitHub Pages.

## Files to deploy (repo root)

| File | Purpose |
|------|---------|
| `index.html` | Main page |
| `robots.txt` | Crawlers + sitemap URL |
| `sitemap.xml` | Single URL for Search Console |
| `CNAME` | Must contain exactly: `subhiafoundation.org` |

## Custom domain (GitHub Pages)

1. **Settings → Pages → Custom domain:** `subhiafoundation.org`
2. **DNS:** A records for `@` to GitHub Pages IPs (`185.199.108.153` … `185.199.111.153`), or your provider’s GitHub Pages setup.
3. **Enforce HTTPS** after DNS verifies.

Canonical URLs and SEO metadata use **`https://subhiafoundation.org/`** (apex). If you also use `www`, redirect **www → apex** so Google has one primary URL.

## Google Search Console

Submit: `https://subhiafoundation.org/sitemap.xml`

Use a **Domain** property for `subhiafoundation.org` if possible.
