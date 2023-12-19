# *Problem Statement:* 

The goal was to build a recurrent neural network (RNN) model for sentiment analysis on the IMDB movie review dataset. This would provide hands-on experience with natural language processing concepts like text preprocessing, model architecture design, training, evaluation and optimization techniques.

# *Dataset Selection:*

The IMDB dataset containing 50,000 highly polarized movie reviews was chosen. It has two columns - the text review and a 'positive' or 'negative' sentiment label. Did exploratory analysis to check for null values, visualize label distribution, etc.

# *Data Preprocessing:*

Preprocessed the text data by tokenizing, removing stop words, and handling issues such as punctuation and capitalization and divided the dataset into training and testing sets. 

# *RNN Architecture Design:*

Design a Recurrent Neural Network (RNN) architecture for sentiment analysis. Experiment with different architectures, including the number of layers, types of recurrent layers, and activation functions.


# *Model Training:*

Trained  RNN model using the training dataset. Experimented with hyperparameters such as learning rate, batch size, and epochs. Monitored the training process and analyze the loss and accuracy trends

# *Model Evaluation:*

While I gave an approach for training the RNN by experimenting with different epochs by 10 and batch size of 128.Calculated the key metrics such as accuracy, precision, recall, and F1 score. Examine misclassifications to understand areas for improvement also plotted the confusion matrix for better improvement.Below are the results-

Accuracy: 0.8627

Precision: 0.8510149368058215

Recall: 0.8819210160746179

F1 Score: 0.8661923789104375

# *Examination of Misclassification:*

1.	Identifying misclassified samples

2.	Analyzing misclassified samples

3.  Visulisation

# *Fine-tuning and Optimization:*

## BIRDIRECTIONAL RNN

Bidirectional recurrent neural networks (BRNNs) are neural network architectures designed to process sequential data. BRNNs process input sequences in both the forward and backward directions so that the network can use information from both the past and future context in its predictions. The primary difference between traditional recurrent neural networks and BRNNs is this.

## DROPOUT

The term "dropout" in machine learning describes the technique of randomly ignoring some nodes in a layer while training. A regularization strategy called a dropout makes sure that no units are codependent on another, which inhibits overfitting.




