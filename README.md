# Chatbot-using-NLP
An AI chatbot is a piece of software that interacts with a human through written language. It is often embedded in web pages or other digital applications to answer customer inquiries without the need for human agents, thus providing affordable effortless customer service. Chatbots are frequently used in a wide variety of online situations, from customer service to sales.

The concepts used in the ChatBot are explained below:

## 1.	Natural Language Processing:
NLP is the study of letting computers understand human languages. Without NLP, human language sentences are just a series of meaningless symbols to computers. Computers don’t recognize the words and don’t understand the grammars. NLP can be regard as a “translator”, who will translate human languages to computer understandable information. Traditionally, users need to follow well-defined procedures accurately, in order to interact with computers. For example, in Linux systems, all commands must be precise. A single replace of a | (pipe) character or even a space can have significant difference. However, the emergence of NLP is changing the way of interacting. Apple Siri and Microsoft Cortana have made it possible to give command in everyday languages and is changing the way of interacting. 
NLP is a subfield of artificial intelligence and is concerned with interactions between computers and human languages. NLP is the process of analyzing, understanding, and deriving meaning from human languages for computers.
NLP helps you extract insights from unstructured text and has several use cases, such as:
•	Automatic summarization
•	Named entity recognition
•	Question answering systems
•	Sentiment analysis

## 2.	Natural Language Processing With spaCy in Python:
spaCy is a free and open-source library for Natural Language Processing (NLP) in Python with a lot of in-built capabilities. It’s written in Cython and is designed to build information extraction or natural language understanding systems. It’s built for production use and provides a concise and user-friendly API.
It’s becoming increasingly popular for processing and analyzing data in NLP. Unstructured textual data is produced at a large scale, and it’s important to process and derive insights from unstructured data. To do that, you need to represent the data in a format that can be understood by computers. NLP can help you do that.
spaCy is a powerful and advanced library that is gaining huge popularity for NLP applications due to its speed, ease of use, accuracy, and extensibility.

## 3.	Sentence Detection:
Sentence Detection is the process of locating the start and end of sentences in a given text. This allows you to you divide a text into linguistically meaningful units. You’ll use these units when you’re processing your text to perform tasks such as part of speech tagging and entity extraction.
In spaCy, the sents property is used to extract sentences. You can also customize the sentence detection to detect sentences on custom delimiters.

## 4.	Tokenization in spaCy:
Tokenization is the next step after sentence detection. It allows you to identify the basic units in your text. These basic units are called tokens. Tokenization is useful because it breaks a text into meaningful units. These units are used for further analysis, like part of speech tagging.
In spaCy, you can print tokens by iterating on the Doc object. spaCy preserves the starting index of the tokens. It’s useful for in-place word replacement. spaCy provides various attributes for the 

## 5.	Stop Words:
Stop words are the most common words in a language. In the English language, some examples of stop words are the, are, but, and they. Most sentences need to contain stop words in order to be full sentences that make sense.
Generally, stop words are removed because they aren’t significant and distort the word frequency analysis. spaCy has a list of stop words for the English language.

## 6.	Lemmatization:
Lemmatization is the process of reducing inflected forms of a word while still ensuring that the reduced form belongs to the language. This reduced form or root word is called a lemma.
For example, organizes, organized and organizing are all forms of organize. Here, organize is the lemma. The inflection of a word allows you to express different grammatical categories like tense (organized vs organize), number (trains vs train), and so on. Lemmatization is necessary because it helps you reduce the inflected forms of a word so that they can be analyzed as a single item. It can also help you normalize the text. spaCy has the attribute lemma_ on the Token class. This attribute has the lemmatized form of a token.

## 7.	Word Frequency:
You can now convert a given text into tokens and perform statistical analysis over it. This analysis can give you various insights about word patterns, such as common words or unique words in the text.

## 8.	Part of Speech Tagging:
Part of speech or POS is a grammatical role that explains how a particular word is used in a sentence. There are eight parts of speech:
1.	Noun
2.	Pronoun
3.	Adjective
4.	Verb
5.	Adverb
6.	Preposition
7.	Conjunction
8.	Interjection
Part of speech tagging is the process of assigning a POS tag to each token depending on its usage in the sentence. POS tags are useful for assigning a syntactic category like noun or verb to each word. In spaCy, POS tags are available as an attribute on the Token objec.

## 9.	Visualization: Using displaCy:
spaCy comes with a built-in visualizer called displaCy. You can use it to visualize a dependency parse or named entities in a browser or a Jupyter notebook. You can use displaCy to find POS tags for tokens.
 
