---
title: "Neddi osti"
author: "1"
date: 2018-08-26
draft: false
categories: ["R"]
tags: ["R Markdown", "blogdown", "#rstats"]
thumbnailImagePosition: left
thumbnailImage: ./images/logo.png
coverImage: ../../../images/transparent.png  
coverSize: partial # full: for maximum cover size
metaAlignment: center
disable_comments: true
output:
  blogdown::html_page:
    toc: false
    fig_width: 8
    css: "/css/my-style.css"
--- 

fofjo  ejfow qof 0fs




```r
library(ggplot2)
ggplot(diamonds, aes(x=carat, y=price, color=clarity)) + geom_point()
```

<div class="figure">
<img src="{{< blogdown/postref >}}index.en_files/figure-html/diamond-1.png" alt="diamonds plot with ggplot2." width="768" />
<p class="caption">Figure 1: diamonds plot with ggplot2.</p>
</div>
