---
title       : Trustworthiness of Information across Information Domains
subtitle    : The "Factiness" of Information
author      : MJ Cho
job         : Cyber Social Mini Conference
logo        : stanford.gif
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
output      : pdf
---



## Information Trustworthiness
>- An open research question!
>- 1. Database, machine learning, and natural language understanding
  - data/knowledge fusion
  - data veracity and source credibility
>- 2. Computational journalism 
  - automated fact-checking: also an engineering question?
  - combining currently available tools vs. "fundamental breakthroughs in multiple fronts"

---

## Factiness, Truthiness
>- 1. True/False value of a claim is importent, but...
  - It's not only about fact; it's also about the possiblity of having some "facts"
  - Nathan Jurgenson: "The facts of Obama’s birthplace mattered less..."
>- 2. Facts vs. "facty" info
  - "Factiness is the taste for the feel and aesthetic of 'facts'" 
  - We like to be informed, like, super informed: "facty" info is attractive whether it true or not

---

## Cyber Social Project and Information Trustworthiness
>- 1. Consumer-side media diet
  - Info presented vs. Info consumed
>- 2. Moment-by-moment granularity
  - Naturally-occurring data
>- 3. Duke Database Research Group's ClaimBuster
  - SVM trained on presidential debate texts
  - Has a REST API

---

## Factiness by Behavioral Categories
<img src="assets/fig/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

---

## Topic Modeling and Trend of the Mean Factiness Score: Phone
<img src="assets/fig/unnamed-chunk-3-1.png" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" style="display: block; margin: auto;" />

---

## Topic Modeling and Trend of the Mean Factiness Score: Laptop
<img src="assets/fig/unnamed-chunk-4-1.png" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" style="display: block; margin: auto;" />

---

## Trend of the Mean Factiness Score, 10-11 am: Phone
<img src="assets/fig/unnamed-chunk-5-1.png" title="plot of chunk unnamed-chunk-5" alt="plot of chunk unnamed-chunk-5" style="display: block; margin: auto;" />

---

## Trend of the Mean Factiness Score, 10-11 am: Laptop
<img src="assets/fig/unnamed-chunk-6-1.png" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" style="display: block; margin: auto;" />

---

## Within-individual Statistical Analysis



```r
mdS[10:23]
```

```
##  [1] "                     Estimate Std. Error t value Pr(>|t|)    " 
##  [2] "(Intercept)           0.58566    0.04572  12.808  < 2e-16 ***" 
##  [3] "categoryFile System  -0.40634    0.08913  -4.559 5.37e-06 ***" 
##  [4] "categoryGaming       -0.14203    0.04624  -3.071  0.00215 ** " 
##  [5] "categoryMail         -0.13758    0.04755  -2.893  0.00384 ** " 
##  [6] "categoryNews         -0.08230    0.04757  -1.730  0.08373 .  " 
##  [7] "categoryOther        -0.08665    0.04598  -1.884  0.05962 .  " 
##  [8] "categorySocial Media -0.12087    0.04761  -2.539  0.01118 *  " 
##  [9] "categoryText Editing -0.33875    0.05457  -6.208 6.17e-10 ***" 
## [10] "categoryText msg     -0.09358    0.05849  -1.600  0.10972    " 
## [11] "categoryVideo        -0.17747    0.17709  -1.002  0.31637    " 
## [12] "categoryWeb surfing  -0.11620    0.04654  -2.497  0.01259 *  " 
## [13] "---"                                                           
## [14] "Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1"
```





