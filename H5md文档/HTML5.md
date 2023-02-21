

## 第一个前端程序



![image-20211122114244237](imgs\image-20211122114244237.png)



### 两步完成一个网页程序

**第一步：使用记事本，编写代码**

在E盘下保存路径`E:/itbaizhan/...`, 文件名`Welcome.html`

![image-20211120165959602](imgs\image-20211120165959602.png)

```html
<html>
	<head>
		<title>我的网页</title>
	</head>
	<body>
		Hello，我的第一个网页
	</body>
</html>
```



​	

> **注意事项**
>
> 1. 文件后缀名以`.html`结尾
> 2. 在编写代码的过程中，`<>`必须是英文状态下编写



**第二步：以浏览器方式打开**

右键打开方式，以浏览器方式打开即可

![image-20211014152648100](imgs\image-20211014152648100.png)



**实时效果反馈**

**1. 网页文件是有其特殊的后缀名规则，以下正确的是：**

<font style="background-color:rgb(233, 30, 100)">A</font>   后缀为`.txt`

<font style="background-color:rgb(255, 197, 10)">B</font>   后缀为`.html`

<font style="background-color:#8bc34a">C</font>   后缀为`Welcome`

<font style="background-color:rgb(2, 170, 244);">D</font>   后缀为`.浏览器`



**2. 以下是编写的标签，符合规范的是:**

<font style="background-color:rgb(233, 30, 100)">A</font>   `《html》《/html》`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<html><html/>`

<font style="background-color:#8bc34a">C</font>   `<html></html>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<html><html>`



**答案**

1=>B  		2=>C 









## 前端工具的选择与安装



![image-20220426211412756](imgs\image-20220426211412756.png)





### 前端常见开发者工具

工欲善其事必先利其器



#### 浏览器

浏览器是我们最重要的合作伙伴

![image-20211014155717770](imgs\image-20211014155717770.png)



> **推荐选择**
>
> 我们推荐谷歌浏览器，有两点原因：
>
> 1. 简洁大方，打开响应速度快
> 2. 开发者调试工具

![image-20211014160058579](imgs\image-20211014160058579.png)



#### 开发者工具

开发者工具有效的提高了开发效率

![image-20211017140437476](imgs\image-20211017140437476.png)



> **推荐选择**
>
> 我们推荐选择VSCode
>
> 1. 打开速度快
> 2. 使用方便

**VSCode中文语言包安装：**

扩展 → 搜索Chinese → 点击安装



**实时效果反馈**

**1. 如何安装VSCode中文语言包：**

<font style="background-color:rgb(233, 30, 100)">A</font>   扩展 → 搜索中文→ 点击安装

<font style="background-color:rgb(255, 197, 10)">B</font>   扩展 → 搜索Chinese → 点击安装

<font style="background-color:#8bc34a">C</font>   文件→ 搜索Chinese → 点击安装

<font style="background-color:rgb(2, 170, 244);">D</font>   文件→ 搜索中文 → 点击安装



**答案**

1 => B







## VScode开发者工具快捷键



![image-20211122160106255](imgs\image-20211122160106255.png)



**VSCode打开文件夹与创建文件**

1. 选择文件夹
2. 拖拽文件夹



生成浏览器文件`.html`的快捷方式

```js
! + 回车
```





**VSCode常用快捷键列表**

1. 代码格式化：`Shift+Alt+F`
2. 向上或向下移动一行：`Alt+Up 或 Alt+Down`
3. 快速复制一行代码：`Shift+Alt+Up 或 Shift+Alt+Down`
4. 快速保存：`Ctrl + S`
5. 快速查找：`Ctrl + F`
6. 快速替换：`Ctrl + H`



**实时效果反馈**

**1. VSCode快速复制一行代码的快捷键是：**

<font style="background-color:rgb(233, 30, 100)">A</font>   Shift+Alt+F

<font style="background-color:rgb(255, 197, 10)">B</font>   Ctrl + S

<font style="background-color:#8bc34a">C</font>   Alt+Up 或 Alt+Down

<font style="background-color:rgb(2, 170, 244);">D</font>   Shift+Alt+Up 或 Shift+Alt+Down



**2. VSCode快速移动一行代码快捷键:**

<font style="background-color:rgb(233, 30, 100)">A</font>   Shift+Alt+F

<font style="background-color:rgb(255, 197, 10)">B</font>   Ctrl + S

<font style="background-color:#8bc34a">C</font>   Alt+Up 或 Alt+Down

<font style="background-color:rgb(2, 170, 244);">D</font>   Shift+Alt+Up 或 Shift+Alt+Down



**答案**

1=>D  		2=>C 







## HTML5简介与基础骨架



![image-20211017170903615](imgs\image-20211017170903615.png)



### HTML5介绍


HTML5是用来描述网页的一种语言，被称为超文本标记语言。用HTML5编写的文件，后缀以`.html`结尾

HTML是一种标记语言，标记语言是一套标记标签。标签是由尖括号包围的关键字，例如：`<html>`

标签有两种表现形式：

1. 双标签，例如：`<html></html>`
2. 单标签，例如：`<img>`



### HTML5的DOCTYPE声明

DOCTYPE是`document type` (文档类型) 的缩写。`<!DOCTYPE html >`是H5的声明位于文档的最前面，处于标签之前。
他是网页必备的组成部分，避免浏览器的怪异模式。

```js
<!DOCTYPE html>
```

![image-20211014164839770](imgs\image-20211014164839770.png)



### HTML5基本骨架

![image-20211014164952540](imgs\image-20211014164952540.png)



#### html标签

定义 HTML 文档，这个元素我们浏览器看到后就明白这是个HTML文档了，所以你的其它元素要包裹在它里面，标签限定了文档的开始点和结束点。

```html
<!DOCTYPE html>
<html>
</html>
```

#### head标签

head标签用于定义文档的头部。文档的头部描述了文档的各种属性和信息，包括文档的标题、在 Web 中的位置以及和其他文档的关系等。绝大多数文档头部包含的数据都不会真正作为内容显示给读者。

```html
<!DOCTYPE html>
<html>
    <head>
    </head>
