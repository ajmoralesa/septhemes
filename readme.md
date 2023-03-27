# README

## Septhemes RMarkdown Theme Package

This is an R package containing an RMarkdown theme that you can use to customize the appearance of your RMarkdown documents.

## Installation

You can install this package directly from GitHub using the `devtools` package:

```devtools::install_github("username/septhemes")```



## Usage

To use the RMarkdown theme provided by this package, add the following code to the YAML header of your RMarkdown document:



```{r}

---
title: "My Document"
output: 
  septhemes::my_html_format:
    toc: true
---

```