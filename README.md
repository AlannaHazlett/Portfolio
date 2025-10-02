# Alanna Hazlett

## About Me:
I hold a Master's degree in Data Science and a Bachelor's degree in Biology, and I am currently working in Neuroscience research. With my combined background in data science and biology, I strive to drive impactful research and contribute to advancements in healthcare and biotechnology. Data science is transforming the way we analyze complex biological systems, and I apply my expertise to extract meaningful insights that lead to real-world solutions. By leveraging data, I aim to make informed, evidence-based contributions that improve societal health outcomes.

## [Project 1: Real Estate - House Prices, Renovation](https://github.com/AlannaHazlett/STAT6021/tree/main/Project%202)
* Linear regression for logarithmic transformation of price with feature selection
        * Can the price of a house to be listed for sale be predicted? What factors influence the price of a house? 
        * Utilizing R and tidyverse a linear regression model was created to best represent the data to make future predictions given house features.
        * In order to best determine a proper fitting model, exploratory data analysis was conducted, feature selection was conducted, and regression assumptions were checked to ensure they had been met.
        * A linear model with a low MSE of 0.0965 was achieved, creating a good predictor model for the price a house should be listed on the market for.
  
<img src="/Images/Log(Price)Dist.png" width="300">
        * Most houses have a log(price) of 13, equating to about $440,000. The training data ranges from log(price) = 11, which is about $60,000 to log(price) = 15.5, which is about $5,400,000.
        
* Logistic regression to determine if the house has been renovated
        * Is it possible to predict if a house has been renovated?
        * Utilizing R and tidyverse a logistic regression model was created to best represent the data to make future predictions given house features.
        * In order to best determine a proper fitting model, exploratory data analysis was conducted and feature selection was conducted.
        * Model performance was evaluated with ROC Curve and Confusion Matrix. The model acheived an AUC of 0.8708 showing a good performance of discriminating between non-renovated and renovated houses. 

<img src="/Images/Age_Renovated.png" width="300">
        * Non-renovated houses (coded as 0) show a wider interquartile range, suggesting a broad distribution of construction years. The median year built appears to be around 1975, indicating that a large proportion of non-renovated houses were built around this time.
        * Renovated houses (coded as 1) tend to have a slightly lower median year built, which suggests that renovations are more common in houses that were built earlier. The IQR for renovated houses is narrower, implying less variability in the construction year among renovated houses compared to non-renovated ones.
      


  
## [Project 2: Haiti Earthquake Disaster - Image Classification of Blue Tarps](https://github.com/AlannaHazlett/DS6030/blob/main/Project/Project2_Group4.Rmd)
* Tidymodels with model tuning and cross-validation for imbalanced data set


![](/Images/orthovnir071_makeshift_villiage1.jpg)
![](/Images/ClassDistributions.png)
![](/Images/ROCCurve2.png)


## Project 3: Chest Disease Classification with Explainability
* Transfer Learning of CNN models with Grad-CAM explainability feature

## Project 4: Virtual Screening for Protein Docking
* Creation of user interface for protein docking for non-technical researchers and associates
* Scalable pipeline for protein docking of nearly 1 billion ligand files