</html>
```

#### body标签

body 元素定义文档的主体。

body 元素包含文档的所有内容（比如文本、超链接、图像、表格和列表等等。）

它会直接在页面中显示出来，也就是用户可以直观看到的内容

```html
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        我会显示在浏览器中
    </body>
</html>
```

#### title标签

1. 可定义文档的标题。
2. 它显示在浏览器窗口的标题栏或状态栏上。
3. `<title>` 标签是 `<head>` 标签中唯一必须要求包含的东西，就是说写head一定要写title
4. `<title>`的增加有利于SEO优化

> SEO是搜索引擎优化的英文缩写。通过对网站内容调整，满足搜索引擎的排名需求


```html
<!DOCTYPE html>
<html>
    <head>
        <title>第一个页面</title>
    </head>
    <body>
        我会显示在浏览器中
    </body>
</html>
```

#### meta标签

meta标签用来描述一个HTML网页文档的属性，关键词等，例如：`charset="utf-8"`是说当前使用的是`utf-8`编码格式，在开发中我们经常会看到`utf-8`，或是`gbk`，这些都是编码格式，通常使用`utf-8`。

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>itbaizhan</title>
    </head>
    <body>
    </body>
</html>
```



**实时效果反馈**

**1. 下列哪些标签书写格式是正确的是：**

<font style="background-color:rgb(233, 30, 100)">A</font>   《html》

<font style="background-color:rgb(255, 197, 10)">B</font>   <!html>

<font style="background-color:#8bc34a">C</font>   html

<font style="background-color:rgb(2, 170, 244);">D</font>   `<html>`



**2.  以下组成HTML5基础骨架标签正确的是:**

