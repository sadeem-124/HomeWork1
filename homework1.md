Homework \#1 – Pet Names Dataset
================
Sadeem Ghareeb Al Enazi

2021-02-14

**Student ID:2201001438**

**Deadline:** 23:59 on Saturday, 13 February 2021

**Total Points:** 30

## Loading Packages

``` r
library(tidyverse)
library(openintro)
library(ggrepel)
```

\#\#Exercises

\`1.

(4 points)

There are 52519 pets (same number of rows in dataset)

\`2.

(4 points)

There are 7 variables
(license\_issue\_date-license\_number-animal\_name-species-primary\_breed-secondary\_breed-zip\_code)

\`3. Copy the code provided in the homework documentation and paste it
here.

(4 points)

``` r
seattlepets %>%
count(animal_name, sort = TRUE)
```

    ## # A tibble: 13,930 x 2
    ##    animal_name     n
    ##    <chr>       <int>
    ##  1 <NA>          483
    ##  2 Lucy          439
    ##  3 Charlie       387
    ##  4 Luna          355
    ##  5 Bella         331
    ##  6 Max           270
    ##  7 Daisy         261
    ##  8 Molly         240
    ##  9 Jack          232
    ## 10 Lily          232
    ## # … with 13,920 more rows

The three most common pet names are:

Name frequency

------------------------------------------------------------------------

Lucy 439  
Charlie 387  
Luna 355

\`4.

(10 points)

\`5. What names are more common for cats than dogs? The ones above the
line or the ones below the line?

Answer here

(4 points)

\`6. Is the relationship between the two variables (proportion of cats
with a given name and proportion of dogs with a given name) positive or
negative? What does this mean in context of the data?

Answer here

(4 points)
