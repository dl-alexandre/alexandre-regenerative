# Alexandre Regenerative

**Restore A2/A2 Protein Powder — Hand-hauled from America’s first certified regenerative dairy to the Central Coast.**

**Live site:** [https://dl-alexandre.github.io/alexandre-regenerative/](https://dl-alexandre.github.io/alexandre-regenerative/)

---

## What it is

A fast, beautiful, mobile-first single-page site that launched the Founders waitlist for limited small-batch releases of **Restore Whole Milk Powder** and **Non-Fat Powder**, plus the signature reusable quart jar program.

- 100% static (`index.html` only) — zero build, instant deploys via GitHub Pages
- Premium earthy design (deep forest, warm cream, organic feel) served via Tailwind CDN
- Lead capture powered by Google Forms for reliable, spam-protected submissions with zero backend
- Highlights regenerative farming story, A2/A2 digestibility, single-origin traceability, and clean ingredients
- Teases the local jar model ($50 Signature Jar + $25 refills) for Central Coast customers

The site went live in May 2026 and is actively collecting early interest ahead of the first production drops.

---

## Live URL

**[https://dl-alexandre.github.io/alexandre-regenerative/](https://dl-alexandre.github.io/alexandre-regenerative/)**

The site auto-deploys from the `main` branch root. Push changes to `index.html` and GitHub Pages publishes the update in ~30–60 seconds.

---

## Deployment (already live)

No further one-time setup required. The repo is configured for GitHub Pages.

To publish updates:

1. Make your changes to `index.html`
2. Commit and push
3. Pages rebuilds automatically

**Custom domain later:** When ready, map `alexandreregenerative.com` (or similar) in the repo’s Settings → Pages panel. Update DNS records to point at GitHub’s servers.

---

## Lead Capture

Form submissions go to a Google Form (`forms.gle/oZaUSPXjW8TqJRVG6`) for maximum reliability and zero maintenance. The page offers both an embedded-style flow and a direct “open in new tab” fallback.

If you ever want to switch providers, the integration point is a single link/iframe in the waitlist section of `index.html`.

---

## Local Development

Open `index.html` directly in any browser. No server or build step needed.

Submissions will actually reach the live Google Form. To test the visual success/confirmation states locally, use DevTools or temporarily stub the redirect.

---

## Customization

Everything lives in one file for maximum simplicity:

- **Brand colors** — Search for the forest/cream palette variables and Tailwind classes
- **Headlines & body copy** — Edit directly in the HTML (kept in sync with the original spec)
- **Product details & pricing** — Jar model, bag sizes, and positioning are all in the “A BETTER PROTEIN POWDER” and “COMING SOON” sections
- **Form destination** — Update the Google Form link when needed
- **Assets** — Currently emoji + CSS. Drop in optimized photos/SVGs when you have final farm imagery and product shots
- **Social / contact** — Footer and nav links point to GitHub and @agrxculture

---

## Roadmap

Short-to-medium term priorities after launch:

1. Grow the Founders waitlist through Central Coast channels, farmers markets, and social
2. Move from waitlist → live sales (Shopify or equivalent) for both pouch and jar SKUs
3. Add real photography, customer testimonials, and third-party lab data
4. Email/SMS nurture for waitlist members
5. Evaluate custom domain + possible lightweight static-site generator if the page grows

The current MVP proved the demand signal quickly with almost no ops cost.

---

## License / Credits

Built for Dalton Alexandre — Alexandre Regenerative / Alexandre Family Farm.

Feel free to fork and adapt the approach for other regenerative ag or direct-to-consumer food projects.

---

Questions about the site, want to iterate on copy, add real visuals, or connect a CRM? Open an issue or reach out.

Let’s put regenerative A2/A2 protein in more hands. 🌾🐄
