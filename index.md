---
title       : Basic Geometric
subtitle    : Developing Data Products
author      : Sandro Matteo C
job         : 
framework   : io2012  # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow    # 
widgets     : [bootstrap]            # {mathjax, quiz, bootstrap}
mode        : standalone #selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Basic Geometric



These slides are a comment to the Shiny app.

**Selecting the right TAB**

the app can calculate the Area and Perimeter of


1. Circle
2. Triangle
3. Rectangle



--- 

## The circle

If you input a radius value:


```r
radius <- 4
```

The area and circumference of the circle are caculated as:


```r
area <- 3.14*radius*radius
circumference <- 6.28*radius
```

so, if you flag the checkbox "Area" and "Circumference" the result printed is:


```
## [1] 50.24
```

```
## [1] 25.12
```

--- 

## The Rectangle

If you input a base and vertical values:


```r
base <- 2
vertical <- 6
```

The area and perimeter are caculated as:


```r
area <- base*vertical
Perimeter <- 2*(base+vertical)
```

so, if you flag the checkbox "Area" and "Perimeter" the result printed is:


```
## [1] 12
```

```
## [1] 16
```

---

## The Triangle

If you input a base and vertical values:


```r
base <- 3
vertical <- 8
```

The area is caculated as:


```r
area <- base*vertical/2
```

**NOTE**: the perimeter of the triangle can not be calculate since it is not possible to find the length of the 3 edges...

