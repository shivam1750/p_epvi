# [EPVI](https://github.com/shivam1750/p_epvi/blob/main/README.md)

Contents:

- [Project Overview](#overview)
- [Exploratory Data Analysis and Data Transformation & Preprocessing](#eda-and-data-transformation--preprocessing)
- [Principal Component Analysis](#principal-component-analysis-pca)
- [Feature Selector](#feature-selector)
- [Hyperparameter Tuning & Model Comparison](#hyperparameter-tuning--model-comparison)
- [How to Run](#how-to-run)

## Overview

Every four years, [EIA](https://www.eia.gov/consumption/residential/) administers the Residential Energy Consumption Survey (RECS) to a nationally representative sample of housing units across the United States to collect energy characteristics data on the housing unit, usage patterns, and household demographics.

This project focused on 2009 RECS survey data , extracted from [USA EIA website](https://www.eia.gov/consumption/residential/data/2009/) which represents the 13th iteration of the RECS program. First conducted in 1978, the Residential Energy Consumption Survey is a national sample survey that collects energy-related data for housing units occupied as a primary residence and the households that live in them. 2009 data were collected from 12,083 households selected at random using a complex multistage, area-probability sample design. The sample represents 113.6 million U.S. households, the Census Bureau’s statistical estimate for all occupied housing units in 2009 derived from their American Community Survey (ACS).

With a combination of linear as well as Ensemble machine learning methods, the project objective was to:

- Describe/Explore the set of features with the strong statistical associations with target variable Annual Electricity Usage (in kWh)
- Use the selected features to predict total Consumption of Energy in residential homes

The target variable was "KWH" which stands for kilowatt-hour.

The Principal Component Analysis coupled with [FeatureSelector](https://github.com/shivam1750/p_epvi/blob/main/feature_selector.py) was utilized to determine the important features for modeling purpose. These important features were then fed into different linear and ensemble machine learning techniques to generate prediction