<font style="background-color:rgb(233, 30, 100)">A</font>   `<html>、<body>、<head>、<div>、<meta>`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<html>、<body>、<DOCTYPE>、<title>、<meta>`

<font style="background-color:#8bc34a">C</font>   `<html>、<body>、<head>、<title>、<meta>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<html>、<body>、<!DOCTYPE html>、<title>、<meta>`



**答案**

1=>D  		2=>C 











## 标签之标题



![image-20211120171417126](imgs\image-20211120171417126.png)



### 标题介绍与应用

标题（Heading）是通过 `<h1> - <h6> `标签进行定义的。

`<h1>`定义最大的标题   `<h6>`定义最小的标题

```html
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
<h4>四级标题</h4>
<h5>五级标题</h5>
<h6>六级标题</h6>
```



> 生成h1~h6快捷键：h$*6



### VSCode插件

快速打开浏览器

扩展 -> 搜索open in browser -> 点击安装



**正确使用标题**

请确保将 HTML 标题标签只用于标题。

不要仅仅是为了生成粗体或大号的文本而使用标题。

正确使用标题有益于SEO

应该将`< h1>` 用作主标题（最重要的），其后是 `<h2>`（次重要的），再其次是 `<h3>`，以此类推



![image-20211014171609998](imgs\image-20211014171609998.png)



**标题标签位置摆放**

在标签中添加属性：`align="left | center | right"` 默认居左

![image-20211017140517014](imgs\image-20211017140517014.png)



 

**实时效果反馈**

**1. 以下那个是三级标题标签：**

<font style="background-color:rgb(233, 30, 100)">A</font>   `<h1></h1>`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<h2></h2>`

<font style="background-color:#8bc34a">C</font>   `<h3></h3>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<h4></h4>`



**2.  标题标签居中摆放属性使用正确的是:**

<font style="background-color:rgb(233, 30, 100)">A</font>   `align="left | center | right"`

<font style="background-color:rgb(255, 197, 10)">B</font>   `align="left"`

<font style="background-color:#8bc34a">C</font>   `align="center"`

<font style="background-color:rgb(2, 170, 244);">D</font>   `align="right"`



**答案**

1=>C  		2=>C 









## 标签之段落、换行、水平线



![image-20211120171852680](imgs\image-20211120171852680.png)



### 标签之段落

段落是通过`<p>`标签定义的

```html
<p>这是一个段落 </p> 
<p>这是另一个段落</p>
```



![image-20211017125215977](imgs\image-20211017125215977.png)



### 换行

如果您希望在不产生一个新段落的情况下进行换行（新行），请使用 `<br>`

`<br />` 元素是一个空的 HTML 元素。

```html
<p>这个<br>段落<br>演示了分行的效果</p>
```

![image-20211014175748915](imgs\image-20211014175748915.png)



### 水平线

`<hr/>`标签在 HTML 页面中创建水平线

```html
<hr color="" width="" size="" align=""/>
```

属性：

1. color：设置水平线的颜色
2. width：设置水平线的宽度
3. size：设置水平线的高度
4. align：设置水平线的对齐方式（默认居中），可取值left|right



**实时效果反馈**

**1. 要实现一个文本换行，可以使用以下那个标签：**

<font style="background-color:rgb(233, 30, 100)">A</font>   `<p>`标签

<font style="background-color:rgb(255, 197, 10)">B</font>   `<hr>`标签

<font style="background-color:#8bc34a">C</font>   `<br>`标签

<font style="background-color:rgb(2, 170, 244);">D</font>   `<img>`标签



**2.  承载段落文本信息使用以下那个标签:**

<font style="background-color:rgb(233, 30, 100)">A</font>   `<p>`标签

<font style="background-color:rgb(255, 197, 10)">B</font>   `<hr>`标签

<font style="background-color:#8bc34a">C</font>   `<br>`标签

<font style="background-color:rgb(2, 170, 244);">D</font>   `<img>`标签



**答案**

1=>C  		2=>A 











## 标签之图片



