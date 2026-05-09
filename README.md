# Helen Palacios — Personal Website

Static HTML/CSS/JS portfolio site. No build step required.

## Files

- `index.html` — Main site (English)
- `llms.txt` — LLM discoverability file (for ChatGPT, Perplexity, Claude)
- `robots.txt` — Crawler permissions
- `Helen_Palacios_Resume_2026.pdf` — English resume (downloadable)
- `Helen_Palacios_CV_2026_ES.pdf` — Spanish CV (downloadable)

## Deploy options

### Vercel (recommended for ease)
1. Drag the folder onto https://vercel.com/new
2. Or: `npm i -g vercel && vercel`

### Netlify
1. Drag the folder onto https://app.netlify.com/drop
2. Or: connect a Git repo at netlify.com

### GitHub Pages
1. Push folder to a public repo
2. Enable Pages in Settings → Pages → Branch: main, Folder: /

## Custom domain
Recommended: `helenpalacios.com` or `helen-palacios.com`

After domain is configured, update:
- `<meta property="og:url">` in index.html
- `Schema.org sameAs` array if needed

## Next steps before launch

1. **Add a real photo** — replace the `.about-photo span` placeholder with a real `<img>` tag
2. **Confirm bio copy** with Helen
3. **Add real metrics** to role descriptions when available (CTR %, ROAS, traffic uplift, etc.)
4. **Optional: add testimonials section** if there are recommendations from past managers/clients
5. **Optional: add case studies** as separate pages (`/case-studies/tecnolite.html`)
6. **Create OG image** (1200x630px) — currently no social preview image is set
7. **Add favicon.ico** to root

## SEO notes

- All content is server-rendered (no JS required for crawling)
- Schema.org Person markup is included
- llms.txt provides structured context for AI search engines
- Meta description and Open Graph tags are present

## Browser support

Uses modern CSS (custom properties, `aspect-ratio`, `backdrop-filter`).
Tested on: Chrome, Safari, Firefox, Edge (current versions).
