---
layout: default
title: Tutorials
description: Vega-lite Tutorial
isHome: false
---

# Vega-lite Tutorial

This tutorial is intended to introduce you to the basics of Vega. We will show
how you can quickly build statistical graphics using Vega-lite. After
completing the tutorial, you shoudl be ready to start describing visualization
with Vega-lite.

## Vega-lite Specifications

A Vega-lite specification is a JSON object that describes a single data source
(`data`), a mark type (`marktype`), key-value visual encodings of data
variables (`enc`), and data transformations including filters (`filter`) and
aggregate functions. Vega-lite assumes a tabular data model: each data source
is a set of records, where each record has values for the same set of
variables.
