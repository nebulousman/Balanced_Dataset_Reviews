# Balanced Dataset of Reviews

Created as part of a CrowdDoing project to classify Amazon reviews of medicinal products. The original dataset contained a majority positive reviews. This is consistent with reviews in general that are typically 70%+ positive. The objective is to balance the data for purpose of modeling. The approach groups by star rating into 2 groups (4-5star & 1-3star) then select the minority class entirely with a random sample of the majority class in the same number. In other words stratified under sampling. There are other possible approaches, however with a minority class of 260K samples the resulting dataset would have over 500K samples which is sufficient for training.

The output file for this code is located at:
Medicinal Foods/DataScience/Data Science Orientation/20200710-Scrapy_Data/Analysis/CrowdDoingAmazonReviews.csv
