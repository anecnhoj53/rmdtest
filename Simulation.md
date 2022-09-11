---
title: "Simulation"
author: "Ethan"
date: "2022-09-11"
output:
  html_document:
    keep_md: true
  pdf_document: default
---




# Generate data


```r
x = rnorm(1e5)
y = rnorm(1e5)
```



```r
library(ggplot2)

ggplot(data = data.frame(x = x, y = y), aes(x,y)) + geom_point()
```

![](Simulation_files/figure-html/unnamed-chunk-2-1.png)<!-- -->


