# OECD Agricultural Production Visualization

This project presents an animated visualization of agricultural production across multiple countries using data from the OECD-FAO Agricultural Outlook (2010–2032). The goal is to demonstrate temporal trends in key commodities through reusable data pipelines and animated charts, in the style of Gapminder visualizations.

---

## Files Included

| File                  | Description                                      |
|-----------------------|--------------------------------------------------|
| `code.qmd`            | Main Quarto document with R code and commentary |
| `code.html`           | Rendered HTML report with embedded animation     |
| `DATA/data.xlsx`      | Source data from OECD-FAO Outlook                |
| `README.md`           | This project documentation                       |

---

## Objectives

- Perform exploratory data analysis using tidyverse pipelines.
- Create a reusable workflow for OECD-based visualizations.
- Produce a **Gapminder-style animation** showing how agricultural production evolves over time.

---

## Tools Used

- `ggplot2` for plotting
- `gganimate` + `gifski` for generating animation
- `readxl` for loading Excel data
- `Quarto` for document generation

---

## How to Reproduce

1. Open `code.qmd` in RStudio.
2. Make sure the following R packages are installed:

   ```r
   install.packages(c("tidyverse", "readxl", "gganimate", "gifski"))
