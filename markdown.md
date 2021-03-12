# Markdown学习

## 标题使用:一级，二级....标题

一级标题：在行首使用#+空格+编辑内容 + 回车或者ctrl + 1，二级标题使用##+空格+编辑内容 + 回车或者ctrl + 2，三级标题以此类推

## 字体：粗体，斜体

需求1：把“hello,world!”变为粗体

操作1：在hello,world!最左边和最右边各敲**或者选中hello,world!后按 ctrl + B

例子：hello,world!  --> **hello,world!**

需求2：把“hello,world!”变为斜体

操作2：在hello,world!最左边和最右边各敲*或者选中hello,world!后按 ctrl + I

例子：hello,world!  --> *hello,world!* 

需求3：把“hello,world!”变为斜体和粗体

操作3：在hello,world!最左边和最右边各敲***或者选中hello,world!后按 ctrl + B，再按ctrl + I

例子：hello,world!  -->  ***hello,world!***

需求4：把“hello,world!”变为划线删除

操作4：在hello,world!最左边和最右边各敲~~

例子：hello,world!  -->  ~~hello,world!~~

需求5：把“hello,world!”添加下划线

操作5：选中hello,world!后按ctrl + U

例子：hello,world!  -->  <u>hello,world!</u> 

## 引用

引用：摘抄别人的话，可以如下操作：行首敲上 > + 别人的话即可

> 本笔记是看b站的狂神说视频和相关弹幕学习的

## 分割线

行首使用*** + 回车或者--- + 回车

---

## 图片

![](https://i.loli.net/2021/03/12/GwbH7C2XSq4NkBF.png)

操作：行首使用英文状态下的! + [图片名] + (本地路径或者网络图片的网址)

新发现：如果发现Markdown由于是本地绝对路径的原因上传的图片在博客上无法查看，可以使用sm.ms图床工具生成网址或者在typora里面配置好PicGo文件，

简直爽到爆炸！

[typora里面配置好PicGo文件知乎链接](https://zhuanlan.zhihu.com/p/137310314)

备注：

本地路径直接可以选中最后要上传的图片，不需要一个一个把文件目录之类的敲上去了

网络图片的网址直接在浏览器里面找一张，鼠标右击图片，复制图像地址即可



![天子之子](https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1179837886,794119963&fm=26&gp=0.jpg)

## 超链接

操作:敲上[],中括号里面写上超链接名，中括号的右边写上英文状态的(),()里面写上要链接的网址。

例如：

[点击跳转到狂神说讲解Markdown的视频](https://www.bilibili.com/video/BV12J41137hu?p=6)

## 列表

### 有序列表

操作：在行首敲上1. +  空格 + 要编辑的内容 +回车

1. 高
2. 富
3. 帅

### 无序列表

操作：行首敲上- + 空格 + 要编辑的内容 + 回车

- 白
- 富
- 美

## 表格



|名字|性别|生日|
|--|--|--|
|张三|男|1998.01.19|

操作：

![image](https://i.loli.net/2021/03/12/735jSKnrfoXgC6c.png)

## 代码

操作：在键盘table键上面连续在行首敲``` + 回车 即可

```java
public class HelloJava {
    public static void main(String[] args) {
        System.out.println("Hello,Java!");
    }
}
```

## 其他

以上操作基本是Markdown在Typora上的语法应用，我们完全可以借助鼠标右键和格式之类的选项卡操作。

所有网站都支持Markdown格式，直接ctrl + A,复制粘贴就可以发送博客了，简直太棒了