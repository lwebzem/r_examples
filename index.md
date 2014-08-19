---
title       : Plotting Basic Functions & Curves in R
subtitle    : Shiny App
author      : lwebzem
job         : student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- .class #id 

## Plotting linear function in R


```r
 par(mar = c(2.0, 2.0, 2.0, 2.0)+0.1)
    x <- seq (0, 20, length = 10)
    plot(x)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 

--- .class #id 

## Plotting parabola


```r
x <- seq (-50, 50, length = 50)
    plot(x^2)
```

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2.png) 

--- .class #id 

## Plotting |x|



```r
 x <- seq (-20, 20, length = 10)
    plot(abs(x))
```

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3.png) 

--- .class #id 

## Plotting a cubic function

```r
 x <- seq (0, 20, length = 10)
    plot(x^3)
```

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4.png) 

--- .class #id 






