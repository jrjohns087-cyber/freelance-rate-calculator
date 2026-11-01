# Freelance Rate Calculator

A simple, zero‑maintenance web app that helps freelancers instantly calculate a fair hourly (and daily) rate based on their desired monthly income, billable hours, and expense percentage.

## Features
- **Instant calculation** – no server, all logic runs in the browser.
- **Responsive UI** – works on desktop and mobile devices.
- **Copy to clipboard** – quickly copy the suggested rates.
- **Affiliate link** – optional partner recommendation (e.g., FreshBooks).

## How it works
1. Enter your target monthly income, how many hours you can bill each month, and the percentage of income you spend on taxes/tools.
2. The calculator deducts expenses, then divides the net income by billable hours to produce an **hourly rate**.
3. It also shows a **daily rate** (8‑hour workday) and lets you copy the results.

## Demo
[Live demo on Netlify](#) *(replace with the actual Netlify URL after deployment)*

## Installation & Deployment
```bash
# Clone the repo
git clone https://github.com/<your‑username>/freelance-rate-calculator.git
cd freelance-rate-calculator

# Open locally (any static server works)
# e.g., with Python's built‑in server
python -m http.server 8000
```

Deploy to a static‑site host (Netlify, GitHub Pages, Vercel) by pushing the repository.

---
*Built with plain HTML, CSS, and JavaScript – no backend required.*