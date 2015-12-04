# Reproducible research with `remake` on R

**What:** This courses introduces the [remake](https://github.com/richfitz/remake) package, a framework for managing computational projects in R. Remake is helpful for reducing compute time and for making research reproducible. The course suits researchers who are already using R code to produce figures and analyses and are looking for ways to improve their workflow.\\

**Where:** University of NSW  Colombo Theatre C 9:00-10:30, Dec 08 2015\\

**Instructors:** Daniel Falster (Macquarie University), Will Cornwell (UNSW)\\

**Contact**: Please mail <daniel.falster@mq.edu.au> for more information.\\

## Requirements

Participants should bring a laptop with the following R packages installed.

First install some dependencies from cran as follows:

```r
install.packages(c("R6", "yaml", "digest", "crayon", "optparse"))
```

Now we'll install some packages from [github](github.com). For this, you'll need the package [devtools](https://github.com/hadley/devtools). If you don't have devtools installed you will see an error "there is no package called 'devtools'"; if that happens install devtools with `install.packages("devtools")`.


Then install the following two packages

```r
devtools::install_github("richfitz/storr")
```
and

```r
devtools::install_github("richfitz/remake")
```

Finally, it would be helpful if you installed the following packages will be used in some of more advanced examples:

```r
install.packages(c("knitr", "rmarkdown"))
```
