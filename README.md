# CT-denoise
##CT image denoise
我在MIRNet的图像上做了简单的CT图像去噪，噪声的代码我放在了上面，可以设置成椒盐噪声或者是高斯噪声。

Because we use the denoising model of MIRNet and did not train on CT images, the effect is general. If you train enough on the CT model, I think the effect should be satisfactory.
The result is ![image](https://github.com/zhangbaijin/CT-denoise/blob/main/2%20(2).jpg)
The original is ![image](https://github.com/zhangbaijin/CT-denoise/blob/main/0001_1.png)
数据集的链接如下：链接：https://pan.baidu.com/s/1UA843ZUphDGidSuwXMebfQ 
提取码：mao9 
数据集包含了test和train两个文件夹，总共800张左右

# Acknowledgement
The code is updaded on https://github.com/swz30/MIRNet 
