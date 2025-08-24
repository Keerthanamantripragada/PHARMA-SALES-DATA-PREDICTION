 ## INTRODUCTION : 
The pharmaceutical industry faces constant challenges in predicting sales due to factors such as drug category, seasonal demand, and market dynamics. Without accurate forecasting, companies risk overstocking, stockouts, or inefficient marketing strategies, which can impact both business performance and patient care.

This project addresses the challenge of analyzing historical pharma sales data to identify key trends and build a predictive model that can forecast future sales accurately.

## About Dataset:
The dataset is built from the initial dataset consisted of 600000 transactional data collected in 6 years (period 2014-2019), indicating date and time of sale, pharmaceutical drug brand name and sold quantity, exported from Point-of-Sale system in the individual pharmacy. Selected group of drugs from the dataset (57 drugs) is classified to the following Anatomical Therapeutic Chemical (ATC) Classification System categories:

**M01AB** - Anti-inflammatory and antirheumatic products, non-steroids, Acetic acid derivatives and related substances 

**M01AE** - Anti-inflammatory and antirheumatic products, non-steroids, Propionic acid derivatives

**N02BA**- Other analgesics and antipyretics, Salicylic acid and derivatives

**N02BE/B**- Other analgesics and antipyretics, Pyrazolones and Anilides

**N05B** - Psycholeptics drugs, Anxiolytic drugs

**N05C** - Psycholeptics drugs, Hypnotics and sedatives drugs

**R03** - Drugs for obstructive airway diseases

**R06** - Antihistamines for systemic use

## PROJECT INSIGHTS:
We have analysed the data trends of the pharma industry of particular drugs on the data which is recorded for the 6 years.After analysing we have predicted the total sales of the drugs and in the prediction we have used DecisionTree for capturing the nonlinearity in the data and for improving the performance of the data we have used RandonForestRegressor which improved the performance of the prediction of the data. After analysing the data and finding out the feature importances of the data we have found out that prediction is majorily based on the **drugN02BE** which have highest sales in all the years major supporter for the increasing in the totalsales.
