# README

## Septhemes RMarkdown Theme Package

This is an R package containing an RMarkdown theme that you can use to customize the appearance of your RMarkdown documents.

## Installation

You can install this package directly from GitHub using the `devtools` package:

```devtools::install_github("ajmoralesa/septhemes")```



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


## Themes
This package currently provides the following RMarkdown themes:

    - `my_html_format`: A custom theme with the INSEP color scheme.


## Contributing
If you want to contribute to this package, please fork the repository and submit a pull request with your changes.

## License
This package is licensed under the MIT License. See the LICENSE file for details.