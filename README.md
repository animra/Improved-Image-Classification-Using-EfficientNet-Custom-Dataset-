# Image Classification using EfficientNet

# Dataset
The dataset is taken from "https://www.kaggle.com/c/deeplearningclassificationtask/data"

- Training set: 5,000 images
- Test set: 8,000 images
- Image size: 96x96

## Label Details

Label in training data consists of 10 labels from 0 to 9 and the detail is given below:

0. airplane
1. bird
2. car
3. cat
4. deer
5. dog
6. horse
7. monkey
8. ship
9. truck

We need a model to predict the label of these images correctly. Hence, EfficientNet is used for this purpose. 

# Classification using EfficientNet
EfficientNet is a family of CNN's built by Google and it is currently the most performant convolutional neural network for classification. These CNNs not only provide better accuracy but also improve the efficiency of the models by reducing the number of parameters as compared to the other state-of-the-art models. 

**By using this model 97% accuracy is acheived on training dataset.**

# Note: 
**You can run this project on Jupyter Notebook or on Google Colaboratory. While training the dataset on Google Colab, change runtime and select GPU for faster computation.**
