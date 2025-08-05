
# Debugging Tools for Functions in R

## Overview

_Description:_

If you write functions but are unsure of efficient strategies to identify the 
source of errors then join this workshop to unlock your programming superpower 
with debugging techniques! In this workshop, we will review code troubleshooting tips, 
discuss debugging functions (traceback(), browser(), debug(), trace(), and recover()), 
and distinguish between strategies for debugging your own code versus someone else’s code.

_Learning goals:_

1. Review code troubleshooting tips. 

2. Apply debugging functions (`traceback()`, `browser()`, `debug()`, `trace()`, and `recover()`) 
and identify the additional benefits of employing some of these strategies within RStudio. 

3. Distinguish between strategies for debugging your own code versus someone else’s code.

_Target audience:_ Individuals with experience writing functions but new to debugging.

## Pre-work

1. Please have a recent version of R and RStudio installed.
- R >= 4.2
- RStudio >= 2024.04.1+748

2. Install the following packages: 
`install.packages(c("usethis", devtools"))`

3. Please make sure your system is ready to build packages. You can 
confirm this by checking if `devtools::has_devel()` returns `Your system is ready to build packages!`. 
If this returns `Could not find tools necessary to compile a package` this indicates
your system needs additional tools - please see https://rstats-wtf.github.io/wtf-personal-radmin-slides/#/how-to-get-the-tools
to identify what to install for your OS.


## Materials

* slides: <https://rstats-wtf.github.io/wtf-debugging-slides/>

* exercises: 

  + <https://github.com/rstats-wtf/wtf-debugging>
  
  + <https://github.com/rstats-wtf/wtfdbg>
  
* book: <https://rstats.wtf>

## Instructors

[Shannon Pileggi](https://www.pipinghotdata.com/) (she/her) is the Associate Director
of Data Science at The Prostate Cancer Clinical Trials Consortium, an occasional blogger, 
and a member of the R-Ladies Global leadership team. She enjoys automating data wrangling 
and data outputs, and making both data insights and learning new material digestible.

[E. David Aja](https://edavidaja.com/) is a Solutions Engineer at Posit. 
Before joining Posit, he worked as a data scientist in the public sector.





