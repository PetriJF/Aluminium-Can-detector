# Aluminium Can Detector

A Tensorflow implementation of a alumium can detector aiming to detect the cans in all states of deformation and obturation. A custom dataset of around 1000 images was used to train the neural network, and after optimization, a general accuracy of 94.23% was achieved.

# Setup

The environment is configured for tensorflow 1.13, CUDA 10 and cuDNN 7.4. Any other versions might form warnings or plain old errors impeding the use of the NN.

The working Neural Network with out can detector model can be accessed by opening the anaconda environment (Or alternative) and doing the following:
- Go to the directory : models/research/object_detection/
- Type the "idle" command
- Press open, and run the webcam or image python scripts
- Enjoy
