---
layout: page
title: Software & Tools
description: Open Source R Packages and Software
image: assets/images/softwareGenerated.png
nav-menu: true
show_tile: true
permalink: /software/
---

## Software & Tools

You can find a selected set of my software projects on my [Github page](https://github.com/BavoDC){:target="_blank"}. Of these, two are published on CRAN. If you have any questions, suggestions, or collaboration interests, please feel free to contact me! I look forward to hearing from you.

### CRAN Packages

### [CalibrationCurves](https://cran.r-project.org/package=CalibrationCurves){:target="_blank"}
With the `CalibrationCurves` package, you can generate (generalized) calibration curves, which are essential for evaluating the calibration performance of predictive models. In addition, it also computes a comprehensive range of statistics to assess the predictive performance of your model. As such, this package provides the necessary tools to evaluate the performance of your predictive model.

Detailed information on the package as well as a tutorial can be found on the [package's website](https://bavodc.github.io/websiteCalibrationCurves/){:target="_blank"}.

**Key Features:**
- Generate calibration plots with base R and [ggplot](https://ggplot2.tidyverse.org/){:target="_blank"}
- Comprehensive calibration and discrimination metrics
- Support for binary, continuous and survival outcomes

### [actuaRE](https://cran.r-project.org/package=actuaRE){:target="_blank"}
Using this package, you can fit a random effects model using either the hierarchical credibility model, a combination of the hierarchical credibility model with a generalized linear model or a Tweedie generalized linear mixed model.

As the CalibrationCurves package, this package also has its own dedicated [website](https://bavodc.github.io/websiteactuaRE/) with a tutorial and comprehensive overview of the package's functionality.

**Key Features:**
- Fit a random effects model with nested random effect using three different estimation methods.
- Obtain a comprehensive overview of the properties of the fitted model.
- Verify whether a fitted model has the balance property (i.e., the sum of the predicted values equals the sum of actual observations).
- Regain the balance property by adjusting the intercept term.
- Analyze and visualize the random effect predictions.
