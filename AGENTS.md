# AGENTS

## Project overview
- This repository contains standalone HTML utilities for converting American betting odds to implied probability.
- The calculator logic is in `convertAmericanOddsToProbability.html` and uses inline JavaScript (`calculateOdds`, `calculateNegativeOdds`, `calculatePositiveOdds`) to update the probability output field.
- `americanOddsToProbabilityTable.html` is a static reference table covering magnitudes 500 to 0 in increments of 5, with separate positive and negative implied probability columns rounded to two decimal places. Zero displays dashes. Its vanilla JS magnitude filter accepts an optional leading sign. Explanatory text covers 1% / 99% and 0.5% / 99.5% odds equivalents.
- Formulas: positive odds imply `100 / (odds + 100)`; negative odds imply `|odds| / (|odds| + 100)`.

## How to run
- Open either HTML file directly in a browser (no build step or server required).

## Conventions
- Keep the implementation as a standalone HTML file unless there is a clear need to add new assets or tooling.
- Prefer small, readable DOM interactions and vanilla JavaScript.

## Maintenance instructions
- After completing each work request, update this `AGENTS.md` file if any new project context or workflow detail should be captured.
- Every time you run, review and update the repository `README.md` to keep the project description current.
