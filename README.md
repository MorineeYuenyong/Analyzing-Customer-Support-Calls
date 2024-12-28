# Analyzing-Customer-Support-Calls
Prepare to embark on a journey to elevate customer service by analyzing support calls.
Taskof this project is to transcribe customer support audio calls, evaluate customers' sentiment, and uncover common named entities and search most similar context to a query by utilizing open-source packages such as SpeachRecognition and spaCy.
## Acknowledgements
This project was originally created as part of a course on [DataCamp](https://www.datacamp.com). The original content and structure were provided by DataCamp.
## Project Overview
This project aims to revolutionize customer service by leveraging cutting-edge speech recognition and natural language processing (NLP) technologies. By transcribing audio calls, analyzing customer sentiment, extracting key named entities, and identifying similar text queries, we aim to provide actionable insights that can enhance customer experience and optimize support services.
Key functionalities include:
- Transcription: Converting audio customer support calls to text.
- Sentiment Analysis: Classifying customer sentiments as positive, negative, or neutral.
- Named Entity Recognition (NER): Extracting and analyzing common named entities in customer conversations.
- Similarity Search: Finding customer complaints most similar to a specific query, such as "wrong package delivery."
## Tools and Libraries 
The project utilizes a range of open-source tools and libraries, including:
-  SpeechRecognition : For transcribing audio calls into text.
-  Pydub *: For audio file manipulation and metadata extraction.
-  spaCy *: For natural language processing tasks, including Named Entity Recognition (NER) and text similarity.
-  NLTK (VADER Sentiment Analyzer) : For performing sentiment analysis on transcribed customer texts.
-  Pandas : For handling and analyzing structured data in CSV format.
-  Sample customer call Data: sample_customer_call.wav
##  Key Tasks 
1.  Speech to Text Conversion :
   - Transcribe a sample customer audio call (`sample_customer_call.wav`) into text using the SpeechRecognition library.
   - Extract and display metadata such as channels and frame rate using Pydub.

2.  Sentiment Analysis :
   - Analyze customer sentiment using NLTK's VADER sentiment analyzer.
   - Add a column to the dataset (`customer_call_transcriptions.csv`) indicating predicted sentiment.
   - Calculate true positive matches for sentiment predictions compared to labeled data.

3.   Named Entity Recognition (NER) :
   - Extract named entities from customer transcriptions using spaCy.
   - Aggregate and count named entities to identify the most frequently mentioned terms.

4.  Text Similarity Search :
   - Find the most similar customer complaints to a specific query (e.g., "wrong package delivery") by calculating similarity scores using spaCy.
   - Return the top-matching text for actionable insights.
