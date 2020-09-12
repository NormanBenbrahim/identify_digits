# Identify digits in images using OCR

Based on the following tutorial: https://www.analyticsvidhya.com/blog/2016/10/an-introduction-to-implementing-neural-networks-using-tensorflow/

# Tutorial data

* http://yann.lecun.com/exdb/mnist/

# Tips from the article:

Neural networks is a special type of machine learning (ML) algorithm. So as every ML algorithm, it follows the usual ML workflow of data preprocessing, model building and model evaluation. For the sake of conciseness, I have listed out a TO DO list of how to approach a Neural Network problem.

* Firstly, neural networks require clear and informative data (and mostly big data) to train. Try to imagine Neural Networks as a child. It first observes how its parent walks. Then it tries to walk on its own, and with its every step, the child learns how to perform a particular task. It may fall a few times, but after few unsuccessful attempts, it learns how to walk. If you don’t let it walk, it might not ever learn how to walk. The more exposure you can provide to the child, the better it is.

* It is prudent to use Neural Networks for complex problems such as image processing. Neural nets belong to a class of algorithms called representation learning algorithms. These algorithms break down complex problems into simpler form so that they become understandable (or “representable”). Think of it as chewing food before you gulp. This would be harder for traditional (non-representation learning) algorithms.
When you have appropriate type of neural network to solve the problem. Each problem has its own twists. So the data decides the way you solve the problem. For example, if the problem is of sequence generation, recurrent neural networks are more suitable. Whereas, if it is image related problem, you would probably be better of taking convolutional neural networks for a change.

* Last but not the least, hardware requirements are essential for running a deep neural network model. Neural nets were “discovered” long ago, but they are shining in the recent years for the main reason that computational resources are better and more powerful. If you want to solve a real life problem with these networks, get ready to buy some high-end hardware!