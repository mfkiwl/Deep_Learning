# Deep_Learning, All data is given by University College London (UCL)

## PROJECT TITLE: "Bag, not bag"

![1](https://user-images.githubusercontent.com/74542643/99829382-24d33200-2b54-11eb-9863-14ec8fd583de.PNG)

A standard dataset in machine learning is the MNIST dataset of handwritten digits that has for many years been used to train and evaluate machine learning algorithms. However, even simple algorithms can perform relatively well on MNIST and its usage has increasingly come into question. As a response, alternative “drop-in” replacement datasets have been made available and we will use exactly such a dataset for all tasks in this assignment. Zalando2 is a German e-commerce company and that has released a dataset “Fashion-MNIST” (Xiao et al., 2017) which instead of digits from 0 to 10, contains 28-by-28 pixel, greyscale images of ten distinct fashion items (see Figure 1 for an example subset). The module organisers have prepared a subset of the dataset where the task is to classify a given image as to whether it depicts a bag or not. We have also created train, validation, and test splits. A Colaboratory notebook loading the data can be found at: https://colab.research.google.com/drive/1Tt4LTpLm_vjwkeOwrjNkNUAf1e49pF6I. You are not to use any automatic differentiation packages (such as Flux, TensorFlow, PyTorch, etc.), you are however free to use any of the (sloppy) code provided in the lecture notebooks, packages that do not implement automatic differentiation, or to implement automatic differentiation on your own.

## Task

| Task          | Tentative Topic |
|:----------------------|:--|
|Task 1| A memory-efficient perceptron|
|Task 2| Mean squared-loss logistic regression|
|Task 3| Three-layer multi-layer perceptron|
|Task 4| Hyperparameter tuning|
|Task 5| Model shootout|

# Stanford Sentiment Treebank

![Capture](https://user-images.githubusercontent.com/74542643/101261952-c9e43200-3732-11eb-8495-35e68c6bf102.PNG)

A common task in natural language processing is sentiment classification, where given a sentence or
a document you are tasked with predicting the overall sentiment of the input. Understandably, this
is a fairly popular task in terms of industrial applications of natural language processing, after all,
who would not like to know the overall emotional impact of a recent marketing campaign or what the
voting population is currently feeling regarding a given topic?
Socher et al. (2013) introduced the Stanford Sentiment Treebank, which not only provides sentiment
labels for sentences as a whole, but also for each node inside of a constituency parse tree,4 providing
annotations for phenomena such as negation (as seen in Figure 2). However, for this assignment we
will only be concerned with sentence-level annotations, as parse trees and the likes are more suitable
for a natural language processing class.

| Task          | Tentative Topic |
|:----------------------|:--|
|Task 1| A multi-class, multi-layer perceptron|
|Task 2| Denoising autoencoder|
|Task 3| Sequence prediction|
|Task 4| Bag of vectors|
|Task 5| Sequence encoding|
