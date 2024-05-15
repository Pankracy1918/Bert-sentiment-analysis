In this project I approached the task of fine-tuning the sentiment analysis using Bert NLP model. 
To the project I used emotions dataset (https://www.kaggle.com/datasets/nelgiriyewithana/emotions) and distilbert-base-uncased.
I used Pytorch, Transfomers, Sklearn and numpy.
In order to train the model I used my own graphic card which is GeForce GTX 1050 Mobile, training took 7 hours on one epoch :(. 


F1 Score is 0.9023
Training loss is 0.5922
Validation loss is 0.273

And the accuracy on particular classes which are related to emotions (sadness (0), joy (1), love (2), anger (3), fear (4), and surprise (5)) are:

Class: 0
Accuracy:8664/9152

Class: 1
Accuracy:10121/10552

Class: 2
Accuracy:1750/2566

Class: 3
Accuracy:3838/4290

Class: 4
Accuracy:2957/3570

Class: 5
Accuracy:927/1131
