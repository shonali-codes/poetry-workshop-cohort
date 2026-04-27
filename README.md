# Poetry Workshop Cohort — May–June 2026

A private cohort hub for *The Power of Poetry — Monthly Cohort*, hosted as an unlisted site on GitHub Pages.

## Files in this repository

| File | Purpose |
|------|---------|
| `index.html` | The hub page — schedule, opening framing, and navigation to all 10 modules |
| `module-01.html` through `module-10.html` | One page per module |
| `styles.css` | Shared stylesheet used by all pages |
| `README.md` | This file |

## How to deploy

1. **Create a new repository on GitHub** named `poetry-workshop-cohort` under your `shonali-codes` account.
2. **Upload all files** (HTML files, CSS file, this README) to the repository root.
3. **Enable GitHub Pages** in the repository settings:
   - Go to Settings → Pages
   - Under "Source", select `main` branch and `/root` folder
   - Save
4. **The site will be live** at `https://shonali-codes.github.io/poetry-workshop-cohort/` within a minute or two.

The site is marked `noindex, nofollow` in its meta tags, so search engines will not index it. It is accessible only to those who know the URL.

## Links to activate before the workshop begins

Several placeholder links need to be replaced with real URLs before the workshop starts. They are marked with `href="#" data-link="..."` in the HTML. When clicked, they currently show a friendly "this will be activated before the workshop begins" alert.

### Links to activate:

| Data-link identifier | What it should link to | Where it appears |
|---------------------|------------------------|-------------------|
| `zoom` | Your Zoom/Meet session link | Hub page resources |
| `feedback` | Post-class feedback Google Form | All pages |
| `homework` | Homework submission portal (can be one shared Form or 10 separate) | Hub page resources |
| `questions` | General questions form | Hub page resources |
| `community` | WhatsApp/Discord/Signal group link | Hub page resources |
| `submit-hw1` through `submit-hw10` | Individual homework submission links per module | Each module page |
| `meditation-link` | Soumitra Chatterjee Gitanjali recitation (YouTube or similar) | Module 08 |

### How to activate a link

1. Open the HTML file in any text editor
2. Find the placeholder: `href="#" data-link="feedback"`
3. Replace with the real URL: `href="https://forms.gle/yourformlink" data-link="feedback"`
4. Save. Commit to GitHub. The update goes live in about a minute.

You can also remove the `data-link` attribute after linking if you prefer — it is only used to trigger the placeholder alert for unlinked items.

## Editing the feedback questions

The feedback form is a Google Form (not part of this website). You can edit the questions any time at forms.google.com without redeploying the website. The link from the website stays the same.

## Editing module content

Module content lives directly in each module HTML file. To change the intention, pointers, or homework framing for any module:

1. Open the relevant `module-XX.html` file
2. Edit the text within the HTML (the structure — tags, classes — should stay the same)
3. Save. Commit to GitHub. The change goes live within a minute.

## Adding a new participant

No code changes needed. Simply:
1. Add them to your Mailchimp audience
2. Send them the welcome email with the hub URL and meeting link
3. Share the feedback form and homework submission form links

## Questions

If anything on the site breaks or needs adjusting, you have a full Claude conversation record to return to for help.

By God's grace, this space is ready to receive its four poets.

— built with care
