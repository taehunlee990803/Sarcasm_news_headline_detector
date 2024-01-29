# Sarcasm News Headline Detector

## Project Overview
The 'Sarcasm News Headline Detector' is a machine learning model designed to detect sarcastic tones in news headlines. This project is built using Python, TensorFlow, and NLTK, and includes text feature extraction with TF-IDF and a classification model using neural networks.

## Installation
To install the necessary libraries for this project, run the following command:

pip install numpy pandas tensorflow nltk sklearn


## How to Use
To use this project, first run the Python script and upload the `Sarcasm_Headlines_Dataset.json` file. Then, you can train the model and predict sarcasm in new headlines.

To test a new headline, use the following function:
```python
headline = "Your Headline Here"
print(is_sarcastic(headline))
