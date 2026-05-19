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
The `CalibrationCurves` package plots calibration curves and computes statistics for assessing calibration performance of predictive models. It provides essential tools for evaluating model calibration, discrimination, and overall predictive performance across various outcome types.

Detailed information on the package as well as a tutorial can be found on the [package's website](https://bavodc.github.io/websiteCalibrationCurves/){:target="_blank"}.

**Key Features:**
- Generate calibration plots with base R and [ggplot](https://ggplot2.tidyverse.org/){:target="_blank"}
- Comprehensive calibration and discrimination metrics
- Support for binary, continuous and survival outcomes

### [actuaRE](https://cran.r-project.org/package=actuaRE){:target="_blank"} (v1.0.0)
The `actuaRE` package handles single-level and hierarchically structured risk factors using credibility and random effects models. It fits random effects models for multi-level/high-cardinality factors using credibility theory (Buhlmann-Straub for single-level, Jewell for hierarchical structures), GLM extensions, or Tweedie generalized linear mixed models. The package provides functions for model fitting, visualization, and prediction.

As the CalibrationCurves package, this package also has its own dedicated [website](https://bavodc.github.io/websiteactuaRE/) with a tutorial and comprehensive overview of the package's functionality.

**Key Features:**
- Fit random effects models for multi-level factors using three different estimation methods.
- Obtain a comprehensive overview of the properties of the fitted model.
- Verify whether a fitted model has the balance property (i.e., the sum of the predicted values equals the sum of actual observations).
- Regain the balance property by adjusting the intercept term.
- Analyze and visualize the random effect predictions.
