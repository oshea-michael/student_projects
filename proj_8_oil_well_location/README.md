# Analysis of Borehole Information to Establish Most Profitable Location for Oil Well

## Overview:

Tools: Python, Pandas, Numpy, Matplotlib, scikit-learn

Goal: Determine most profitable region for oil drilling

Borehole testing data from oil company was used to establish a. the most profitable and b. the most sure choice of region for drilling a new oil well.

Topics/Techniques: Regression, bootstrap, business model analysis

## Description:

The goal of this project is to provide recommendations for an oil company that seeks to drill a new oil well. The company has done preliminary surveying of three different regions, and it has requested information about which of the three will prove the most profitable. In addition to the question of potential profit, the company has requested an analysis of the potential risk of negative profit.

The data contains information from different test sites, including unlabeled (i.e. nature of information not provided) information about content as well as yield. The data is separated by region, and within each region results from test sites can differ greatly. Due to this, the approach chosen for this analysis is to train a linear regression model, then to make use of the bootstrap technique to establish a 95% confidence interval about drilling in a given region and to draw conclusions based on this confidence interval.
