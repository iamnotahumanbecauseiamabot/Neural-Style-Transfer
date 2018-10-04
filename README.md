# Neural-Style-Transfer
neural style transfer by eager execution  
paper: https://arxiv.org/pdf/1508.06576v2.pdf

weights used content_weight=2*1e3 style_weight=1e-2

layers used:
content_layers = ['block5_conv2'] 

style_layers = ['block1_conv1',
                'block2_conv1',
                'block3_conv1'
                'block4_conv1'
                'block5_conv1'
               ]
 reference : https://medium.com/tensorflow/neural-style-transfer-creating-art-with-deep-learning-using-tf-keras-and-eager-execution-7d541ac31398