## 10.	Preprocessing Functions:
You can create a preprocessing function that takes text as input and applies the following operations:
•	Lowercases the text
•	Lemmatizes each token
•	Removes punctuation symbols
•	Removes stop words
A preprocessing function converts text to an analyzable format. It’s necessary for most NLP tasks.

## 11.	Named Entity Recognition:
Named Entity Recognition (NER) is the process of locating named entities in unstructured text and then classifying them into pre-defined categories, such as person names, organizations, locations, monetary values, percentages, time expressions, and so on.
You can use NER to know more about the meaning of your text. For example, you could use it to populate tags for a set of documents in order to improve the keyword search. You could also use it to categorize customer support tickets into relevant categories.
spaCy has the property ents on Doc objects. You can use it to extract named entities. 

## 12.	Machine Learning:
Machine Learning (ML) is an area of computer science that "gives computers the ability to learn without being explicitly programmed". The parameter of the formulas is calculated from the data, rather than defined by the programmer. Two most common usage of ML is Classification and Regression. As shown in Figure 2, Classification means to categorize different types of data, while Regression means to find a way to describe the data. 
Basic ML program will have two stages, fitting and predicting. In the fitting stage, the program will be given a large set (at least thousands) of data. The program will try to adjust its parameter based on some statistical models, in order to make it “fit” the input data best. In the predicting stage, the program will give a prediction for a new input based on the parameters it just calculated out. For example, the famous Iris flower dataset contains the measurement of several features of three different species of flowers, such as the length of sepals and petals. A well-defined ML program can learn the pattern behind this feature and give prediction accordingly. 
 
## 13.	Sentiment Analysis:
Sentiment analysis is the process of classifying whether a block of text is positive, negative, or, neutral. Sentiment analysis is contextual mining of words which indicates the social sentiment of a brand and also helps the business to determine whether the product which they are manufacturing is going to make a demand in the market or not. The goal which Sentiment analysis tries to gain is to analyze people’s opinion in a way that it can help the businesses expand. It focuses not only on polarity (positive, negative & neutral) but also on emotions (happy, sad, angry, etc.). It uses various Natural Language Processing algorithms such as Rule-based, Automatic, and Hybrid.

## 14.	Deep Learning:
Deep learning is based on the branch of machine learning, which is a subset of artificial intelligence. Since neural networks imitate the human brain and so deep learning will do. In deep learning, nothing is programmed explicitly. Basically, it is a machine learning class that makes use of numerous nonlinear processing units so as to perform feature extraction as well as transformation. The output from each preceding layer is taken as input by each one of the successive layers.

## 15.	Neural Network:
In information technology (IT), an artificial neural network (ANN) is a system of hardware and/or software patterned after the operation of neurons in the human brain. ANNs -- also called, simply, neural networks -- are a variety of deep learning technology, which also falls under the umbrella of artificial intelligence, or AI.
Commercial applications of these technologies generally focus on solving complex signal processing or pattern recognition problems. Examples of significant commercial applications since 2000 include handwriting recognition for check processing, speech-to-text transcription, oil-exploration data analysis, weather prediction and facial recognition.

## 16.	How neural networks learn:
Typically, an ANN is initially trained or fed large amounts of data. Training consists of providing input and telling the network what the output should be. For example, to build a network that identifies the faces of actors, the initial training might be a series of pictures, including actors, non-actors, masks, statuary and animal faces. Each input is accompanied by the matching identification, such as actors' names or "not actor" or "not human" information. Providing the answers allows the model to adjust its internal weightings to learn how to do its job better.
For example, if nodes David, Dianne and Dakota tell node Ernie the current input image is a picture of Brad Pitt, but node Durango says it is Betty White, and the training program confirms it is Pitt, Ernie will decrease the weight it assigns to Durango's input and increase the weight it gives to that of David, Dianne and Dakota.
In defining the rules and making determinations -- that is, the decision of each node on what to send to the next tier based on inputs from the previous tier -- neural networks use several principles. These include gradient-based training, fuzzy logic, genetic algorithms and Bayesian methods. They may be given some basic rules about object relationships in the data being modeled.

## 17.	Keras:
Keras is an open source deep learning framework for python. It has been developed by an artificial intelligence researcher at Google named Francois Chollet. Leading organizations like Google, Square, Netflix, Huawei and Uber are currently using Keras. 
Keras is based on minimal structure that provides a clean and easy way to create deep learning models based on TensorFlow or Theano. Keras is designed to quickly define deep learning models. Well, Keras is an optimal choice for deep learning applications.
