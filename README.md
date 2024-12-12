# ERM Data Visualization

Repository for Data Visualization class in the Empirical Research Method (ERM) Phd Course at Politecnico di Torino

## Building

You can build the slides using `quarto render` command:

```
quarto render DataVisualization.qmd
quarto render DataRepresentation.qmd
quarto render GGPlot.qmd
```

## Requirements

To build the slides you need

- [Quarto](https://quarto.org)
- [R](https://cran.r-project.org) including the libraries:
  `tidyverse` and `knitr`
  - The libraries can be installed from **R** using the commands
  ```
  install.packages(c("tidyverse","knitr"))
  ```


