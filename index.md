---
title       : Data Products - Course Project - Presentation
subtitle    : Guess the Order of the Top 10 R Packages for 2015
author      : Giora Simchoni
logo        : Rlogo-1.png
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [quiz, bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## How familiar are you with R?

* Many of us use R for a very limited scope of purpose. Unless you are a [r-bloggers](http://r-bloggers.com) fanatic, chances are you're not even starting to guess what R can do
* For example, what is the easiest way to get the length of a string?

```r
nchar("encyclopedia")
```

[1] 12

```r
nchar(NA) #But what happens here?
```

[1] 2
* So have you ever heard of the ```stringr``` package and what it can do for you?

```r
stringr::str_c(NA)
```

[1] NA

--- 

## What's in the app? (1)

* This little project was made to make sure you're familiar with at least the currently top 10 most downloaded packages
* You'll look at a random order list of the top 10 most downloaded R packages for Jan-Jun 2015, as reported by [KDNuggets](http://kdnuggets.com) (but don't peak!)
* ![project screenshot](assets/img/project_screenshot.png)
* You'll then have to sort this list from most downloaded (1) to least downloaded (10), press the "See my results" button and hope you got it right!

--- 

## What's in the app? (2)

* The app will tell you how many correct ranks you got out of 10 (but not which :))
* You can try again and again
* And when you finally succeed - the app will also tell you how long it took!
* But remember - the idea is not just ordering the packages. If you find yourself unfamiliar with any of these top 10 packages, now would be a good time to find out what it does
* To help you get started, answer the following multiple-choice question, to get the most downloaded R package (Rank 1) - the rest is up to you...

--- &radio 

## Jump Start

Which is the most downloaded R package of H2/2015 (Rank 1)?

1. ggplot2
2. plyr
3. _Rcpp_
4. RColorBrewer

*** .hint
It wasn't made for fancy plotting...

*** .explanation
Dirk Eddelbuettel et al. Rcpp package, which integrates R with C++, is the most downloaded package of H2/2015.
