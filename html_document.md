---
title: "Module 3 html doc"
author: "Sia Gerard"
date: "2025-05-05"
output: 
  html_document: 
    keep_md: true
    fig_width: 6
    fig_height: 6
    toc: yes
    toc_float: true
    code_folding: hide
---



# Module 3 - HTML document

## R Markdown {#nextsteps .ephasized}

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

### Plot the Cars dataset


``` r
plot(cars)
```

![](html_document_files/figure-html/cars-1.png)<!-- -->

## Including Plots

You can also embed plots, for example:

### Plot the presure dataset

![](html_document_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## A Short List

 *apples
 *oranges
 *bananas

## A simple equation 

$$ Y = \beta_0 + \beta_1*X $$
