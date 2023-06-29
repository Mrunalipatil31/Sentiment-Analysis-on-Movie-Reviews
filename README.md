**Sentiment-Analysis-on-Movie-Review-dataset**

**Overview:**

The project domains background around the area of Sentiment analysis. Sentiment analysis or Opinion mining is a significant task in the field of Natural Language Processing also in machine learning and Data science. It is used to understand the sentiment in social media, in political analysis and in survey responses. In general the main aim of this is to determine the attitude of speaker with positive, neutral and negative polarity.

**Problem Statement:**

The project that the proposal infers to is called “Movie Review Sentiment Analysis”. The main goal is to classify the sentiment of reviews from the Rotten Tomatoes dataset. The Rotten Tomatoes movie review dataset is a corpus of movie reviews used for sentiment analysis. The main task is to label phrases on a scale of five values: negative, somewhat negative, neutral, somewhat positive, positive. There are many obstacles such as sentence negation, sarcasm, language ambiguity, and many others make the sentiment prediction more difficult. In general, this particular Sentiment Analysis is a multiclass classification task to be faced.

**Data exploration:**

The dataset contains tab-separated files with phrases from the Rotten Tomatoes dataset. The train/test split has been preserved to benchmark, but the sentences have been shuffled from their original order. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

The Train Set has 4 columns and 156060 rows of data. Its features are the following:
PhraseId, is a unique Phrase identifier per phrase. Multiple phrases originate from the same sentence and its data type is “numeric”. We have 156060 unique PhraseIds in the entire train set.
SentenceId, is a unique sentence. In the trainset we have 8543 unique Sentences in the train dataset.
Phrase, it is type of “string” and it stems from the Sentence that is referenced by SentenceId. In total they are 156060 unique Phrases and each phrase is the result from a unique split to the Sentence that belongs to.
Sentiment, it is the Sentiment Labels and the target feature that must be predicted in the Test Set. Its labels are the following: 0 – negative, 1 - somewhat negative, 2 – neutral, 3 - somewhat positive, 4 – positive.
The Test Set has 3 columns and they are the following:
PhraseId, is a unique Phrase identifier per phrase. Multiple phrases originate from the same sentence and its datatype is “numeric”. We have 66292 unique PhraseIds in the test set.
SentenceId, is a unique Sentence. In the trainset we have 3310 unique Sentences/reviews in the test set.
Phrase, it is type of “string” and it stems from the Sentence that is referenced by SentenceId. In total they are 156060 unique Phrases in the test set and each phrase is the result from a unique split to the Sentence that belongs to.
**Independent variables:**

• PhraseId • Sentence Id • Phrase

**Dependent variables:**

• Sentiment

**The workflow will show the complete building of model:**

> Importing libraries
> Exploratory Data Analysis
> Cleaning text data using NLP techniques
> Using wordcloud to indicate size of each word and its importance.
> Evaluate algorithms.

**Algorithms and Techniques:**

The machine learning techniques that are used are:
Logistic Regression,Multinomial Naive Bayes,Decision Tree Classifier,K-Neighbors Classifier.

Comparatively,Naive Bayes algorithm gives more accuracy on both train and test datasets.
