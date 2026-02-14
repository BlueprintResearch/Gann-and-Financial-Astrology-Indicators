# Gann & Financial Astrology Indicators

```
   ════════════════════════════════════════════════════════════
        BLUEPRINT RESEARCH • GANN & ASTRO INDICATORS
   ════════════════════════════════════════════════════════════

                      "I'm surprised he ever
                       published them for
                       the general public."
                                    
                       — Amazon review of
                         Patrick Mikula's work

   ════════════════════════════════════════════════════════════
```

**Open-source TradingView indicators implementing W.D. Gann, Patrick Mikula, Donald Bradley, and more.**

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Pine Script v6](https://img.shields.io/badge/Pine%20Script-v6-blue)](https://www.tradingview.com/pine-script-docs/)
[![TradingView](https://img.shields.io/badge/TradingView-Published-green)](https://www.tradingview.com/u/BlueprintResearch/)

---

## Why This Exists

In 1995, Patrick Mikula did something remarkable. He published *Gann's Scientific Methods Unveiled* — the first book devoted entirely to decoding W.D. Gann's hidden astrological methods. He laid bare what Gann had obscured behind words like "natural" and "scientific." He showed how to convert price to longitude, how to use eclipses, how planetary ingress correlates with market turns.

When that book went out of print, used copies sold for $450.

Mikula could have kept it locked away. Instead, he republished it as an affordable ebook. He wrote a second volume. He kept teaching.

That generosity changed how I approach this work.

This repo is my attempt to give back the way Mikula gave back. Every indicator here is open source. Study the code. Fork it. Improve it. Just don't sell it.

---

## Indicators

### Bradley Siderograph
Donald Bradley's 1947 planetary barometer for market timing.

- **Method:** Weighted sum of planetary aspects (declination parallels & contraparallels, longitude aspects)
- **Source:** *Stock Market Prediction* (1947)
- **TradingView:** [View](https://www.tradingview.com/script/dV18xsto-Bradley-Siderograph/)
- **Features:** Sidereal potential, long-term and mid-term planetary aspects, declination factor

### Price and Longitude Angles
Gann/Mikula planetary price geometry — plots price levels based on price per planetary longitude ratio.

- **Method:** Converts planetary positions to price using configurable scale; fan angles from anchor points
- **Source:** Patrick Mikula, *Gann's Scientific Methods Unveiled, Volume 2*
- **TradingView:** [View](https://www.tradingview.com/script/EksWr4T1-Price-and-Longitude-Angles/)
- **Features:** Heliocentric/geocentric toggle, Single/Average & Synodic mode selection, customizable price-per-degree, mirrored fans, zodiac-colored longitude display, cycle tracking

### Mikula's Master 360° Square of 12
Patrick Mikula's circle chart methodology for price and time analysis.

- **Method:** 360° division anchored to price; zodiac rail with planetary transit/natal tracking
- **Source:** Patrick Mikula's discussion of W.D. Gann's "Master 12" chart
- **TradingView:** [View](https://www.tradingview.com/script/SjKU5fwY-Mikula-s-Master-360-Square-of-12/)
- **Features:** Progress/regress through cycles, A/B level bands, swing pivot tinting, transit and natal planet rails with retrograde indication

### Path of the Planets
Visualizes planetary longitude positions over time — W.D. Gann's planetary tracking method.

- **Method:** Plots geocentric/heliocentric longitude and declination for all planets
- **Source:** W.D. Gann's original methods, specifically Chart 5-9 artistic replica by Patrick Mikula
- **TradingView:** [View](https://www.tradingview.com/script/25tcltg4-Path-of-the-Planets/)
- **Features:** Start point anchoring, longitude mirroring, 360° shift adjustments, positions table with real-time data

### Planetary Retrograde Dashboard
Multi-planet retrograde status indicator.

- **Method:** Calculates planetary speed to detect retrograde periods across all timeframes
- **TradingView:** [View](https://www.tradingview.com/script/QG4Rr9kx-Planetary-Retrograde-Dashboard/)
- **Features:** Historical and real-time retrograde overlay, ℞ symbol display, adapts to any timeframe and retrograde clusters

### Planetary Retrograde Periods
Single-planet deep-dive into retrograde cycles with future projections and midpoints.

- **Method:** Speed-based detection (more accurate than longitude-based methods)
- **TradingView:** [View](https://www.tradingview.com/script/P6OyG809-Planetary-Retrograde-Periods/)
- **Features:** Two-phase visualization (first half vs. second half), station markers (℞, ½, D), 500-bar future projections, per-planet alert conditions

### Planetary Ingress
Marks when planets cross from one zodiac sign to another.

- **Method:** Detects sign boundary crossings with precise date/time and retrograde status
- **TradingView:** [View](https://www.tradingview.com/script/HV5IiCIv-Planetary-Ingress/)
- **Features:** All 10 celestial bodies including lunar nodes, historical markers and future projections, timezone-aware labels

### Gann Square of Nine: Planetary Degrees
Maps planetary positions to Gann's Square of Nine grid with pivot tracking.

- **Method:** Planetary longitude mapped to So9 cells; pivot high/low degree tracking
- **Source:** W.D. Gann's Square of Nine, grid adapted from ThiagoSchmitz
- **TradingView:** [View](https://www.tradingview.com/script/wz5TKq4Q-Gann-Square-of-Nine-Planetary-Degrees/)
- **Features:** Target degree alerts, future projections, retrograde indicator, geocentric/heliocentric modes

### Moon Declination & More
Comprehensive lunar declination visualization with phase coloring.

- **Method:** ELP2000-82 lunar theory for Moon declination tracking
- **TradingView:** [View](https://www.tradingview.com/script/Pk4dWSvp-Moon-Declination-More-BlueprintResearch/)
- **Features:** Moon/Sun/Node declinations, zodiac sign coloring, OOB highlighting, future projections

### Hyperfork Matrix
Advanced Andrews Pitchfork with action/reaction propagation lines.

- **Method:** Pitchfork variants (Original, Schiff, Modified Schiff) with lattice matrix
- **Source:** Patrick Mikula, *The Best Trendline Methods of Alan Andrews*
- **TradingView:** [View](https://www.tradingview.com/script/Sq5Xt0eZ-Hyperfork-Matrix/)
- **Features:** Forward/backward projections, lattice grid, price crossing alerts

### Natal & Transit Planetary Aspect Table
Aspect table comparing natal (birth) with transit (current) planetary positions.

- **Method:** 14 aspect types with configurable orbs, applying/separating detection
- **TradingView:** [View](https://www.tradingview.com/script/h7SjXsq8-Natal-Transit-Planetary-Aspect-Table/)
- **Features:** 20+ preset natal dates (BTC, ETH, NYSE, etc.), geocentric/heliocentric toggle

### Double Numbered Triangle Chart
Gann triangle chart for price and time analysis.

- **Method:** Triangle progression/regression with support/resistance levels
- **Source:** Patrick Mikula, *The Definitive Guide to Forecasting Using W.D. Gann's Square of Nine*
- **TradingView:** [View](https://www.tradingview.com/script/8xwdXwyz-Double-Numbered-Triangle-Chart-Progression-Regression/)
- **Features:** Left edge/center/right edge angles, pivot detection, customizable increments

### Doubled Numbered Square of Nine
Square of Nine progression/regression tool for price analysis.

- **Method:** So9 spiral with angle-based support/resistance levels
- **Source:** Patrick Mikula, *The Definitive Guide to Forecasting Using W.D. Gann's Square of Nine*
- **TradingView:** [View](https://www.tradingview.com/script/dh3Cpnga-Doubled-Numbered-Square-of-Nine-Progression-Regression/)
- **Features:** 8 angle selections (0° through 315°), pivot tracking, time variable display

---

## Planetary Ephemeris Library

These indicators are powered by **blueprint_ephemeris_lib** — a consolidated Pine Script library implementing VSOP87D, ELP2000-82, and Meeus algorithms with sub-arcminute precision validated against NASA's DE440 ephemeris.

**TradingView:** [blueprint_ephemeris_lib](https://www.tradingview.com/script/f7cvFJjG-blueprint-ephemeris-lib/)
**Repository:** [BlueprintResearch/planetary-ephemeris](https://github.com/BlueprintResearch/planetary-ephemeris)
**License:** MIT (the math is free for any use)

The v2 rewrite consolidated the original 11 libraries into one, fixed critical L1[0] precession coefficient errors across all VSOP87 planets, and reduced code size by 28%.

<details>
<summary>Legacy libraries (v1)</summary>

The original 11 separate libraries remain available but will be updated with the fix. Use `blueprint_ephemeris_lib` for new work.

| Library | Body | TradingView |
|---------|------|-------------|
| lib_vsop_core | Foundation | [Link](https://www.tradingview.com/script/z1Zy5i9B-lib-vsop-core/) |
| lib_vsop87_mercury | Mercury | [Link](https://www.tradingview.com/script/LtS4cY82-lib-vsop87-mercury/) |
| lib_vsop87_venus | Venus | [Link](https://www.tradingview.com/script/4jqxHSck-lib-vsop87-venus/) |
| lib_vsop87_mars | Mars | [Link](https://www.tradingview.com/script/xpCxFyqU-lib-vsop87-mars/) |
| lib_vsop87_jupiter | Jupiter | [Link](https://www.tradingview.com/script/R9kp0lbC-lib-vsop87-jupiter/) |
| lib_vsop87_saturn | Saturn | [Link](https://www.tradingview.com/script/jC9ATVEA-lib-vsop87-saturn/) |
| lib_vsop87_uranus | Uranus | [Link](https://www.tradingview.com/script/0CTzo5sg-lib-vsop87-uranus/) |
| lib_vsop87_neptune | Neptune | [Link](https://www.tradingview.com/script/z8yHMJNT-lib-vsop87-neptune/) |
| lib_elp2000_moon | Moon | [Link](https://www.tradingview.com/script/XsQ6sAXD-lib-elp2000-moon/) |
| lib_meeus_pluto | Pluto | [Link](https://www.tradingview.com/script/E1N99jzO-lib-meeus-pluto/) |
| lib_ephemeris | Master | [Link](https://www.tradingview.com/script/RcA3QSO7-lib-ephemeris/) |

</details>

---

## TrendSpider (Coming soon)

The planetary ephemeris has also been ported to TrendSpider for those who prefer that platform. This represents the first serious Gann astro work available on TrendSpider.

---

## Attribution & References

### Patrick Mikula
- *Gann's Scientific Methods Unveiled, Volume 1* (1995) — Eclipse method, planetary phenomena, decoding Gann's language
- *Gann's Scientific Methods Unveiled, Volume 2* — Price-longitude conversion, circle charts, practical applications
- *The Best Trendline Methods of Alan Andrews*
- *The Definitive Guide to Forecasting Using W.D. Gann's Square of Nine*

Mikula's work is the reason these indicators exist. His willingness to publish what others hoarded changed the field.

### Donald Bradley
- *Stock Market Prediction: The Planetary Barometer and How to Use It* (1947)

### W.D. Gann
- *How to Make Profits in Commodities* (1941)
- *The Tunnel Thru the Air* (1927)
- Original commodity courses and private correspondence

### Jean Meeus
- *Astronomical Algorithms* (2nd Edition, 1998) — Implementation reference for ephemeris calculations

### BarefootJoey
- His open-source astro library on TradingView gave me the chance to learn, implement, and test. He inspired me to create a new planetary ephemeris, which enabled me to give back in my own way. Thanks, m8.
- [AstroLib](https://www.tradingview.com/u/BarefootJoey/)

### ThiagoSchmitz
- Square of Nine grid visualization adapted from "Gann Square of 9" (Feb 2023)
- [Gann Square of 9](https://www.tradingview.com/script/cSzck7Kl-Gann-Square-of-9/)

### Greg Miller
- VSOP87 coefficient validation via his [vsop87-multilang](https://github.com/gmiller123456/vsop87-multilang) project, which provided complete VSOP87D coefficient tables in accessible formats
- Instrumental in discovering L1[0] precession errors affecting all 8 VSOP87 planets in the original libraries
- Released into the public domain

### Susan Abbott Gidel
- First trade dates for commodities and financial instruments
- *Trading In Sync With Commodities: Introducing Astrology To Your Technical Toolbox*

---

## Dependencies

Astro Indicators are built using:
- [BlueprintResearch/blueprint_ephemeris_lib](https://www.tradingview.com/script/f7cvFJjG-blueprint-ephemeris-lib/)

---

## Community

**X:** [@Blueprint_So9](https://twitter.com/Blueprint_So9)  
**X Community:** Blueprint Terminal  
**TradingView:** [BlueprintResearch](https://www.tradingview.com/u/BlueprintResearch/)  
**GitHub:** [BlueprintResearch](https://github.com/BlueprintResearch)

---

## License

**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit and link to this repository
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — If you remix or build upon the material, you must distribute under the same license

**This is not open-source in the OSI sense.** The non-commercial restriction means you cannot sell these indicators or include them in paid products.

For commercial licensing inquiries, contact Blueprint Research blueprintresearch9@gmail.com 

Full license: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## Why Non-Commercial?

The planetary ephemeris libraries are MIT licensed — use them however you want, including commercially. That's just math.

These indicators represent something different: specific implementations of Gann, Mikula, and Bradley methods. The logic, the problem-solving, the translation of classical techniques into working code.

Patrick Mikula could have charged $450 for his knowledge. He chose to make it accessible.

I'm doing the same. Study it. Use it. Improve it. Just don't sell it.

---

## Disclaimer

This repository is provided for **educational and research purposes only**.

No claim is made that the trading methods, indicators, or ideas presented here will result in profits or prevent losses. The planetary ephemeris libraries and all indicators are tools for analysis — they are not financial advice and carry no guarantee of performance.

**You are solely responsible for your own trading decisions.** Past performance of any method or indicator does not guarantee future results. Trading involves substantial risk of loss and is not suitable for all investors.

Use at your own risk.

---

© 2026 Blueprint Research LLC • Licensed under CC BY-NC-SA 4.0
