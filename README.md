# GamblingUtility-ConvertAmericanOddsToProbability

A small, standalone HTML utility that converts American betting odds to implied probability.

## Usage
1. Open `convertAmericanOddsToProbability.html` in a browser.
2. Enter American odds (positive or negative) and click **Calculate** to see the implied probability.

For a quick reference instead of typing values, open `americanOddsToProbabilityTable.html`, which lists odds magnitudes from 500 to 0 in increments of 5, with separate positive and negative implied probability columns and a filter box for lookups. The page also explains the +9900 / -9900 and +19900 / -19900 equivalents for 1% / 99% and 0.5% / 99.5%. Zero has no valid conversion.

## Project structure
- `convertAmericanOddsToProbability.html`: single-page calculator with inline JavaScript.
- `americanOddsToProbabilityTable.html`: static reference table of American odds to implied probability, with a client-side filter.
- `AGENTS.md`: project context and maintenance instructions for future agents.
