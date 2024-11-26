This project implements sentiment analysis on Uber reviews from Yelp using the BERT framework (nlptown/bert-base-multilingual-uncased-sentiment). The reviews are scraped directly from Yelp's website and analyzed using a pre-trained BERT model to assign sentiment scores ranging from 1 (negative) to 5 (positive).

The website used to scrape data: https://www.yelp.com/brands/uber

Features:
    -Data Collection:
        -Reviews are scraped from Yelp using BeautifulSoup and cleaned to ensure quality.
    -Sentiment Analysis:
        -A pre-trained BERT model (nlptown/bert-base-multilingual-uncased-sentiment) is used for sentiment classification.
        -Each review is tokenized and passed through the model, producing a sentiment score.
    -Data Visualization:
        -Sentiment score distributions are visualized using matplotlib and seaborn.

Requirements: 
    -python3
    -BeautifulSoup4
    -PyTorch
    -numpy
    -pandas
    -requests
    -transformers
    -seaborn
    -matplotlib


Currently Underway:
    -AWS Integration
        -Deploy the sentiment analysis model on AWS for scalable and remote proecessing
    -Flask
        -Develop a web-based dashboard using Flask to display sentiment results and graphs

Notes on BERT

The project uses the nlptown/bert-base-multilingual-uncased-sentiment model. This is a fine-tuned version of BERT specifically designed for multilingual sentiment analysis, trained on Yelp and Trustpilot datasets. Its great at multilingual capabilities making it an ideal model for analyzing user reviews across various languages.

For more information, refer to this link: https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment