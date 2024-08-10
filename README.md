<font style="background: rgb(124,250,125)"> #Shilren.github.io  
## 个人网站设计思路&原型图 </font>
- **项目的基调：**
作品集、博客或者linkedin个人主页。
- **制作原型图：**
预想制作一个首页，包括导航页，【财会CPA】【产品运营笔记】【数据分析】【ps视频剪辑绘画】【语言学习】
- **动作：**
点击相应板块就能跳转到相应的位置。
- **缺点：**
技术和时间有限导致过于简陋，信息展板参考企业官网。
- **资料：**  
    *需要准备的是一个icon*  
    ![iconpic](picture/icon.jpg "shilren's zone")  
    *准备一个背景图*
    ![backgroundpic](./picture/bule%20water.jpeg)
---
## 问题备注:
1.icon无论如何调试都无法显示。（liveServer和github服务器，以及edge和chrome都无法显示，icon已裁减至16*16，采用最新语法，参MDN）  
2.head标签中的内容跑到body里面，导致很多渲染不成功。已经修改为utf-8 with bom 或使用notepad++保存，仍然出现渲染标签错位的情况。（但并不影响视图）  thanks for this tutorial vedio.i've tried those codes, and everything seemed fine on the surface,but when the browser rendered, i found the <link> and <meta>  elements moved from the head to the body. i've tried to save file with utf-8 with bom,but still doesn't work, i don't know why.     
> re1&2: 
> 检查后发现并不是浏览器渲染问题，因code中字符出错导致渲染出错。 
3.github托管网站需要识别index文件，倘若没有则渲染readme文件。  
4.系统自动生成的index文件被误删，导致重命名的Index非常不稳定，时常渲染md文件，现恢复之前的文件，有一定效果，具体原因未知。  
5.想要设置下载链接，需要先制作种子文件获取磁链接，将磁链接放入href中，而download内容为文本。  
6.在css中，样式的顺序不能随意放置，从上到下读取信息的过程中需要样式出现遵循逻辑顺序。  
7.奈何没有设计美感导致第五页奇丑😥  
8.当元素出现遮挡问题的时候，记得设置z-index调整显示层级。  
9.经测试发现页面图片过大，加载缓慢。
10.手机视图非常糟糕。媒体查询可能需要设计安卓页面，囿于时限暂搁置，遂取消宽度自适应。
---
## 原型图:
![prototype](picture/首页.png "prototype")
