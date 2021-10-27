# SMS-Spam-Detection

## About

In recent years, we have all started to receive multiple spam messages every single day, whether they come through as phone calls, emails, or texts. The cost to send a text or make a phone call has decreased drastically in the past decade and it is now free in most cases to send a text, email, or make a phone call within the United States. Unfortunately, this has enabled spammers to send millions of spam messages or make millions of spam calls every single day.

Spam filtering using machine learning has become common among email providers. However, spam filtering of SMS text messages has not been widely implemented. A big reason for SMS to be lagging behind email in terms of spam filtering is the lack of a large, quality SMS text dataset. This dataset from UCI (see below) combines multiple different datasets together to provide an industry-leading SMS spam vs ham dataset. 

One of the most important aspects of spam filtering is preventing legitimate messages from being blocked (false positive). Even a single legitimate call or message getting blocked may be seen as unacceptable. As a result, we will need to focus on preventing false positives while trying to flag as many spam messages as possible.

This project is intended to demonstrate proficiency with working with text data, NLP techniques, and creating highly tuned models. 

## Dataset

This project was inspired by the SMS Spam Collection dataset from the UC Irvine Machine Learning Repository. The dataset claims to be the largest collection of real, unencoded SMS messages available. The dataset and a more in depth description can be accessed here:
https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

The original paper published with the dataset discusses the creation of the dataset, some of the characteristics of the dataset, and some of the benchmark models that were created for predicting whether an SMS message is spam or ham. The paper can be accessed here:
https://dl.acm.org/doi/pdf/10.1145/2034691.2034742

## Running the project

To run the project, clone the repo into your workspace:
```
git clone https://github.com/bengruher/SMS-Spam-Detection
```

and open the sms-spam-detection.ipynb Jupyter notebook. Press Shift-Enter to run each cell. Note that your execution times may vary. The notebook was originally run on an ml.t2.medium EC2 instance from AWS. 


Tags: NLP, spam detection, unstructured data