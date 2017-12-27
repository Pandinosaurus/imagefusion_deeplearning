# Infrared and Visible Image Fusion using Deep Learning Framework
Our paper will be submitted to ICPR2018.

### Fusion method
![](https://github.com/exceptionLi/imagefusion_deeplearning/blob/master/framework/framework_method.png)

### Fusion detail parts
![](https://github.com/exceptionLi/imagefusion_deeplearning/blob/master/framework/fusion_detail.png)

### Multi-layers fusion strategy
![](https://github.com/exceptionLi/imagefusion_deeplearning/blob/master/framework/fusion_strategy.png)


## Abstract
We proposed an effective image fusion method using deep learning framework to generate a single image which contains all the features from infrared and visible images. 

The source images are decomposed into base parts and detail parts, firstly. 

Then the base parts are fused by weighted-average strategy. For detail parts, we use deep learning network to extract multi-layers features. For these layer features, we use l_1-norm and weighted-average strategy to generate several initial fused detail parts. 

After we get these initial fused detail parts, the choose-max strategy is used to get final fused detail part. 

Finally, the fused image will be reconstructed by combine the fused base part and detail part. 


## Experimental Setting

We use MatConvNet and [VGG-19](https://pan.baidu.com/s/1eSgxtyM) to extract multi-layers strategy.

If you have any question about this code, feel free to reach me(hui_li_jnu@163.com) 
