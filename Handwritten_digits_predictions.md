### Using tensor flow and Keras libraries, I built a deep learning network that reads in the MNIST dataset and predicts hand written digits with at least 98% accuracy. 

- The model consists of three layers, which are arranged sequentially. The first layer, "Flatten", takes the input image data (which has dimensions of 28x28 pixels and one color channel) and flattens it into a one-dimensional array. 

- The second layer is a "Dense" layer with 128 nodes and a ReLU activation function. The ReLU activation function helps to introduce non-linearity into the output, which enables the network to learn complex patterns in the data.

- The final layer is another "Dense" layer, which outputs a probability distribution over the number of classes (which is denoted by "num_types"). This layer uses the "softmax" activation function, which ensures that the output probabilities add up to 1, making them easier to interpret as class probabilities.


- The plots showed that the model performed better on the training data than it did for the validation data which implies that the model is overfitting. I increased the depths and widths of the layers but they made no significant improvemnets. 
- So to reduce overfitting, I added a dropout layer. This technique randomly selects some network weights during the updating process, keeping them fixed to ensure that the network doesn't rely too heavily on a particular subset of nodes. This randomness helps to minimize overfitting by eliminating different neuron subsets dynamically on each observation.

- The dropout layer that was added helped randomly drop out some of the neurons during training, so the model is forced to distribute its learning over multiple neurons. 

- This helped solved the overfitting problem by reducing the model's dependence on a narrow range of features.