![image-20211017175408325](imgs\image-20211017175408325.png)



### 网站中最多的元素

网站中最多的元素毋庸置疑，一定是图片

`<img>` 标签定义 HTML 页面中的图像

```html
<img src="" alt="" title="" width="" height="">
```



> **注意事项**
>
> `<img>`是单标签，不需要进行闭合操作



属性：

1. src：路径（图片地址与名字）
2. alt：规定图像的替代文本
3. width：规定图像的宽度
4. height：规定图像的高度
5. title：鼠标悬停在图片上给予提示



**实时效果反馈**

**1. `<img>`标签中alt属性的作用：**

<font style="background-color:rgb(233, 30, 100)">A</font>   规定图像的替代文本

<font style="background-color:rgb(255, 197, 10)">B</font>   鼠标悬停在图片上给予提示

<font style="background-color:#8bc34a">C</font>   路径（图片地址与名字）

<font style="background-color:rgb(2, 170, 244);">D</font>   规定图像的宽度和高度



**2.  以下那个不是`<img>`标签的属性：**

<font style="background-color:rgb(233, 30, 100)">A</font>   src

<font style="background-color:rgb(255, 197, 10)">B</font>   alt

<font style="background-color:#8bc34a">C</font>   title

<font style="background-color:rgb(2, 170, 244);">D</font>   href



**答案**

1=>A  		2=>D 









## 图片路径详解



![image-20211120172729161](imgs\image-20211120172729161.png)



### 绝对路径

绝对路径是电脑的盘符存储与访问的具体地址

```html
E:\itbaizhanCode\1.jpg
```

```html
<img src="E:\itbaizhanCode\1.jpg">
```



### 相对路径

两者相对关系，两者在同⼀路径下可以直接访问

1. 子级关系: `/`

2. 父级关系: `../`

3. 同级关系: `./`（可以省略）

   

### 网络路径

具体的⽹络地址: http://iwenwiki.com/api/newworld/images/n1.png







**实时效果反馈**

**1. 以下那个是相对路径：**

<font style="background-color:rgb(233, 30, 100)">A</font>   `E:\itbaizhanCode\1.jpg`

<font style="background-color:rgb(255, 197, 10)">B</font>   `http://iwenwiki.com/api/newworld/images/n1.png`

<font style="background-color:#8bc34a">C</font>   `../images/1.jpg`

<font style="background-color:rgb(2, 170, 244);">D</font>   `C:\itbaizhanCode\2.jpg`



**2.  以下关于相对路径描述正确的是：**

<font style="background-color:rgb(233, 30, 100)">A</font>   相对路径是电脑的盘符存储与访问的具体地址

<font style="background-color:rgb(255, 197, 10)">B</font>   相对路径是两者相对关系，两者在同⼀路径下可以直接访问

<font style="background-color:#8bc34a">C</font>   相对路径是具体的⽹络地址

<font style="background-color:rgb(2, 170, 244);">D</font>   相对路径是不存在的



**答案**

1=>C  		2=>B 









## 标签之超文本链接



![image-20211120173236840](imgs\image-20211120173236840.png)



### 超链接描述

HTML使用标签 `<a>`来设置超文本链接

超链接可以是一个字，一个词，或者一组词，也可以是一幅图像，您可以点击这些内容来跳转到新的文档

```html
<a href="url">链接文本</a>
```





### 超链接属性

在标签`<a> `中使用了`href`属性来描述链接的地址

默认情况下，链接将以，以下形式出现在浏览器中：

1. 一个未访问过的链接显示为蓝色字体并带有下划线。

2. 访问过的链接显示为紫色并带有下划线。

3. 点击链接时，链接显示为红色并带有下划线。

   

> **特别提示**
>
> 后期我们会通过CSS样式修改掉这些效果





### 超链接表现

当您把鼠标指针移动到网页中的某个链接上时，箭头会变为一只小手

![image-20211017141221711](imgs\image-20211017141221711.png)







