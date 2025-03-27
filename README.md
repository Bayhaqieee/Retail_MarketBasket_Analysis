# Retail Market Basket Analysis

Welcome to  **Retail Market Basket Analysis** ! This project focuses on analyzing retail transaction data to discover product combinations frequently bought together. By applying association rule mining techniques, we can uncover valuable insights into customer purchasing behavior.

## Project Status

🚧  **Status** : `Completed!`

## Features

Here's an overview of the analysis and methods used in this project:

* **Data Preprocessing and Cleaning**
  * **Functionality:** Load and preprocess transactional retail data for association rule mining.
  * **Techniques:** Data transformation into a transaction format for market basket analysis.
* **Product Combination Analysis**
  * **Functionality:** Analyze frequent itemsets and product combinations.
  * **Techniques:** Support, confidence, and lift calculations to determine significant associations.
* **Apriori Algorithm Implementation**
  * **Functionality:** Apply the Apriori algorithm to identify frequent itemsets.
  * **Techniques:** Subset analysis, rule generation, and interpretation.
* **Data Visualization**
  * **Functionality:** Visualize association rules and frequent itemsets.
  * **Visualization:** Item frequency plots, association rule graphs, and scatter plots.

## Technologies

This project is built using R and leverages the following libraries:

* **arules** : A package for mining association rules and frequent itemsets.
* **arulesViz** : A visualization package for association rule mining.
* **ggplot2** : A powerful data visualization library for plotting insights.

## Setup

To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Bayhaqieee/Retail_Market_Basket_Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd retail_market_basket_analysis
   ```
3. Open RStudio and install required dependencies:
   ```r
   install.packages(c("arules", "arulesViz", "ggplot2"))
   ```
4. Run the analysis script:
   ```r
   source("market_basket_analysis.R")
   ```
5. Alternatively, you can run specific sections of the script by selecting and executing blocks of code.

## Live Visualization

For a more interactive experience, you can visualize the association rules and frequent itemsets using network graphs and item frequency plots.

---

This project provides key insights into retail transaction patterns using Market Basket Analysis in R. Feel free to contribute or modify the analysis to enhance its capabilities!

📌 **Author:** Bayhaqie
📌 **Repository:** [GitHub](https://github.com/Bayhaqieee/Retail_Market_Basket_Analysis)
