# Homework 6: Neural Networks with Batching and CNNs

Problem 1 (50 pts):

1.a. Create a fully connected Neural Network for all 10 classes in CIFAR-10 with only one hidden layer with the size of 512. Train your network for 300 epochs. Report your training time, training loss and evaluation accuracy after 300 epochs. Analyze your results in your report. Make sure to submit your code by providing the GitHub URL of your course repository for this course. (20pt)

2.b. Extend your network with two more additional hidden layers, like the example we did in lecture. Train your network for 300 epochs. Report your training time, loss, and evaluation accuracy after 300 epochs. Analyze your results in your report and compare your model size and accuracy over the baseline implementation in Problem1. a. Do you see any over-fitting? Make sure to submit your code by providing the GitHub URL of your course repository for this course. (30pt)

 

Problem 2 (50 pts):

2.a. Build a Convolutional Neural Network, like what we built in lectures to classify the images across all 10 classes in CIFAR 10. You need to adjust the fully connected layer at the end properly with respect to the number of output classes. Train your network for 300 epochs. Report your training time, training loss, and evaluation accuracy after 300 epochs. Analyze your results in your report and compare them against a fully connected network (Problem 1) on training time, achieved accuracy, and model size. Make sure to submit your code by providing the GitHub URL of your course repository for this course (20pt)

2.b. Extend your CNN by adding one more additional convolution layer followed by an activation function and pooling function. You also need to adjust your fully connected layer properly with respect to intermediate feature dimensions. Train your network for 300 epochs. Report your training time, loss, and evaluation accuracy after 300 epochs. Analyze your results in your report and compare your model size and accuracy over the baseline implementation in Problem2.a. Do you see any over-fitting? Make sure to submit your code by providing the GitHub URL of your course repository for this course (30pt)