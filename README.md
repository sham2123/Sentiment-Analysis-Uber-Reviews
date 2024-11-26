# Sentiment Analysis on Uber Reviews

This project implements sentiment analysis on Uber reviews from Yelp using the BERT framework (`nlptown/bert-base-multilingual-uncased-sentiment`). This is a fine-tuned version of BERT specifically designed for multilingual sentiment analysis, trained on Yelp and Trustpilot datasets. It excels at multilingual capabilities, making it an ideal model for analyzing user reviews across various languages. The reviews are scraped directly from Yelp's website and analyzed using a fine-tuned BERT model to assign sentiment scores ranging from 1 (negative) to 5 (positive).

The website used to scrape data: [Yelp Uber Reviews](https://www.yelp.com/brands/uber)

For more information, refer to this link: [BERT Sentiment Model](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment)

## Features:

### Data Collection:
- Reviews are scraped from Yelp using BeautifulSoup and cleaned to ensure quality.

### Sentiment Analysis:
- A pre-trained BERT model (`nlptown/bert-base-multilingual-uncased-sentiment`) is used for sentiment classification.
- Each review is tokenized and passed through the model, producing a sentiment score.

### Data Visualization:
- Sentiment score distributions are visualized using matplotlib and seaborn.
