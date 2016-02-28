---
title       : Prediction Algorithm Tester
subtitle    : Presentation of Data Products Course Project
author      : Dominique Loete
job         : Data Science specialization student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [quiz, bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction


* The app for testing various prediction algorithms.
    **Lots** of options and **tweaking** available!

* Wine dataset from MIT OpenCourseWare website ([Dataset](http://ocw.mit.edu/courses/sloan-school-of-management/15-097-prediction-machine-learning-and-statistics-spring-2012/datasets/wine.csv) : [Description about dataset](http://ocw.mit.edu/courses/sloan-school-of-management/15-097-prediction-machine-learning-and-statistics-spring-2012/datasets/wine_info.txt))
    + Header of the dataset:
    

```
##    Class Alcohol Malic acid  Ash Alcalinity of ash Magnesium Total phenols
## 1:     1   13.20       1.78 2.14              11.2       100          2.65
## 2:     1   13.16       2.36 2.67              18.6       101          2.80
## 3:     1   14.37       1.95 2.50              16.8       113          3.85
##    Flavanoids Nonflavanoid phenols Proanthocyanins Color intensity  Hue
## 1:       2.76                 0.26            1.28            4.38 1.05
## 2:       3.24                 0.30            2.81            5.68 1.03
## 3:       3.49                 0.24            2.18            7.80 0.86
##    OD280/OD315 of diluted wines Proline
## 1:                         3.40    1050
## 2:                         3.17    1185
## 3:                         3.45    1480
```

--- .class #id 

## Features

**Multiple** algorithms
* RDA
* SDA
* GBM
* RF

  
Several **resampling** methods
* Cross-Validation
* Bootstrap
* Repeated Cross-Validation
* Adaptive Bootstrap
  
 
**And more...**

---

## Instructions

All the info about the dataset is on the ***Data***-tab.

On the second tab ***Algorithm*** you can choice your prediction parameters.

When you are happy with the choices: Press the ***Calculate***-button.

A message will be visible topright while the app is doing his calculations.

It will then update the last tab ***Prediction Outcomes***.

Feel free to click around while it is calculating. This will not influence the calculation.


--- &radio

## Quiz

What is the best algorithm? (For this *wine*-dataset)

1. RF
2. GBM
3. _RDA_
4. SDA

***.hint

This time it seems the heaviest is the most accurate...

***.explanation

The dataset is quite small and very well defined. None of the algorithms have a problem with it. But SDA is clearly the least capable of the 4.



***


Go find out in my ***Prediction Algorithm Tester*** app...!

