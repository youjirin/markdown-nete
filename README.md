# Hello World!

* * * 
## 前言

第一次用GitHub，刚刚接触Markdown的语法。打算就用Markdown记录一下语法。

## Markdown基本语法

### 标题
> 
> 
> Markdown中标题分为六级，分别以“ # ”的个数代表标题的等级。从1~6，由大变小。
> 
> ```
> # 标题
> ## 标题
> ### 标题
> #### 标题
> ##### 标题
> ###### 标题
> ```
> 
> #### 演示效果
> 
> # 标题  
> ## 标题  
> ### 标题  
> #### 标题  
> ##### 标题  
> ###### 标题  


> ### 列表

> 列表分为两种。一种为有序列表，另一种为无序列表。无序列表行前加“ *，+，- ”,有序列表用“ 1. 2. 3. …… ”用来加以表示
> 为了避免有序列表不轻易产生，可以在句点前面加上反斜杠

> ```
> - 列1
> - 列2
> - 列3

> 1. 列1
> 2. 列2
> 3. 列3
> ```
> #### 演示效果

> - 列1  
> - 列2  
> - 列3  

> 1. 列1  
> 2. 列2  
> 3. 列3 



> ## 定义性列表

> 由定义词和解释组成。一行写上定义，另一行写上解释。解释的写法:紧跟一个或缩进(Tab)

> #### 演示效果

> ```
> Markdown
> :    轻量级文本标记语言，可以转换成html，pdf等格式（左侧有一个可见的冒号和四个不可见的空格）
> 代码块 2
> :   这是代码块的定义（左侧有一个可见的冒号和四个不可见的空格）
>         代码块（左侧有八个不可见的空格）
> ```


> Markdown
> :    轻量级文本标记语言，可以转换成html，pdf等格式（左侧有一个可见的冒号和四个不可见的空格）
> 代码块 2
> :   这是代码块的定义（左侧有一个可见的冒号和四个不可见的空格）
>         代码块（左侧有八个不可见的空格）


> ### 跳转链接与图片

> 自动链接语法结构:以比较简短的自动链接形式来处理网址和电子邮件信箱，只要是用<>包起来
> 链接的语法结构：[页面所显示的文本内容](链接的地址)
> 链接的语法结构：[页面所显示的文本内容](链接的地址 "链接标题")
> 图片的语法结构：![](图片链接地址)

> ```
> <http://github.com/>
> <address@example.com>
> 点击跳转[GitHub](https://github.com)
> 点击跳转[GitHub](https://github.com "点击前往")
> 图片1![图片1](https://www.baidu.com/img/bd_logo1.png)  
> ```

> #### 演示效果

> <http://github.com/>
> <address@example.com>
> 点击跳转[GitHub](https://github.com)
> 点击跳转[GitHub](https://github.com "点击前往")
> 图片1![图片1](https://www.baidu.com/img/bd_logo1.png)  


> ### 参考式

> 参考式链接分为两部分，文中的写法 [链接文字][链接标记]，在文本的任意位置添加[链接标记]:链接地址 “链接标题”，链接地址与链接标题前有一个空格。

> ```
> 我经常去的几个网站[Google][1]现已被墙、[百度][2]
> [GitHub][3]是一个不错的[网站][]。
> [1]:http://www.google.com "Google"
> [2]:http://www.baidu.com "百度"
> [3]:http://http://github.com "GitHub"
> [网站]:http://http://github.com  
> ```

> #### 演示效果

> 我经常去的几个网站[Google][1]现已被墙、[百度][2]
> [GitHub][3]是一个不错的[网站][]。
> [1]:http://www.google.com "Google"
> [2]:http://www.baidu.com "百度"
> [3]:http://http://github.com "GitHub"
> [网站]:http://http://github.com  


> ### 锚点

> 在想跳转到的指定标题后插入锚点{#标记}，然后在文档的anywhere写上连接到锚点的链接。 

> #### 演示效果

> ```
> ## 0. 目录{#index}
> 跳转到[目录](#index)
> ```

> ## 0. 目录{#index}
> 跳转到[目录](#index)

> ### 引用

      > 文本前加“ > ”,“ > ”与文本间有一个字符的间距。
      > 表项目内放进引用，那 > 就需要缩进

```
> 静夜思
>> 李白
> 窗前明月光，
> 疑是地上霜。
> 举头望明月，
> 低头思故乡。
```

#### 演示效果

> 静夜思  
>> 李白  
> 窗前明月光，  
> 疑是地上霜。  
> 举头望明月，  
> 低头思故乡。  


> ### 粗体和斜体

> 用“ ** ”包裹起来的文本为粗体，“ * ”包裹起来的文本所呈现的是斜体。

> ```
>    Hello world！
>   *Hello World！*  
>  **Hello World！**
> ***Hello World！***
>  ~~Hello World！~~
> ```
> #### 演示效果

> Hello world！
> *Hello World！*  
> **Hello World！**
> ***Hello World！***
> ~~Hello World！~~


> ### 代码的引用

> 单行代码用“ ` ”包裹，多行代码用“ ``` ”进行包裹。
```
`<span>Hello World！</span>`
```

```
 "```"
 <div>
	 <div>
 		 <span>Hello World!</span>	
	 </div>
  </div>
 "```"
```

> #### 演示效果

`<span>Hello World！</span>`

```
<div>
	<div>
		<span>Hello World!</span>	
	</div>
 </div>
```


> ### 表格

```
 |1|2|3|4|5|
 |:-----|-----|:-----:|-----|-----:|
 |一|二|三|四|五|
 |金|木|水|火|土|
 ```

#### 演示效果

|1|2|3|4|5|
|:-----|-----|:-----:|-----|-----:|
|一|二|三|四|五|
|金|木|水|火|土|



### 注脚

> 文字后加上脚注名字[^注脚名字],称为加注

> #### 演示效果


```
使用 Markdown[^1]可以效率的书写文档。

[^1]:Markdown是一种纯文本标记语言

```


使用 Markdown[^1]可以效率的书写文档。

[^1]:Markdown是一种纯文本标记语言


### LaTeX 公式

> $表示行内公式,$$ 表示整行公式

> #### 演示效果

> ```
圆的面积：$S=πr^2$

$$\sum_{i=1}^n a_i=0$$

$$f(x_1,x_x,\ldots,x_n) = x_1^2 &#43; x_2^2 &#43; \cdots &#43; x_n^2 $$

$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$
```


圆的面积：$S=πr^2$

$$\sum_{i=1}^n a_i=0$$

$$f(x_1,x_x,\ldots,x_n) = x_1^2 &#43; x_2^2 &#43; \cdots &#43; x_n^2 $$

$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$


### 流程图

#### 演示效果


```
flow
st=&gt;start: Start:&gt;https://www.baidu.com
io=&gt;inputoutput: verification
op=&gt;operation: Your Operation
cond=&gt;condition: Yes or No?
sub=&gt;subroutine: Your Subroutine
e=&gt;end

st-&gt;io-&gt;op-&gt;cond
cond(yes)-&gt;e
cond(no)-&gt;sub-&gt;io
`````

flow
st=&gt;start: Start:&gt;https://www.baidu.com
io=&gt;inputoutput: verification
op=&gt;operation: Your Operation
cond=&gt;condition: Yes or No?
sub=&gt;subroutine: Your Subroutine
e=&gt;end

st-&gt;io-&gt;op-&gt;cond
cond(yes)-&gt;e
cond(no)-&gt;sub-&gt;io

### 分隔线

> ```
> * * *
> ***
> *****
> - - - 
> ```
### 代码

> 行内嵌 : '',
> HTML 原始码

* * * 
