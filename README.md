# Nifty500 Risk Decomposition

A quantitative research project that decomposes total equity risk into **systematic** and **idiosyncratic** components across the Nifty500 universe and its constituent sectors using the Capital Asset Pricing Model (CAPM).

---

## Overview

This project estimates the extent to which the risk of each stock is driven by overall market movements versus company-specific factors. The analysis is performed across the Nifty500 universe and aggregated at the sector level to compare risk characteristics across industries.

---

## Methodology

For each stock, daily returns are regressed against the Nifty500 benchmark using a CAPM framework:

\[
R_i = \alpha + \beta R_m + \epsilon
\]

Where:

- **Systematic Risk** = Risk explained by market movements
- **Idiosyncratic Risk** = Company-specific (unsystematic) risk captured by the regression residuals

The project computes these measures for every stock and summarizes the results by sector.

---

## Features

- Historical data collection for the Nifty500 universe
- CAPM regression for individual stocks
- Systematic and idiosyncratic risk decomposition
- Stock-level and sector-level analysis
- Summary statistics and visualizations
- Exportable results for further research

---

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- yFinance

---

## Applications

This project can be used for:

- Equity research
- Portfolio construction
- Risk management
- Sector comparison
- Quantitative investment research

---

## Disclaimer

This project is intended for educational and research purposes only and should not be considered investment advice.

---

**Author:** Navon Isaac
