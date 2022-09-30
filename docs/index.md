--- 
title: "Core Statistics in R"
author: "Matt Castle and Martin van Rongen"
date: "2022-09-28"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
# url: your book url like https://bookdown.org/yihui/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
description: "These are the supporting materials for the Core Statistics modules of the PSLS Biostatistics Initiative, Cambridge University." 
---



# Overview

These sessions are intended to enable you to perform core data analysis techniques appropriately and confidently using R.

- 6 lecture-practicals
- Ongoing formative assessment exercises
- No formal assessment

- No mathematical derivations
- No pen and paper calculations

They are **not** a “how to mindlessly use a stats program” course!

## Core aims
:::highlight
To know what to do when presented with an arbitrary dataset e.g.

1. Know what data analysis techniques are available
2. Know which ones are allowable
3. Be able to carry these out and understand the results
:::

## Core topics

1. [Simple hypothesis testing](#cs1-intro)
2. [Categorical predictor variables](#cs2-intro)
3. [Continuous predictors](#cs3-intro) 
4. [Two predictor variables](#cs4-intro)
5. [Multiple predictor variables](#cs5-intro) 
6. [Power analysis](#cs6-intro)

## Practicals

Each practical document is divided up into various sections. In each section there will be some explanatory text which should help you to understand what is going on and what you’re trying to achieve.
There may be a list of commands relevant to that section which will be displayed in boxes like this:

:::note
**Conditional  operators**

To set filtering conditions, use the following _relational operators_:

- `>` is greater than
- `>=` is greater than or equal to
- `<` is less than
- `<=` is less than or equal to
- `==` is equal to
- `!=` is different from
- `%in%` is contained in
 
To combine conditions, use the following _logical operators_:
 
- `&` AND
- `|` OR
:::

## Datasets {#index-datasets}

This course uses various data sets. The easiest way of accessing these is by creating an R-project in RStudio. Then download the `data` folder [here](data.zip) by right-clicking on the link and <kbd>Save as...</kbd>. Next unzip the file and copy it into your working directory. Your data should then be accessible via `<working-directory-name>/data/tidy`.
