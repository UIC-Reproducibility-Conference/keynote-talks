# UIC Reproducibility Keynotes

<!-- badges: start -->
<!-- badges: end -->

## Description

This repo is workspace for Vicky and Hao to collaboratively work on keynote presentations for the November 2021 virtual symposium on Research Reproducibility hosted by the University of Illinois Chicago University Library.

To build the slides locally, you need to install R, RStudio, and the [`renv`](https://rstudio.github.io/renv/articles/renv.html) R package. Once you have done so, open the `UIC-repro-keynote.Rproj` file in this repository with RStudio. Once in RStudio, you can install the dependencies of this repository with `renv` like so:

~~~
> renv::restore()
~~~

Then run the following commands in the console to see Hao's slides:

~~~
> rmarkdown::render('slides_02_Hao.Rmd', 'xaringan::moon_reader')
~~~

You will then see `slides_02_Hao.html`. Open this files in a web browser, and you will be able to see his slides.

## Talk Schedule

|date | time | person | talk title | primary file |
|-----|------|--------|------------|--------------|
|Tuesday, November 2, 2021| 1300 CT / 1400 ET | Vicky | Reproducibility is a means to an end | [script_01_Vicky.md](script_01_Vicky.md) |
|Wednesday, November 3, 2021| 0900 CT / 1000 ET | Hao | {TBD} | {TBD} |

## Team

* Vicky Rampin | [@VickyRampin](https://twitter.com/VickyRampin) | she/her/hers or they/them/theirs
* Hao Ye | [@ha0ye](https://twitter.com/ha0ye) | he/him/his
