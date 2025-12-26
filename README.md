# Industrial Monitoring Dashboard

A single‑page, data‑driven dashboard that simulates an industrial plant monitoring screen using HTML, CSS, JavaScript and Chart.js.

## Demo

Deployed on Vercel: **[ADD_YOUR_VERCEL_URL_HERE]**

The page shows real‑time synthetic telemetry for:
- Temperature (°C)
- Vibration (mm/s)
- Pressure (bar)

It also displays live status chips (OK / WARNING / CRITICAL) based on configurable thresholds.

## Features

- Live clock and auto‑refresh every 2 seconds
- Responsive dark / glassmorphism‑style layout
- Line charts powered by Chart.js for:
  - Temperature
  - Vibration
  - Pressure
  - Combined “All signals” view
- Status evaluation logic that updates:
  - Status text
  - Status chip color (OK / WARNING / CRITICAL)
  - Reason message below the chip

## Tech Stack

- **HTML5** – Structure and layout
- **CSS3** – Styling and responsive design
- **JavaScript (Vanilla)** – Data generation, status rules, tab logic
- **Chart.js 4.x** – Realtime line charts loaded via CDN

## Getting Started

### 1. Clone the repository

