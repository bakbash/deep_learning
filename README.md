# deep_learning

## PURPOSE
The purpose of the charity funding analysis for Alphabet Soup was to predict where the company would approve/make investments. Our goal was to use machine learning and neural networks to apply target/features on the dataset, create a binary classifier that was capable of predicting whether investors would be successful if funded by Alphabet Soup. 

Target variable:
IS_SUCCESSFUL

Dropped Variables:
EIN and Name

The model achieved performance of 72.62%
_________________________________________________________________
 Layer (type)                Output Shape              Param  
=================================================================
 dense (Dense)               (None, 80)                3520      
                                                                 
 dense_1 (Dense)             (None, 30)                2430      
                                                                 
 dense_2 (Dense)             (None, 1)                 31        
                                                                 
=================================================================
Total params: 5981 (23.36 KB)
Trainable params: 5981 (23.36 KB)
Non-trainable params: 0 (0.00 Byte)


## Optimization:
1.Added third layer 
2.Addded neurons
3.Adjusted epochs and learning rate

The model achieved performance of 72.90%
_________________________________________________________________
Layer (type)                Output Shape              Param  
=================================================================
 dense_15 (Dense)            (None, 50)                2200      
                                                                 
 dense_16 (Dense)            (None, 25)                1275      
                                                                 
 dense_17 (Dense)            (None, 13)                338       
                                                                 
 dense_18 (Dense)            (None, 1)                 14        
                                                                 
=================================================================
Total params: 3827 (14.95 KB)
Trainable params: 3827 (14.95 KB)
Non-trainable params: 0 (0.00 Byte)

