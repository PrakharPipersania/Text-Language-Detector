# [Text-Language-Detector](https://github.com/PrakharPipersania/Text-Language-Detector)
### Project Description
#### "Language Detection using NLP"
Language detection is a fascinating branch of Natural Language Processing. Its goal is to create a model that is able to detect the language a text is written in.
### The Problem
Language detection is a Text Classification Problem. The problem we are going to face is to create a model that, once fed with a text, is able to detect its language. The text can be a sentence, a word, a more complicated text, and so on. The output variable can be, for example, the language (like "English"). </br>
A good idea would be to have a model that detects the language of a text even if this text contains words that the model has not seen in the training phase. We want a model that can generalize the underlying structure of a language in a way that makes it detect it properly. </br>
Training this model to detect languages the model will be fed with a dataset of different languages. The datasets are in the form of sentences, and after the preprocessing, the dataset of sentences will be split into training and test sets.
### Platform
● Jupyter Notebook
### Technology Specific
#### Natural Language Processing
NLP is a field within artificial intelligence (AI) and Machine Learning that combines linguistics and computer science to break down language so that it can be analyzed by machines. Text can be an extremely rich source of information, but extracting insights from it can be hard and time-consuming due to its unstructured nature. Machine learning text classification can help businesses automatically structure and analyze their text, quickly and cost-effectively, to automate processes and enhance data-driven decisions.
#### Text Classification
It is the process of assigning tags or categories to text according to its content. It can be used to organize, structure, and categorize pretty much any kind of text – from documents, medical studies and files, and all over the web.
#### TF-IDF Vectorization
In our model, we will be using TF-IDF Vectorization because it creates vectors from the text which contains information on the more important words and the less important ones as well. TF-IDF is a statistical measure that evaluates how relevant a word is to a document in a collection of documents. This is done by multiplying two metrics: how many times a word appears in a document, and the inverse document frequency of the word across a set of documents. It has many uses, most importantly in automated text analysis, and is very useful for scoring words in machine learning algorithms for Natural Language Processing (NLP).
#### Vectorization using Characters & Words
Here the classification problem have n-valued class. And the target variable is Language. The features we are going to use are characters and words. We can use a set of 1-gram to 4-gram consecutive characters or words in a sentence. Consider, for example, the word "hello". In this case, the char 1-grams are 'h', 'e', 'l', 'l', ‘o’, char 2-grams are "he", "el", "ll", "lo” and so on.
### Market Demand of the Project
To sustain and stay at the top of the market and give absolute comfort to the consumers, business organizations are using different strategies and technologies. NLP is one such technology penetrating deeply and widely in the market, irrespective of the industry and domains. </br>
The global market for natural language processing is significantly driven by the massive jump in digital data, the rise in the utility of smart devices, and the increasing demand for enhanced customer experience. In addition to this, the surging investments in the healthcare sector and the emergence of several new application areas are anticipated to further boost the natural language processing market. </br>
NLP can be used for applications such as information extraction, question answering, machine translation, and report generation in a number of industry verticals, including automotive, retail and consumer goods, high tech and electronics, government, banking, financial services, and insurance (BFSI), health care and life sciences, research and education, and media and entertainment. </br>
NLP has made the communication process way easier and compatible with the end-users. It is extensively applied in businesses today and it is the buzzword in every engineer’s life. In short, NLP is everywhere.
### Conclusion:
This is a simple language detection model using Logistic Regression. The power of the model relies, as usual, on the input features, and using the char 2-grams or 3-grams seems to have been a good idea and can predict a language with 98.7-99 % accuracy.
