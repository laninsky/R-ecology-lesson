[![Build Status](https://travis-ci.org/datacarpentry/R-ecology-lesson.svg?branch=master)](https://travis-ci.org/datacarpentry/R-ecology-lesson)
[![Create a Slack Account with us](https://img.shields.io/badge/Create_Slack_Account-The_Carpentries-071159.svg)](https://swc-slack-invite.herokuapp.com/)
[![Slack Status](https://img.shields.io/badge/Slack_Channel-DC_Ecology_R-E01563.svg)](https://swcarpentry.slack.com/messages/C9X9EC405)


# Data carpentry: R for data analysis and visualization of Ecological Data

This is an introduction to R designed for participants with no programming
experience. These lessons can be taught in 3/4 of a day (6 hours). They start
with some basic information about syntax for the R programming language, the
RStudio interface, and move through to specific programming tasks, such as
importing CSV files, the structure of data frame objects in R, dealing with
categorical variables (i.e. factors), basic data manipulation (adding/removing
rows and columns), and finishing with calculating summary statistics and a brief
introduction to plotting. There is also a lesson on how to use databases from R that is intended to be taught after the SQL lesson, and ideally at the end of a Data Carpentry workshop.

## Prerequisites

> * Having R and RStudio installed (though see the first
> lesson, [Before we start](http://datacarpentry.org/R-ecology-lesson/00-before-we-start.html) for installation
> instructions)

## Topics

* [Before we start](https://github.com/laninsky/R-ecology-lesson/blob/master/_site/00-before-we-start.html)
* [Introduction to R](https://github.com/laninsky/R-ecology-lesson/blob/master/_site/01-intro-to-r.html)
* [Aggregating and analyzing data with dplyr](https://github.com/laninsky/R-ecology-lesson/blob/master/02-dplyr.Rmd)
* [Data visualization with ggplot2](https://github.com/laninsky/R-ecology-lesson/blob/master/04-visualization-ggplot2.Rmd)

## Code handout

There is "[code handout](code-handout.R)" (`code-handout.R`) that is intended to
be distributed to the participants. This file includes some of the examples used
during teaching and the titles of the section. It provides a guide that the
participants can fill in as the lesson progresses. Participants can also source
code from this file to avoid typos in more complex examples.

## Contributing

If you would like to contribute to the content and development of these lessons,
we encourage you to review our [contributing guide](CONTRIBUTING.Rmd).

## Questions

If you have any questions or feedback, please open an issue, contact the
maintainers, or come chat with us on the [Slack Channel for this lesson](https://swcarpentry.slack.com/messages/C9X9EC405). If you don't already have a Slack account with the Carpentries, you can [create one](https://swc-slack-invite.herokuapp.com/).

* Ana Costa Conrado
* Auriel Fournier
* François Michonneau
* Brian Seok
* Shiva Guru

## Modifications by laninsky
Lessons 00, 01, 02 (tidyverse), and 04 are up to date as of 9 Feb in respect to changes made in master that it made sense to make. Modified 02 (tidyverse) for changes that had to be made seeing as we are giving it a go presenting it straight after the intro.
