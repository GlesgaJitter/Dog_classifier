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
