---
title       : Iris Prediction
subtitle    : A Slidify presentation about a Shiny App
author      : Jay Chuang
job         : Aspiring Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

* This is a slidify presentation about a Shiny App that I built.
* The Shiny App is a interactive prediction program that allows the user to pick from two different predictions algorithms.
* The user can also use four sliders to select different values for predictors and the algorithm will present a result.

--- .class #intro

## Data

* The data used is the Iris dataset.
* This dataset was created by Edgar Anderson.
* It contains measurements (in centimeters) of the variables of sepal length & width and petal length & width for 50 flowers of each of three species of iris.
* The species are Iris setosa, Iris versicolor, and Iris virginica.

--- .class #data

## Prediction

* The prediction algorithms that can be selected in the Shiny App are "rpart" and "rf."
* rpart is a recursive partitioning algorithm for classification, regression and survival trees. Most of its functionality is based on the 1984 book by Breiman, Friedman, Olshen and Stone.
* rf is a random forest algorithim, which implements Breiman's random forest algorithm (based on Breiman and Cutler's original Fortran code) for classification and regression.
* After selecting an algorithm, the user is told shown the accuracy of the algorithm on the test set (25% of the data).

--- .class #prediction

## Shiny App

* This Shiny App utilizes selectInput and sliderInputs to allow the user to select different prediction algorithms and predictor values.
* It uses the user's selected preidiction algorithm and predictor values to produce a prediction.
* This app can give you an idea of how Shiny can be used to create interactive web apps with powerful R programming happening in the background.

--- .class #shiny
