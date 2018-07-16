##<center> 目录

###基本语法点

* [基本常识](#user_basic)
* [加粗](#use_strong)
* [斜体](#use_italiy)
* [链接](#use_link)
* [图片](#use_pic)
* [锚点(局内跳转)](#use_maidian)
* [列表](#use_list)
* [块引用](#block_quote)
* [代码区](#code_block)
* [inline_code](#inline_code)
* [水平线](#horizontal_rules)
* [表格](#use_table)



<a name = "user_basic"> </a> **BASIC**  
````
标题 用#表示 ，字符串用 ``,多行字符串用 ```  ```
````

 <a name="use_strong"></a> **加粗**:
`**strong**` or `__strong__`  **快捷键**:`command+B`

 <a name="use_italiy"></a>**斜体**:
`*斜体*` or  _斜体_     **快捷键**：`command+I`

 <a name="use_link"></a>**链接**:
`[名称](url地址)` 例如 `[百度](https:www.baiddu.com)` [百度](https:www.baidu.com)  <br>
还有一种变形 `[名称][id]` 然后在后面实现`[id]:http:www.XXX.com`
如`[百度][baiduId]` [百度][baiduId] <br> 
`[baiduId]: https:www.baidu.com`
 [baiduId]:https:www.baidu.com

<a name="use_pic"></a>**图片**： 
 `![名称](图片url)` 例如 `![MacDown图片](http://www.iconpng.com/png/free-blue-clouds/sexy_girl.png)`  ![macDow图片](http://www.iconpng.com/png/free-blue-clouds/sexy_girl.png)
 
 ![动态图片](https://blog.ibireme.com/wp-content/uploads/2015/11/bench_gif_demo.gif)
 

<a name="use_maidian"></a>**锚点**：
跳转到当页的某处 `[名称](#className)`<br>
 例如 `[锚点](#maodian)` [加粗锚点](#use_strong) 还要实现锚点的声明 `<a name= className></a>` 如 `<a name= use_strong> </a>`

<a name="use_list"></a>**List列表**

* 列表
* 列表2  `*+空格+xxxx`
	* 次级列表 
	* 次级列表2 `tab+*+空格+xxxx`
		1. 三级列表
		2. 三级列表2 `tab+tab+1.+XXXX`
		
		
源代码：

```
* 列表
* 列表2  `*+空格+xxxx`
	* 次级列表 
	* 次级列表2 `tab+*+空格+xxxx`
		1. 三级列表
		2. 三级列表2 `tab+tab+1.+XXXX`
```


<a name="block_quote"></a>**blcok quote(块引用)** 
> 使用`>`可以缩进一列  
> 敲击回车键，自动生成下一行
> > 使用`> >`可以进行二级缩进
> > > 三级缩进 `> > >`依次类推


<a name="inline_code"></a>**inline code**  

如果你想展示 一个`` ` ``,你需要用比你展示的多一个`` ` ``,例如想展示`` ` ``,你的代码应该是``` `` ` `` ```,你想展示 ``` `` ```,你的代码是
```` ``` `` ``` ````， 依次类推。

<a name="horizontal_rules"></a>**水平线** 

粗水平线可以用`***`，但是需要注意`***`需要另起一行
***

细水平线也可以用 `---`,也需要另起一行
---

<a name="code_block"> </a>**代码块** 

多行代码块可以用 ```` ```  ````来实现
同时可以用首行缩进 一个(或者多个)`tab`来实现
eg.

````
这是一个代码块用的是``` ```的方法
````

	这是一个用tab缩进的方法
		这是一个用2个tab缩进的方法

<a name= "use_table"></a>**表格Table**	 	

左对齐(`:`放在左边) | 居中对齐(默认或者`:`放在两边) | 右对齐（`:`放在右边）
:-----------------|:-------------------------:|--------------------:
   这是左对齐的     |				  这是居中对齐    |       这是右对齐       |


	方法名			|		代码			    |       效果              |
	-------------|-----------------------|-------------------------|
	斜体			|`*斜体1*` `<em>斜体2</em>`|    <em>斜体1</em>  *斜体2* |
	删除线			|	`<del>删除线</del>`  |    <del>删除线</del>      |
	下划线			| `<u>下划线</u>` 		|    <u>下划线</u>          |
	双引号			|  `<q>双引号</q>`		|     <q>双引号</q>         |
	高亮			|  `<mark>高亮</mark>`	|   <mark>高亮</mark>       | 
	上标			|  `上标<sup>TMD</sup>`	|   上标<sup>TMD</sup>      |
	注释索引		|  `悟已往之不谏[^谏]`    |   悟已往之不谏[^谏]        |
		





###注释
[^谏]: 古意 谏止，劝止的意思





