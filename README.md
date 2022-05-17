# Dog_classifier

In this project, I have created a dog-breed classifier powered by a convolutional neural network (CNN). 
I have built this as part of the Udacity Data Science programme. 

The classifier's main output is identifying the breed of a dog in an image provided by the user. 
An additional functionality is that the classifier also attempts to classify human faces into dog breeds. 
The classifier thus:
- detects whether a dog or human is present in an image
- if a dog is present, a breed is predicted
- if a human is present, a breed is given which resembles the human. 

The process of building the program is outline in my Medium blog post:

https://medium.com/@andrew.croudace/whats-that-dog-or-human-f07498678f9d

# What's in the program

The program is written as a Jupyter Notebook (.ipynb file). 

In this notebook, we perform the following steps:
- Step 0: Import Datasets (images of dogs and humans)
- Step 1: Detect Humans (build a function to detect whether a human is present in an image)
- Step 2: Detect Dogs (build a function to detect whether a dog is present in an image)
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 6: Write an Algorithm to take an image path as an argument, and predict the dog's breed (if present)
- Step 7: Test Your Algorithm (tests are performed on some human and dog images, with some discussion on the results)

# The CNN

To build the CNN, we use ResNet-50 bottleneck features. 
This classifier is in the public domain and has been widely used with success in image recognition and classification. 
It performs well in this application. 

As it uses 50 layers (48 convolutional layers, 1 max pooling layer and 1 average pooling layer), this is a very deep learning algorithm. 
On top of this, we apply a global average pooling layer in our architecture. 

# Results

I have discussed the results in my Medium blog, and have indicated areas of success, limitations and possible improvements.

# Acknowledgements

Many thanks go to the Udacity team for their help and guidance, and for their great programme which has been critical to building my skills and understanding of Data Science, machine learning, and program documentation. 
