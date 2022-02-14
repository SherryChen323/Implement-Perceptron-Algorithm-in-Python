# Implement-Perceptron-Algorithm-in-Python
(a) Implement the perceptron algorithm for binary classification. Train and test it for classifying digits ”1” and ”6” in MNIST dataset. Note that we don’t need the data of other digits in this part. Please use 1000 training examples and 1000 testing examples. Plot the accuracy on the test set w.r.t. the number of iterations. Here, processing each data-point is considered one iteration, so 1000 iterations means one pass over all training data.
(b) Visualize the learned model in the image form to see if it makes sense. Note that the weight vector has both positive and negative values, so you should plot those on two separate planes. Note that you should use exactly the same testing data to be able to compare the results.
(c) For each class, visualize the 20 best scoring and 20 worst scoring images that are classified as that class. The worst ones are close to the boundary and may be wrong.
(d) Randomly flip the label (add labeling error) for 10% of the training data and repeat (b) and (c).
(e) Sort the data before training so that all ”1”s appear before ”6”s and plot the accuracy w.r.t. the number of iterations. Is this faster or slower in training? Explain why.
(f) Repeat (a) with 10 training examples per class and compare with the result of (a).
