# Expansion Radar

A customer success daily-AI-build. Scores an account's expansion readiness across five weighted signals (usage depth and growth, organisational spread, champion advocacy, buying signals, timing fit) and returns the specific upsell or cross-sell play to run, not just a health number.

Companion piece to [Pulse Check](https://github.com/kakkarprerna/pulse-check), which diagnoses risk. Expansion Radar diagnoses growth.

Deterministic scoring, no AI model call, no API key required, nothing entered ever leaves the browser. Every input field also takes a custom, user-typed option when the presets don't fit.

Static HTML/CSS/JS, no build step, no dependencies.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```
npx serve .
```

## Deploy

Deployed on Vercel as a static site. See the deploy commands used for this build, or run:

```
vercel --prod
```
