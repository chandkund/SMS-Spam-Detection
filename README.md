# SMS-Spam-Detection
## Project Overview

This project focuses on detecting spam messages from a dataset that contains text data labeled as either "spam" or "ham" (non-spam). The goal is to develop a classification model that can accurately differentiate between spam and non-spam messages. This is crucial for applications like email filtering, SMS spam detection, and improving overall user experience by reducing the influx of unwanted or malicious content.

### Dataset

The dataset used for this project consists of five columns:
1. **v1**: Indicates whether the message is "ham" (non-spam) or "spam".
2. **v2**: Contains the text message.
3. **Unnamed: 2**, **Unnamed: 3**, **Unnamed: 4**: These columns are empty or contain irrelevant data and will be ignored in the analysis.

Sample data:
```
0    ham    Go until jurong point, crazy.. Available only ...
1    ham    Ok lar... Joking wif u oni...
2    spam   Free entry in 2 a wkly comp to win FA Cup fina...
3    ham    U dun say so early hor... U c already then say...
4    ham    Nah I don't think he goes to usf, he lives aro...
```


# Spam Detection Project

## Overview
This project aims to build a machine learning model that detects whether a given message is spam or not. The dataset contains labeled messages as either "ham" (non-spam) or "spam". By leveraging natural language processing (NLP) techniques, this project strives to build a robust classifier that can automatically filter out spam messages.

## Dataset
The dataset consists of 5 columns:
- **v1**: Spam or Ham (Target)
- **v2**: Message text
- **Unnamed: 2**, **Unnamed: 3**, **Unnamed: 4**: Unused or irrelevant data.
  
Sample messages:
- "ham": Go until jurong point, crazy.. Available only in bugis n great world...
- "spam": Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005...

## Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/chandkund/SMS-Spam-Detection.git
cd SMS-Spam-Detection
pip install -r requirements.txt
```

## Usage
1. Preprocess the data:
   - Remove irrelevant columns and missing values.
   - Tokenize and vectorize the text data using methods like TF-IDF.
2. Train the classifier:
   - Use machine learning algorithms such as Naive Bayes or Logistic Regression.
   - Evaluate the model's performance using metrics like accuracy and F1 score.
  

3. Predict spam messages:
```bash
python predict.py --message "Free entry to win cash prizes!"
```


## License
This project is licensed under the MIT License.
