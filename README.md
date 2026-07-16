# Building with AI — mini workshop

A one-hour, hands-on session that takes complete beginners from "AI is a mystery" to building their first web app, just by describing it to Claude.

## What's here

- `index.html` — workshop landing page (served at the site root on Netlify)
- `ai-workshop-deck.html` — the presentation (self-contained HTML slide deck; arrow keys or on-screen buttons to advance)
- `participant-handout.html` / `participant-handout.pdf` — take-home guide: the prompt recipe, an easy/medium/hard app menu, ready-to-paste starter prompts, and a glossary
- `facilitator-guide.html` — presenter run sheet: minute-by-minute timing, the live-demo script, rescue prompts, troubleshooting
- `participant-handout-tr.txt` — Turkish translation of the handout

## Live

- Site: https://mini-ai-app-workshop.netlify.app
- Share your app: https://shareapps.netlify.app/

The site is a direct (manual) Netlify deploy of this repo's contents. It is not wired to Git, so pushes here do not auto-redeploy: redeploy manually, or connect the repo in Netlify for continuous deploys.

## Notes

Everything is static; there is no build step. Netlify serves the repo root, with `index.html` as the landing page.

Presenter: Yusuf Pisan · yusuf.pisan@gmail.com
