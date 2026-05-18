# Alexandre Regenerative

**Premium regenerative A2/A2 dairy powders — hand-hauled from family farm to the Central Coast.**

This repo hosts the official waitlist landing page at:

**https://dl-alexandre.github.io/alexandre-regenerative/**

---

## What it is

A beautiful, mobile-first single-page site built for early customer acquisition while we prepare the next farmers market cycle and small-batch hauls.

- Fully static → perfect for GitHub Pages (free hosting + custom domain support)
- Zero build step — just `index.html`
- Premium earthy design using Tailwind via CDN
- Complete lead capture form matching the spec (name, email, ZIP, interest, bag size, usage)
- Instant thank-you experience with personalized message + 15% Founders Discount callout
- Graceful demo mode (console logs + visual success even without backend)

---

## Live URL (once deployed)

After you enable GitHub Pages:

→ **https://dl-alexandre.github.io/alexandre-regenerative/**

---

## Deploying to GitHub Pages (one-time setup)

1. Go to your repo: **https://github.com/dl-alexandre/alexandre-regenerative**
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under "Build and deployment":
   - **Source**: Deploy from a branch
   - **Branch**: `master` / `(root)`
4. Click **Save**

GitHub will publish the site in ~30–60 seconds.  
Your live URL will be shown on that same page.

**Pro tip:** You can later map a custom domain (e.g. `alexandreregenerative.com`) in the same settings panel.

---

## Making the form actually save leads (IMPORTANT)

The form is currently in **demo mode**. Submissions are pretty-printed in the browser console and the success screen still appears (great for testing UX).

### Recommended: Formspree (free, 50 submissions/mo, perfect for this)

1. Go to **[https://formspree.io](https://formspree.io)** and sign up (GitHub login works)
2. Create a new form called **"Alexandre Regenerative Waitlist"**
3. Copy the endpoint URL it gives you (looks like `https://formspree.io/f/abcd1234`)
4. Open `index.html` and replace this line near the top of the `<script>`:

   ```js
   const FORMSPREE_ENDPOINT = 'https://formspree.io/f/YOUR_FORM_ID_HERE';
   ```

   with your real URL.

5. Commit + push. Done.

Formspree will email you every new lead and you can also connect it to Google Sheets, Slack, Airtable, etc.

### Alternative free backends that work great with GitHub Pages

- [Getform.io](https://getform.io)
- [Formsubmit.co](https://formsubmit.co)
- [Basin](https://usebasin.com)

All follow the same pattern — swap the `FORMSPREE_ENDPOINT` constant.

---

## Customization

Everything is in one file (`index.html`). Easy changes:

- **Brand colors**: Search for `#0c2e1f` (deep forest) and `#f8f5f0` (warm cream) in the file.
- **Headlines / copy**: Directly edit the HTML — all copy is in the spec document.
- **Form fields**: The names (`firstName`, `email`, `zipCode`, `interest`, `bagSize`, `usage`) match what Formspree will receive.
- **Logo / favicon**: Currently an inline leaf emoji. Replace with an SVG or real image path when you have assets.
- **Social links**: Footer and nav contain GitHub + Carrd links. Update X handle if needed.

---

## Future evolution (per original plan)

This GitHub Pages site is the **MVP** to start collecting names today.

Later recommended path:

1. **Short term** — Keep here or move to [Carrd.co](https://carrd.co) (beautiful + forms + cheap)
2. **Medium term** — Shopify landing page + checkout (best for actual sales)
3. **Long term** — Full branded site + Shopify + email automation (Klaviyo / ConvertKit)

The current form already qualifies people by ZIP code and captures usage intent — exactly what you need to validate demand before the next haul.

---

## Local development

Just open `index.html` in any browser. No server needed.

To test the full success flow:
- Open DevTools → Console
- Fill out and submit the form
- Watch the data appear + the thank-you screen

---

## License / Credits

Built for Dalton Alexandre — Alexandre Regenerative.  
Feel free to fork and adapt for your own regenerative projects.

---

Questions or want to iterate on the design / add photos / connect a CRM? Just open an issue or reach out.

Let’s get some Central Coast folks on the list. 🌿🐄
