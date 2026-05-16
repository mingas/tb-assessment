# Testosterone Blueprint Assessment Tool

Interactive testosterone assessment tool deployed at [testosteroneblueprintguide.com/testosterone-test](https://testosteroneblueprintguide.com/testosterone-test).

## Files

- `app.css` — Stylesheet (minified, ~30KB)
- `app.js` — Application logic (minified, ~68KB)

## How it works

These files are loaded via jsDelivr CDN into a Webflow page using a small embed:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/USERNAME/REPO@main/app.css">
<div id="tb-assessment-root"></div>
<script src="https://cdn.jsdelivr.net/gh/USERNAME/REPO@main/app.js"></script>
```

## Features

- 19-point symptom checklist (Bonus Card B1)
- Vermeulen Free Testosterone calculator
- 8-question lifestyle audit
- Combined Blueprint Score
- 4 modes via URL hash: `#assessment`, `#free-t-calculator`, `#symptom-checker`, `#lifestyle-audit`

© 2026 M. Videika · Based on The Testosterone Blueprint book
