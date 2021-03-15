---
title: What a Year Ahead
author: R package build
date: '2021-03-15'
slug: what-a-year-ahead
categories:
  - Test
tags:
  - Blog
  - Courses
description: What's the future looking like? A lot of knowledge to be discovered
image: zaksheuskaya.jpg
math: ~
license: ~
hidden: no
comments: yes
---
Although it may seem that I'm referring to the current COVID-19 situation, this is actually a post on how I've decided to ruin my life once and for all, with everything I'd like to know by the end of the year. Seems like a heck of a long shot now that I'm reading this again, but let this boy dream. Below some stuff I'm studying now and something that's planned for the future.

# Hit 'em with the Nested List

* Courses I'm currently taking 
  * Genomic Data Science
  * R for Data Science
  * Machine Learning A-Z™: Hands-on Python & R In Data Science
* Courses I've planned 
  * Single Cell RNA-seq Data Analysis
  * Data Visualization & Dashboarding with R
  * Statistics for Genomic Data Science
  * Statistical Inference and Modeling for High-throughput Experiments
  * High dimensional Data Analysis
  * Case Studies in Functional Genomics
  * HarvardX Biomedical Data Science Open Online Training
  * SQL for data science

## What's cooking?
These are courses I've chosen to start with, two of them are actually thought through and well planned. Third one's just an impulse and probably the least needed at this point (aka the ML one). But what can you do when your brain goes rouge and decides on its own, if not following it? 

### Genomic Data Science
I won't redirect to the website of the Master's program simply 'cause it's only in Italian and I don't think will be that helpful, unless you wanna see google translate fail miserably. Also, I won't get into much detail here because I have a post coming out exactly on this topic, not because I'm lazy.  It's a two years commitment just like any other master, nothing fancy, lots of statistics. Various modules and courses that can hint you what it means to be a data scientist working on genomics, ranging from regression models and genomic epidemiology to statistics for genomics and bioinformatics applied to big data. Oh yeah, and a never-ending internship that'll make you regret your life's choices.

### [R for Data Science](https://r4ds.had.co.nz/index.html)
Probably one of the most complete resources on the "basics" of R for data science and by far the most cited resource to start with data science in R that I've found. If you want a hard copy, help yourself [here](https://www.amazon.com/R-Data-Science-Hadley-Wickham/dp/1491910399/ref=as_li_ss_tl?ie=UTF8&qid=1469550189&sr=8-1&keywords=R+for+data+science&linkCode=sl1&tag=devtools-20&linkId=6fe0069f9605cf847ed96c191f4e84dd).  And basics' s in quotes for a reason and I'll get back to that in a second.  

It's structured like this: it throws you directly into the visualization/data manipulation/exploratory data analysis world, without knowing anything about programming; and then teaches you about the fundamentals of data wrangling (data import, tidying, strings, and factors), programming (functions, vectors, iterations and so on) and modeling.
Now, while I do believe the modeling part should be taught at the very end, I wonder why the core programming is taught later in the book. I was confused at the beginning, especially when manipulating data with dyplr, and I know some stuff about R.  

I'm picturing someone approaching this for the very first time going like "the heck is this? Seriously, at some point was really hard to follow along even knowing the syntax, I can only imagine the struggle a complete newbie has to go through. 
That's why I've placed basics in quotes at the beginning, while some parts are really toddler material, this is actually a bit more complex than other introductions to R that you can find online (IMO). I found out that when we start using flights data frame (classic data frame used in data science for teaching) my brain cells just crumble and die.  

Besides this, I do think it's a stupidly good book for learning data science and imma cherry-pick, from the chapters, what I suck at and work on it. But now that I think of it, I don't think I can use "cherry-pick" for stuff  I'm bad at, right? But what if, you do enjoy slamming your face onto your keyboard and google searching every other minute? Is that cherry-picking stuff you suck at a positive behavior? The only way to get better at it? Am I losing my own thread here? I think so, let's move on before it's too late.

