---
layout: default
title: Home
description: A Visualization Grammar for Visual Analysis
isHome: true
---


Vegalite is a visualization grammar for visual analysis modeled after existing tools and grammars such as
[Tableau’s VizQL](http://www.tableausoftware.com/products/technology),
[Wilkinson’s Grammar of Graphics](http://books.google.com/books/about/The_Grammar_of_Graphics.html?id=_kRX4LoFfGQC)
and [Wickham’s ggplot2](http://ggplot2.org/), and generates detailed [Vega](https://vega.github.io/) specifications.

Vegalite specifications consist of a set of mappings between visual encoding channels and (potentially transformed) data variables. Like other high- level grammars, these specifications are incomplete, in the sense that they may omit details ranging from the type of scales used to visual elements such as fonts, line widths and so on. The Vegalite compiler uses a rule-based system to resolve these ambiguities and translate a Vegalite specification into a detailed specification in the lower-level Vega visualization grammar.


# Overview

A Vegalite specification is a JSON object that describes a data source
(`data`), a mark type (`marktype`), key-value visual encodings of data
variables (`enc`), and data transformations including filters (`filter`) and
aggregate functions. Vegalite assumes a tabular data model: each data source
is a set of records, where each record has values for the same set of
variables.


<!-- Vegalite specifications consist of simple mappings of variables in a data set
to visual encoding channels such as position (`x`,`y`), `size`, `color` and
`shape`. These mappings are then translated into full visualization
specifications using the Vega visualization grammar. These resulting
visualizations can then be exported or further modified to customize the
display. -->

## Data

Similar to Vega, Vegalite use tabular data model and supports inline or loading data from url.

{% highlight json %}
{
  data: {
    url: "<data_url>"
  }
}
{% endhighlight %}

## Marktype


## Encoding


## Displaying Vegalite


## Filter

## Config

## Schema


The complete schema for specifications as [JSON schema](http://json-schema.org/) is at [spec.json](https://uwdata.github.io/vegalite/spec.json). Use Vegalite in the [online editor](https://uwdata.github.io/vegalite/).


## Vegalite Specification
