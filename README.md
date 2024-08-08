# Shilren.github.io
## 个人网站设计基调&原型图
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
## 问题备注
1.icon无论如何调试都无法显示。（liveServer和github服务器，以及edge和chrome都无法显示，icon已裁减至16*16，采用最新语法，参MDN）  
2.head标签中的内容跑到body里面，导致很多渲染不成功。已经修改为utf-8 with bom 或使用notepad++保存，仍然出现渲染标签错位的情况。（但并不影响视图）  
> re2:thanks for this tutorial vedio.i've tried those codes, and everything seemed fine on the surface,but when the browser rendered, i found the <link> and <meta>  elements moved from the head to the body. i've tried to save file with utf-8 with bom,but still doesn't work, i don't know why.  
> 检查后发现并不是浏览器渲染问题，因code中字符出错导致渲染出错。  

---
## 原型图:
![prototype](picture/首页.png "prototype")
