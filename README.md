# Mayor's Decision in Disaster Recovery

An interactive website for an ATMO course project. A mayor has a limited flood budget and must choose whether to spend it on **hazard**, **exposure**, or **vulnerability**, the three parts of disaster risk:

**Risk = Hazard × Exposure × Vulnerability**

The site shows how this political decision can reduce financial losses and help citizens recover from a disaster.

**Live site:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

## What the site shows

| Component | Real-life example | What it changes |
|---|---|---|
| Hazard | Build levees, floodwalls and detention ponds | How often a damaging flood reaches the city |
| Exposure | Buy out flood-prone homes and turn the land into parks | How much property sits in the floodplain |
| Vulnerability | Raise homes above flood level and use stronger building codes | How much damage a flood does when it arrives |

- **Graph:** expected flood losses over 30 years (US dollars) against money spent ($ millions), with one line for each component and a "do nothing" baseline.
- **Sliders:**
  1. Mayor's budget ($10M–$300M), which affects all three components
  2. Heavier rainfall from climate change (today to +50%), which affects hazard and vulnerability
  3. Average home value ($150k–$600k), which affects exposure and vulnerability
  4. Share of older homes built before flood codes (20%–90%), which affects vulnerability
- **Comparison table:** what the budget buys, the change in each risk factor, the 30-year loss, the losses avoided and the return per $1 spent. The best option is highlighted.

## What to notice

- With a small budget, levees barely help, because a half-built levee protects almost no one.
- Heavier rainfall makes levees less effective, while buyouts and raised homes keep working.
- Cheaper or newer homes make buyouts the best choice.
- The best choice depends on the city, so there is no single right answer.

## Model and data sources

The model describes one imaginary mid-sized U.S. river city with 4,000 homes in its floodplain. Default values come from:

- NOAA Climate.gov: heavy-rain trends
- GAO-04-30: levee costs (about $7M per mile on the American River)
- Congressional Research Service: buyouts at the pre-disaster market value
- Marketplace (2023) and the City of Hampton, VA: the cost of raising a home
- FEMA: percent-damage guidance
- National Institute of Building Sciences, *Mitigation Saves*: about $7 saved per $1 spent on riverine flood buyouts

Some inputs are model assumptions, and the page labels them that way. These include how much more often floods come as rainfall increases, the shape of each spending curve, and belongings being worth half the building. Losses cover property only. They are summed over 30 years with no discounting. Full links are in the "Where the numbers come from" section of the page.

## Files

- `index.html`: the whole website (HTML, CSS and JavaScript in one file, with no build step)
- `README.md`: this file
- `LICENSE`: MIT License

## Run it

- **Locally:** open `index.html` in any web browser.
- **On GitHub Pages:** go to Settings → Pages, choose **Deploy from a branch**, then select **main** and **/(root)**.

## Author

Cindy, ATMO course project, 2026.
