顶部/底部走线方向
====
### **参数描述**
本设置可用于更改打印成品的顶部和底部的走线方向，适用于直线和锯齿形走线图案。

您可以设置多个角度（单位为度），并以逗号分隔，则各层的走线会交替改变方向。例如，您可以设置**[0,90,180,270]**，每层的走线方向就会依次旋转 90 度。

![Lines pattern with 0°, 60° and 120° angles alternating](../images/skin_angles.gif)

默认情况下，会按照对角线方向打印直线，这在笛卡尔龙门系统中可以保证打印的准确性。因为当转向下一条走线时，打印机可以同时利用 X 轴和 Y 轴的电机来进行加速。

### **参数影响**
改变走线方向的几个原因如下：
* 为了实现某种视觉效果。
* 为了提升打印成品的强度。
* 为了减少悬垂。您可以选择与填充互相垂直的走线方向，这样可以减少顶部/底部的走线悬垂于填充上方的情况，提高打印件表面的质量。