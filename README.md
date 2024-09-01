# Fake-News-Identifier
This project aims to develop a machine-learning model which is capable of identifying and classifying any news article as fake or no. I have used four techniques to determine the results of the model.
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Gradient Boost Classifier**
4. **Random Forest Classifier**

## Project Overview

Fake news has become a significant issue in today's digital age, where information spreads rapidly through various online platforms. This project leverages machine learning algorithms to automatically determine the authenticity of news articles, providing a valuable tool to combat misinformation.

## Dataset

I have used a labelled dataset containing news articles along with their corresponding labels (true or false). The dataset is divided into two classes:
- True: Genuine news articles
- False: Fake or fabricated news articles

## Dependencies

Before running the code, make sure you have the following libraries and packages installed:

- Python 3
- Scikit-learn
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Regular Expression

You can install these dependencies using pip:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install sklearn
pip install seaborn 
pip install re 
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone [https://github.com/Pratheek1603/Fake-News-Identifier.git]
```

2. Navigate to the project directory:

```bash
cd fake-news-detection
```

3. Execute the Jupyter Notebook or Python scripts associated with each classifier to train and test the models. For example:

```bash
python random_forest_classifier.py
```

4. The code will produce evaluation metrics and provide a prediction for whether the given news is true or false based on the trained model.

