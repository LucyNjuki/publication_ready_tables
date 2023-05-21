# R.U.M: Publication Ready Tables

## User-defined functions to create summary tables

### June 1st, 2023

Occasionally, we encounter environments like Microsoft Azure that do not support the default viewer mode. Consequently, utilising packages like `gtsummary` becomes impractical. Therefore, it would be preferable to develop user-defined functions for data summarisation. In this example, I will demostrate, the use of user-defined functions to summarise data, and using `knitr::kable()` to beautify the tables. Plus, I will show how we can utilise the `summarytools::dfSummary` R function which gives descriptive statistics for both numerical and categorical variables.
