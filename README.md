# StudyJavaScript
Study JavaScript 

#Img的几种属性

HTML 图像标签
标签 	描述
<img> 	定义图像
<map> 	定义图像地图
<area> 	定义图像地图中的可点击区域

示例"创建图像映射"中的代码：

通过usemap 引用 map中的name字段

<img src="planets.gif" width="145" height="126" alt="Planets" usemap="#planetmap">

<map name="planetmap">
  <area shape="rect" coords="0,0,82,126" alt="Sun" href="sun.htm">
  <area shape="circle" coords="90,58,3" alt="Mercury" href="mercur.htm">
  <area shape="circle" coords="124,58,8" alt="Venus" href="venus.htm">
</map>

该段代码中的shape指的是点击区域的形状，coords指的应该是链接区域在图片中的坐标（像素为单位）

1、距形：(左上角顶点坐标为(x1,y1)，右下角顶点坐标为(x2,y2))
<area shape="rect" coords="x1,y1,x2,y2" href=url>

2、圆形：(圆心坐标为(X1,y1)，半径为r)
<area shape="circle" coords="x1,y1,r" href=url>

3、多边形：(各顶点坐标依次为(x1,y1)、(x2,y2)、(x3,y3) ......)
<area shape="poly" coords="x1,y1,x2,y2 ......" href=url>



