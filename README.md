# crypto-sentiment-Week-12
Imports:
1. os
2. pandas
3. dotenv
4. nltk
5. newsapi.newsapi_client
6. hvplot
7. wordcloud
8. matplotlib
9. spacy

## Sentiment Analysis
- Get sentiment scores for each article's title and description for BTC and ETH using polarity scores. Then compare the scores with one another using pandas describe method.
- Tokenize title and descriptions for each article (splitting, attaining root-words, and lower-casing)

## Frequency Analysis
- Attain ngrams of 2 for title and descriptions, using Counter function to display high frequency combinations
- Find Top 10 words based on frequency
- Create word clouds

## NER
- Join together descriptions and titles
- Create an NER
- Find entities referenced for descriptions and titles