**实时效果反馈**

**1. 超链接的作用是**

<font style="background-color:rgb(233, 30, 100)">A</font>   跳转到新的文档

<font style="background-color:rgb(255, 197, 10)">B</font>   显示图片的标签

<font style="background-color:#8bc34a">C</font>   显示段落的标签

<font style="background-color:rgb(2, 170, 244);">D</font>   显示标题的标签



**2.  超链接中`href`属性的作用**

<font style="background-color:rgb(233, 30, 100)">A</font>   设置超链接的宽度和高度

<font style="background-color:rgb(255, 197, 10)">B</font>   设置超链接的跳转地址

<font style="background-color:#8bc34a">C</font>   设置超链接的显示颜色

<font style="background-color:rgb(2, 170, 244);">D</font>   设置超链接的文本内容



**答案**

1 =>A 	2=>B 









## 标签之文本



![image-20211120173736274](imgs\image-20211120173736274.png)



### 常用文本标签

|    标签    |        描述        |
| :--------: | :----------------: |
|   `<em>`   |    定义着重文字    |
|   `<b>`    |    定义粗体文本    |
|   `<i>`    |     定义斜体字     |
| `<strong>` |    定义加重语气    |
|  `<del>`   |     定义删除字     |
|  `<span>`  | 元素没有特定的含义 |



> **特别提示**
>
> 常用文本标签和段落是不同的，段落代表一段文本，而文本标签一般表示文本词汇





**实时效果反馈**

**1. 定义加重语气的标签是哪一个：**

<font style="background-color:rgb(233, 30, 100)">A</font>   `em`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<i>`

<font style="background-color:#8bc34a">C</font>   `<del>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<strong>`



**2.  定义着重文字的标签是哪一个：**

<font style="background-color:rgb(233, 30, 100)">A</font>   `em`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<i>`

<font style="background-color:#8bc34a">C</font>   `<del>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<strong>`



**答案**

1=>D  		2=>A 









## 列表标签之有序列表



![image-20211120174415921](imgs\image-20211120174415921.png)





### 有序列表

有序列表是一列项目，列表项目使用数字进行标记。 有序列表始于` <ol>` 标签。每个列表项始于 `<li> `标签。

```html
<ol>
    <li>尚学堂</li>
    <li>百战程序员</li>
</ol>
```



![image-20211017132005211](imgs\image-20211017132005211.png)



### type属性

`<ol>`的属性type 拥有的选项

1. 1   表示列表项目用数字标号（1,2,3...）
2. a   表示列表项目用小写字母标号（a,b,c...）
3. A  表示列表项目用大写字母标号（A,B,C...）
4. i   表示列表项目用小写罗马数字标号（i,ii,iii...）
5. I   表示列表项目用大写罗马数字标号（I,II,III...）



### 有序列表嵌套

列表是可以进行嵌套的

```html
<ol>
    <li>尚学堂</li>
    <li>
        <ol>
            <li>阿里</li>
            <li>京东</li>
        </ol>
    </li>
    <li>百战程序员</li>
</ol>
```







**实时效果反馈**

**1. 有序列表展示效果以下那个描述是正确的：**

<font style="background-color:rgb(233, 30, 100)">A</font>   展示一个段落效果

<font style="background-color:rgb(255, 197, 10)">B</font>   展示一个无序的列表效果

<font style="background-color:#8bc34a">C</font>   展示一个有序的列表效果

<font style="background-color:rgb(2, 170, 244);">D</font>   展示一个加粗的文本效果



**2.  有序列表的标签组合正确的是：**

<font style="background-color:rgb(233, 30, 100)">A</font>   `<ul> + <li>`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<ol> + <li>`

<font style="background-color:#8bc34a">C</font>   `<h1> + <li>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<img> + <li>`



**答案**

1=>C  		2=>B 









## 列表标签之无序列表



![image-20211120174927373](imgs\image-20211120174927373.png)



### 无序列表实现

无序列表是一个项目的列表，此列项目使用粗体圆点（典型的小黑圆圈）进行标记

无序列表始于 `<ul>` 标签。每个列表项始于` <li>` 标签。

```html
<ul>
    <li>尚学堂</li>
    <li>百战程序员</li>
