# cifar-10
Cifar-10 classifer: Used pca on cifar-10 images and then different classifiers

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class.
The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another.
Between them, the training batches contain exactly 5000 images from each class. 

I used PCA to reduce the number of features in these images, yet maintained>95% variance.
Then used various classifiers on dataset.
