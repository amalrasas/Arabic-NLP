# Arabic-NLP

In this assignment you are required to create word embeddings, use them in a sentiament
analysis task and then compare that to already available embeddings library.
Part 1: Arabic Word Embeddings
In this part you are required to choose at least one document to create word embeddings
for Arabic words.
Perform the text preprocessing steps that you think are important, such as handling emojis
and numbers, prepare the dataset for training your model similar to that we have seen in the class,
and then create the NN model and train it. Once you are done, extract the embeddings and create
a simple API that takes an Arabic word and returns its embeddings. It may also implement other
features that may help you in later tasks. Use proper documentation when you submit this part and
include the documents you have used.
Part 2: Sentiment Analysis - 1
In this task you are going to create a NN model that classify the status of the writer of some
Arabic text to “happy” and “sad” based on the text. In this task you will represent the text by
averaging the embeddings of the words comprising the text. For the word embeddings here, use
the API you have created in Part 1.
CpE 597: Special Topics in Computer Engineering – Machine Learning December 2022
Use proper documentation when you submit this part and include the proper performance
metrics for the training and validation. The test set will be released to you after you submit your
code.
Part 3: Sentiment Analysis - 2
In this task you are going to create a NN model that classify the status of the writer of some
Arabic text to “happy” and “sad” based on the text. In this task you will represent the text by
averaging the embeddings of the words comprising the text. For the word embeddings here, use
the already available AraVec 3.0 (https://github.com/bakrianoo/aravec).
Use proper documentation when you submit this part and include the proper performance
metrics for the training and validation. The test set will be released to you after you submit your
code.
Part 4: Sentiment Analysis - 3
Re-implement the same task using a RNN employing LSTM and uses the embeddings
generated using your API. Note that here you will feed your model with the embedding for each
word in sequence.
Use proper documentation when you submit this part and include the proper performance
metrics for the training and validation. The test set will be released to you after you submit your
code.
Part 5: Sentiment Analysis - 4
Re-implement the same task using a RNN employing LSTM and uses the embeddings
generated using AraVec 3.0. Note that here you will feed your model with the embedding for each
word in sequence
