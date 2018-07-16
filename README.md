Abaqus 手册：https://classes.engineering.wustl.edu/2009/spring/mase5513/abaqus/docs/v6.6/index.html
https://wenku.baidu.com/view/ee78ab75f242336c1eb95e52.html
# abaqus技巧

## Abaqus 常用快捷键
旋转：Ctrl+Alt+左键
平移：Ctrl+Alt+中键
缩放：Ctrl+Alt+右键

## Abaqus 设置相关
改变背景：主菜单 > view > graphics options 》 Viewport Background > Solid
<div align=center>

![Abaqus Background](https://github.com/youshenfan/abaqus-/blob/master/pics/abaqus-background.PNG)
</div>

打开多个显示窗口：主菜单 > tools > query 》Visualization Module Queries > Ply stack plot
<div align=center>

![Abaqus Multiplot](https://github.com/youshenfan/Abaqus/blob/master/pics/abaqus-ply%20stack%20plot.PNG)
![Abaqus Multiplot](https://github.com/youshenfan/Abaqus/blob/master/pics/abaqus-ply%20stack%20plot2.PNG)

</div>



## Abaqus中Johnson Cook 模型的设置

Johnson-Cook模型是一种金属材料变形级破坏行为的本构模型，其参数通过试验测量（知网上有文献专门介绍测试方法）。
Abaqus中计算Johnson-Cook需要的参数有：a,b,c,m,n,参考应变,以及破坏参数D1~D5，每个参数的意思在帮助文档中都会有详细的说明。


## Abaqus 各文件的用途
abaqus.rpy  记录一次操作中几乎所有的ABAQUS/CAE命令
