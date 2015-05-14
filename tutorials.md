---
layout: default
title: Tutorials
description: Vegalite Tutorial
isHome: false
---

# Vegalite Tutorial

This tutorial is intended to introduce you to the basics of Vega. We will show
how you can quickly build statistical graphics using Vegalite. After
completing the tutorial, you shoudl be ready to start describing visualization
with Vegalite.

## Vegalite Specifications

A Vegalite specification is a JSON object that describes a single data source
(`data`), a mark type (`marktype`), key-value visual encodings of data
variables (`enc`), and data transformations including filters (`filter`) and
aggregate functions. Vegalite assumes a tabular data model: each data source
is a set of records, where each record has values for the same set of
variables.
