# MLS Defensive Value & Gameplan Style

## What this covers

An analysis of a full 2024 MLS season of StatsBomb event data, looking at where teams'
defensive value comes from (proactive ball-winning vs. reactive last-ditch defending)
and how that relates to each team's broader gameplan — how directly they move the ball
and how intensely they press.

See `analysis.Rmd` for the full write-up, including data preparation notes, two
visualizations, and interpretation.

## How to reproduce

1. Clone this repo.
2. Place the season event-level CSV (StatsBomb data, not included here — see note below)
   in a folder named `data/` at the project root: `data/mls_events_2024.csv`
3. Open `analysis.Rmd` in RStudio.
4. Install required packages if you don't already have them:
   ```r
   install.packages(c("tidyverse", "ggrepel"))
   ```
5. Restart R (Session > Restart R) and Knit the document, to confirm it reproduces
   cleanly from a fresh session.

## Data

This repository does **not** include the raw event data. It is proprietary, licensed
data provided for this assessment and is intentionally excluded per the assessment's
confidentiality terms. Place your own copy in `data/` as described above to run the
analysis locally.
