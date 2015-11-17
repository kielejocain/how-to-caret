# Datasets in R and its Packages

`R` has a great many datasets built into its core installation under the package `datasets`.  In addition, both `caret` and its graphical dependancy `ggplot2` come with several datasets built in.

## Accessing any of these datasets

If you see a dataset that interests you, make sure the relevant package is loaded (if necessary).  Then, by running the command `data(<dataset>)` you get your dataset of choice pre-loaded into your instance.  Technically the dataset doesn't fully arrive until you try to do something with it, but since you'll want to inspect it almost immediately:

    data(iris)
    str(iris)

This sequence will load the `iris` dataset and then tell you about its structure.  You could also run `?iris` to get the documentation on the data set, which might bring more clarity to the columns.

## Datasets built into `R` via the `datasets` package

[Official list](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/00Index.html)

Unfortunately several of these data sets are quite small.  Two that might be of interest:

1. `airquality` - Ozone readings in parts per billion based on 5 predictors.
2. `iris` - A classification of iris species on 4 predictors.

## Datasets in the `caret` package

[Official list](http://topepo.github.io/caret/datasets.html)

Much more thorough descriptions at the `caret` page.  Each dataset is relatively flush with predictors and observations.

A relatively approachable dataset might be `cars`.

## Datasets in the `ggplot2` package

[Official list](http://docs.ggplot2.org/current/) (look under the **Data** heading a little over half-way down)

No descriptions here (though again, you can use `?<dataset>` to get the documentation).

Of particular interest here is the `diamonds` dataset.  50,000 observations, 9 predictors for price, endless possibilities.
