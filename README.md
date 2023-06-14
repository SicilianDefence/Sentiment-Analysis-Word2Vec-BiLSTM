# Sentiment Analysis Word2Vec-BiLSTM

## Dataset
Twitter Dataset: https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

## Sentiment Analysis
Sentiment analysis, also known as opinion mining, is the process of determining the sentiment or emotional tone expressed in a piece of text, such as a sentence, paragraph, or document. It involves using natural language processing (NLP) techniques to classify the subjective information within the text as positive, negative, or neutral.

The goal of sentiment analysis is to understand the overall sentiment or attitude conveyed by the author or speaker. By analyzing the sentiment of text data, businesses and organizations can gain insights into public opinion, customer feedback, social media discussions, and other forms of textual data.

### Example
<strong>Let's say we have a review from twitter:</strong>

"Amazon UK launches Sherlock Holmes Advent Calendars - amzto / 3jH8yZN and amzto / 2Z4yNlf - last year's calendars sold out so early!"

In this case, sentiment analysis would analyze the text and determine the sentiment expressed by the tweet. The analysis would likely classify this review as neutral because the tweet just inform about Amazon UK launches Sherlock Holmes Advent Calendars and this calendars sold out.

The output of the sentiment analysis could be a sentiment score or a binary classification (positive, negative, or neutral). In this example, the sentiment analysis would classify the review as neutral.

## Word2Vec
Word2Vec is a popular algorithm used in natural language processing (NLP) to generate word embeddings. Word embeddings are dense vector representations of words that capture semantic and syntactic relationships between words based on their contextual usage.

The Word2Vec algorithm was introduced by Tomas Mikolov et al. at Google in 2013. It is a shallow, two-layer neural network model that is trained on a large corpus of text data to learn word embeddings. The main idea behind Word2Vec is that words with similar meanings tend to appear in similar contexts. Therefore, by learning from the co-occurrence patterns of words in a text corpus, Word2Vec can capture the semantic relationships between words.

![Word2Vec-CBOW-and-Skip-gram-There-are-two-different-methods-in-the-Word2Vec-algorithm](https://github.com/SicilianDefence/Sentiment-Analysis-Word2Vec-BiLSTM/assets/45375601/73249aec-cc0e-4e88-b745-87b692338960)

Image Source: https://www.researchgate.net/figure/Word2Vec-CBOW-and-Skip-gram-There-are-two-different-methods-in-the-Word2Vec-algorithm_fig2_320829283

## Bi-LSTM
Bi-LSTM, short for Bidirectional Long Short-Term Memory, is a type of recurrent neural network (RNN) architecture that incorporates information from both past and future contexts of a given sequence. It addresses the limitation of standard LSTM models, which only consider past information.

LSTM is a variant of RNN that is designed to handle long-term dependencies by utilizing memory cells and gating mechanisms. It has proven effective in various sequential data tasks, including natural language processing, speech recognition, and time series analysis.

Bi-LSTM extends the capabilities of LSTM by incorporating two separate LSTM layers: one processing the input sequence in the forward direction, and the other processing it in the reverse direction. This arrangement allows the model to capture information from both past and future contexts simultaneously.

<img width="689" alt="Screen_Shot_2020-05-25_at_8 54 27_PM" src="https://github.com/SicilianDefence/Sentiment-Analysis-Word2Vec-BiLSTM/assets/45375601/7edf2e98-bc29-4ccd-8e79-d534996c0909">

Image Source: https://paperswithcode.com/method/bilstm
