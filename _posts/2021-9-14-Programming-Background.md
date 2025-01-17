Programming Background
================
Jenna Wilkie
9/14/2021

``` r
#code chunk to change image output destination
knitr::opts_chunk$set(fig.path = "../images/")
```

## Prompt:

**Everyone in this course had some programming experience coming in (due
to the prerequisites). What are your thoughts on R vs whatever other
software you’ve used? What functionality do you like about R? What parts
do you miss about your other language? Do you consider R a difficult
language to learn? (If you knew R prior to the course, describe your
experience when first learning it.)**

The first programming language I learned was Python. When I first
started learning R, I thought it was much more difficult than Python.
The syntax used in Python felt much more straightforward. I also felt
the same way about SAS language vs. R. There are also not as many
functions in Python that do the same thing (at least that I know of), so
that made it an easier language to pick up in the beginning. Now that
I’ve had a little more time to get used to R, I like that it has many
functions built in for statistical analysis. I think, of the programming
languages I’ve learned, R was the most difficult. In terms of
statistical analysis, I usually prefer SAS, but R does have some perks.
I really like how easy it is to use the R markdown tool to make reports
that include code. Once I had more time to practice in R, it was not
nearly as daunting as when I was first learning it.

## Example R Markdown Output

``` r
library(Lahman)
plot(Pitching$ER)
```

![](../images/plot-1.png)<!-- -->
