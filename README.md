# Contents of Repository

```basic_nn/perceptron with two features.ipynb```

```pneumoniaTest/chest_xray/```

```pneumoniaTest/pneumoniaTracker.ipynb```

```README.md```

```pneumoniaTracker.ipynb``` Is the program which trains a Neural Network to identify an x-ray with pneumonia. 
I used a repository from [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) to find a dataset
of patients with and without pneumonia. The program also uses helper functions that I used from my programming assignments in 
[Andrew Ng's Deep Learning Specialization course](https://www.coursera.org/specializations/deep-learning?utm_source=gg&utm_medium=sem&utm_content=17-DeepLearning-US&campaignid=904733485&adgroupid=46370300620&device=c&keyword=coursera%20deep%20learning%20ai&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=415429098219&hide_mobile_promo&gclid=EAIaIQobChMIs_CFtrnm6QIVhRh9Ch1SOQBvEAAYASAAEgIsR_D_BwE).
In addition, I pre-processed the images and trained the Network with various hyperparameters (learning_rate, number of 
hidden layers, hidden layer size). 

```chest_xray``` contains the contents of the training, validation, and test sets as well as the "trainTEMP" set I created
from the training set to confirm that I correctly preprocessed images.

```perceptron with two features.ipynb``` contains a very simplified, non-rigorous version of a neural network. In fact, we only use a single node, so the official term is a `perceptron`. 
