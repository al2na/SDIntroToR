# SDIntroToR

This package contains a set of instructional material to introduce R in a guided interactive way.  A beamer slide presentation with examples meant to be worked by students is included.

# Installation

## Windows

1. Start R (or RStudio)
2. Paste the following code into your R session

```{r}
source('http://bioconductor.org/biocLite.R')
biocLite('SDIntroToR',siteRepos = "http://watson.nci.nih.gov/~sdavis/software/R")

```

## Linux/Mac 

1. Start R (or RStudio)
2. Paste the following code into your R session

```{r}
source('http://bioconductor.org/biocLite.R')
biocLite('SDIntroToR',siteRepos = "http://watson.nci.nih.gov/~sdavis/software/R",type="source")
```

# Where are the slides?

After installing the package, various exercise sets and R Intro slides are available by typing:

```{r}
browseVignettes(package='SDIntroToR')
```

