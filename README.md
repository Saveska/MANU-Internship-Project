# MANU-Internship-Project

In the following project, we will look at creating a book recommendation system, where we will cover all the key steps for its creation.

The data was taken from Kaggle https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data?select=books_data.csv and only a part of this massive data set was used.

We have visualized the data so that the reader has a clearer picture of what type of data it is, as well as for help in cleaning the data and reducing it. In this same section, we analyze the sentiment to have a clearer picture of the data.

Furthermore, we extract all important properties from the data, such as book genre, author, and publisher. Using the name and description of the books, we used the RoBERTa model to add a vector representation of them.

With that, the next step is to create the graph using Pytorch Geometric. With this, we create a computer representation of our knowledge graph on which we will further train and test the models - GraphSAGE, GAT and Transformers. After a long period of training - we test and compare all models using the hit metric. From our results we get a high level of accuracy and a good sign that this problem could be (and already is) useful and used in real life on a huge amount of data from different fields.
