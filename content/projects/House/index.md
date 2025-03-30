---
layout: page
permalink: "house"
title: "Predicting House Prices with the Ames Housing Dataset"
date: 2025-03-16
showAuthor: true
showDate: true
showReadingTime: true
---

In today’s competitive real estate market, accurately predicting house prices is critical for making informed buying and selling decisions. Using the Ames Housing Dataset, which includes over 70 features capturing structural details, neighborhood demographics, and other housing attributes, we aim to build a regression model that forecasts a property’s final sale price.

## Overview

In today’s competitive real estate market, accurately predicting house prices is critical for making informed buying and selling decisions. This project leverages the detailed Ames Housing Dataset to build two regression models:
- **Linear Regression:** A baseline model.
- **Elastic Net:** An enhanced model that combines L1 (Lasso) and L2 (Ridge) regularization to improve prediction accuracy by mitigating multicollinearity and overfitting.

## Dataset Description

The Ames Housing dataset provides comprehensive details about residential properties in Ames, Iowa. It is a preferred alternative to other housing datasets due to its rich feature set covering various structural, spatial, and demographic characteristics.

## Recommendations & Conclusion

Based on our analysis and modeling results comparing a baseline Linear Regression model with an Elastic Net regularized model, we draw the following conclusions:

1. The Elastic Net model outperformed the basic Linear Regression model by achieving a lower RMSE and higher R². This suggests that incorporating regularization helps to mitigate issues like multicollinearity and overfitting, leading to more reliable predictions.

2. Key predictive features identified in both models include Total Living Area (TotalSF), Overall Quality, and House Age. These results highlight that both the size and the perceived quality (or age) of a property are critical drivers of its sale price.

3. For potential Home Buyers:
 - Prioritize properties with ample living space and strong overall quality, as these factors are strongly linked to market value.
 - Consider the age and condition of a home, since these elements can influence future resale value.

4. For Home Sellers:
 - Invest in improvements that enhance the overall quality or expand functional living space (for instance, finishing a basement), which are likely to increase a home’s market appeal and sale price.


 For further details: [https://github.com/treylonwofford/project2](https://github.com/treylonwofford/project2)
