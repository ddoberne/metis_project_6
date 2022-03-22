```
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 conv2d_42 (Conv2D)          (None, 286, 430, 16)      1312      
                                                                 
 dropout_69 (Dropout)        (None, 286, 430, 16)      0         
                                                                 
 max_pooling2d_39 (MaxPoolin  (None, 143, 215, 16)     0         
 g2D)                                                            
                                                                 
 conv2d_43 (Conv2D)          (None, 141, 213, 32)      4640      
                                                                 
 dropout_70 (Dropout)        (None, 141, 213, 32)      0         
                                                                 
 max_pooling2d_40 (MaxPoolin  (None, 70, 106, 32)      0         
 g2D)                                                            
                                                                 
 flatten_10 (Flatten)        (None, 237440)            0         
                                                                 
 dense_37 (Dense)            (None, 100)               23744100  
                                                                 
 dropout_71 (Dropout)        (None, 100)               0         
                                                                 
 dense_38 (Dense)            (None, 20)                2020      
                                                                 
 dropout_72 (Dropout)        (None, 20)                0         
                                                                 
 dense_39 (Dense)            (None, 10)                210       
                                                                 
=================================================================
Total params: 23,752,282
Trainable params: 23,752,282
Non-trainable params: 0
_________________________________________________________________
```
