---
title       : Dynamic Yield Curve
subtitle    : Market Crash Predictor
author      : Horacio Ballinas
date        : November 21, 2017 
job         : Developing Data Projects Course Project
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github      :
  user: hballinas
  repo: Developing-Data-Products/Week_4

--- .class #id 

## Why is the Yield Curve so important?


>1. The Secret To Success combines Good Returns with Good Risk Management

>2. What Good Are Good Returns If We Don't Know When To Exit?

>3. "Stock valuations make sense in 2017 with interest rates where they are" - Warren Buffett

---
## Slide 2

The Dynamic Yield Curve app let you visualize how the interest rates at different maturity dates have behaved in the past (A graph showing these Interest Rates at different maturity dates is called the Yield Curve).  You'll notice that right before every market crash, the yield curve inverts. The Yield Curve is the Best Predictor Known to Man that a Market Crash is Imminent. 

---
## Slide 3
> First, we load the interest rates datasets from the FED and the S&P from Yahoo Finance...

```
## [1] "DGS3MO"
```

```
## [1] "DGS1"
```

```
## [1] "DGS2"
```

```
## [1] "DGS5"
```

```
## [1] "DGS7"
```

```
## [1] "DGS10"
```

```
## [1] "DGS20"
```

```
## [1] "DGS30"
```

```
## [1] "GSPC"
```

---
## Slide 4

The app let's you visualize the market and yield curve at any date using a slider
![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png)

---
## Slide 5
Please note that the yield curve is flattening in 2017.  I recommend you monitor this graph closely and take action if the curve inverts.  
![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3-1.png)


