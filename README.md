# nlp_sentiment_ticker_mentions
Using Spark NLP and SpaCy NLP to extract the stock tickers from comments, to find mentions for each stock and train and utlise sentiment model to classify comments as positive, negative or neutral sentiment. Used 100,000 comments as a dataset downloaded from 12th Jan 2021 - 12th Dec 2020.

Spark NLP pipeline built to preprocess the comments:
DocumentAssembler -> Tokenizer -> Normaliser -> ViveknSentimentModel -> Finisher -> Outputs Final Sentiment column

Overview of the notebook: Screenshots
<img width="748" alt="Screenshot 2022-01-15 at 10 47 28" src="https://user-images.githubusercontent.com/42198709/149615968-cd71da5f-47ee-47c5-9473-0d013b82e8b7.png">

<img width="405" alt="Screenshot 2022-01-15 at 10 48 17" src="https://user-images.githubusercontent.com/42198709/149615974-154ba89b-2b95-4ad0-bc8e-ac10204922c6.png">

<img width="750" alt="Screenshot 2022-01-15 at 10 48 23" src="https://user-images.githubusercontent.com/42198709/149615975-545c21e1-d337-4b05-95b0-8a57a1a9bbfb.png">
