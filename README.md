Mueller Price Optimization
Overview
This repository contains a data science project developed as part of a Buynomics pricing optimization assessment.
The objective is to model how sales are influenced by pricing, product attributes, and market conditions, and then use this model to optimize pricing strategies for the Mueller brand.

Project Objectives
Data Exploration

Understand sales trends, price distributions, and flavour performance across the market.

Compare Mueller’s position against competitors.

Predictive Modeling

Build a market-wide Generalized Additive Model (GAM) to estimate demand (units sold) from:

Product price

Market average price (competitor influence)

Flavour and brand factors

Revenue Optimization

Simulate different price points and market scenarios.

Identify revenue-maximizing prices for each Mueller flavour.

Key Features
Exploratory Data Analysis (EDA)

Visualizations: price distribution, units vs price, market share, flavour popularity.

Elasticity Modeling

GAM model capturing non-linear price-demand relationships and flavour/brand effects.

Optimization Simulation

Price sensitivity curves

Revenue optimization under varying market conditions

Actionable Insights

Optimal price points and expected revenue uplift

Competitor scenario analysis (±15% market price shift)

Technologies Used
Python 3.11+

Libraries:

pandas, numpy (data manipulation)

matplotlib, seaborn (visualization)

pyGAM (Generalized Additive Models)

