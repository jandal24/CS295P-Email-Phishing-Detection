# CS295P Email-Phishing-Detection

# File Descriptions
Files are found in the **code** folder

- **PhishingTxt.ipynb:** This notebook trains and creates the model that is able to classify email text as phishing or not. Make sure to have the data **phishingtxt.csv** and update the path to where this file is placed. This model uses BERT classifier to speed up the learning in order to create the most accurate baseline model. There is a section to test out performance of the trained model.
 
- **Txt_prototype.ipynb:** This notebook is the prototype to show how to use the model created from **PhishingTxt.ipynb**. Make sure to have the created model path updated. You will be able to input any type of text to see if the text is a phishing message or not. 

- **PhishingURL.ipynb:** This notebook trains and creates the model that is able to classify URLs as phishing or not. Make sure to have the data **phishing_site_url.csv** and update the path to where this file is placed. This model uses Logistic Regression to detect common patterns in most phishing URLs. There is a section to test out performance of the trained model.
 
- **URL_prototype.ipynb:** This notebook is the prototype to show how to use the model created from **PhishingURL.ipynb**. Make sure to have the created model path updated. You will be able to input any type of URL to see if the URL is a phishing site or not. 

- **Data.zip:** Zip file containing the necessary data to train the models above. 


# Trained Models

This link includes our baseline trained models. 

https://drive.google.com/drive/folders/1U4ZKMbei1owrBHgZPSz0yDJogYAEkVZu?usp=sharing


# Data

**phishing_site_urls.csv:** In this file are a column of URLs and a column with each URLs classification as good or bad. 

**phishingtxt.csv:** In this file are a column of email messages and a column containing whether they are phishing (1) messages or not (0).


