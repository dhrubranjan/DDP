---
title: "Coursera Developing Data Products- Shiny Project"
author: "Dhrub Ranjan"
highlighter: highlight.js
output: pdf_document
job: null
knit: slidify::knit2slides
mode: standalone
hitheme: tomorrow
subtitle: Project Deck
framework: io2012
widgets: []
---

## US Rig Count Dataset Explorer  

This Shiny App is for searching and visulizating US Rig Count information from year 1987 to 2015. The total number of records is 333, seperated across Onshore, Offshore, Crude Oil and Natura Gas Rigs.
The dataset is from U.S. Energy Information Administration (http://www.eia.gov/dnav/ng/NG_ENR_DRILL_S1_M.htm).  

Data Source: http://www.eia.gov/dnav/ng/NG_ENR_DRILL_S1_M.htm  

Link to Source Files: [GitHub](https://github.com/dhrubranjan/DDP)

--- .class #id 

# The Data for the Rig Counts

```
## Loading required package: xlsx
```

```
## Loading required package: rJava
```

```
## Loading required package: xlsxjars
```

```
## 
## Attaching package: 'xlsx'
```

```
## The following object is masked from 'package:slidifyLibraries':
## 
##     getCells
```

```
## Loading required package: base64enc
```

```
## Warning: package 'dplyr' was built under R version 3.2.5
```

```
## 
## Attaching package: 'dplyr'
```

```
## The following objects are masked from 'package:stats':
## 
##     filter, lag
```

```
## The following objects are masked from 'package:base':
## 
##     intersect, setdiff, setequal, union
```

```
## Warning: package 'reshape' was built under R version 3.2.5
```

```
## 
## Attaching package: 'reshape'
```

```
## The following object is masked from 'package:dplyr':
## 
##     rename
```

```
## Error in loadWorkbook(file): Cannot find ./data/USRigCount.xlsx
```

```
## Error in eval(expr, envir, enclos): could not find function "setnames"
```

```
## Error in eval(expr, envir, enclos): could not find function "setnames"
```

```
## Error in eval(expr, envir, enclos): could not find function "setnames"
```

```
## Error in data$Date: object of type 'closure' is not subsettable
```

```
## Error in eval(expr, envir, enclos): could not find function "setnames"
```

```
## Error in data[, c("Date", "Year", "Onshore", "Offshore", "CrudeOil", "NaturalGas")]: object of type 'closure' is not subsettable
```

```
##                                                                      
## 1 function (..., list = character(), package = NULL, lib.loc = NULL, 
## 2     verbose = getOption("verbose"), envir = .GlobalEnv)            
## 3 {                                                                  
## 4     fileExt <- function(x) {                                       
## 5         db <- grepl("\\\\.[^.]+\\\\.(gz|bz2|xz)$", x)              
## 6         ans <- sub(".*\\\\.", "", x)
```
# Melted Flat Dataset


```
## Error in head(flatdata): object 'flatdata' not found
```

--- .class #id 

## Total Number of Rig Counts in the US for each type


```
Error in eval(i, data, env): object 'flatdata' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

--- .class #id 

## Total Number of Rig Counts in the US


```
Error in eval(i, data, env): invalid 'envir' argument of type 'closure'
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```


