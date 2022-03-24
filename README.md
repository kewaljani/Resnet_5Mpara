# Resnet_5Mpara
<!-- Created Resnet architecture with parameters less than 5M  -->
<!-- #Running the python File -->

# Introduction
Recent advances in deep neural networks have achieved numerous state of the art results in image classification tasks. It was found that even though deeper networks yield breakthrough results , they are faced with a degradation problem . As the network gets deeper, accuracy was observed to fall substantially as the gradient kept diminishing with depth. This problem wasn't due to overfitting since training loss and test loss was observed to be deteriorating. Residual Networks have introduced the concept of a skip connection that allows the network to resolve the vanishing gradient problem by adding back the input of the current block to its output. This network architecture has substantially improved performance over previously available convolutional networks. It was also shown that with deeper layers, these networks performed much better. In our project, we were provided with the ResNet-18 architecture that was used in and we will be presenting our ResNet architecture with lower than 5M parameters compared to the original network.

The ResNet-18 architecture provided to us consists of around 11.17M trainable parameters. In order to achieve our goal of adapting this model to be stored on devices with limited storage capacity, we had to specifically look into ways of reducing our model size to contain parameters under 5M. This made us take a new approach of using various block size combinations within each residual layer. We then show our findings by training our optimized model on the CIFAR-10 dataset, where we gained around 92.94\% accuracy.

# Execution of program
## 1) Method 1: 
execute the google Collab file. The trained file has been uploaded to the google drive hence it will directly fetch the file from the account

-> Authorize the user select the google account on which you want to run the file 
-> Copy the authentication Key and past it in the collab file.
-> Press Enter after pasting the authentication Key

## 2) Method 2 (Running on HPC or your own device): 

-> Download the python and PT file and keep it in same directory.
-> run the py file 


