# Handwritten Digit Recognition
---
## About the project
In this, I have trained and evaluated a simple neural network using PyTorch for detecting digits from 0 to 9.

## About the data
- The MNIST data used here is obtained from a Kaggle competition
- Here, digit-recognizer.zip contains the data
- It contains two files:<br/>
  `train.csv` - for train and validate the model.<br/>
  `test.csv` - for testing the model's prediction capability on unseen data<br/>

## Project Overview
- Builds a feedforward neural network in PyTorch
- Uses Cross-Entropy Loss and the Stochastic Gradient Descent optimizer
- Learning rate = 0.01

# Running the file
**Dependencies**
- PyTorch
- Numpy
- Pandas
- os<br/>

**Steps for running the file**
1. Clone this repository
   https://github.com/syssoni/Handwritten_digit_recognition.git
2. Create a virtual environment (optional but recommended)
3. Install the required packages
   - Pytorch
   - Numpy
   - Pandas
4. Launch the notebook
   jupyter notebook test_network.ipynb<br/>
   
# Results and Screenshot
---
 - Testing accuracy on validation dataset: 94.42  
<img src="https://raw.githubusercontent.com/syssoni/Handwritten_digit_recognition/main/Results/neural_network.png" alt="Neural Network" width="70%">
<img src="https://raw.githubusercontent.com/syssoni/Handwritten_digit_recognition/main/Results/Testing_accuracy.png" alt="Accuracy" width="70%">
