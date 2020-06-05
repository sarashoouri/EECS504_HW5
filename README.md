# EECS504_HW5
 Scene Recognition
In this problem set, you will train a CNN to solve the scene recognition problem, i.e., the
problem of determining which scene category a picture depicts. You will train two neural
networks, which we call MiniVGG and MiniVGG-BN. MiniVGG is a smaller, simplified version
of the VGG [1] architecture, while MiniVGG-BN is identical to MiniVGG except that we added
batch normalization layers after each convolution layer.
You will train the neural networks on the MiniPlaces dataset1
. We’ll use 90,000 images for
training, 10,000 images for validation, and the remaining 10,000 images for testing.
