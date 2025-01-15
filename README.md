The generative RBF NN is trained by MNIST x_train digits and the median image of (x_train + 1) digit as the labels.
Then, images of x_test are given to the model to generate the next digit images.
A simple RBF Neural Network Classifier takes the generated digits and tries to classify (recognise) them.
Accuracy of the generation is being tested comparing the recognised digits with the (y_test + 1) set.
Contrust enhancement is applied to the generated images to help the recognition. 
