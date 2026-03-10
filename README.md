# Care Plan Builder

A care plan reference tool for nurse case managers. Browse by body system, select chronic conditions, and instantly get pre-written care plan content including problem statements, goals, interventions, and education notes — ready to copy into your clinical documentation.

## Features

- **10 Body Systems**: Cardiac, Pulmonary, Endocrine, Renal, Neurological, Gastrointestinal, Musculoskeletal, Hematological, Pain Management, Care Coordination
- **40+ Chronic Conditions** with education content, dietary information, emergency guidance, and community resources
- **Multi-condition support**: Select multiple conditions and the care plan auto-combines the relevant content
- **Knowledge Deficit care plan template** with 5 interventions: Education & Self Management, Dietary Education, Emergency Guidance, Educational Materials, Community Resources
- **Installable PWA**: Works offline after first visit

## Setup (GitHub Pages)

1. Push all files to a GitHub repository
2. Go to Settings → Pages → Source: main branch, / (root)
3. Your app will be live at `https://yourusername.github.io/reponame`
4. Open in Chrome and click the install icon in the address bar

## Files

- `index.html` — Complete self-contained app
- `manifest.json` — PWA manifest for installability
- `sw.js` — Service worker for offline caching
- `icons/` — App icons (192px and 512px)

## Updating

Replace `index.html` and bump the cache version in `sw.js` (change `careplan-v1` to `careplan-v2`, etc.). Push to GitHub and the update will propagate to all installed instances.
