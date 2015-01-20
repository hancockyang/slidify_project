---
title       : Slidify Project
subtitle    : Pitch shiny project
author      : Hankang Yang  
job         : TA
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



## Introduction of Circle shiny app

1. This presentation give a ducomentation of this "Circle shiny" applicaton
2. This app is aimed to calculate circumference or area of circle by user defined radius
3. "Circle" shiny application is posted in this [link](https://hankang.shinyapps.io/shinnyprojectforDataproducecourse/)
4. The related `serve.R` and `ui.R` file can be found in [Github](https://github.com/hancockyang/shiny_project)
<img class=center src=1.png height=450>

--- .class #id 

## Simple mathematic

This app only allows user to enter 2 variables:

1. Radius of circle, $R$
2. Subject user wants to calculate (circumference, $C$ or area, $A$)

$$C = 2 \pi R^2$$
$$A = \pi R^2$$

---

## Core R code

The main R code performs this caculation is 

Example:


```r
R <- 3
```


```r
2*pi*R
```

```
[1] 18.84956
```


```r
pi*R^2
```

```
[1] 28.27433
```

---

## Know how

Operation sequence:

1. Enter the radius value in the textbox in the sidebar

2. Specify the subject you want to calculate, circumference or area by the dropdwon bar

3. Hit the 'submit' buttom

4. The mainbar will diplay the result and the variable you specified

5. Next slide show what the result look like

--- 

Results

<img class=center src=2.png height=550>


