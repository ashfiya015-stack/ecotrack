# 🌱 EcoTrack – AI Energy & Waste Copilot
**Problem statement:** Smart & Sustainable Future

## Problem
Households and campuses see only a monthly bill. They don't know whether usage is rising, what it costs the environment, or which action saves the most.

## Solution
EcoTrack takes 6 months of electricity data plus habit and waste inputs and returns:
- **Forecast** of next month's kWh and bill (least-squares regression)
- **Carbon footprint** (electricity + landfill waste, kg CO₂e/month)
- **Sustainability score** (0–100)
- **Ranked recommendations** by CO₂ saved (AC setpoint, LED switch, standby load, composting, recycling)

## Tech stack
HTML, CSS, vanilla JavaScript, inline SVG charts. No backend, no API keys, runs offline.

## Run locally
Open `index.html` in a browser.

## Assumptions
Grid factor 0.82 kg CO₂/kWh; landfill factors organic 0.5, paper 1.0, plastic 0.2 kg CO₂e/kg. Savings are estimates.

## Originality
Combines energy forecasting and waste footprint into one ranked action list for non-experts.

## Limitations & next steps
Manual data entry; rule-based advice. Next: smart-meter/CSV import, LLM chat explanations, campus multi-building view, Streamlit/Flask backend.

## Demo video script (2 min)
1. 0:00 Problem: bills hide the story.
2. 0:20 Enter data, show forecast and score.
3. 1:00 Change AC hours and recycling, watch recommendations re-rank.
4. 1:40 Impact and next steps.

## License
MIT

## Project structure
```
index.html            # the full app
data/sample_usage.csv # sample file for the Import CSV button (month,kwh)
docs/                 # submission description + demo script
LICENSE
```

## Deploy (live link)
Push to GitHub, then Settings → Pages → deploy from `main` / root. Or drag the folder onto Netlify or Vercel.
