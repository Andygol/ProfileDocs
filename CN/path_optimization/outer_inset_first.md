先外壁后内壁
====
该设置可确定内壁和外壁的先后打印顺序。

![The inner wall is printed first](../images/outer_inset_first_disabled.gif)
![The outer wall is printed first](../images/outer_inset_first_enabled.gif)

启用该设置对质量和尺寸精度有轻微影响：
* 该设置会提高尺寸精度。相邻壁面通常会相互挤压，特别是对于壁线宽小于喷嘴口径的情况。先打印的壁面可以更早地固化，受到相邻壁面的挤压影响较小。因此，先打印外壁可提高外壁的位置精度。
* 如果内部填充优先在壁面之前打印，那么启用先外壁后内壁之后，填充在模型表面的显露程度将会降低。否则，如果先打印填充，再依次打印内壁和外壁，那么外壁分别会由于填充和内壁的推力向外移动。打印成品不仅尺寸精度降低，填充图案也会显露在外。如果打印完填充后，先打印外壁再打印内壁，则外壁可以更早固化，免受内壁推力的影响。
* 先打印外壁通常会影响悬垂结构的质量，因为先打印外壁的话，外壁没有任何可以依附的结构。