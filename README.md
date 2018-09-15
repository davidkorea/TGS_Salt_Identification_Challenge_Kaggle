# TGS_Salt_Identification_Challenge_Kaggle


# Issue 2 - Up-Sampling: Bilinear Interpolation双线性插值

![](https://images2015.cnblogs.com/blog/904258/201603/904258-20160305184525205-215659449.jpg)
![](https://user-images.githubusercontent.com/26485327/45526107-d2c65180-b810-11e8-9a56-fdc6e09187c9.png)

Reference
1. [双线性插值原理与实现](https://www.cnblogs.com/hustlx/p/5245504.html)
2. [双线性插值算法的详细总结](https://blog.csdn.net/sinat_33718563/article/details/78825971)

# Issue 1 - Black and white zone of mask images

**White = Salt**

For simplicity you can take a look at the [image](http://photobucket.com/gallery/user/MUnewspaper/media/bWVkaWFJZDo3NjE1NTIwOA==/?ref=). The top is the geophonetic record images, the bottom is the "mask" in which the white part delineates where the salt is and the black part where the sediment is.

You job is that given an image from the top, you have to predict the bottom, which is essentially looking at an image and determines where the salt is. The work of determining which pixel in the image is something is called "Segmentation"

Reference: [Relationship between mask and images](https://www.kaggle.com/c/tgs-salt-identification-challenge/discussion/61954)