</ul>
```



### type属性

`<ul>`的属性type 拥有的选项

- disc 默认实心圆

- circle 空心圆

- square 小方块

- none 不显示



### 无序列表嵌套

列表是可以进行嵌套的

```html
<ul>
    <li>尚学堂</li>
    <li>
        <ul>
            <li>阿里</li>
            <li>京东</li>
        </ul>
    </li>
    <li>百战程序员</li>
</ul>
```



### 常见应用场景

1. 无序的列表效果
2. 导航效果



### 导航效果

```html
<ul>
    <li>Xiaomi手机</li>
    <li>Redmi 红米</li>
    <li>电视</li>
    <li>笔记本</li>
</ul>
```



![image-20211016124431658](imgs\image-20211016124431658.png)



> **快捷键**
>
> 快速生成ul+li的布局：ul>li*3（数字根据自己的需要的li数量修改）



**实时效果反馈**

**1. 无序列表的type属性以下描述错误的是：**

<font style="background-color:rgb(233, 30, 100)">A</font>   disc 默认实心圆

<font style="background-color:rgb(255, 197, 10)">B</font>   circle 空心圆

<font style="background-color:#8bc34a">C</font>   square 小方块

<font style="background-color:rgb(2, 170, 244);">D</font>   triangle 三角形



**2.  无序列表的标签组合正确的是：**

<font style="background-color:rgb(233, 30, 100)">A</font>   `<ul> + <li>`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<ol> + <li>`

<font style="background-color:#8bc34a">C</font>   `<h1> + <li>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<img> + <li>`



**答案**

1=>D  		2=>A 







## 标签之表格



![image-20211120180329440](imgs\image-20211120180329440.png)



### 表格展示效果

表格在数据展示方面非常简单，并且表现优秀



![image-20211016145021813](imgs\image-20211016145021813.png)



> **表格组成与特点**
>
> 行、列、单元格 
>
> 单元格特点：同行等高、同列等宽。
>
> ---
>
> **表格标签**
>
> 表格：`<table>`
>
> 行：`<tr>`
>
> 单元格(列)：`<td>`

```html
<table>
    <tr>
        <td>尚学堂</td>
        <td>百战程序员</td>
    </tr>
    <tr>
        <td>阿里</td>
        <td>京东</td>
    </tr>
</table>
```



> **快捷键**
>
> 快速生成表格结构：table>tr*2>td{单元格}



### 表格属性

1. border：设置表格的边框
2. width：设置表格的宽度
3. height：设置表格的高度





**实时效果反馈**

**1. 以下那个是表格组成标签组合：**

<font style="background-color:rgb(233, 30, 100)">A</font>   table + tr + td

<font style="background-color:rgb(255, 197, 10)">B</font>   table + tr + dl

<font style="background-color:#8bc34a">C</font>   ul + tr + td

<font style="background-color:rgb(2, 170, 244);">D</font>   ul + table + tr



**2.  以下代码，空格处要填写的标签：**

```html
<table>
    ___
        <td>尚学堂</td>
        <td>百战程序员</td>
    ___
</table>
```

<font style="background-color:rgb(233, 30, 100)">A</font>   `<th>` `</th>`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<tbody>` `</tbody>`

<font style="background-color:#8bc34a">C</font>   `<td>` `</td>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<tr>` `</tr>`



**答案**

1=>A  		2=>D 







## 表格单元格合并



![image-20211124111834625](imgs\image-20211124111834625.png)





### 单元格合并属性



![image-20211124133917914](imgs\image-20211124133917914.png)



- 水平合并：colspan
- 垂直合并：rowspan

```html
<table border="1" width="500px" height="200px">
    <tr>
        <td colspan="3">单元格1单元格2单元格3</td>
        <td>单元格4</td>
        <td>单元格5</td>
    </tr>
    <tr>
        <td rowspan="2">单元格6-11</td>
        <td>单元格7</td>
        <td rowspan="3">单元格81318</td>
        <td colspan="2" rowspan="2">单元格9101415</td>
    </tr>
    <tr>
        <td>单元格12</td>
    </tr>
    <tr>
        <td>单元格16</td>
        <td>单元格17</td>
        <td>单元格19</td>
        <td>单元格20</td>
    </tr>
