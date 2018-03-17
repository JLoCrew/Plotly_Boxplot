JLo_Course9_Week3 Assignment
========================================================
author: Joyce Lo
date: Mar-14-2018
autosize: true

Analysis on Wine and Spirits
========================================================
- In the next few slides, we will analyze wines and spirits sold at BC Liquor Stores
- Specifically, we shall examine if there is any correlation between:

    + Alcohol Content and Class of Liquor
    
    + Class of Liquor and Country of Origin

Loading and Formatting data
========================================================


```r
#fileURL <- "http://pub.data.gov.bc.ca/datasets/176284/BC_Liquor_Store_Product_Price_List.csv"
#if(!file.exists("data")){dir.create("data")}
#download.file(fileURL, destfile = "./data/liquor.csv")
liquor <- read.csv("./data/liquor.csv")

#Remove rows with NA
liquor2 <- na.omit(liquor)
```


Boxplot - Alcohol Content by Class of Liquor
========================================================



```
Error in loadNamespace(name) : there is no package called 'webshot'
```
