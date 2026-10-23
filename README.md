Interactive slides for **MAS 818: Applied Time Series Analysis**
The Analysis of Time Series: An Introduction 5th Ed. by Chris Chatfield 
Chapter II: *Simple Descriptive Techniques*. Built in R with `ioslides_presentation` + Shiny runtime.

## What's inside

| File | Purpose | Source
|---|---|---|
| `TSAnalysis_slides.Rmd` | The presentation (Shiny-powered, plotly visuals) |
| `Convolution.png` | Figure for the filters-in-series slide |
| `salesData Ex2.1.xlsx` | Textbook 4-weekly sales (1967-1970) | [Execise 2.1 pg.25 of the book](https://docs.google.com/spreadsheets/d/1MuOyjepRkJtzNjgaJTbKBrThO4njMAeh/edit?usp=sharing&ouid=100299949886468366251&rtpof=true&sd=true)
| `maize.xlsx` | Ahero (Kisumu) dry maize price, 2023-2026 | [KNBS LEI reports 2018-2026](https://www.knbs.or.ke/leading-economic-indicators/)
| `cane.xlsx` | Cane deliveries ('000 tonnes), 2019-2026 | [KNBS LEI reports 2018-2026](https://www.knbs.or.ke/leading-economic-indicators/)
| `local electricity consumption KPLC.xlsx` | Kenya power consumption (million kWh), 2019-2026 | [KNBS LEI reports 2018-2026](https://www.knbs.or.ke/leading-economic-indicators/)
| `mobile.xlsx` | Mobile money agents, accounts, volume and value, 2007-2026 | [Central Bank of Kenya Mobile Payment data](https://www.centralbank.go.ke/national-payments-system/mobile-payments/)
| `manifest.json` | rsconnect deployment manifest |

## Topics covered

- **Variation:** trend, seasonality, cyclic and irregular components (additive vs multiplicative `decompose()`)
- **Stationarity** and time plot best practice
- **Transformations:** log, Box-Cox (Guerrero's λ via `forecast::BoxCox.lambda`)
- **Trend fitting:** linear (cane), quadratic (maize), Gompertz via `nls(SSgompertz)` (mobile accounts)
- **Filtering:** symmetric MAs (3/5-point), Gaussian MA with live sliders, exponential smoothing (`HoltWinters`), convolution
- **Differencing:** first, second and seasonal (∇₁₂)
- **Seasonal models** A/B/C, **autocorrelation** and the correlogram

  Access the slides [here](https://01a16a64-debf-0909-5343-c87e3d44f2d2.share.connect.posit.cloud/)
