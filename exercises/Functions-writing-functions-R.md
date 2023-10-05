---
layout: exercise
topic: Functions
title: Writing Functions
language: R
---

1. Copy the following function (which converts weights in pounds to weights in grams) into your assignment and replace the `________` with variables names for the input and output.

```r
convert_pounds_to_grams <- function(________) {
    grams = 453.6 * pounds
    return(________)
}
```

Use the function to calculate how many grams there are in 3.75 pounds.

2. Copy the following function (which converts temperatures in fahrenheit to temperatures in celcius) into your assignment and replace the `________` with the needed commands and variable names so that the function returns the calculated value for fahrenheit.

```r
convert_fahrenheit_to_celcius <- ________(________) {
    celcius = (fahrenheit - 32) * 5 / 9
    ________(________)
}
```

Use the function to calculate the temperature in celcius if the temperature in fahrenheit is 80°F.

3. Write a function that takes a number as input and outputs that number multiplied by 2. Run it with an input of 512.

4. Write a function that takes three arguments, `a`, `b`, and `x`, and returns `y` using `y = a + b * x` (like a prediction from a simple linear model). Run it with `a` = 6, `b` = 0.8, and `x` = 26.
