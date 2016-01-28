---
title       : Random Forest with First Two Principal Components
subtitle    : Developing Data Products - Shiny
author      : Giovanni Viglioni (2016 - Jan)
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## PCA Transformation I

. Let's check the data

![Base](assets/img/Base_Dados.jpg)

. Due to the non-negative feature, transform the numeric variables by logarithm first

![Transform](assets/img/Transform_Variable.jpg)

. Print and plot can be directly applied on the PCA object produced by prcomp function

. Loadings and variance explained on each PC factors are printed and graphed

--- .class #id 
## PCA Transformation II

This function computes the standard deviation of the values in x. If na.rm is TRUE then missing values are removed before computation proceeds.

![Desvio](assets/img/Desvio_Padrao.jpg)

--- .class #id 
## Scatter plot

Show the relationship between two numeric variables

![C_Scatter](assets/img/Comando_ScatterPlot.jpg)

![G_Scatter](assets/img/Grafico_ScatterPlot.jpg)

--- .class #id 
## Correlation matrix

Calculate and visualize the correlation between features

![C_Correlation](assets/img/Comando_Correlation.jpg)

![G_Correlation](assets/img/Grafico_Correlation.jpg)

--- .class #id 
## Shiny App: IRISApp

![First_Imagem](assets/img/First_Imagem.jpg)

[Random Forest with First Two Principal Components App Hosted by shinyapps.io](https://gviglioni.shinyapps.io/IrisApp/)


--- .class #id 
## Thank you!

![Thanks](assets/img/Thanks.jpg)

Feel free to send me your comments,questions or report bugs [gviglioni@gmail.com].
