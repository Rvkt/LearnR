# Notes on Variables in R

## Overview of Variables in R

Variables in R are fundamental components used to store data that can be manipulated throughout a program. Unlike many other programming languages, R does not require explicit declaration of variables; they are created upon assignment.

## Rules for Naming Variables

When creating variable names in R, several rules must be followed:

-   **Start with a letter or a period**: Variable names must begin with a letter (a-z, A-Z) or a period (.), but if they start with a period, the next character cannot be a digit.
-   **Allowed characters**: Variable names can include letters, digits (0-9), periods (.), and underscores (\_).
-   **Case sensitivity**: Variable names are case-sensitive; for example, `age` and `Age` are considered different variables.
-   **No reserved words**: Certain keywords (e.g., `TRUE`, `FALSE`, `NULL`) cannot be used as variable names.

### Examples of Valid and Invalid Variable Names

| Valid Names  | Invalid Names |
|--------------|---------------|
| `var1`       | `1var`        |
| `my.var`     | `.2var`       |
| `data_frame` | `_data`       |
| `foo_bar`    | `TRUE`        |

## Variable Assignment

In R, variables can be assigned values using several operators:

``` r
## **Assignment Operator (`=`)**: Commonly used but can lead to confusion in certain contexts.
x = 10

## Leftward Assignment (<-): Preferred method for assigning values.
y <- "Hello"

## Rightward Assignment (->): Less common but valid.
"World" -> z

## Variables can also be assigned multiple values simultaneously:
a <- b <- c <- 0
```
