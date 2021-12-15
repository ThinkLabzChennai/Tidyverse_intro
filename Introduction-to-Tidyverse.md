---
title: "Introduction <br> to <br> Tidyverse"
author:    
    -  "RSN_Thinklabz_Chennai"

output:
  html_document:
    toc: yes
    keep_md: true
    
---





# Preamble
This notes aims at giving an introduction to Tidyverse package, which is extremely useful for data manipulation. We shall see the packages which comes with Tidyverse and also their functionality.

# Tidyverse
The tidyverse is a collection of R packages designed for data science. It was introduced by a team lead by Hadley Wickham, a statistician from New Zealand who is currently chief scientist at RStudio. All packages in tidyverse share an underlying design philosophy, grammar and data structures. The packages which are part of core Tidyverse(version 1.3.0) are 
   
   1) ggplot2
   2) dplyr
   3) tidyr
   4) readr
   5) purr
   6) tibble
   7) stringr
   8) forcats   
   
The ultimate aim of the packages is to aid us load, clean, wrangle, plot and model the data

##  Functionality of packages

Let us briefly look at functionality of these packages

### ggplot2
ggplot2 is a package for creating beautiful graphs, based on the idea 'Grammar of Graphics'. Once we understand the fundamental structure of ggplot2 functions we can produce any graphical representation of data with ease.  

### dplyr
dplyr provides a grammar of data manipulation. The functions in dplyr are easy to understand, which are called verbs. Tasks like subsetting, filtering, grouping can be done using this package

### tidyr
tidyr provides a set of functions that help you get to tidy data. Tidy data is data with a consistent form. It describes a standard way of storing data that is used wherever possible throughout the tidyverse. 

### readr
readr provides a fast and friendly way to read rectangular data (like csv, tsv, and fwf). It helps us parse a flat file into a tibble. 

### purrr
purrr enhances R's functional programming (FP) toolkit by providing a complete and consistent set of tools for working with functions and vectors. With purr's usage we can modify our code in more efficient way for writing loops and defining functions etc.

### tibble
tibble is a modern re-imagining of the data frame, keeping what time has proven to be effective, and throwing out what it has not. Tibbles are data frames that are lazy and surly: they do less and complain more forcing you to confront problems earlier, typically leading to cleaner, more expressive code.

### stringr
String manipulation is an important skill a data science enthusiast need to make use of data. stringr provides a cohesive set of functions designed to make working with strings as easy as possible. 

### forcats
 R uses factors to handle categorical variables, variables that have a fixed and known set of possible values.Factors are also helpful for reordering character vectors to improve display. forcats gives us tools to solve common problems with factors.
    
    
    
The tidyverse also includes many other packages with more specialised usage such as
   
   1) lubridate for handling date time
   2) blob for storing binary data
   3) hms for handling time durations

# End note
 In this notes we have given an introduction to tidyverse and some default packages that comes with it and their functionality, one can learn more about tidyverse from [here](https://www.tidyverse.org/) 
 

