# Financial News Sentiment Analysis

## Live Demo: [Financial News Sentiment Analysis](https://160121.github.io/Sentiment-Analysis/)

## Description

This repository contains the code for a financial news sentiment analysis project, designed to classify financial news articles as positive, negative, or neutral. Using machine learning and NLP techniques, the project aims to help users quickly assess the sentiment behind financial news, potentially aiding in investment and financial decisions.

## Features

- **Sentiment Classification**: Analyze financial news articles to categorize their sentiment as positive, negative, or neutral.
- **Data Visualization**: Visualize sentiment distribution for easier interpretation of news trends.
- **Pre-trained Models**: The project provides a trained sentiment analysis model ready to classify financial news articles.
- **Customizable**: Modify the model or add new datasets to extend functionality.
- **Interactive Notebook**: Includes Jupyter notebooks to demonstrate data exploration, model training, and evaluation.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/160121/Sentiment-Analysis.git
2. Install dependencies using:

   ```bash
   pip install -r requirements.txt

3. Download or provide a dataset of financial news articles for analysis. Place the dataset in the data directory and ensure it has columns like headline, content, and sentiment.

4. Open the notebooks/EDA.ipynb notebook to explore the data and train the model.

## Usage

1. Training: Run the training script to build the sentiment analysis model:

   ```bash
   python models/model_training.py

2. Evaluation: Evaluate the model’s performance using the test dataset:

   ```bash
   python models/evaluation.py
   
3. Sentiment Analysis: Use the sentiment_analysis.py script to classify the sentiment of new financial news articles.

   ```bash
   from src.sentiment_analysis import analyze_sentiment
   
   print(analyze_sentiment("Sample financial news content"))
   
## Contributing

Contributions to this project are welcome! Feel free to fork the repository, make improvements, and create a pull request. Contributions may include adding new models, improving visualization, or enhancing the dataset.

## Acknowledgments
>Special thanks to the financial news dataset providers for the data used in this analysis.

>Thanks to the open-source community for providing powerful NLP libraries and machine learning resources that made this project possible.
