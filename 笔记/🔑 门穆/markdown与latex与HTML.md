[markdown文档](https://markdown.com.cn/basic-syntax/)

---

markdown纯文本格式编写文档，可与HTML混编，可导出 HTML、PDF 以及本身的 .md 格式的文件。
- Markdown 标题语法。 #
- Markdown 标题语法。== 号来标识一级标题， -- 号来标识二级标题。
# Heading level 1	

## Heading level 2 	 	

### Heading level 3 	 	

#### Heading level 4 	 	

##### Heading level 5 	 	

###### Heading level 6 	 	

Heading level 1
===============

Heading level 2
---------------
---
- Markdown 段落语法。要创建段落，请使用空白行将一行或多行文本进行分隔。
- Markdown 段落语法。不要用空格（spaces）或制表符（ tabs）缩进段落。
---
- Markdown 换行语法。在一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行
- Markdown 换行语法。为了兼容性，请在行尾添加“结尾空格”或 HTML 的 $<br>$ 标签来实现换行。  

This is the first line.  
And this is the second line.  

This is the first line.<br>
And this is the second line.<br>

---

- Markdown 强调语法。加粗。
- Markdown 强调语法。斜体。  
I just love **bold text**.I just love __bold text__.Love**is**bold<br>
A*cat*meow<br>

---

- 块引用

> Dorothy followed her through many of the beautiful rooms in her castle.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

---

- 列表。数字不必按数学顺序排列，但是列表应当以数字 1 起始。
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.

---

- Markdown 代码语法。

``Use `code` in your Markdown file.`` 

---

- 链接语法
* <https://markdown.com.cn>
* <fake@example.com>

See the section on [`code`](#code).

---

- 转义符语法<br>
\* Without the backslash, this would be a bullet in an unordered list.
