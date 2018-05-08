# Installing tensorflow 
- OS
- GPU
- Environment 
-- Docker, Virtual
- Python Version 3.x later

- prebuilt soln
- GPU support - nvidia card
- Geforce products

## how to install
- native pip
- anaconda

- install --upgrade tensorflow 
- import tensorflow as tf
- tf.session()
- tensorflow, numpy, math , matplotlib

## Training a model 
- Prepared Data - generate data (70% train 30% test)
- Inference - predictions
- Loss measurement - optimizers e.g gradient descent
- Optimizer to optimize loss 

## Steps
- Data prep
-- normalize data passed in
-- Split data (70:30)
- define operations for predicting values

### Tensor types
- Constant
- Variable
- Placeholder for graphs

- Define the loss function 
- learning rate (Optimizer learning rate)
- tf.train.gradientdescentoptimizer

- plot to see test and train data is closer

# Tensor properties 
- Rank - dimensions Scalar, Vector, Matrix , 3-tensor (cube)
- shape - [] , [x], [x,y]
- size 

## datatypes
- int and unsigned integers uint 
- string bool 
- complex64 , complex128
- qint8, qint16, quint8

### Quantitized values
- scaled to reduce size
- decrease process size by 75%
- Tensorflow processing units use these numbers 

### Methods
- get-shape ()
- reshape ()
- rank
- dtype - return type
- cast

# Gradient Descent Optimizer
- add animation if req to show how variables change through iterations 
- 
