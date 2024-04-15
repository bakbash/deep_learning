# deep_learning

## PURPOSE
The purpose of the charity funding analysis for Alphabet Soup was to predict where the company would approve/make investments. Our goal was to use machine learning and neural networks to apply target/features on the dataset, create a binary classifier that was capable of predicting whether investors would be successful if funded by Alphabet Soup. 

Target variable:
IS_SUCCESSFUL

Dropped Variables:
EIN and Name

Model: "sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense (Dense)               (None, 80)                3520      
                                                                 
 dense_1 (Dense)             (None, 30)                2430      
                                                                 
 dense_2 (Dense)             (None, 1)                 31        
                                                                 
=================================================================
Total params: 5981 (23.36 KB)
Trainable params: 5981 (23.36 KB)
Non-trainable params: 0 (0.00 Byte)
_________________________________________________________________


