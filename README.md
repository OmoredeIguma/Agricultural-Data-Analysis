# Agricultural-Data-Analysis
Agricultural Data Analyst Portfolio Project
# Overview
This project explores a crop yield dataset provided on [Kaggle by Samuel Oti Attakorah](https://www.kaggle.com/datasets/samuelotiattakorah/agriculture-crop-yield). This dataset provides a comprehensive view aimed at predicting crop yield (in tonnes per hectare) based on several factors. Each entry in the dataset corresponds to a unique crop with its unique profile, such as the region where it was grown, the soil type, the amount of rainfall, etc, offering a detailed breakdown of how these factors could affect yield. The dataset originally consisted of 1 million rows, but was scaled down to 500 due to technical limitations such as lags and crashes. <br /> 

Visualisations can be found [Here](https://omoredeiguma.github.io/Website-Hosting-Agriculture/)

The transformed dataset and the raw SPSS output file are presented above along with the results and discussions in a Word document presented in APA 7th edition format which goes in-depth into the findings. Below this readme file is a quick summary of findings and recommendations based on the results obtained from the dataset.<br />

# Data Preparation
The variables Region, Soil Type, Crop, Fertiliser Used, Irrigation Used, and Weather, were recoded automatically using SPSS built-in automatic recode function. The decimals for the scale variables were reduced to 2 decimal places. No duplicates or missing values were found in the dataset.

# Objectives
**Objective 1:** Descriptive statistics for Region, Soil Type, Crop, Fertiliser used?, Irrigation Used?, Rainfall, Temperature, Days to Harvest, Yield per hectares and Weather Condition. This was achieved using frequency count, mean, and percentages. <br />

**Objective 2:** Effect of Fertiliser used on Yield per hectare. This was achieved using an independent samples t-test to compare the average yield between whether fertiliser was applied or not. <br />

**Objective 3:** Effect of irrigation used on Yield per hectare. This was achieved using an independent samples t-test to compare the average yield between whether irrigation was applied or not. <br />

**Objective 4:** Correlations. This was achieved using Pearson's correlation to examine the relationship between Rainfall, Temperature, Days to Harvest and Yield per hectare(tonnes). <br />

**Objective 5:** Factors influencing crop yield. This was achieved using multiple linear regression analysis to determine if rainfall, temperature, days to harvest, fertiliser used and soil type have an effect on overall yield. <br />

**Objective 6:** Analysis of Variance (ANOVA). This was conducted to examine if total yield differs from one region to the other. <br />

# Tools I Used
* IBM SPSS 27
* Microsoft Word <br />
* Tableau

# Insights
**Objective 1:** From the descriptive statistics, Of the 500 samples, The regional distribution of the data showed that the largest proportion of samples came from the North (32%), followed by the West (24.4%).Regarding soil type, silt was the most common (18%), closely followed by clay (17.8%) <br />
Crop distribution was relatively even, with cotton being the most frequently cultivated (17.8%), and soybeans the least (15%). <br /> Approximately half of the fields used fertiliser (49.2%), while the other half did not (50.8%). Similarly, irrigation was reported in just over half the cases (51.4%), with 48.6% not using irrigation. Sunny Weather conditions was were most cultivations were carried out. <br /> The average rainfall across all observations was 542.70 mm, Mean temperature was 27.68°C, average time to harvest was 105.32 days, The average yield was 4.65 tons per hectare. <br />
Rice had the highest yield at 422.78 tonnes <br />

**Objective 2:** There was a statistically significant difference in yield for fertiliser used (_M_ = 5.35, _SD_ = 1.51) and fertiliser not used (_M_ = 3.97, _SD_ = 1.64), _t_(498) = 9.78, _p_ = <.001 <br />

**Objective 3:** There was a statistically significant difference in yield for irrigation used (_M_ = 5.32, _SD_ = 1.54) and irrigation not used (_M_ = 3.94, _SD_ = 1.62), _t_(498) = 9.82, _p_ = <.001. <br />

**Objective 4:** Rainfall and yield per hectare were strongly positively correlated (r =.77, _p_ < .001), indicating that greater rainfall is associated with higher yield. Other variables were not significant and had a low or very low effect size. <br />

**Objective 5:** Rainfall and temperature had a significant effect on overal yield, which impliles that an increase in these variables would lead to an increase in crop yield. Fertiliser used was also significant, indicating that if fertiliser was used, it would lead to an increase in crop yield. <br />

**Objective 6:** The result from the ANOVA was not statistically significant, indicating that there was no difference in yield obtained from the four regions (North, South, East, West). The effect size was very small, indicating low practicality.
