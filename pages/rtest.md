---
layout: page
title: test block code
---

# Load data set

```
# R code to import .csv file.
data <- read.table(file = "C:/Users/hwlee/Desktop/R Tutorial/Materialism.csv", header = TRUE, sep = ",") 

# R code for converting integer to factor and adding value labels to the factor.
data$Gender <- factor(data$Gender, levels = c(0, 1), labels = c("male", "female"))
data$Income2017 <- factor(data$Income2017, levels = c(0, 1), labels = c("low", "high"))
data$UserType <- factor(data$UserType, levels = c(1, 2, 3), labels = c("Weekday", "Weekend", "All Week"))
```

- [ ] task open
- [ ] task open
- [x] task completed
