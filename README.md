# RTutorGasolineTaxes
This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

--- Within this problem set, we will analyze the effects of gasoline taxes on consumer behavior based on the article Gasoline Taxes 
and Consumer Behavior by Shanjun Li, Joshua Linn and Erich Muehlegger (2014). 
The purpose of the paper is to examine how gasoline taxes affect gasoline consumption as distinct from tax-inclusive or tax-exclusive retail gasoline prices.
The authors found that gasoline tax changes indeed lead to stronger consumer responses than commensurate changes in the tax-inclusive gasoline prices. 

The paper can be found online at https://www.aeaweb.org/articles/pdf/doi/10.1257/pol.6.4.302---

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("melinakle/RTutorGasolineTaxes")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorGasolineTaxes)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorGasolineTaxes")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorGasolineTaxes",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
