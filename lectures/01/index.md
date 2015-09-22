---
title    : Introduction to Data Science and Text Analytics
subtitle : lecture 01
author   : 謝舒凱 Graduate Institute of Linguistics
mode     : selfcontained # {standalone, draft}
url      : {lib: "../../libraries", assets: "../../assets"}
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
lecnum   : "01"
widgets  : [mathjax, quiz, bootstrap]    # {mathjax, quiz, bootstrap}
ext_widgets: {rCharts: [libraries/widgets/nvd3]}
knit     : slidify::knit2slides
bibliography: /Users/shukai/LOPE_LexInfo/BIB/myRef.bib
github      : {user: loperntu, repo: lads}



--- bg:#FFFAF0
## 大綱
1. Background
2. Text, Text, Text
3. Linguistic Data Science
4. 實例


---
## 大綱
1. __`Background`__
2. Text, Text, Text
3. Linguistic Data Science
4. 實例


---
## 背景

- <span style="color:blue; font-weight:bold"> 文本分析 (text analysis) </span> 在語言學裡 1950 年代即開始。文本自動分析 (text analytics) 則是受到大數據的影響開始興起。

---
# Text Analysis and Text Analytics
目前的關注主題

1. text categorization
2. text clustering / similarity / association 
3. Named Entity Extraction / topic modelling / event detection
4. Sentiment analysis / Opinion mining
5. document summarization
6. text and social network


---
## 應用面

- Historical text mining
- Legal text mining
- Product/comments 




--- bg:#FFFAF0
## 大綱
1. Background
2. __``Text, Text, Text``__
3. Linguistic Data Science
4. 實例


---
## 文本長什麼樣子






--- bg:#FFFAF0
## 大綱
1. Background
2. Text, Text, Text
3. __``Linguistic Data Science``__
4. 實例




---
## 一句話激怒語言學家




---
## 為什麼 BOW 沒用，功能語言學會告訴妳

- BOW (bag-of-word) appraoch



---
## 來源：Local, Web, Sensors







--- bg:#FFFAF0
## 大綱
1. Background
2. Text, Text, Text
3. Linguistic Data Science
4. __``實例``__





---
## 實例 walk through


- numeric data 
- textual data



---


```r
#R code goes here
```



---
## 香水評論
<!-- 改用台北政府資料
-->


```r
comments <- read.csv("../../../data/week2/perfumes_comments.csv", sep = "\t", 
                     dec = ".", quote = "\"")
head(comments)
summary(comments)
```




---
測試

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 




--- &radio

## 複習

What is 1 + 1?

1. 1
2. _2_
3. 3
4. 4

*** .hint

This is easy!

*** .explanation

Really, you don't know how?


---
## 作業

