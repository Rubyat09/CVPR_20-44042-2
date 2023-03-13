# CVPR_20-44042-2
**The KNN code implements the k-Nearest Neighbors (k-NN) algorithm for the CIFAR-10 dataset. The code reads the training images from a directory and creates a list TRAIN_DATA with their corresponding class labels. The list is then shuffled and a random sample of 50 images with their labels is displayed. The training data is divided into 5 folds, and the code uses one fold for validation and the remaining 4 for training. Two distance metrics, L1 and L2, are used to calculate the distances between the validation and training images. The code computes the accuracy of the algorithm for k values of 1, 3, 5, 7, and 9, and records the average accuracy over the 5 folds for each k value. Finally, the code plots the average accuracies for both L1 and L2 distances.**
