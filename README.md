# bdsi_2022

Contains slides and handouts for BDSI review classes. 

## Housekeeping

The lectures have little active learning components where you will be reviewing how to use `R` to analyse some real-life datasets. In order to do so effectively, please make sure you run the following code chunk 

```r
install.packages("librarian")
librarian::shelf(tidyverse, patchwork, ggsci)
```

and then run

```r
nhanes.samp.adult.500 <- read_csv("https://raw.githubusercontent.com/soumikp/bdsi_2022/main/data/nhanes.samp.adult.500.csv")
prevend.samp <- read_csv("https://raw.githubusercontent.com/soumikp/bdsi_2022/main/data/prevend.samp.csv")
```
If your installation was not successful, you'll get an error message. Feel free to email me (soumikp@umich.edu) if you have trouble! 
