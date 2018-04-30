---
title: "README"
author: "Kridsadakorn Chaichoompu"
date: "27/04/2018"
output:
  html_document:
    keep_md: yes
  pdf_document: default
---



# R Package kris

## Summary

The R package ```kris``` (**K**een and **R**eliable **I**nterface**S** for 
bioinformatic analysis) is the package providing useful funcions which are 
needed for bioinformatic analysis.

The R package ```kris``` requires the package ```rARPACK```.

Here is the list of functions in the R package ```kris```:

* ```cal.pc.linear```
* ```fst.each.snp.hudson```
* ```fst.hudson```
* ```plot3views```
* ```read.bed```
* ```rubikclust```
* ```write.bed```
* ```xxt```

Moreover, here is the list of example datasets in the R package ```kris```:

* ```simsnp```
* ```sample_labels```

## Installation

Install the released version of ```kris``` from CRAN:


```r
install.packages("kris")
```

## Problems in building the package

### Error of Roxygen2 in building RD files

The source codes in this package include the Roxgen's syntax. If there is a 
problem for generating the RD files (facing some errors) using RStudio (_Build > 
Document_), try to use ```roxygen2::roxygenise()``` instead of _Build > Document_ 
from the menu. Alternatively, install the package ```devtools```, then enable 
RStudio to use the functions from ```devtools``` (check _Build > Configure Build 
Tools... > use devtools package functions if available_) or run 
```devtools::document()``` in the console.

### Error of testthat for unit testing

When facing error for ```testthat```, try to update the package ```testthat``` and add 
```Suggests: testthat``` in _DESCRIPTION_ file.

## CONTRIBUTOR CODE OF CONDUCT

As contributors and maintainers of this project, we pledge to respect all people 
who contribute through reporting issues, posting feature requests, updating 
documentation, submitting pull requests or patches, and other activities.

We are committed to making participation in this project a harassment-free 
experience for everyone, regardless of level of experience, gender, gender 
identity and expression, sexual orientation, disability, personal appearance, 
body size, race, ethnicity, age, or religion.

Examples of unacceptable behavior by participants include the use of sexual 
language or imagery, derogatory comments or personal attacks, trolling, public 
or private harassment, insults, or other unprofessional conduct.

Project maintainers have the right and responsibility to remove, edit, or reject 
comments, commits, code, wiki edits, issues, and other contributions that are 
not aligned to this Code of Conduct. Project maintainers who do not follow the 
Code of Conduct may be removed from the project team.

Instances of abusive, harassing, or otherwise unacceptable behavior may be 
reported by opening an issue or contacting one or more of the project 
maintainers.

This Code of Conduct is adapted from the Contributor Covenant, version 1.0.0, 
available at https://www.contributor-covenant.org/version/1/0/0/code-of-conduct.html

