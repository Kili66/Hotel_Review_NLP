# Hotel Review with Sentiment Analysis:

This project focuses on analyzing hotel reviews using sentiment analysis techniques. The aim is to build a system that can automatically classify hotel reviews as positive, negative, or neutral based on the sentiments expressed in the text.
# Steps Used
* Data Collection from github 
* Data Cleaning: We check the missing values and then we correct them by replacing them with another similar values
* Remove some unuseful columns from the dataset
* Data Visualization: Hotel Count, Review Per Hotel, Locations Visualization on the Map with Folium python library...
* Create Sentiment Anlaysis columns: we create positive and negative according to the reviews Rates
* Text Analysis: We analysis the Reviews contents(text)
* Text Preprocessing: Remove Stop Words, apply lemmatization
* Plot the most frequents words using NLTK (Natural Language Toolkit): Library for natural language processing tasks such as text tokenization, lemmatization, and stop word removal.
* Split the data
* Use TfidfVectorizer for feature extraction 
* Train the model using Random Forest Classifier
* Accuracy: 0.83
