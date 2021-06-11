# test

- 保护隐私的照相机硬件：或是再照相机硬件层面执行隐私编码工作，或是直接对源图像进行加水印或动画化，亦或是操控增益、曝光或数字化后信息。

  > For computational cameras, one approach is to perform privacy algorithms at the camera level, and using encryption or other methods for information afterwards [9, 15]. Another approach is to build sensors which preserve privacy through watermarking [37] or cartooning [54] or manipulating gain/digitization/exposure [42].

## Lensless Camera

无镜头照相机使用一个同心圆衍射薄膜取代了传统的镜头，**但并没有取代后面的感光器件**。光源发出/反射的光透过这个薄膜发生衍射现象生成一张结果图像。这个图像中除了像本身的信息，甚至还携带有距离信息。经过算法反推/机器学习训练后，可以重建出原始图像。

这里的重建环节则可以做文章。可以训练出来一种只重建脸以外图像部分的网络，而只有当得到授权的用户访问时才会重建出完整图像。

<img src="https://raw.githubusercontent.com/Pearlzju/Markdown4Zhihu/master/Data/test/1.jpg" alt="[image] Figure: Principle of newly developed lensless camera technology" style="zoom:70%;" />