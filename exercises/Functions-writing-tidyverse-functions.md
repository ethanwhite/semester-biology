---
layout: exercise
topic: Functions
title: Writing Tidyverse Functions
language: R
---

1. Copy the following vectors into R and combine them into a data frame named `count_data`

```r
states <- c("FL", "FL", "FL", "FL", "GA", "GA", "GA", "GA", "SC", "SC", "SC", "SC")
count <- c(9, 16, 3, 10, 2, 26, 5, 8, 17, 8, 2, 6)
area <- c(3, 5, 1.9, 2.7, 2, 2.6, 6.2, 4.5, 8, 4, 1, 3)
```

2. Write a function takes a data frame like `count_data` and a state abbreviation (like `"FL"`) as input and uses dplyr to return a data frame filtered to only include rows from that state. Use it to get the data where the `states` column is `"GA"`.

3. Write a function takes a data frame with a `count` column and an `area` column and makes a plot with `area` on the x-axis and `count` on the y-axis. Use it to make a plot of count as a function of area for the `count_data` data frame.

4. Use the two functions together to make a plot of count as a function of area for the values in `count_data` where the state is `"SC"`.