

---

# Assignment#1

## Description

This project contains R scripts that demonstrate the usage of factors in R. Factors are a special type of categorical variables in R, which can take only a limited number of different values, known as levels.

In this code snippet, we create a factor variable `x` with two levels ("yes" and "no"), and explore its properties using various R functions.

## Getting Started

### Dependencies

* R (version 4.1.0 or later)

### Executing the code

1. Open the R console or an R script file.
2. Create a factor variable `x` with the following code:
```R
x <- factor(c("yes","yes", "no", "yes", "no"))
```
3. Display the contents of `x` with the following code:
```R
x
```
4. Create a frequency table of `x` with the following code:
```R
table(x)
```
5. Display the underlying integer codes of `x` with the following code:
```R
unclass(x)
```
The output will show that "yes" is assigned the integer code 1, and "no" is assigned the integer code 2. This demonstrates how R stores factors internally as integers, with the levels mapped to unique integer values.

## Built With

* R - The R Project for Statistical Computing (<https://www.r-project.org/>)

## Authors

* MIrzoAkbar Karimov - 

## License

This project is licensed under the MIT License 


---
