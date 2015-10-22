---
title       : Developing Data Products Project
subtitle    : 
author      : Shahfik Amasha
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Predictive Application

- The application showcases a simple 3-step process for a user to run a predictive algorithm based on Random Forest using a Web UI.
- It builds upon the Practical Machine Learning course project where movement parameters are classfied into one of five classes.
- An RData is used to load the environment parameters without having to run the modelling each time the application loads.

Shiny App: https://shahfik.shinyapps.io/project 

GitHub Repo: https://github.com/shahfik/Coursera-DDP

--- .class #id 

## 3-Step Process

A simple 3 step process allows the user to quickly learn to use the application.

1. Download and edit the template data file.
2. Upload the file.
3. Download the results.

--- .class #id 

## Random Forest Model

```
## randomForest(formula = classe ~ ., data = data_train_new, ntree = 500, 
##     mtry = 7, importance = TRUE)
```

```
##      A    B    C    D    E  class.error
## A 5579    0    0    0    1 0.0001792115
## B    6 3789    2    0    0 0.0021069265
## C    0    3 3418    1    0 0.0011689071
## D    0    0    6 3209    1 0.0021766169
## E    0    1    0    4 3602 0.0013861935
```

--- .class #id 

## Output

The output of the presentation is shown in the Prediction

