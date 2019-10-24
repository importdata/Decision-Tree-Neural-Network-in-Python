# Decision-Tree-Neural-Network-in-Python
*** Please navigate to the link provided below if you can't open .ipynb file ***

https://nbviewer.jupyter.org/github/kotexan/Decision-Tree-Neural-Network-in-Python/blob/master/Machine_Learning_Assignment_2.ipynb

About Dataset:
- MNIST data, a dataset of thousands of images of handwritten digits. Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive. The  data set has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.” mnist.csv file contains 10k samples of images, you have equal number of samples belonging to each label (i.e 1k samples of label ‘0’, 1k samples of label ‘1’ and so on).

Tasks:
1. Took random sample of 100 instances out of each label (1,000 instances in total). 
2. Applied Decision Tree and Multi-Layer Perceptron methods on the whole dataset as training dataset, and calculated the training and test accuracy for each method.
3. Applied k-fold cross validation using the sampled dataset generated in task 1. Performed the k-fold cross validation using the following values: k=2, and k=4.
