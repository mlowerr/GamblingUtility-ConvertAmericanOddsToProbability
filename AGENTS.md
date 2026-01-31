# AGENTS

## Project overview
- This repository contains a single-page HTML utility that converts American betting odds to implied probability.
- The core logic is in `convertAmericanOddsToProbability.html` and uses inline JavaScript (`calculateOdds`, `calculateNegativeOdds`, `calculatePositiveOdds`) to update the probability output field.

## How to run
- Open `convertAmericanOddsToProbability.html` directly in a browser (no build step or server required).

## Conventions
- Keep the implementation as a standalone HTML file unless there is a clear need to add new assets or tooling.
- Prefer small, readable DOM interactions and vanilla JavaScript.

## Maintenance instructions
- After completing each work request, update this `AGENTS.md` file if any new project context or workflow detail should be captured.
- Every time you run, review and update the repository `README.md` to keep the project description current.
