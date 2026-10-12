# Lewis & Co Advocates — Production Website

Static, responsive 8-page website using the established reference law-firm design system. No build step or runtime dependency is required.

## Firm details
- Official firm name: Lewis & Co Advocates
- Founder & Managing Partner: Lewis Gicheha Karanja (as published on the firm's WordPress site)
- Office: Muthaiga Square, 2nd Floor, Office 203, Nairobi, Kenya
- Telephone / WhatsApp: +254 718 262 673
- Email: info.gladvocates20@gmail.com

## Files
- `index.html` homepage
- `/about/`, `/practice-areas/`, `/managing-partner/`, `/insights/`, `/contact/`, `/privacy/`, `/terms/`
- `assets/site.css`, `assets/site.js` are shared, dependency-free
- `assets/lewis-logo-transparent-4k.png` and `assets/lewis-logo-footer-4k.png` are transparent 3840-pixel-wide versions processed from the supplied logo
- `assets/lewis-gicheha-portrait.webp` and `assets/lewis-gicheha-office.webp` are the two user-supplied images

## Contact form
The form prepares an email in the visitor's email app. It DOES NOT transmit or store submissions on a server. Wire up a secure form service only if the owner requests it; do not imply delivery in its current state.

## Hosting
Deploy this folder as a static site through Vercel (Other framework, root directory, no build command). `vercel.json` includes routing and security headers.

```bash
# From the website directory
npx vercel --prod
```

## Online photographs
Distinct Pexels image IDs used across sections (see `PHOTO-SOURCES.md`). They are externally hosted and may become unavailable: confirm image loading and appropriate licensing before final public launch. No generated images used.

## Source references
- [Legal profile](https://gichehalewis.wordpress.com/2020/08/20/legal-profile/)
- [Gicheha Lewis profile](https://gichehalewis.wordpress.com/2024/08/09/gicheha-lewis-profile/)
- [Articles and firm journal](https://gichehalewis.wordpress.com/)

The WordPress profile contains an older office suite and some differently formatted contact details. The current user-supplied Muthaiga Square 2nd Floor Office 203 and contact email/telephone take precedence.

## Before publishing
Confirm the firm's preferred domain, consent to display portrait/logo, the suite number and email accuracy, and the legal wording of policy pages.

## SEO

The site includes unique page titles and descriptions, canonical links, Open Graph / Twitter sharing metadata, LegalService JSON-LD and an XML sitemap. After deployment, verify `/sitemap.xml` and submit the sitemap in Google Search Console. Google indexing is not automatic or guaranteed.