</table>
```





**实时效果反馈**

**1. 下列那个是单元格垂直合并的属性：**

<font style="background-color:rgb(233, 30, 100)">A</font>   border

<font style="background-color:rgb(255, 197, 10)">B</font>   align

<font style="background-color:#8bc34a">C</font>   colspan

<font style="background-color:rgb(2, 170, 244);">D</font>   rowspan



**答案**

1=>D  	







## Form表单



![image-20211124172703466](imgs\image-20211124172703466.png)





表单在 Web 网页中用来给用户填写信息，从而能采用户信息，使网页具有交互的功能。

所有的用户输入内容的地方都用表单来写，如登录注册、搜索框

<img src="imgs\image-20211124143834115.png" alt="image-20211124143834115" style="zoom:50%;" />

表单是由容器和控件组成的,一个表单一般应该包含用户填写信息的输入框,按钮等，这些输入框,按钮叫做控件,表单就是容器,它能够容纳各种各样的控件

```html
<form action="url" method="get|post" name="myform"></form>
```

> **属性说明**
>
> action服务器地址
>
> name表单名称
>
> **method中Get和Post的区别**
>
> 1. 数据提交方式，get把提交的数据url可以看到，post看不到
> 2. get一般用于提交少量数据，post用来提交大量数据



### 表单元素

一个完整的表单包含三个基本组成部分：表单标签、表单域、表单按钮

1. 表单标签
2. 表单域
3. 表单按钮

```html
<form>
    <input type="text">
    <input type="submit">
</form>
```



**实时效果反馈**

**1.以下哪个元素不是表单元素：**

<font style="background-color:rgb(233, 30, 100)">A</font>   表单标签

<font style="background-color:rgb(255, 197, 10)">B</font>   表单域

<font style="background-color:#8bc34a">C</font>   表单按钮

<font style="background-color:rgb(2, 170, 244);">D</font>   图片



**答案**

1=>D  









## 表单元素



![image-20211124173247447](imgs\image-20211124173247447.png)



### 文本框

文本域通过`<input type="text">` 标签来设定，当用户要在表单中键入字母、数字等内容时，就会用到文本域

```html
<form>
    First name: <input type="text" name="firstname">
    <br>
    Last name: <input type="text" name="lastname">
</form>
```

![image-20211124145315178](imgs\image-20211124145315178.png)



### 密码框

密码字段通过标签`<input type="password">` 来定义

```html
<form>
    Password: <input type="password" name="pwd">
</form>
```

![image-20211124145447289](imgs\image-20211124145447289.png)



> **温馨提示**
>
> 密码字段字符不会明文显示，而是以星号或圆点替代



### 提交按钮

当用户单击确认按钮时，表单的内容会被传送到另一个文件。表单的动作属性定义了目的文件的文件名。由动作属性定义的这个文件通常会对接收到的输入数据进行相关的处理

```html
<form name="input" action="url" method="get">
    Username: <input type="text" name="user">
    <input type="submit" value="Submit">
