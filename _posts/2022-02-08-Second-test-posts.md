---
layout: post
title:  "Unsupervised clustering analysis with R"
categories: R Statistics Retail_Data 
---
This analytical report aims to segment clients' data by their annual income. Once clusterd, we can compare the relation between each cluster and each variable in order to conduct a precise customer analysis. <br>

Variables of dataset: <br>
*  Income: annual household income of the client<br>
*  Amount for each product category over the last 2 years<br>
*  Number of purchases made for each channel and with discount<br>


Statistical methods applied in this report: <br>
* Principal component analysis <br>
* K-means <br>
* Test anova<br>
* Test K²<br>

1. Data exploration - Descriptive statistics analysis :<br>
<br>
2 Extracts of graphics: <br>
- Boxplot of annual household income of the client<br>
<img alt="boxplot of annual household income of the client" src="https://raw.githubusercontent.com/Pai-U/pai-u.github.io/main/assets/boxplot_income_.jpg" width="500"/><br>

- histograms of amount for each product category<br>
<img src="https://raw.githubusercontent.com/Pai-U/pai-u.github.io/main/assets/His.jpg" width="500"/><br>

2. Matrix of correlation :<br>
<img src="https://raw.githubusercontent.com/Pai-U/pai-u.github.io/main/assets/corelationmatrix.jpg" width="500"/><br>
3. Principal component analysis :<br>
Variables of PCA<br>
<img src="https://raw.githubusercontent.com/Pai-U/pai-u.github.io/main/assets/variable_pca.jpg" width="500"/><br>
PCA Biplot<br>
<img src="https://raw.githubusercontent.com/Pai-U/pai-u.github.io/main/assets/PCA_biplot.jpg" width="500"/><br>
4. 