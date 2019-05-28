# Measuring-size-of-objects-in-an-image-with-OpenCV
基于opencv的图像目标尺寸检测。
关键点：（1）需要有参照物，默认为图像中的左侧目标
       （2）拍摄的图像角度需要尽可能的处于竖直方向
     
     
 文中提到了一个概念pixels_per_metric，图像目标尺寸检测类似于计算从我们的相机到一个物体的距离——在这两种情况下，我们都需要事先定义一个比率来测量每个给定度量单位的像素数（pixels_per_metric）。在这里所说的这个被称为“pixels_per_metric”的比率指标，pixels_per_metric =物体像素宽 / 物体真实宽，获得这个比率之后就可以获得其他物体的大小。
 
 
 如下图中所示的例子，就是以最左边的硬币为参照物：
 
![image](https://github.com/joehalfish/Measuring-size-of-objects-in-an-image-with-OpenCV/blob/master/images/example_01.png)
