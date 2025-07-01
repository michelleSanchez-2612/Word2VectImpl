# Word2VectImpl
Word2Vect Implementation: Skipgram and CBOW

In this exercise, I will create my own implementation of word2vec for a small corpus using both most famous algorithms: CBOW and skipgram algorithms.

For this exercise, I will use Pytorch library and I will apply the following steps on both models:

*   First, apply one-hot vectors for data representation to the input layer.
*   For the training process I will use Cross Entropy as the loss function, optimizied with Adam.
*   Finally, I will use PCA to reduce the dimensionality of the word embeddings and visualize them in 2D.


To have final results of the models, I will:


*   Evaluating target words with the CBOW Model.
*   Finding the context words with Skip Gram Model.