### [Machine Learning A-Z™: Hands-on Python & R In Data Science](https://www.udemy.com/course/machinelearning/)
I'll be brutally honest with ya, this was utterly unnecessary at this point, but I was so goddam intrigued. Be it because ML is everywhere if you open up Twitter; every other post in data science threads is some random 13 years old that's teaching ML to grownups 'cause he's already figured out between recesses, what he wants to do with his own life, while I'm there, not sure what I'll cook for dinner. Seriously, it's everywhere. Dunno, why I haven't started this before (no wait I know, I think it's called lacking foundations).  

Anyway, now that I pretty much know what's going on in R, I thought this would be the perfect time to dive deep into the subject. I was particularly interested in what's happening under the hood, mostly because R makes super easy running algorithms, thus I just can't go running around and pressing buttons hoping to get something out. Apparently, you gotta understand what you're doing.  

The course is structured so you can use both R and Python and tries to give you a foundation on the most used algos for machine learning. It's something like "here are your toys, now figure how what you like and how to use them". But we'll talk about this a lot in future posts.



## Courses I'm taking this year
The following are courses I'm planning on taking in the next few months. The underlying idea is to mix things up and integrate more field-specific courses with others that are broader and focus more on data science per se. This is what I came up with for now and hopefully, I'll be able to get them done by the end of the year

### [Single Cell RNA-seq Data Analysis with R offered by CSC](https://www.csc.fi/web/training/-/scrnaseq)
First one up on the list is, without any shadow of a doubt, scRNA-seq analysis (single-cell RNA sequencing). The course is sponsored by elixir [EXCELERATE](https://elixir-europe.org/about-us/how-funded/eu-projects/excelerate) program and organized by the Finnish company [CSC](https://www.csc.fi/en/training). The course is structured with video lessons that can be found on their [youtube channel](https://www.youtube.com/watch?v=BfxDfL1GBzk&list=PLjiXAZO27elC_xnk7gVNM85I2IQl5BEJN), slides, and exercise notebooks on [GitHub](https://github.com/NBISweden/excelerate-scRNAseq).   

Long story short, the course starts with data quality and preprocessing, normalization, confounding removal, and data integration. Then it focuses on dimensionality reduction, clustering, DGEA (Differential Gene Expression Analysis) and ends with cell-type identification, trajectories/Pseudo-time and spatial transcriptomics. 
Even though high-dimensional data concepts are being explained throughout the course, better integration is required. Thus, the courses on edX and Coursera are just about that.

### [Data Visualization & Dashboarding with R on Coursera](https://www.coursera.org/specializations/jhu-data-visualization-dashboarding-with-r)
A bit more of a general-purpose compilation of courses of data visualization. I'm skipping quite a bit here 'cause it repeats a lot of the basics and hopefully, at this point I'm decent enough with R. First course is all about importing, tidying data and there's a lot of info on reporting with R Markdown, and that's why I've chosen this course, mainly.  
Second course's main topic is ggplot2, of course. Cant' go wrong with that guy. I'll quickly browse through this again, but most of the work it's already done in "R for Data Science".   
Third course's the previous one but on steroids.  
Lastly, the fourth one, is all about publishing visualizations with Shiny and Flexdashboard. We going fancy fam.

### [Statistics for Genomic Data Science on Coursera](https://www.coursera.org/learn/statistical-genomics?specialization=genomic-data-science)
This is a course that I'd consider borderline between field-specific biology and multi-purpose statistics. The reason is that, through the course, most of the statistics that are being taught are pretty much all the time applied to genomics and are case-specific. I'll take this hoping that it'd cement my knowledge on exploratory data analysis, normalization, preprocessing, clustering and modeling for genomics.  
Also, in the last module they give you common pipelines for RNA/ChiP-seq, DNA methylation studies, and GWAS. Who am I to refuse this?


### [Statistical Inference and Modeling for High-throughput Experiments on edX](https://www.edx.org/course/statistical-inference-and-modeling-for-high-throug)
This definitely will be the hardest one, mostly 'cause of statistics overload. It'll either bend me or break me, and there's no going back. This is my public statement of commitment. The course focuses on a variety of statistical topics, ranging from multiple testing, error rate controls, false discovery rates to statistical modeling and Bayesian statistics.  
I know, from the very beginning, that this will cause a stupid amount of pain, but what really hurts is that, deep down, I know that I need this. You can't run around the Genomics playground making your own statistics up. You gotta learn this. I gotta learn this. So, off I go, I guess.

### [High dimensional Data Analysis on edX](https://www.edx.org/course/high-dimensional-data-analysis)
This is the first integration to the scRNA-seq course from CSC and provided by HarvardX on the [edX](https://www.edx.org) platform. This course revolves around concepts like mathematical distance, dimensionality reduction, singular value decomposition (SVC), and principal component analysis(PCA).  
Other modules that I find appealing are how to deal with batch effects, heatmaps and clustering, while I'm probably dropping the intro to machine learning also provided by them. I have nothing funny to say about this, sorry.

### [Case Studies in Functional Genomics on edX](https://www.edx.org/course/case-studies-in-functional-genomics?index=product&queryID=ed6c49ffde7ddfe8c8787c6239463e95&position=1)
I'll probably take this one at the same time as the High Dimensional Data analysis, giving the fact this is focusing especially on the analysis of RNA-seq, DNA methylation and ChiP-seq data. Also, it's gonna give a basic understanding of how reads are being mapped to the reference genome and how to assess the quality of NextGen data.  
Basically, NextGen data will become your best friend.

### [HarvardX Biomedical Data Science Open Online Training](http://rafalab.github.io/pages/harvardx.html)
I'm gonna make this quick, there's this GitHub repo that's been made from this book, [hard copy here](https://www.amazon.com/Data-Analysis-Life-Sciences-R/dp/1498775675/ref=sr_1_1?s=books&ie=UTF8&qid=1500332088&sr=1-1), or maybe is the other way around, and it's divided into three sections: [Data Analysis for the Life Sciences](http://rafalab.github.io/pages/harvardx.html#series_1), [Genomics Data Analysis](http://rafalab.github.io/pages/harvardx.html#series_2) and [Using Python for Research](http://rafalab.github.io/pages/harvardx.html#python).  
While the Python section is a hard pass (even though at some point I gotta learn that sneaky little brat), the others look super interesting even if they're most likely repeating some stuff. As a general integration to the other courses, they seem appropriate.

### [SQL for data science on Coursera](https://www.coursera.org/learn/sql-for-data-science?specialization=learn-sql-basics-data-science)
Well, there's not much to say here, you can't work in any data science-related field without knowing a wee bit of SQL.  

This is it, lots of stuff, not much time, way less determination. Let's see what the future holds. 

See ya.