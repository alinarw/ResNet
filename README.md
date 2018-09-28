# ResNet
Implementing 18-layer ResNet from scratch in Keras based on the original paper Deep Residual Learning for Image Recognition by Kaiming He, Xiangyu Zhang , Shaoqing Ren and Jian Sun, 2015.

The residual blocks are based on the improved scheme proposed in “Identity Mappings in Deep Residual Networks” by Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun, 2016.

To synchronize the dimentions between the identity and plain block, Conv2D with strides=(2, 2) was applyed to X.