</form>
```

![image-20211124150330131](imgs\image-20211124150330131.png)





**实时效果反馈**

**1.设置输入框为密码框，type属性应该填写内容：**

<font style="background-color:rgb(233, 30, 100)">A</font>   text

<font style="background-color:rgb(255, 197, 10)">B</font>   password

<font style="background-color:#8bc34a">C</font>   radio

<font style="background-color:rgb(2, 170, 244);">D</font>   name



**答案**

1=>B









## 块元素与行内元素（内联元素）



![image-20211126104646087](imgs\image-20211126104646087.png)



HTML5出现之前，经常把元素按照块级元素和内联元素来区分。在HTML5中，元素不再按照这种⽅式来区分， 而是按照内容模型来区分，分为元数据型(metadata content)、区块型(sectioning content)、标题型(heading content)、文档流型(flow content)、语句型(phrasing content)、内嵌型(embedded content)、交互型 (interactive content)。元素不属于任何⼀个类别，被称为穿透的，元素可能属于不止⼀个类别，称为混合的



![Content_categories_venn](imgs\Content_categories_venn.png)



详细参考地址：https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/Content_categories 



虽然到了HTML5的版本，元素分类更细致了，但是这对初学者并不友好,所以我们仍然按照块元素和内联元素做区分，这对我们的布局起到了至关重要的作用



内联元素和块级元素的区别 

|                   块级元素                   |                   内联元素                   |
| :------------------------------------------: | :------------------------------------------: |
| 块元素会在页面中独占一行（自上向下垂直排列） | 行内元素不会独占页面中的一行，只占自身的大小 |
|          可以设置width，height属性           |      行内元素设置width，height属性无效       |
|  ⼀般块级元素可以包含行内元素和其他块级元素  |    ⼀般内联元素包含内联元素不包含块级元素    |



常见块级元素

> div、form、h1~h6、hr、p、table、ul、等



常见内联元素(行内元素)

> a、b、em、i、span、strong等 



行内块级元素（特点：不换行、能够识别宽高）

> button、img、input等 





**实时效果反馈**

**1.下列关于元素分类描述错误的是：**

<font style="background-color:rgb(233, 30, 100)">A</font>   块元素会在页面中独占一行,行内元素不会独占页面中的一行，只占自身的大小

<font style="background-color:rgb(255, 197, 10)">B</font>   块元素可以设置width，height属性,行内元素设置width，height属性无效

<font style="background-color:#8bc34a">C</font>   ⼀般块级元素可以包含行内元素和其他块级元素,⼀般内联元素包含内联元素不包含块级元素 

<font style="background-color:rgb(2, 170, 244);">D</font>   块元素可以设置大小,不会独占一行,行内元素无法无法设置大小,但是会独占一行



**答案**

1=>D  







## HTML5新增标签



![image-20211126170309621](imgs\image-20211126170309621.png)



`HTML5`是`HTML`最新的修订版本，2014年10月由万维网联盟`（W3C）`完成标准制定

在`HTML5`出现之前，我们一般采用`DIV+CSS`布局我们的页面。但是这样的布局方式不仅使我们的文档结构不够清晰，而且**不利于搜索引擎爬虫对我们页面的爬取**。为了解决上述缺点，`HTML5`新增了很多新的语义化标签





### 扩展知识

`div`容器元素，也是页面中见到的最多的元素



div实现

![image-20211126150749756](imgs\image-20211126150749756.png)



H5新标签实现

![image-20211126150757403](imgs\image-20211126150757403.png)





**H5新标签**

1. `<header></header>`  头部
2. `<nav></nav>`  导航
3. `<section></section>`定义文档中的节,比如章节、页眉、页脚
4. `<aside></aside>`  侧边栏
5. `<footer></footer>` 脚部
6. `<article></article>`  代表一个独立的、完整的相关内容块,例如一篇完整的论坛帖子，一篇博客文章，一个用户评论等



**实时效果反馈**

**1.下列哪个不属于HTML5的新增标签**

<font style="background-color:rgb(233, 30, 100)">A</font>   `<header></header>`

<font style="background-color:rgb(255, 197, 10)">B</font>   `<div></div>`

<font style="background-color:#8bc34a">C</font>   `<footer></footer>`

<font style="background-color:rgb(2, 170, 244);">D</font>   `<nav></nav>`



**答案**

1=>B  
