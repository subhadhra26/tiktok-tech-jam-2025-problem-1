# [Filtering the Noise: ML for Trustworthy Location Reviews]

### Project Overview

This ML project is an automated tool that classifies location-based reviews related to Food and Beverages into 
4 categories namely, "Advertisement","Spam","Valid Review" and "Not Related to F&B". This solution addresses the challenge of assessing review quality by streamlining the analysis of large datasets. 
It provides business owners with clear, actionable insights by filtering out irrelevant reviews and highlighting valuable feedback.


**Key Features:**
* **Classification:** It automatically classifies reviews into specific categories like "Valid Review," "Spam," "Advertisement," or "Not Related to F&B." This provides immediate insight into the nature of the feedback, helping businesses quickly sort through and prioritize reviews.
* **Relevancy Scoring:** For reviews identified as valid, the system calculates a numerical relevancy score. This score quantifies how much a review's content aligns with the business's categories and attributes, helping businesses pinpoint feedback on key aspects of their service.
* **Spam Filtering:** Flags a review if the same reviewer has repeatedly reviewed the same business more than 5 times

### Setup Instructions

Follow these steps to get a local copy of the project up and running.

**1.Create a copy of this folder:**
https://drive.google.com/drive/folders/1tqrRAY0WtueQebLfQixyxI9WB9tf22Cc?usp=drive_link
and unzip the yelp_merged_dataset.json and yelp_business.json files

**2.Add these files into MyDrive of your google drive**

**3.Create a copy of this main file on google colab:** https://colab.research.google.com/drive/1Zh1aDhrA-Hd9rC5ZEaND9gBy0qwNB6Fj?usp=drive_link

**4.Run the code chunks to see the result**

### Setup Instructions
**Development tools used:** Colab, VScode

**APIs used:** Qwen

**Libraries and frameworks used:** Hugging Face Transformers, pandas, duckdb

**Assets and datasets used:** 
- Yelp businesses,reviews and users dataset from https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset
- Scraped Top 10 restaurant google reviews for California and Florida 
