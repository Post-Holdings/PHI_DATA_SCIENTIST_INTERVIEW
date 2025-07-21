## Data Science Take-Home Exercise: Product Competitor Analysis

# Overview
Your task is to build a recommendation system that identifies the N-closest competitors for any given product (ASIN) and present your findings to leadership, using a dataset containing Amazon products across various categories. The goal of this presentation is to show the executive that you that understand how to explain data science modeling to business people in a consise and effective manner.

You are welcome to slim this dataset down in any way that you see fit, including limiting it to certain categories. You are encouraged to make reasonable assumptions where helpful. There is no single "right" approach. A simple, explanable model is sufficient. Beyond that, well-reasoned theories on features that would improve the model - but require more time/resources than can be dedicated to this exercise - will be a useful part of the presentation

Dataset: 
Download the Amazon Products Dataset 2023 from Kaggle: https://www.kaggle.com/datasets/asaniczka/amazon-products-dataset-2023-1-4m-products?resource=download

# Requirements
Part 1: Model Development
Build a system that takes an ASIN as input and returns the N-closest competitors. Your approach should address:

Define "competitor" - Clearly articulate your definition of what makes products competitive to each other
Feature engineering - Create meaningful features from the available data to capture product similarity
Model selection - Choose and implement an appropriate similarity/distance metric or machine learning approach
Validation - Demonstrate that your model produces reasonable results
Scalability - Discuss how your solution would perform with larger datasets

# Part 2: Executive Summary
Prepare a concise presentation - 4 simple slides or less - for the VP of Data and Analytics that includes:

Methodology overview - High-level explanation of your approach (non-technical)
Example outputs, insights and visuals - Show competitor recommendations for 2-5 diverse products with interesting insights
Potential feature improvements - Features that you theorize would be effective, but required too much time/resources to include in this effort
