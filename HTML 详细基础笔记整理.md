#  HTML 详细基础笔记整理

- 可以使用 HTML 来建立自己的 WEB 站点，HTML 运行在浏览器上，由浏览器来解析。
- HTML 很容易学习

------

## HTML 教程

> **HTML**的英语是：**HyperText Markup Language**，简称：HTML，中文叫做**超文本标记语言**，是一种用于创建网页的标准标记语言，你通过**浏览器**访问的所有主流网页，包括淘宝，京东，腾讯网，网易等都是基于HTML创建的。
>
> ![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/7f9ee00c-a3bc-4c8f-a6d0-eda905184cfa/kuangstudy98f0b39d-16d4-4425-b080-fdf9ce24a01f.png?resizeSmall&width=832)

### HTML 代码预览

```
<!DOCTYPE html><html><head><title>这是网页的标题！</title><metacharset="UTF-8"/></head><body><h1>Hello World</h1><p>今天我们学习了<h1>标签 ©</p></body></html>
```

**注意**：对于中文网页需要使用 <meta charset="utf-8"> 声明编码，否则会出现乱码。有些浏览器（如 360 浏览器）会设置 GBK 为默认编码，则你需要设置为 **utf-8**

### HTML 文档的后缀名



![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/dd95a5e2-8966-41f6-b884-b8e247b7a272/kuangstudyfa83c6de-449f-41ad-bf80-4d1c9b9a29b1.png?resizeSmall&width=832)



### 总结

- HTML Hypertext Markup Language

- 超文本标记语言

- 超文本：图片，视频，链接

- 标记：标签

- 一对尖括号括起来的：<标签名>

- 一般是成对出现的

- `<h1>Hello World</h1>`

- 标准格式
  `<html><head></head><body><h1>Hello World<h1></body></html>`

- HTML对换行，制表不敏感

- head中的内容不会在网页中看见

- body中的内容是可见的

- title：网页的标题标签

  ## HTML 简介

  ### HTML 实例

  ```
  <!DOCTYPE html><html><head><title>这是网页的标题！</title><metacharset="UTF-8"/></head><body><h1>Hello World</h1><p>今天我们学习了<h1>标签 ©</p></body></html>
  ```

  ### 解析

- `<!DOCTYPE html>` 声明为 HTML5 文档

- `<html>` 元素是 HTML 页面的根元素

- `<head>` 元素包含了文档的元（meta）数据，如 `<meta charset=“utf-8”>`定义网页编码格式为 utf-8。

- `<title>` 元素描述了文档的标题
  -`<body>` 元素包含了可见的页面内容

- `<h1>` 元素定义一个大标题
  -`<p>`元素定义一个段落

  ### 什么是HTML?

  **HTML 是用来描述网页的一种语言。**

- HTML 指的是超文本标记语言: HyperText Markup Language

- HTML 不是一种编程语言，而是一种标记语言

- 标记语言是一套标记标签 (markup tag)

- HTML 使用标记标签来描述网页

- HTML 文档包含了HTML 标签及文本内容

- HTML文档也叫做 web 页面

- HTML 标签

- HTML 标记标签通常被称为 HTML

  ### 标签 (HTML tag)

- HTML 标签是由尖括号包围的关键词，比如 <html>

- HTML 标签通常是成对出现的，比如 `<b> 和 </b>`

- 标签对中的第一个标签是开始标签，第二个标签是结束标签

- 开始和结束标签也被称为开放标签和闭合标签

  > 
  >
  > **<标签>内容</标签>**
  >
  > 

### HTML 元素

**“HTML 标签” 和 “HTML 元素” 通常都是描述同样的意思.**

但是严格来讲, 一个 HTML 元素包含了开始标签与结束标签，如下实例:

HTML 元素:

> <p>这是一个段落。</p>

### Web 浏览器

Web浏览器（如谷歌浏览器，Internet Explorer，Firefox，Safari）是用于**读取HTML文件**，并将其作为网页显示。

浏览器并不是直接显示的HTML标签，但可以使用标签来决定如何**展现HTML页面的内容给用户**：

### HTML 网页结构

下面是一个可视化的HTML页面结构：

```
<html><head><title>页面标题</title></head><body><h1>这是一个一级标题</h1><p>这是一个段落。</p><p>这是另外一个段落。</p></body></html>
```

> **只有 <body> 区域才会在浏览器中显示。

### HTML版本和发展历史

| 版本      | 发布时间 |
| :-------- | :------- |
| HTML      | 1991     |
| HTML+     | 1993     |
| HTML 2.0  | 1995     |
| HTML 3.2  | 1997     |
| HTML4     | 1999     |
| XHTML 1.0 | 2000     |
| HTML5     | 2012     |
| XHTML5    | 2013     |

### <!DOCTYPE> 声明

识别网页的版本
doctype声明

> HTML4.01
> <!DOCTYPE HTML PUBLIC “-//W3C//DTD HTML 4.01//EN” “http://www.w3.org/TR/html4/strict.dtd"%3E
>
> XHTML1.0
> <!DOCTYPE html PUBLIC “-//W3C//DTD XHTML 1.0 Strict//EN” “http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"%3E
>
> HTML5
>
> <!DOCTYPE html>

------

## HTML 编辑器

### HTML 编辑器推荐

可以使用专业的 HTML 编辑器来编辑 HTML

------

## HTML 基础

HTML 教程- 4个实例

### HTML 标题

HTML 标题（Heading）是通过 **`<h1> - <h6>`** 标签来定义的.

```
<h1>这是一个标题</h1><h2>这是一个标题</h2><h3>这是一个标题</h3>
```

### HTML 段落

HTML 段落是通过标签 **`<p>`** 来定义的.

```
<p>这是一个段落。</p><p>这是另外一个段落。</p>
```

**空白折叠现象**：在HTML中，字符之间有再多的空格、换行，浏览器也只会当成一个空格解析

### HTML 链接

HTML 链接是通过标签`<a>` 来定义的.

> <a href="https://www.axihe.com"> 这是一个链接 <a>

提示:在 href 属性中指定链接的地址。

### HTML 图像

HTML 图像是通过标签 **`img`**来定义的.

### 总结

```
<!doctype html><html><head><title>这是网页的标题</title><metacharset="UTF-8"></head><body><!-- 这是h1标签，他表示一级标题 --><h1>一级标题</h1><h2>二级标题</h2><h3>三级标题</h3><h4>四级标题</h4><h5>五级标题</h5><h6>六级标题</h6><p>联播+10月16日，中华人民  共和国<br>成立70周年庆祝活动总结会议在京举行。习近平总书记在人民大会堂亲切会见庆祝活动筹办工作有关方面代表，向他们表示衷心感谢和诚挚问候，对他们在工作中取得的优异成绩给予充分肯定，勉励大家奋发有为、再立新功。</p><p>a<b>c</p><hr><imgsrc="../image/aaa/Koala.jpg"alt="这是一只考拉"></body></html>
```

> HTML的注释
> <!-- 注释的内容 -->

- meta：自结束标签
- 属性名=”属性值”
- key value
- 乱码问题
- 编码<meta charset="UTF-8">
- HTML是负责描述文档语义的语言
- h1标签有什么作用？
- 给文本增加一级标题的语义
- 错：给字体加粗，让字体变大
- h1,h2,h3常用
- 段落标签
- p
- 空白折叠现象：在HTML中，字符之间有再多的空格、换行，浏览器也只会当成一个空格解析
- 转意字符：
  ( &l t; &g t; & nbsp; & copy;)
- br
- hr
- img
- 相对路径：
- 绝对路径：
- HTML语法规范
- HTML不区分大小写 一般都小写
- 注释不能嵌套
- 自结束标签

------

## HTML 元素

### HTML 元素

HTML 文档由 HTML 元素定义。

| 开始标签 *               | 元素内容     | 结束标签 * |
| :----------------------- | :----------- | :--------- |
| `<p>`                    | 这是一个段落 | `</p>`     |
| `<a href=“default.htm”>` | 这是一个链接 | `</a>`     |
| <br>                     | 换行         |            |

> 开始标签常被称为**起始标签（opening tag）**，结束标签常称为**闭合标签（closing tag）**。
>
> ### HTML 元素语法

- HTML 元素以**开始标签**起始
- HTML 元素以**结束标签**终止
- **元素的内容**是开始标签与结束标签之间的内容
- 某些 HTML 元素具有**空内容（empty content）**
- 空元素**在开始标签中进行关闭**（以开始标签的结束而结束）
- 大多数 HTML 元素可拥有**属性**

------

## HTML 属性

### HTML 属性

------

属性是 HTML 元素提供的附加信息。

------

### HTML 属性

- HTML 元素可以设置**属性**
- 属性可以在元素中添加**附加信息**
- 属性一般描述于**开始标签**
- 属性总是以名称/值对的形式出现，**比如：`name=“value”`**。

------

### 属性实例

HTML 链接由 标签定义。链接的地址在 **`href` 属性**中指定：

### 实例

```
<ahref="https://www.axihe.com">这是一个链接</a>
```

------

### HTML 属性常用引用属性值

属性值应该始终被包括在引号内。

双引号是最常用的，不过使用单引号也没有问题。

**提示:** 在某些个别的情况下，比如属性值本身就含有双引号，那么您必须使用单引号，例如：`name=‘John “ShotGun” Nelson’`

------

### HTML 提示：使用小写属性

属性和属性值对大小写不敏感。

不过，万维网联盟在其 HTML 4 推荐标准中推荐小写的属性/属性值。

而新版本的 (X)HTML 要求使用小写属性。

------

### HTML 属性参考手册

查看完整的HTML属性列表: HTML 标签参考手册

下面列出了适用于大多数 HTML 元素的属性：

| 属性  | 描述                                                         |
| :---- | :----------------------------------------------------------- |
| class | 为html元素定义一个或多个类名（classname）(类名从样式文件引入) |
| id    | 定义元素的唯一id                                             |
| style | 规定元素的行内样式（inline style）                           |
| title | 描述了元素的额外信息 (作为工具条使用)                        |

------

## HTML 标题

标题（Heading）是通过`<h1> - <h6>` 标签进行定义的.

`<h1>` 定义最大的标题。 `<h6>` 定义最小的标题。

```
<h1>这是一个标题。</h1><h2>这是一个标题。</h2><h3>这是一个标题。</h3>
```

**注释:** 浏览器会自动地在标题的前后添加空行。

------

### 标题很重要

请确保将 HTML 标题 标签只用于标题。不要仅仅是为了生成**粗体**或**大号**的文本而使用标题。

搜索引擎使用标题为您的网页的结构和内容编制索引。

因为用户可以通过标题来快速浏览您的网页，所以用标题来呈现文档结构是很重要的。

应该将 h1 用作主标题（最重要的），其后是 h2（次重要的），再其次是 h3，以此类推。

------

### HTML 水平线

------

<hr> 标签在 HTML 页面中创建水平线。

hr 元素可用于分隔内容。

```
<p>这是一个段落。</p><hr><p>这是一个段落。</p><hr><p>这是一个段落。</p>
```

------

### HTML 注释

可以将注释插入 HTML 代码中，这样可以提高其可读性，使代码更易被人理解。浏览器会忽略注释，也不会显示它们。

注释写法如下:

```
<!-- 这是一个注释 -->
```

**注释:** 开始括号之后（左边的括号）需要紧跟一个叹号，结束括号之前（右边的括号）不需要，合理地使用注释可以对未来的代码编辑工作产生帮助。。

------

### HTML 提示 - 如何查看源代码

你是否看过一些网页然后惊叹它是如何实现的的。

如果您想找到其中的奥秘，只需要单击右键，然后选择”查看源文件”（IE）或”查看页面源代码”（Firefox），其他浏览器的做法也是类似的。这么做会打开一个包含页面 HTML 代码的窗口。

------

### HTML 标签参考手册

你将在本教程下面的章节中学到更多有关 HTML 标签和属性的知识。

| 标签          | 描述           |
| :------------ | :------------- |
| `<html>`      | 定义 HTML 文档 |
| `<body>`      | 定义文档的主体 |
| `<h1> - <h6>` | 定义 HTML 标题 |
| `<hr>`        | 定义水平线     |
| `<!–…–>`      | 定义注释       |

------

## HTML 段落

### HTML 段落

------

HTML 可以将文档分割为若干段落。

------

### HTML 段落

段落是通过`<p>` 标签定义的。

```
<p>这是一个段落 </p><p>这是另一个段落</p>
```

**注意：**浏览器会自动地在段落的前后添加空行。`（</p> 是块级元素）`

------

### 不要忘记结束标签

即使忘了使用结束标签，大多数浏览器也会正确地将 HTML 显示出来：

```
<p>这是一个段落<p>这是另一个段落
```

上面的例子在大多数浏览器中都没问题，但不要依赖这种做法。忘记使用结束标签会产生意想不到的结果和错误。

**注释:** 在未来的 HTML 版本中，不允许省略结束标签。

------

### HTML 折行

如果您希望在不产生一个新段落的情况下进行换行（新行），请使用`<br>` 标签：

```
<p>这个<br>段落<br>演示了分行的效果</p>
```

元素是一个空的 HTML 元素。由于关闭标签没有任何意义，因此它没有结束标签。

------

### HTML 输出- 使用提醒

我们无法确定 HTML 被显示的确切效果。屏幕的大小，以及对窗口的调整都可能导致不同的结果。

对于 HTML，您无法通过在 HTML 代码中添加额外的空格或换行来改变输出的效果。

当显示页面时，浏览器会移除源代码中多余的空格和空行。所有连续的空格或空行都会被算作一个空格。需要注意的是，HTML 代码中的所有连续的空行（换行）也被显示为一个空格。

------

### HTML 标签参考手册

| 标签   | 描述                 |
| :----- | :------------------- |
| `<p>`  | 定义一个段落         |
| `<br>` | 插入单个折行（换行） |

------

## HTML 文本格式化

### HTML 文本格式化

```
<b>加粗文本</b><br><br><i>斜体文本</i><br><br><code>电脑自动输出</code><br><br>这是 <sub> 下标</sub> 和 <sup> 上标</sup>
```

演示效果如下

------

**加粗文本**

*斜体文本*

```
电脑自动输出
```

### 这是 下标 和 上标



![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/628afdaf-5e24-4dc6-88ac-d532b4a5442b/kuangstudye60c63d2-8931-4fa8-bfe6-b50a35b5a861.png?resizeSmall&width=832)

演示结束



------

### HTML 格式化标签

HTML 使用标签 `<b>(“bold”) 与 <i>(“italic”)` 对输出的文本进行格式,

如：**粗体** or *斜体_***

这些HTML标签被称为格式化标签（请查看底部完整标签参考手册）。

> 通常标签 `<strong>` 替换加粗标签 `<b>` 来使用, `<em>` 替换 `<i>`标签使用。
>
> 然而，这些标签的含义是不同的：

`<b> 与<i>` 定义粗体或斜体文本。

`<strong> 或者 <em>`意味着你要呈现的文本是重要的，所以要突出显示。现今所有主要浏览器都能渲染各种效果的字体。不过，未来浏览器可能会支持更好的渲染效果。

------

### HTML 文本格式化标签

| 标签       | 描述         |
| :--------- | :----------- |
| `<b>`      | 定义粗体文本 |
| `<em>`     | 定义着重文字 |
| `<i>`      | 定义斜体字   |
| `<small>`  | 定义小号字   |
| `<strong>` | 定义加重语气 |
| `<sub>`    | 定义下标字   |
| `<sup>`    | 定义上标字   |
| `<ins>`    | 定义插入字   |
| `<del>`    | 定义删除字   |

### HTML “计算机输出” 标签

| 标签     | 描述               |
| :------- | :----------------- |
| `<code>` | 定义计算机代码     |
| `<kbd>`  | 定义键盘码         |
| `<samp>` | 定义计算机代码样本 |
| `<var>`  | 定义变量           |
| `<pre>`  | 定义预格式文本     |

### HTML 引文, 引用, 及标签定义

| 标签           | 描述               |
| :------------- | :----------------- |
| `<abbr>`       | 定义缩写           |
| `<address>`    | 定义地址           |
| `<bdo>`        | 定义文字方向       |
| `<blockquote>` | 定义长的引用       |
| `<q>`          | 定义短的引用语     |
| `<cite>`       | 定义引用、引证     |
| `<dfn>`        | 定义一个定义项目。 |

------

## HTML 链接

### HTML 链接

------

HTML 使用超级链接与网络上的另一个文档相连。几乎可以在所有的网页中找到链接。点击链接可以从一张页面跳转到另一张页面。

------

如何在HTML文档中创建链接。

------

### HTML 超链接（链接）

HTML使用标签 来设置超文本链接。

超链接可以是一个字，一个词，或者一组词，也可以是一幅图像，您可以点击这些内容来跳转到新的文档或者当前文档中的某个部分。

当您把鼠标指针移动到网页中的某个链接上时，箭头会变为一只小手。

在标签 中使用了href属性来描述链接的地址。

默认情况下，链接将以以下形式出现在浏览器中：

- 一个未访问过的链接显示为蓝色字体并带有下划线。
- 访问过的链接显示为紫色并带有下划线。
- 点击链接时，链接显示为红色并带有下划线。

> 注意：如果为这些超链接设置了 CSS 样式，展示样式会根据 CSS 的设定而显示。

------

### HTML 链接语法

链接的 HTML 代码很简单。它类似这样：

```
<ahref="url">链接文本</a>
```

href 属性描述了链接的目标。.

```
<ahref="https://www.baidu.com/">访问百度</a>
```

上面这行代码显示为：[访问百度](https://app.yinxiang.com/OutboundRedirect.action?dest=https%3A%2F%2Fwww.xn--wxtr44c.com%2F)

点击这个超链接会把用户带到百度界面(www.baidu.com)的首页。

**提示:** *“链接文本”* 不必一定是文本。图片或其他 HTML 元素都可以成为链接。

------

### HTML 链接 - target 属性

使用 target 属性，你可以定义被链接的文档在何处显示。

下面的这行会在新窗口打开文档：

```
<ahref="https://www.baidu.com/"target="_blank">        访问百度(www.baidu.com)</a>
```

### HTML 链接- id 属性

id属性可用于创建在一个HTML文档书签标记。

**提示:** 书签是不以任何特殊的方式显示，在HTML文档中是不显示的，所以对于读者来说是隐藏的。

在HTML文档中插入ID:

```
<aid="tips">有用的提示部分</a>
```

在HTML文档中创建一个链接到”有用的提示部分(id=“tips”）”：

```
<ahref="#tips">访问有用的提示部分</a>
```

或者，从另一个页面创建一个链接到”有用的提示部分(id=“tips”）”：

```
<ahref="https://www.baidu.com/#tips">访问有用的提示部分</a>
```

------

### 基本的注意事项 - 有用的提示

> **注释：** 请始终将正斜杠添加到子文件夹。

假如这样书写链接：`href="https://www.baidu.com/index/html"`，就会向服务器产生两次 HTTP 请求。这是因为服务器会添加正斜杠到这个地址，然后创建一个新的请求，就像这样：href=“[https://www.baidu.com/index/html/"。](https://app.yinxiang.com/OutboundRedirect.action?dest=https%3A%2F%2Fwww.baidu.com%2Findex%2Fhtml%2F%22%E3%80%82)

------

### HTML 链接标签

| 标签  | 描述             |
| :---- | :--------------- |
| `<a>` | 定义一个超级链接 |

------

## HTML head

------

### HTML`<head>` 元素

`<head>` 元素包含了所有的头部标签元素。在`<head>`元素中你可以插入脚本（scripts）, 样式文件（CSS），及各种meta信息。

可以添加在头部区域的元素标签为:`<title>, <style>, <meta>, <link>, <script>, <noscript>, and <base>.`

## HTML `<title>`元素

`<title>` 标签定义了不同文档的标题。

`<title>` 在 HTML/XHTML 文档中是必须的。

`<title>` 元素:

```
*定义了浏览器工具栏的标题*当网页添加到收藏夹时，显示在收藏夹中的标题*显示在搜索引擎结果页面的标题
```

一个简单的 HTML 文档:

实例

```
<!DOCTYPE html><html><head><metacharset="utf-8"><title>文档标题</title></head><body>文档内容......</body></html>
```

### HTML`<base>` 元素

`<base>`标签描述了基本的链接地址/链接目标，该标签作为HTML文档中所有的链接标签的默认链接:

```
<head><basehref="https://www.kuangstudy.com/"target="_blank"></head>
```

### HTML `<link>` 元素

`<link>` 标签定义了文档与外部资源之间的关系。

`<link>` 标签通常用于链接到样式表:

```
<head><linkrel="stylesheet"type="text/css"href="mystyle.css"></head>
```

### HTML`<style>`元素

<style> 标签定义了HTML文档的样式文件引用地址.

在`<style>` 元素中你也可以直接添加样式来渲染 HTML 文档:

```
<head><styletype="text/css">body {background-color:yellow}p {color:blue}</style></head>
```

HTML`<meta>` 元素 meta标签描述了一些基本的元数据。

<meta> 标签提供了元数据.元数据也不显示在页面上，但会被浏览器解析。

META 元素通常用于指定网页的描述，关键词，文件的最后修改时间，作者，和其他元数据。

元数据可以使用于浏览器（如何显示内容或重新加载页面），搜索引擎（关键词），或其他Web服务。

<meta> 一般放置于 <head> 区域

### `<meta>` 标签- 使用实例

为搜索引擎定义关键词:

```
<metaname="keywords"content="HTML, CSS, XML, XHTML, JavaScript">
```

为网页定义描述内容:

```
<metaname="description"content="教程">
```

定义网页作者:

```
<metaname="author"content="Daly">
```

每30秒钟刷新当前页面:

```
<metahttp-equiv="refresh"content="30">
```

### HTML `<script>`元素

<script>标签用于加载脚本文件，如： JavaScript。

<script> 元素在以后的章节中会详细描述。

HTML head 元素

| 标签       | 描述                               |
| :--------- | :--------------------------------- |
| `<head>`   | 定义了文档的信息                   |
| `<title>`  | 定义了文档的标题                   |
| `<base>`   | 定义了页面链接标签的默认链接地址   |
| `<link>`   | 定义了一个文档和外部资源之间的关系 |
| `<meta>`   | 定义了HTML文档中的元数据           |
| `<script>` | 定义了客户端的脚本文件             |
| `<style>`  | 定义了HTML文档的样式文件           |

------

## HTML 样式- CSS

### HTML 样式- CSS

------

CSS (Cascading Style Sheets) 用于渲染HTML元素标签的样式.

### 如何使用CSS

CSS 是在 HTML 4 开始使用的,是为了更好的渲染HTML元素而引入的.

CSS 可以通过以下方式添加到HTML中:

- 内联样式- 在HTML元素中使用”style” 属性
- 内部样式表 -在HTML文档头部 `<head> 区域使用<style>` 元素 来包含CSS
- 外部引用 - 使用外部 CSS 文件

最好的方式是通过外部引用CSS文件.

我们使用了内联CSS样式来介绍实例，这是为了简化的例子，也使得你能更容易在线编辑代码并在线运行实例。

------

### 内联样式

当特殊的样式需要应用到个别元素时，就可以使用内联样式。 使用内联样式的方法是在相关的标签中使用样式属性。样式属性可以包含任何 CSS 属性。以下实例显示出如何改变段落的颜色和左外边距。

```
<pstyle="color:blue;margin-left:20px;">This is a paragraph.</p>
```

### HTML样式实例 - 背景颜色

背景色属性（background-color）定义一个元素的背景颜色：

实例

```
<bodystyle="background-color:yellow;"><h2style="background-color:red;">这是一个标题</h2><pstyle="background-color:green;">这是一个段落。</p></body>
```

早期背景色属性（background-color）是使用 bgcolor 属性定义。

### HTML 样式实例 - 字体, 字体颜色 ，字体大小

我们可以使用font-family（字体），color（颜色），和font-size（字体大小）属性来定义字体的样式:

实例

```
<h1style="font-family:verdana;">一个标题</h1><pstyle="font-family:arial;color:red;font-size:20px;">一个段落。</p>
```

现在通常使用font-family（字体），color（颜色），和font-size（字体大小）属性来定义文本样式，而不是使用<font>标签。

### HTML 样式实例 - 文本对齐方式

使用 text-align（文字对齐）属性指定文本的水平与垂直对齐方式：

实例

```
<h1style="text-align:center;">居中对齐的标题</h1><p>这是一个段落。</p>
```

文本对齐属性 text-align取代了旧标签 `<center>` 。

### 部样式表

当单个文件需要特别样式时，就可以使用内部样式表。你可以在`<head> 部分通过 <style>`标签定义内部样式表:

```
<head><styletype="text/css">body {background-color:yellow;}p {color:blue;}</style></head>
```

### 外部样式表

当样式需要被应用到很多页面的时候，外部样式表将是理想的选择。使用外部样式表，你就可以通过更改一个文件来改变整个站点的外观。

```
<head><linkrel="stylesheet"type="text/css"href="mystyle.css"></head>
```

### HTML 样式标签

| 标签      | 描述             |
| :-------- | :--------------- |
| `<style>` | 定义文本样式     |
| `<link>`  | 定义资源引用地址 |

------

## HTML 图像

### HTML 图像- 图像标签（ `<img>`）和源属性（Src）

在 HTML 中，图像由 标签定义。

<img> 是空标签，意思是说，它只包含属性，并且没有闭合标签。

要在页面上显示图像，你需要使用源属性（src）。src 指 “source”。源属性的值是图像的 URL 地址。

定义图像的语法是：

```
<imgsrc="url"alt="some_text">
```

URL 指存储图像的位置。如果名为 “alipay-redpack.png” 的图像位于 www.baidu.com 的 images 目录中，那么其 URL 为 [https://baike.baidu.com/item/Angelababy/1509275?fr=aladdin](https://app.yinxiang.com/OutboundRedirect.action?dest=https%3A%2F%2Fbaike.baidu.com%2Fitem%2FAngelababy%2F1509275%3Ffr%3Daladdin)“ target=”_blank” 。
`<a href="https://baike.baidu.com/item/Angelababy/1509275?fr=aladdin" target="_blank">百度百科</a>`
浏览器将图像显示在文档中图像标签出现的地方。如果你将图像标签置于两个段落之间，那么浏览器会首先显示第一个段落，然后显示图片，最后显示第二段。

------

### HTML 图像- Alt属性

alt 属性用来为图像定义一串预备的可替换的文本。

替换文本属性的值是用户定义的。

```
<imgsrc="boat.gif"alt="Big Boat">
```

在浏览器无法载入图像时，替换文本属性告诉读者她们失去的信息。此时，浏览器将显示这个替代性的文本而不是图像。为页面上的图像都加上替换文本属性是个好习惯，这样有助于更好的显示信息，并且对于那些使用纯文本浏览器的人来说是非常有用的。

------

### HTML 图像- 设置图像的高度与宽度

height（高度） 与 width（宽度）属性用于设置图像的高度与宽度。

属性值默认单位为像素:

```
<imgsrc="pulpit.jpg"alt="Pulpit rock"width="304"height="228">
```

提示: 指定图像的高度和宽度是一个很好的习惯。如果图像指定了高度宽度，页面加载时就会保留指定的尺寸。如果没有指定图片的大小，加载页面时有可能会破坏HTML页面的整体布局。

------

### 基本的注意事项 - 有用的提示：

注意: 假如某个 HTML 文件包含十个图像，那么为了正确显示这个页面，需要加载 11 个文件。加载图片是需要时间的，所以我们的建议是：慎用图片。

注意: 加载页面时，要注意插入页面图像的路径，如果不能正确设置图像的位置，浏览器无法加载图片，图像标签就会显示一个破碎的图片。

------

### HTML 图像标签

| 标签     | 描述                       |
| :------- | :------------------------- |
| `<img>`  | 定义图像                   |
| `<map>`  | 定义图像地图               |
| `<area>` | 定义图像地图中的可点击区域 |

------

## HTML 表格

### HTML 表格

------

### HTML 表格实例:

| FIRST NAME | LAST NAME | POINTS |
| :--------- | :-------- | :----- |
| Jill       | Smith     | 50     |
| Eve        | Jackson   | 94     |
| John       | Doe       | 80     |
| Adam       | Johnson   | 67     |

------

### HTML 表格

表格由`<table>` 标签来定义。每个表格均有若干行（由 `<tr>` 标签定义），每行被分割为若干单元格（由 `<td>` 标签定义）。字母 td 指表格数据（table data），即数据单元格的内容。数据单元格可以包含文本、图片、列表、段落、表单、水平线、表格等等。

## 表格实例

```
<tableborder="1"><tr><td>row 1, cell 1</td><td>row 1, cell 2</td></tr><tr><td>row 2, cell 1</td><td>row 2, cell 2</td></tr></table>
```

在浏览器显示如下：:

| ROW 1, CELL 1 | ROW 1, CELL 2 |
| :------------ | :------------ |
| row 2, cell 1 | row 2, cell 2 |

------

## HTML 表格和边框属性

如果不定义边框属性，表格将不显示边框。有时这很有用，但是大多数时候，我们希望显示边框。

使用边框属性来显示一个带有边框的表格：

```
<tableborder="1"><tr><td>Row 1, cell 1</td><td>Row 1, cell 2</td></tr></table>
```

------

### HTML 表格表头

表格的表头使用`<th>` 标签进行定义。

大多数浏览器会把表头显示为粗体居中的文本：

### 实例

```
<tableborder="1"><tr><th>Header 1</th><th>Header 2</th></tr><tr><td>row 1, cell 1</td><td>row 1, cell 2</td></tr><tr><td>row 2, cell 1</td><td>row 2, cell 2</td></tr></table>
```

在浏览器显示如下：

| HEADER 1      | HEADER 2      |
| :------------ | :------------ |
| row 1, cell 1 | row 1, cell 2 |
| row 2, cell 1 | row 2, cell 2 |

------

### HTML 表格标签

| 标签         | 描述                 |
| :----------- | :------------------- |
| `<table>`    | 定义表格             |
| `<th>`       | 定义表格的表头       |
| `<tr>`       | 定义表格的行         |
| `<td>`       | 定义表格单元         |
| `<caption>`  | 定义表格标题         |
| `<colgroup>` | 定义表格列的组       |
| `<col>`      | 定义用于表格列的属性 |
| `<thead>`    | 定义表格的页眉       |
| `<tbody>`    | 定义表格的主体       |
| `<tfoot>`    | 定义表格的页脚       |

------

## HTML 列表

### HTML 列表

------

HTML 支持有序、无序和定义列表:

### HTML 列表

#### 有序列表

1. 第一个列表项
2. 第二个列表项
3. 第三个列表项

#### 无序列表

- 列表项
- 列表项
- 列表项

------

### HTML无序列表

无序列表是一个项目的列表，此列项目使用粗体圆点（典型的小黑圆圈）进行标记。

无序列表使用 `<ul>` 标签

```
<ul><li>Coffee</li><li>Milk</li></ul>
```

浏览器显示如下：

- Coffee
- Milk

------

## HTML 有序列表

同样，有序列表也是一列项目，列表项目使用数字进行标记。 有序列表始于`<ol>` 标签。每个列表项始于 `<li>` 标签。

列表项使用数字来标记。

```
<ol><li>Coffee</li><li>Milk</li></ol>
```

浏览器中显示如下：

1. Coffee
2. Milk

------

## HTML 自定义列表

自定义列表不仅仅是一列项目，而是项目及其注释的组合。

自定义列表以`<dl>` 标签开始。每个自定义列表项以 `<dt>` 开始。每个自定义列表项的定义以 `<dd>` 开始。

```
<dl><dt>Coffee</dt><dd>- black hot drink</dd><dt>Milk</dt><dd>- white cold drink</dd></dl>
```

浏览器显示如下：

- Coffee
  - black hot drink
- Milk
  - white cold drink

------

### 注意事项 - 有用提示

**提示:** 列表项内部可以使用段落、换行符、图片、链接以及其他列表等等。

------

### HTML 列表标签

| 标签   | 描述                 |
| :----- | :------------------- |
| `<ol>` | 定义有序列表         |
| `<ul>` | 定义无序列表         |
| `<li>` | 定义列表项           |
| `<dl>` | 定义列表             |
| `<dt>` | 自定义列表项目       |
| `<dd>` | 定义自定列表项的描述 |

------

## HTML 块级元素

### HTML`<div> 和<span>`

HTML 可以通过`<div> 和 <span>`将元素组合起来。

------

### HTML 区块元素

大多数 HTML 元素被定义为块级元素或内联元素。

块级元素在浏览器显示时，通常会以新行来开始（和结束）。

实例: `<h1>, <p>, <ul>, <table>`

------

### HTML 内联元素

内联元素在显示时通常不会以新行开始。

实例: `<b>, <td>, <a>, <img>`

------

### HTML`<div>` 元素

HTML `<div>` 元素是块级元素，它可用于组合其他 HTML 元素的容器。

<div> 元素没有特定的含义。除此之外，由于它属于块级元素，浏览器会在其前后显示折行。

如果与 CSS 一同使用，`<div>`元素可用于对大的内容块设置样式属性。

<div> 元素的另一个常见的用途是文档布局。它取代了使用表格定义布局的老式方法。使用 <table> 元素进行文档布局不是表格的正确用法。<table> 元素的作用是显示表格化的数据。

------

### HTML `<span>` 元素

HTML `<span>` 元素是内联元素，可用作文本的容器

`<span>` 元素也没有特定的含义。

当与 CSS 一同使用时，`<span>` 元素可用于为部分文本设置样式属性。

------

### HTML 分组标签

| 标签     | 描述                                        |
| :------- | :------------------------------------------ |
| `<div>`  | 定义了文档的区域，块级 (block-level)        |
| `<span>` | 用来组合文档中的行内元素， 内联元素(inline) |

------

## HTML 布局

### HTML 布局

------

网页布局对改善网站的外观非常重要。

请慎重设计您的网页布局

------

### 网站布局

大多数网站会把内容安排到多个列中（就像杂志或报纸那样）。

大多数网站可以使用`<div> 或者 <table>`元素来创建多列。CSS 用于对元素进行定位，或者为页面创建背景以及色彩丰富的外观。

> 
>
> 虽然我们可以使用HTML table标签来设计出漂亮的布局，但是table标签是不建议作为布局工具使用的 - 表格不是布局工具。
>
> 

------

### HTML 布局 - 使用`<div>` 元素

div 元素是用于分组 HTML 元素的块级元素。

下面的例子使用五个 div 元素来创建多列布局：

> 
>
> <!DOCTYPE html>
>
> 

上面的 HTML 代码会产生如下结果：

<!DOCTYPE html>

![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/7b19f6a5-98c5-4d40-b921-b19e7569ac94/kuangstudy60f5fca9-7e31-459b-adf9-a9fab42cd77b.png?resizeSmall&width=832)



------

### HTML 布局 - 使用表格

使用 HTML `<table>` 标签是创建布局的一种简单的方式。

大多数站点可以使用`<div> 或者 <table>` 元素来创建多列。CSS 用于对元素进行定位，或者为页面创建背景以及色彩丰富的外观。

> 
>
> 即使可以使用 HTML 表格来创建漂亮的布局，但设计表格的目的是呈现表格化数据 - 表格不是布局工具！
>
> 

下面的例子使用三行两列的表格 - 第一和最后一行使用 colspan 属性来横跨两列：

实例

```
<!DOCTYPE html><html><head><metacharset="utf-8"><title>表格布局</title></head><body><tablewidth="500"border="0"><tr><tdcolspan="2"style="background-color:#FFA500;"><h1>主要的网页标题</h1></td></tr><tr><tdstyle="background-color:#FFD700;width:100px;"><b>菜单</b><br>HTML<br>CSS<br>JavaScript</td><tdstyle="background-color:#eeeeee;height:200px;width:400px;">内容在这里</td></tr><tr><tdcolspan="2"style="background-color:#FFA500;text-align:center;">Daly</td></tr></table></body></html>
```

上面的 HTML 代码会产生以下结果：

<!DOCTYPE html>

![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/f82dea79-7417-427b-b50f-001125ec23a7/kuangstudy55fd20e1-2b9e-40aa-8f12-1b4de9af0a4b.png?resizeSmall&width=832)



------

### HTML 布局 - 有用的提示

**Tip:** 使用 CSS 最大的好处是，如果把 CSS 代码存放到外部样式表中，那么站点会更易于维护。通过编辑单一的文件，就可以改变所有页面的布局

**Tip:** 由于创建高级的布局非常耗时，使用模板是一个快速的选项。通过搜索引擎可以找到很多免费的网站模板（您可以使用这些预先构建好的网站布局，并优化它们）。

------

### HTML 布局标签

| 标签     | 描述                                  |
| :------- | :------------------------------------ |
| `<div>`  | 定义文档区块，块级(block-level)       |
| `<span>` | 定义 span，用来组合文档中的行内元素。 |

------

## HTML 表单

### HTML 表单和输入

HTML 表单用于收集不同类型的用户输入。

### HTML 表单

表单是一个包含表单元素的区域。

表单元素是允许用户在表单中输入内容，比如：文本域 (textarea)、下拉列表、单选框 (radio-buttons)、复选框 (checkboxes) 等等。

表单使用表单标签 `<form>` 来设置：

```
<form>.input 元素.</form>
```

### HTML 表单 - 输入元素

多数情况下被用到的表单标签是输入标签`（<input>）`。

输入类型是由类型属性（type）定义的。大多数经常被用到的输入类型如下：

### 文本域（Text Fields）

文本域通过 `<input type=“text”>` 标签来设定，当用户要在表单中键入字母、数字等内容时，就会用到文本域。

```
<form>First name: <inputtype="text"name="firstname"><br>Last name: <inputtype="text"name="lastname"></form>
```

浏览器显示如下：

![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/955e73c5-e99c-4321-9d6b-98fa8e1c1e24/kuangstudy56f58cba-0d3f-499a-8c17-8bf3d6d30ea3.png?resizeSmall&width=832)

**注意：**表单本身并不可见。同时，在大多数浏览器中，文本域的缺省宽度是 20 个字符。



### 密码字段

密码字段通过标签 `<input type=“password”>` 来定义：

```
<form>Password: <inputtype="password"name="pwd"></form>
```

浏览器显示效果如下：

![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/c0e5f2aa-04cc-4afa-bcb8-6bd1893e8ac3/kuangstudya55fc358-ebaf-4508-a6cb-109a8a359a4f.png?resizeSmall&width=832)

**注意：**密码字段字符不会明文显示，而是以星号或圆点替代。



### 单选按钮（Radio Buttons）

`<input type=“radio”>`标签定义了表单单选框选项

```
<form><inputtype="radio"name="sex"value="male">Male<br><inputtype="radio"name="sex"value="female">Female</form>
```

浏览器显示效果如下：

![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/59bb663e-65a5-406b-804a-11a8ff3e622d/kuangstudy0349d341-3570-42ed-91b1-c81acfeaccdf.png?resizeSmall&width=832)



### 复选框（Checkboxes）

`<input type=“checkbox”>` 定义了复选框。用户需要从若干给定的选择中选取一个或若干选项。

```
<form><inputtype="checkbox"name="vehicle"value="Bike">I have a bike<br><inputtype="checkbox"name="vehicle"value="Car">I have a car</form>
```

浏览器显示效果如下：

![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/5ed7f676-4d96-4802-a952-b724d6e7b2f3/kuangstudy58d1134a-c6bf-4473-a683-d51bc108f141.png?resizeSmall&width=832)



### 提交按钮 (Submit Button)

`<input type=“submit”>` 定义了提交按钮。

当用户单击确认按钮时，表单的内容会被传送到另一个文件。表单的动作属性定义了目的文件的文件名。由动作属性定义的这个文件通常会对接收到的输入数据进行相关的处理。:

```
<formname="input"action="html_form_action.php"method="get">Username: <inputtype="text"name="user"><inputtype="submit"value="Submit"></form>
```

浏览器显示效果如下：

![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/75813134-9752-47b0-a4e9-ce0599706b23/kuangstudyf6885cb4-0a88-4b3e-9939-59b2b8587069.png?resizeSmall&width=832)

假如您在上面的文本框内键入几个字母，然后点击确认按钮，那么输入数据会传送到 “html_form_action.php” 的页面。该页面将显示出输入的结果。



### HTML 表单标签

New : HTML5 新标签

```
|标签|描述||:------------|:-------------------------------------------||<form>|定义供用户输入的表单||<input>|定义输入域||<textarea>|定义文本域（一个多行的输入控件）||<label>|定义了<input>元素的标签，一般为输入标题||<fieldset>|定义了一组相关的表单元素，并使用外框包含起来||<legend>|定义了<fieldset>元素的标题||<select>|定义了下拉选项列表||<optgroup>|定义选项组||<option>|定义下拉列表中的选项||<button>|定义一个点击按钮||<datalist>New|指定一个预先定义的输入控件选项列表||<keygen>New|定义了表单的密钥对生成器字段||<output>New|定义一个计算结果|--------
```

## HTML 框架

### HTML 框架

通过使用框架，你可以在同一个浏览器窗口中显示不止一个页面。

```
<!doctype html><html><head><title>网页的标题</title><metacharset="UTF-8"><metaname="keywords"content="HTML,网页设计,前端开发"><metaname="description"content="这是关于网页设计可的一个教学用的网页"></head><body><ahref="https://www.baidu.com">百度</a><br><ahref="demo.html"target="_self">我要跳转到demo.html(在当前窗口打开)</a><br><ahref="demo.html"target="_blank">我要跳转到demo.html(在新窗口中打开)</a><br><ahref="demo.html"target="allen">我要跳转到demo.html（在指定名字的内联框架中打开）</a><br><ahref="#">我要跳转到当前页面</a><br><p>有问题，找<ahref="https://www.baidu.com"target="_blank">百度</a></p><p>段落1</p><p>段落2</p><pid="pp3">段落3</p><p>段落4</p><p>段落5</p><p>段落6</p><pid="pp7">段落7</p><p>段落8</p><p>段落9</p><p>段落10</p><p>段落11</p><p>段落12</p><p>段落13</p><p>段落14</p><p>段落15</p><p>段落16</p><p>段落17</p><iframename="allen"src="https://www.baidu.com"height="1800px"width="900px"></iframe><ahref="#">返回顶部</a><br><ahref="#pp3">返回段落3</a><ahref="#pp7">返回段落7</a></body></html>
```

**iframe 语法:**

该URL指向不同的网页。

### Iframe - 设置高度与宽度

height 和 width 属性用来定义iframe标签的高度与宽度。

属性默认以像素为单位, 但是你可以指定其按比例显示 (如：”80%“)。

```
<iframesrc="demo_iframe.htm"width="200"height="200"></iframe>
```

------

### Iframe - 移除边框

frameborder 属性用于定义iframe表示是否显示边框。

设置属性值为 “0” 移除iframe的边框:

```
<iframesrc="demo_iframe.htm"frameborder="0"></iframe>
```

------

### 使用iframe来显示目标链接页面

iframe可以显示一个目标链接的页面

目标链接的属性必须使用iframe的属性，如下实例:

```
<iframesrc="demo_iframe.htm"name="iframe_a"></iframe><p><ahref="https://www.baidu.com"target="iframe_a">https://www.baidu.com</a></p>
```

------

```
### HTML iframe 标签|标签|说明||:-------|:-------------------||```<iframe>```|定义一个内联的iframe |------
```

## HTML 颜色

### HTML 颜色

------

HTML 颜色由红色、绿色、蓝色混合而成。

------

### 颜色值

HTML 颜色由一个十六进制符号来定义，这个符号由红色、绿色和蓝色的值组成（RGB）。

每种颜色的最小值是0（十六进制：#00）。最大值是255（十六进制：#FF）。

这个表格给出了由三种颜色混合而成的具体效果：

```
<pstyle="background-color:#FFFF00">通过十六进制设置背景颜色</p><pstyle="background-color:rgb(255,255,0)">通过 rbg 值设置背景颜色</p><pstyle="background-color:yellow">通过颜色名设置背景颜色</p>
```

通过十六进制设置背景颜色

通过 rbg 值设置背景颜色

通过颜色名设置背景颜色

### 1600万种不同颜色

三种颜色 红，绿，蓝的组合从0到255，一共有1600万种不同颜色(256 x 256 x 256)。

在下面的颜色表中你会看到不同的结果，从0到255的红色，同时设置绿色和蓝色的值为0,随着红色的值变化，不同的值都显示了不同的颜色。

| RED LIGHT | COLOR HEX | COLOR RGB    |
| :-------- | :-------- | :----------- |
|           | #000000   | rgb(0,0,0)   |
|           | #080000   | rgb(8,0,0)   |
|           | #100000   | rgb(16,0,0)  |
|           | #180000   | rgb(24,0,0)  |
|           | #200000   | rgb(32,0,0)  |
|           | #280000   | rgb(40,0,0)  |
|           | #300000   | rgb(48,0,0)  |
|           | #380000   | rgb(56,0,0)  |
|           | #400000   | rgb(64,0,0)  |
|           | #480000   | rgb(72,0,0)  |
|           | #500000   | rgb(80,0,0)  |
|           | #580000   | rgb(88,0,0)  |
|           | #600000   | rgb(96,0,0)  |
|           | #680000   | rgb(104,0,0) |
|           | #700000   | rgb(112,0,0) |
|           | #780000   | rgb(120,0,0) |
|           | #800000   | rgb(128,0,0) |
|           | #880000   | rgb(136,0,0) |
|           | #900000   | rgb(144,0,0) |
|           | #980000   | rgb(152,0,0) |
|           | #A00000   | rgb(160,0,0) |
|           | #A80000   | rgb(168,0,0) |
|           | #B00000   | rgb(176,0,0) |
|           | #B80000   | rgb(184,0,0) |
|           | #C00000   | rgb(192,0,0) |
|           | #C80000   | rgb(200,0,0) |
|           | #D00000   | rgb(208,0,0) |
|           | #D80000   | rgb(216,0,0) |
|           | #E00000   | rgb(224,0,0) |
|           | #E80000   | rgb(232,0,0) |
|           | #F00000   | rgb(240,0,0) |
|           | #F80000   | rgb(248,0,0) |
|           | #FF0000   | rgb(255,0,0) |

------

### 灰暗色调

以下展示了灰色到黑色的渐变

| GRAY SHADES | COLOR HEX | COLOR RGB        |
| :---------- | :-------- | :--------------- |
|             | #000000   | rgb(0,0,0)       |
|             | #080808   | rgb(8,8,8)       |
|             | #101010   | rgb(16,16,16)    |
|             | #181818   | rgb(24,24,24)    |
|             | #202020   | rgb(32,32,32)    |
|             | #282828   | rgb(40,40,40)    |
|             | #303030   | rgb(48,48,48)    |
|             | #383838   | rgb(56,56,56)    |
|             | #404040   | rgb(64,64,64)    |
|             | #484848   | rgb(72,72,72)    |
|             | #505050   | rgb(80,80,80)    |
|             | #585858   | rgb(88,88,88)    |
|             | #606060   | rgb(96,96,96)    |
|             | #686868   | rgb(104,104,104) |
|             | #707070   | rgb(112,112,112) |
|             | #787878   | rgb(120,120,120) |
|             | #808080   | rgb(128,128,128) |
|             | #888888   | rgb(136,136,136) |
|             | #909090   | rgb(144,144,144) |
|             | #989898   | rgb(152,152,152) |
|             | #A0A0A0   | rgb(160,160,160) |
|             | #A8A8A8   | rgb(168,168,168) |
|             | #B0B0B0   | rgb(176,176,176) |
|             | #B8B8B8   | rgb(184,184,184) |
|             | #C0C0C0   | rgb(192,192,192) |
|             | #C8C8C8   | rgb(200,200,200) |
|             | #D0D0D0   | rgb(208,208,208) |
|             | #D8D8D8   | rgb(216,216,216) |
|             | #E0E0E0   | rgb(224,224,224) |
|             | #E8E8E8   | rgb(232,232,232) |
|             | #F0F0F0   | rgb(240,240,240) |
|             | #F8F8F8   | rgb(248,248,248) |
|             | #FFFFFF   | rgb(255,255,255) |

------

### Web安全色?

数年以前，当大多数计算机仅支持 256 种颜色的时候，一系列 216 种 Web 安全色作为 Web 标准被建议使用。其中的原因是，微软和 Mac 操作系统使用了 40 种不同的保留的固定系统颜色（双方大约各使用 20 种）。

我们不确定如今这么做的意义有多大，因为越来越多的计算机有能力处理数百万种颜色，不过做选择还是你自己。

最初，216 跨平台 web 安全色被用来确保：当计算机使用 256 色调色板时，所有的计算机能够正确地显示所有的颜色。

| 000000 | 000033 | 000066 | 000099 | 0000CC | 0000FF |
| :----- | :----- | :----- | :----- | :----- | :----- |
| 003300 | 003333 | 003366 | 003399 | 0033CC | 0033FF |
| 006600 | 006633 | 006666 | 006699 | 0066CC | 0066FF |
| 009900 | 009933 | 009966 | 009999 | 0099CC | 0099FF |
| 00CC00 | 00CC33 | 00CC66 | 00CC99 | 00CCCC | 00CCFF |
| 00FF00 | 00FF33 | 00FF66 | 00FF99 | 00FFCC | 00FFFF |
| 330000 | 330033 | 330066 | 330099 | 3300CC | 3300FF |
| 333300 | 333333 | 333366 | 333399 | 3333CC | 3333FF |
| 336600 | 336633 | 336666 | 336699 | 3366CC | 3366FF |
| 339900 | 339933 | 339966 | 339999 | 3399CC | 3399FF |
| 33CC00 | 33CC33 | 33CC66 | 33CC99 | 33CCCC | 33CCFF |
| 33FF00 | 33FF33 | 33FF66 | 33FF99 | 33FFCC | 33FFFF |
| 660000 | 660033 | 660066 | 660099 | 6600CC | 6600FF |
| 663300 | 663333 | 663366 | 663399 | 6633CC | 6633FF |
| 666600 | 666633 | 666666 | 666699 | 6666CC | 6666FF |
| 669900 | 669933 | 669966 | 669999 | 6699CC | 6699FF |
| 66CC00 | 66CC33 | 66CC66 | 66CC99 | 66CCCC | 66CCFF |
| 66FF00 | 66FF33 | 66FF66 | 66FF99 | 66FFCC | 66FFFF |
| 990000 | 990033 | 990066 | 990099 | 9900CC | 9900FF |
| 993300 | 993333 | 993366 | 993399 | 9933CC | 9933FF |
| 996600 | 996633 | 996666 | 996699 | 9966CC | 9966FF |
| 999900 | 999933 | 999966 | 999999 | 9999CC | 9999FF |
| 99CC00 | 99CC33 | 99CC66 | 99CC99 | 99CCCC | 99CCFF |
| 99FF00 | 99FF33 | 99FF66 | 99FF99 | 99FFCC | 99FFFF |
| CC0000 | CC0033 | CC0066 | CC0099 | CC00CC | CC00FF |
| CC3300 | CC3333 | CC3366 | CC3399 | CC33CC | CC33FF |
| CC6600 | CC6633 | CC6666 | CC6699 | CC66CC | CC66FF |
| CC9900 | CC9933 | CC9966 | CC9999 | CC99CC | CC99FF |
| CCCC00 | CCCC33 | CCCC66 | CCCC99 | CCCCCC | CCCCFF |
| CCFF00 | CCFF33 | CCFF66 | CCFF99 | CCFFCC | CCFFFF |
| FF0000 | FF0033 | FF0066 | FF0099 | FF00CC | FF00FF |
| FF3300 | FF3333 | FF3366 | FF3399 | FF33CC | FF33FF |
| FF6600 | FF6633 | FF6666 | FF6699 | FF66CC | FF66FF |
| FF9900 | FF9933 | FF9966 | FF9999 | FF99CC | FF99FF |
| FFCC00 | FFCC33 | FFCC66 | FFCC99 | FFCCCC | FFCCFF |
| FFFF00 | FFFF33 | FFFF66 | FFFF99 | FFFFCC | FFFFFF |

------

## HTML 颜色值

### HTML 颜色值

颜色由红®、绿(G)、蓝(B)组成。

------

### 颜色值

颜色值由十六进制来表示红、绿、蓝（RGB）。

每个颜色的最低值为 0(十六进制为 00)，最高值为 255(十六进制为FF)。

十六进制值的写法为 # 号后跟三个或六个十六进制字符。

三位数表示法为：#RGB，转换为6位数表示为：#RRGGBB。

### 颜色实例

| 颜色 | 3位十六进制颜色值 | 6位十六进制颜色值 | RGB              |
| :--- | :---------------- | :---------------- | :--------------- |
|      | #000              | #000000           | rgb(0,0,0)       |
|      | #F00              | #FF0000           | rgb(255,0,0)     |
|      | #0F0              | #00FF00           | rgb(0,255,0)     |
|      | #00F              | #0000FF           | rgb(0,0,255)     |
|      | #FF0              | #FFFF00           | rgb(255,255,0)   |
|      | #0FF              | #00FFFF           | rgb(0,255,255)   |
|      | #F0F              | #FF00FF           | rgb(255,0,255)   |
|      | #888              | #888888           | rgb(136,136,136) |
|      | #FFF              | #FFFFFF           | rgb(255,255,255) |

## [" class="reference-link">](https://app.yinxiang.com/shard/s46/nl/32093335/true)![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/d4b36f5f-d5a5-4410-8e95-4b23f1595952/kuangstudyd5f0b161-a986-4ffd-a7d2-561d84709bec.png?resizeSmall&width=832)

## HTML 颜色名

### HTML 颜色名

------

### 目前所有浏览器都支持以下颜色名。

141个颜色名称是在HTML和CSS颜色规范定义的（17标准颜色，再加124）。下表列出了所有颜色的值，包括十六进制值。

> 
>
> 提示: 17标准颜色：黑色，蓝色，水，紫红色，灰色，绿色，石灰，栗色，海军，橄榄，橙，紫，红，白，银，蓝绿色，黄色。点击其中一个颜色名称（或一个十六进制值）就可以查看与不同文字颜色搭配的背景颜色。
>
> 

------

### 按颜色名排序

单击一个颜色名或者 16 进制值，就可以查看与不同文字颜色搭配的背景颜色。

| COLOR NAME | HEX  | COLOR |
| :--------- | :--- | :---- |
|            |      |       |

## [" class="reference-link">](https://app.yinxiang.com/shard/s46/nl/32093335/true)![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/b7fd1ee8-d5ed-4e41-9a61-6ef8a2ea2341/kuangstudy291bbff1-6dbc-406f-a1d7-e24bf9eac0c7.png?resizeSmall&width=832)

## HTML 脚本

------

JavaScript 使 HTML 页面具有更强的动态和交互性。

------

### HTML标签

```
<script> 标签用于定义客户端脚本，比如 JavaScript。<script> 元素既可包含脚本语句，也可通过 src 属性指向外部脚本文件。
```

JavaScript 最常用于图片操作、表单验证以及内容动态更新。

下面的脚本会向浏览器输出”Hello World!“：

```
<script>document.write("Hello World!");</script>
```

------

### HTML 标签

```
​```<noscript>```标签提供无法使用脚本时的替代内容，比方在浏览器禁用脚本时，或浏览器不支持客户端脚本时。```<noscript>```元素可包含普通 HTML 页面的 body 元素中能够找到的所有元素。只有在浏览器不支持脚本或者禁用脚本时，才会显示```<noscript> ```元素中的内容：
```

```
<script>document.write("Hello World!")</script><noscript>抱歉，你的浏览器不支持 JavaScript!</noscript>
```

------

### JavaScript体验

JavaScript可以直接在HTML输出:

```
document.write("<p>这是一个段落。</p>");
```

JavaScript事件响应:

```
<buttontype="button"onclick="myFunction()">点我！</button>
```

JavaScript处理 HTML 样式:

```
document.getElementById("demo").style.color="#ff0000";
```

------

### HTML 脚本标签

```
|标签|描述||:---------|:-------------------------------||``` <script>```|定义了客户端脚本||```<noscript>```|定义了不支持脚本浏览器输出的文本|-----------------
```

## HTML 字符实体

### HTML 字符实体

------

HTML 中的预留字符必须被替换为字符实体。

一些在键盘上找不到的字符也可以使用字符实体来替换。

------

### HTML 实体

在 HTML 中，某些字符是预留的。

在 HTML 中不能使用小于号`（<）和大于号（>）`，这是因为浏览器会误认为它们是标签。

如果希望正确地显示预留字符，我们必须在 HTML 源代码中使用字符实体（character entities）。 字符实体类似这样：

```
&entity_name;或&#entity_number;
```

如需显示小于号，我们必须这样写：

```
<或<或<
```

渲染效果：`< 或 < 或 <`

> 
>
> 提示： 使用实体名而不是数字的好处是，名称易于记忆。不过坏处是，浏览器也许并不支持所有实体名称（对实体数字的支持却很好）。
>
> 

------

### 不间断空格(Non-breaking Space)

HTML 中的常用字符实体是不间断空格( )。

浏览器总是会截短 HTML 页面中的空格。如果您在文本中写 10 个空格，在显示该页面之前，浏览器会删除它们中的 9 个。如需在页面中增加空格的数量，您需要使用 字符实体。

------

### 结合音标符

发音符号是加到字母上的一个”glyph(字形)“。

一些变音符号, 如 尖音符 ( ̀) 和 抑音符 ( ́) 。

变音符号可以出现字母的上面和下面，或者字母里面，或者两个字母间。

变音符号可以与字母、数字字符的组合来使用。

以下是一些实例:

| 音标符 | 字符 | CONSTRUCT | 输出结果 |
| :----- | :--- | :-------- | :------- |
| ̀       | a    | à         | à        |
| ́       | a    | á         | á        |
| ̂       | a    | â         | â        |
| ̃       | a    | ã         | ã        |
| ̀       | O    | Ò         | Ò        |
| ́       | O    | Ó         | Ó        |
| ̂       | O    | Ô         | Ô        |
| ̃       | O    | Õ         | Õ        |

### HTML字符实体

> 
>
> 实体名称对大小写敏感！
>
> 

| 显示结果 | 描述        | 实体名称     | 实体编号 |
| :------- | :---------- | :----------- | :------- |
|          | 空格        |              |          |
| <        | 小于号      | <            | <        |
| >        | 大于号      | >            | >        |
| &        | 和号        | &            | &        |
| “        | 引号        | "            | "        |
| ‘        | 撇号        | ' (IE不支持) | '        |
| ￠       | 分          | ¢            | ¢        |
| £        | 镑          | £            | £        |
| ¥        | 人民币/日元 | ¥            | ¥        |
| €        | 欧元        | €            | €        |
| §        | 小节        | §            | §        |
| ©        | 版权        | ©            | ©        |
| ®        | 注册商标    | ®            | ®        |
| ™        | 商标        | ™            | ™        |
| ×        | 乘号        | ×            | ×        |
| ÷        | 除号        | ÷            | ÷        |

> 
>
> 虽然 html 不区分大小写，但实体字符对大小写敏感。
>
> 

------

## HTML 统一资源定位器

### HTML 统一资源定位器(Uniform Resource Locators)

------

URL 是一个网页地址。

URL可以由字母组成，如”axihe.com”，或互联网协议（IP）地址： 192.68.XX.xx。大多数人进入网站使用网站域名来访问，因为 名字比数字更容易记住。

------

### URL - 统一资源定位器

Web浏览器通过URL从Web服务器请求页面。

当您点击 HTML 页面中的某个链接时，对应的 标签指向万维网上的一个地址。

一个统一资源定位器(URL) 用于定位万维网上的文档。

一个网页地址实例语法规则:

```
scheme://host.domain:port/path/filename
```

说明:

- scheme - 定义因特网服务的类型。最常见的类型是 http/https/ftp/…
- host - 定义域主机（http 的默认主机是 www）
- domain - 定义因特网域名，比如 axihe.com
- :port - 定义主机上的端口号（http 的默认端口号是 80）
- path - 定义服务器上的路径（如果省略，则文档必须位于网站的根目录中）。
- filename - 定义文档/资源的名称

------

### 常见的 URL Scheme

以下是一些URL scheme：

| SCHEME | 访问               | 用于…                               |
| :----- | :----------------- | :---------------------------------- |
| http   | 超文本传输协议     | 以 http:// 开头的普通网页。不加密。 |
| https  | 安全超文本传输协议 | 安全网页，加密所有信息交换。        |
| ftp    | 文件传输协议       | 用于将文件下载或上传至网站。        |
| file   |                    | 您计算机上的文件。                  |

------

### URL 字符编码

URL 只能使用 ASCII 字符集.

来通过因特网进行发送。由于 URL 常常会包含 ASCII 集合之外的字符，URL 必须转换为有效的 ASCII 格式。

URL 编码使用 “%” 其后跟随两位的十六进制数来替换非 ASCII 字符。

URL 不能包含空格。URL 编码通常使用 + 来替换空格。

------

### URL 编码实例

| 字符 | URL 编码 |
| :--- | :------- |
| €    | %80      |
| £    | %A3      |
| ©    | %A9      |
| ®    | %AE      |
| À    | %C0      |
| Á    | %C1      |
| Â    | %C2      |
| Ã    | %C3      |
| Ä    | %C4      |
| Å    | %C5      |

------

## HTML 速查列表

### HTML 速查列表

=========

------

HTML 速查列表. 你可以打印它，以备日常使用。

------

### HTML 基本文档

```
<!DOCTYPE html><html><head><title>文档标题</title></head><body>可见文本...</body></html>
```

------

### 基本标签（Basic Tags）

```
<h1>最大的标题</h1><h2> . . . </h2><h3> . . . </h3><h4> . . . </h4><h5> . . . </h5><h6>最小的标题</h6><p>这是一个段落。</p><br> （换行）<hr> （水平线）<!-- 这是注释 -->
```

------

### 文本格式化（Formatting）

```
<b>粗体文本</b><code>计算机代码</code><em>强调文本</em><i>斜体文本</i><kbd>键盘输入</kbd><pre>预格式化文本</pre><small>更小的文本</small><strong>重要的文本</strong><abbr> （缩写）<address> （联系信息）<bdo> （文字方向）<blockquote> （从另一个源引用的部分）<cite> （工作的名称）<del> （删除的文本）<ins> （插入的文本）<sub> （下标文本）<sup> （上标文本）
```

------

### 链接（Links）

```
普通的链接：<a href="http://www.example.com/">链接文本</a>图像链接： <a href="http://www.example.com/"><img src="URL" alt="替换文本"></a>邮件链接： <a href="mailto:webmaster@example.com">发送e-mail</a>书签：<a id="tips">提示部分</a><a href="#tips">跳到提示部分</a>
```

------

### 图片（Images）

```
<imgsrc="URL"alt="替换文本"height="42"width="42">
```

------

### 样式/区块（Styles/Sections）

```
<styletype="text/css">h1 {color:red;}p {color:blue;}</style><div>文档中的块级元素</div><span>文档中的内联元素</span>
```

------

### 无序列表

```
<ul><li>项目</li><li>项目</li></ul>
```

------

### 有序列表

```
<ol><li>第一项</li><li>第二项</li></ol>
```

------

### 定义列表

```
<dl><dt>项目 1</dt><dd>描述项目 1</dd><dt>项目 2</dt><dd>描述项目 2</dd></dl>
```

------

### 表格（Tables）

```
<tableborder="1"><tr><th>表格标题</th><th>表格标题</th></tr><tr><td>表格数据</td><td>表格数据</td></tr></table>
```

------

### 架（Iframe）



![img](https://app.yinxiang.com/shard/s46/nl/32093335/48eebe92-dadd-4381-93e2-380255196cba/res/023d2e5b-d3b4-43d8-874d-8bef6ce7c938/kuangstudy8c4ba459-6379-407a-975b-31b42eee06e9.png?resizeSmall&width=832)



------

### 表单（Forms）

```
<formaction="demo_form.php"method="post/get"><inputtype="text"name="email"size="40"maxlength="50"><inputtype="password"><inputtype="checkbox"checked="checked"><inputtype="radio"checked="checked"><inputtype="submit"value="Send"><inputtype="reset"><inputtype="hidden"><select><option>苹果</option><optionselected="selected">香蕉</option><option>樱桃</option></select><textareaname="comment"rows="60"cols="20"></textarea></form>
```

------

### 实体（Entities）

```
<等同于```<>```等同于>©等同于©
```

------

## HTML 总结

### HTML 总结

本教程已教你如何使用 HTML 创建站点。

HTML 是一种在 Web 上使用的通用标记语言。HTML 允许你格式化文本，添加图片，创建链接、输入表单、框架和表格等等，并可将之存为文本文件，浏览器即可读取和显示。

HTML 的关键是标签，其作用是指示将出现的内容。

------

### 现在，你已学完HTML，接下来该学习什么呢？

------

### 学习 CSS

CSS被用来同时控制多重网页的样式和布局。

通过使用 CSS，所有的格式化均可从 HTML 中剥离出来，并存储于一个独立的文件中。

------

### 学习 JavaScript

JavaScript 可以让你的网页更加生动。

如果你只想展示内容，静态网站是很好的展示形象，如果你想与用户进行交换或者让网页更加生动那就需要使用到Javascript。

JavaScript是互联网上最流行的脚本语言，目前所有主流浏览器都支持Javascript。

------

### 站点服务器

在自己的服务器上托管网站始终是一个选项。有几点需要考虑：

#### 硬件支出

如果要运行”真正”的网站，您不得不购买强大的服务器硬件。不要指望低价的 PC 能够应付这些工作。您还需要稳定的（一天 24 小时）高速连接。

#### 软件支出

请记住，服务器授权通常比客户端授权更昂贵。同时请注意，服务器授权也许有用户数量限制。

### 3 人工费

不要指望低廉的人工费用。您必须安装自己的硬件和软件。您同时要处理漏洞和病毒，以确保您的服务器时刻正常地运行于一个”任何事都可能发生”的环境中。

------

### 使用因特网服务提供商（ISP）

从 ISP 租用服务器也很常见。

大多数小公司会把网站存放到由 ISP 提供的服务器上。其优势有以下几点：

#### 连接速度

大多数 ISP 都拥有连接因特网的高速连接。

#### 强大的硬件

ISP 的 web 服务器通常强大到能够由若干网站分享资源。您还要看一下 ISP 是否提供高效的负载平衡，以及必要的备份服务器。

#### 安全性和可靠性

ISP 是网站托管方面的专家。他们应该提供 99% 以上的在线时间，最新的软件补丁，以及最好的病毒防护。

------

### 选择 ISP 时的注意事项

#### 24 小时支持

确保 ISP 提供 24 小时支持。不要使自己置于无法解决严重问题的尴尬境地，同时还必须等待第二个工作日。如果您不希望支付长途电话费，那么免费电话服务也是必要的。

#### 每日备份

确保 ISP 会执行每日备份的例行工作，否则您有可能损失有价值的数据。

#### 流量

研究一下 ISP 的流量限制。如果出现由于网站受欢迎而激增的不可预期的访问量，那么您要确保不会因此支付额外费用。

#### 带宽或内容限制

研究一下 ISP 的带宽和内容限制。如果您计划发布图片或播出视频或音频，请确保您有此权限。

#### E-mail 功能

请确保 ISP 支持您需要的 e-mail 功能。

#### 数据库访问

如果您计划使用网站数据库中的数据，那么请确保您的 ISP 支持您需要的数据库访问。

------

## HTML - XHTML

### HTML - XHTML

------

XHTML 是以 XML 格式编写的 HTML。

------

### 什么是 XHTML?

- XHTML 指的是可扩展超文本标记语言
- XHTML 与 HTML4 几乎是相同的
- XHTML 是更严格更纯净的 HTML 版本
- XHTML 是以 XML 应用的方式定义的 HTML
- XHTML 是 2001 年 1 月 “W3C XHTML 活动” 发布的 W3C 推荐标准
- XHTML 得到所有主流浏览器的支持

------

### 为什么使用 XHTML?

因特网上的很多页面包含了”糟糕”的 HTML。

如果在浏览器中查看，下面的 HTML 代码运行起来非常正常（即使它并未遵守 HTML 规则）：

```
<html><head><metacharset="utf-8"><title>这是一个不规范的 HTML</title><body><h1>不规范的 HTML<p>这是一个段落</body>
```

XML 是一种必须正确标记且格式良好的标记语言。

今日的科技界存在一些不同的浏览器技术。其中一些在计算机上运行，而另一些可能在移动电话或其他小型设备上运行。小型设备往往缺乏解释”糟糕”的标记语言的资源和能力。

所以 - 通过结合 XML 和 HTML 的长处，开发出了 XHTML。XHTML 是作为 XML 被重新设计的 HTML。

------

### 与 HTML 相比最重要的区别：

#### 文档结构

XHTML DOCTYPE 是强制性的`<html>`中的 XML namespace 属性是强制性的 `<html>、<head>、<title> 以及 <body>` 也是强制性的

#### 元素语法

XHTML 元素必须正确嵌套 XHTML 元素必须始终关闭 XHTML 元素必须小写 XHTML 文档必须有一个根元素

#### 属性语法

XHTML 属性必须使用小写 XHTML 属性值必须用引号包围 XHTML 属性最小化也是禁止的

### <!DOCTYPE ….>是强制性的

XHTML 文档必须进行 XHTML 文档类型声明（XHTML DOCTYPE declaration）。

`<html>, <head>, <title>, 和 <body>` 元素也必须存在，并且必须使用 <html> 中的 xmlns 属性为文档规定 xml 命名空间。

下面的例子展示了带有最少的必需标签的 XHTML 文档：

```
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN""http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"><htmlxmlns="http://www.w3.org/1999/xhtml"><head><metacharset="utf-8"><title>文档标题</title></head><body>文档内容</body></html>
```

### XHTML 元素必须合理嵌套

在 HTML 中，一些元素可以不互相嵌套，像这样：

```
<b><i>粗体和斜体文本</b></i>
```

在 XHTML 中，所有的元素都必须互相合理地嵌套，像这样：

```
<b><i>粗体和斜体文本</i></b>
```

### XHTML 元素必须有关闭标签

错误示例：

```
<p>这是一个段落<p>这是另外一个段落
```

正确示例：

```
<p>这是一个段落</p><p>这是另外一个段落</p>
```

### 空元素必须包含关闭标签

错误示例：

```
分行:<br>水平线:<hr>图片:<img src="happy.gif" alt="Happy face">
```

正确示例：

```
分行:<br />水平线:<hr />图片:<img src="happy.gif" alt="Happy face"/>
```

### XHTML 元素必须是小写

错误示例:

```
<BODY><P>这是一个段落</P></BODY>
```

正确示例：

```
<body><p>这是一个段落</p></body>
```

### 属性名称必须是小写

错误示例：

```
<tableWIDTH="100%">
```

正确示例:

```
<tablewidth="100%">
```

## 属性值必须有引号

错误示例：

```
<tablewidth=100%>
```

正确示例：

```
<tablewidth="100%">
```

不允许属性简写 错误示例：

```
<inputchecked><inputreadonly><inputdisabled><optionselected>
```

正确示例：

```
<inputchecked="checked"><inputreadonly="readonly"><inputdisabled="disabled"><optionselected="selected">
```

### 如何将 HTML 转换为 XHTML

1. 添加一个 XHTML <!DOCTYPE> 到你的网页中
2. 添加 xmlns 属性添加到每个页面的html元素中。
3. 改变所有的元素为小写
4. 关闭所有的空元素
5. 修改所有的属性名称为小写
6. 所有属性值添加引号

------

## HTML 多媒体

### HTML 多媒体

------

Web 上的多媒体指的是音效、音乐、视频和动画。

现代网络浏览器已支持很多多媒体格式。

------

### 什么是多媒体？

多媒体来自多种不同的格式。它可以是您听到或看到的任何内容，文字、图片、音乐、音效、录音、电影、动画等等。

在因特网上，您会经常发现嵌入网页中的多媒体元素，现代浏览器已支持多种多媒体格式。

在本教程中，您将了解到不同的多媒体格式，以及如何在您的网页中使用它们。

------

### 浏览器支持

第一款因特网浏览器只支持文本，而且即使是对文本的支持也仅限于单一字体和单一颜色。随后诞生了支持颜色、字体和文本样式的浏览器，图片支持也被加入。

不同的浏览器以不同的方式处理对音效、动画和视频的支持。某些元素能够以内联的方式处理，而某些则需要额外的插件。

您将在下面的章节学习更多有关插件的知识。

------

### 多媒体格式

格式 多媒体元素（比如视频和音频）存储于媒体文件中。

确定媒体类型的最常用的方法是查看文件扩展名。当浏览器得到文件扩展名 .htm 或 .html 时，它会假定该文件是 HTML 页面。.xml 扩展名指示 XML 文件，而 .css 扩展名指示样式表。图片格式则通过 .gif 或 .jpg 来识别。

多媒体元素元素也拥有带有不同扩展名的文件格式，比如 .swf、.wmv、.mp3 以及 .mp4。

------

### 视频格式

MP4是互联网推出新的视频格式。

YouTube 推荐使用 MP4 。

Flash Players 支持 MP4

HTML5 支持 MP4。

| 格式      | 文件        | 描述                                                         |
| :-------- | :---------- | :----------------------------------------------------------- |
| AVI       | .avi        | AVI (Audio Video Interleave) 格式是由微软开发的。所有运行 Windows 的计算机都支持 AVI 格式。它是因特网上很常见的格式，但非 Windows 计算机并不总是能够播放。 |
| WMV       | .wmv        | Windows Media 格式是由微软开发的。Windows Media 在因特网上很常见，但是如果未安装额外的（免费）组件，就无法播放 Windows Media 电影。一些后期的 Windows Media 电影在所有非 Windows 计算机上都无法播放，因为没有合适的播放器。 |
| MPEG      | .mpg/.mpeg  | MPEG (Moving Pictures Expert Group) 格式是因特网上最流行的格式。它是跨平台的，得到了所有最流行的浏览器的支持。 |
| QuickTime | .mov        | QuickTime 格式是由苹果公司开发的。QuickTime 是因特网上常见的格式，但是 QuickTime 电影不能在没有安装额外的（免费）组件的 Windows 计算机上播放。 |
| RealVideo | .rm/.ram    | RealVideo 格式是由 Real Media 针对因特网开发的。该格式允许低带宽条件下（在线视频、网络电视）的视频流。由于是低带宽优先的，质量常会降低。 |
| Flash     | .swf / .flv | Flash (Shockwave) 格式是由 Macromedia 开发的。Shockwave 格式需要额外的组件来播放。但是该组件会预装到 Firefox 或 IE 之类的浏览器上。 |
| Mpeg-4    | .mp4        | Mpeg-4 (with H.264 video compression) 是一种针对因特网的新格式。事实上，YouTube 推荐使用 MP4。YouTube 接收多种格式，然后全部转换为 .flv 或 .mp4 以供分发。越来越多的视频发布者转到 MP4，将其作为 Flash 播放器和 HTML5 的因特网共享格式。 |

> 
>
> 最新的 HTML5 标准只支持 MP4, WebM, 和 Ogg 视频格式。
>
> 

### 声音格式

MP3是一种音频压缩技术，其全称是动态影像专家压缩标准音频层面3（Moving Picture Experts Group Audio Layer III），简称为MP3。它被设计用来大幅度地降低音频数据量。如果你的站点是音乐类型的，你可以选择mp3格式。

| 格式      | 文件        | 描述                                                         |
| :-------- | :---------- | :----------------------------------------------------------- |
| MIDI      | .mid/ .midi | MIDI (Musical Instrument Digital Interface) 是一种针对电子音乐设备（比如合成器和声卡）的格式。MIDI 文件不含有声音，但包含可被电子产品（比如声卡）播放的数字音乐指令。 因为 MIDI 格式仅包含指令，所以 MIDI 文件极其小巧。上面的例子只有 23k 的大小，但却能播放将近 5 分钟。MIDI 得到了广泛的平台上的大量软件的支持。大多数流行的网络浏览器都支持 MIDI。 |
| RealAudio | .rm/.ram    | RealAudio 格式是由 Real Media 针对因特网开发的。该格式也支持视频。该格式允许低带宽条件下的音频流（在线音乐、网络音乐）。由于是低带宽优先的，质量常会降低。 |
| Wave      | .wav        | Wave (waveform) 格式是由 IBM 和微软开发的。所有运行 Windows 的计算机和所有网络浏览器（除了 Google Chrome）都支持它。 |
| WMA       | .wma        | WMA 格式 (Windows Media Audio)，质量优于 MP3，兼容大多数播放器，除了 iPod。WMA 文件可作为连续的数据流来传输，这使它对于网络电台或在线音乐很实用。 |
| MP3       | .mp3/.mpga  | MP3 文件实际上是 MPEG 文件的声音部分。MPEG 格式最初是由运动图像专家组开发的。MP3 是其中最受欢迎的针对音乐的声音格式。期待未来的软件系统都支持它。 |

> 
>
> HTML5 的最新标准支持 MP3, WAV, 和 Ogg 音频格式。
>
> 

------

## HTML 插件

### HTML 插件

------

插件的功能是扩展 HTML 浏览器的功能。

------

### HTML 助手（插件）

辅助应用程序（helper application）是可由浏览器启动的程序。辅助应用程序也称为插件。

辅助程序可用于播放音频和视频（以及其他）。辅助程序是使用 标签来加载的。

使用辅助程序播放视频和音频的一个优势是，您能够允许用户来控制部分或全部播放设置。

插件可以通过 标签或者 标签添加在页面中。

大多数辅助应用程序允许对音量设置和播放功能（比如后退、暂停、停止和播放）的手工（或程序的）控制。

我们可以使用`<video>` 和 `<audio>` 标签来显示视频和音频

------

### `<object>` 元素

所有主流浏览器都支持 `<object>` 标签。

`<object>` 元素定义了在 HTML 文档中嵌入的对象。

该标签用于插入对象 (例如在网页中嵌入 Java 小程序, PDF 阅读器, Flash 播放器) 。

```
<objectwidth="400"height="50"data="bookmark.swf"></object>
```

`<object>` 元素同样可用于包含HTML文件：

```
<objectwidth="100%"height="500px"data="snippet.html"></object>
```

或者插入一张图片:

```
<objectdata="audi.jpeg"></object>
```

------

### `<embed>`元素

所有主流浏览器都支持 `<embed>` 元素。

`<embed>` 元素表示一个 HTML Embed 对象 。

<embed> 元素已经出现很长一段时间了，但是在 HTML5 前并未被详细说明，该元素在 HTML 5 页面上会被验证，在 HTML 4 上不会。

```
<embedwidth="400"height="50"src="bookmark.swf">
```

> 
>
> 注意 元素没有关闭标签。 不能使用替代文本。
>
> 

`<embed>` 元素同样可用于包含 HTML 文件：

```
<embedwidth="100%"height="500px"src="snippet.html">
```

或者插入一张图片:

实例

```
<embedsrc="audi.jpeg">
```

------

## HTML 音频(Audio)

### HTML 音频(Audio)

------

声音在HTML中可以以不同的方式播放.

------

### 问题以及解决方法

在 HTML 中播放音频并不容易！

您需要谙熟大量技巧，以确保您的音频文件在所有浏览器中（Internet Explorer, Chrome, Firefox, Safari, Opera）和所有硬件上（PC, Mac , iPad, iPhone）都能够播放。

------

### 使用插件

浏览器插件是一种扩展浏览器标准功能的小型计算机程序。

插件可以使用 标签 或者 标签添加在页面上.

这些标签定义资源（通常非 HTML 资源）的容器，根据类型，它们即会由浏览器显示，也会由外部插件显示。

------

### 使用 `<embed>` 元素

标签定义外部（非 HTML）内容的容器。（这是一个 HTML5 标签，在 HTML4 中是非法的，但是所有浏览器中都有效）。

下面的代码片段能够显示嵌入网页中的 MP3 文件：

```
<embedheight="50"width="100"src="horse.mp3">
```

#### **问题:**

- 标签在 HTML 4 中是无效的。页面无法通过 HTML 4 验证。
- 不同的浏览器对音频格式的支持也不同。
- 如果浏览器不支持该文件格式，没有插件的话就无法播放该音频。
- 如果用户的计算机未安装插件，无法播放音频。
- 如果把该文件转换为其他格式，仍然无法在所有浏览器中播放。

------

### 使用 `<object>` 元素

标签也可以定义外部（非 HTML）内容的容器。

下面的代码片段能够显示嵌入网页中的 MP3 文件：

```
<objectheight="50"width="100"data="horse.mp3"></object>
```

#### **问题:**

- 不同的浏览器对音频格式的支持也不同。
- 如果浏览器不支持该文件格式，没有插件的话就无法播放该音频。
- 如果用户的计算机未安装插件，无法播放音频。
- 如果把该文件转换为其他格式，仍然无法在所有浏览器中播放。

------

### 使用 HTML5 `<audio>`元素

HTML5

元素是一个 HTML5 元素，在 HTML 4 中是非法的，但在所有浏览器中都有效。

### 流量器兼容

格中的数字表示支持该属性的第一个浏览器版本号。

| 元素 | CHROME | IE   | 火狐 | SAFARI |
| :--- | :----- | :--- | :--- | :----- |
|      | 4.0    | 9.0  | 3.5  | 4.0    |

以下我们将使用

以下我们将使用`<audio>`标签来描述 MP3 文件(Internet Explorer、Chrome 以及 Safari 中是有效的), 同样添加了一个 OGG 类型文件(Firefox 和 Opera浏览器中有效).如果失败，它会显示一个错误文本信息:

实例

```
<audiocontrols><sourcesrc="horse.mp3"type="audio/mpeg"><sourcesrc="horse.ogg"type="audio/ogg">  Your browser does not support this audio format.</audio>
```

#### **问题:**

- 标签在 HTML 4 中是无效的。您的页面无法通过 HTML 4 验证。
- 您必须把音频文件转换为不同的格式。
- 元素在老式浏览器中不起作用。

------

### 最好的 HTML 解决方法

下面的例子使用了两个不同的音频格式。HTML5 `<audio>` 元素会尝试以 mp3 或 ogg 来播放音频。如果失败，代码将回退尝试 `<embed>` 元素。

```
<audiocontrolsheight="100"width="100"><sourcesrc="horse.mp3"type="audio/mpeg"><sourcesrc="horse.ogg"type="audio/ogg"><embedheight="50"width="100"src="horse.mp3"></audio>
```

#### **问题:**

- 您必须把音频转换为不同的格式。
- 元素无法回退来显示错误消息。

------

### 使用超链接

如果网页包含指向媒体文件的超链接，大多数浏览器会使用”辅助应用程序”来播放文件。

以下代码片段显示指向 mp3 文件的链接。如果用户点击该链接，浏览器会启动”辅助应用程序”来播放该文件：

实例

```
<ahref="horse.mp3">Play the sound</a>
```

------

### 内联的声音说明

当您在网页中包含声音，或者作为网页的组成部分时，它被称为内联声音。

如果您打算在 web 应用程序中使用内联声音，您需要意识到很多人都觉得内联声音令人恼火。同时请注意，用户可能已经关闭了浏览器中的内联声音选项。

我们最好的建议是只在用户希望听到内联声音的地方包含它们。一个正面的例子是，在用户需要听到录音并点击某个链接时，会打开页面然后播放录音。

------

### HTML 多媒体标签

New : HTML5 新标签

| 标签       | 描述                                                         |
| :--------- | :----------------------------------------------------------- |
| embed>     | 定义内嵌对象。HTML4 中不赞成，HTML5 中允许。                 |
| object>    | 定义内嵌对象。                                               |
| param>     | 定义对象的参数。                                             |
| audio>New  | 定义了声音内容                                               |
| video>New  | 定义一个视频或者影片                                         |
| source>New | 定义了media元素的多媒体资源`(<video> 和 <audio>)`            |
| track>New  | 规定media元素的字幕文件或其他包含文本的文件`(<video> 和<audio>`) |

------

## HTML 视频（Videos）

### HTML 视频（Videos）

------

在 HTML 中播放视频的方法有很多种。

------

### HTML视频（Videos）播放

```
<videowidth="320"height="240"controls><sourcesrc="movie.mp4"type="video/mp4"><sourcesrc="movie.ogg"type="video/ogg"><sourcesrc="movie.webm"type="video/webm"><objectdata="movie.mp4"width="320"height="240"><embedsrc="movie.swf"width="320"height="240"></object></video>
```

------

### 问题以及解决方法

在 HTML 中播放视频并不容易！

您需要谙熟大量技巧，以确保您的视频文件在所有浏览器中（Internet Explorer, Chrome, Firefox, Safari, Opera）和所有硬件上（PC, Mac , iPad, iPhone）都能够播放。

------

### 使用 `<embed>` 标签

标签的作用是在 HTML 页面中嵌入多媒体元素。

下面的 HTML 代码显示嵌入网页的 Flash 视频：

```
<embedsrc="intro.swf"height="200"width="200">
```

**问题**

- HTML4 无法识别 `<embed>`标签。您的页面无法通过验证。
- 如果浏览器不支持 Flash，那么视频将无法播放
- iPad 和 iPhone 不能显示 Flash 视频。
- 如果您将视频转换为其他格式，那么它仍然不能在所有浏览器中播放。

------

### 使用 `<object>`标签

标签的作用是在 HTML 页面中嵌入多媒体元素。

下面的 HTML 片段显示嵌入网页的一段 Flash 视频：

```
<objectdata="intro.swf"height="200"width="200"></object>
```

**问题:**

- 如果浏览器不支持 Flash，将无法播放视频。
- iPad 和 iPhone 不能显示 Flash 视频。
- 如果您将视频转换为其他格式，那么它仍然不能在所有浏览器中播放。

------

### 使用 HTML5 元素

HTML5`<video>` 标签定义了一个视频或者影片.

<video> 元素在所有现代浏览器中都支持。

以下 HTML 片段会显示一段嵌入网页的 ogg、mp4 或 webm 格式的视频：

```
<videowidth="320"height="240"controls><sourcesrc="movie.mp4"type="video/mp4"><sourcesrc="movie.ogg"type="video/ogg"><sourcesrc="movie.webm"type="video/webm">    您的浏览器不支持 video 标签。</video>
```

**问题:**

- 您必须把视频转换为很多不同的格式。
- 元素在老式浏览器中无效。

------

### 最好的 HTML 解决方法

以下实例中使用了 4 中不同的视频格式。HTML 5`<video>` 元素会尝试播放以 mp4、ogg 或 webm 格式中的一种来播放视频。如果均失败，则回退到 `<embed>` 元素。

```
<videowidth="320"height="240"controls><sourcesrc="movie.mp4"type="video/mp4"><sourcesrc="movie.ogg"type="video/ogg"><sourcesrc="movie.webm"type="video/webm"><objectdata="movie.mp4"width="320"height="240"><embedsrc="movie.swf"width="320"height="240"></object></video>
```

**问题:**

- 您必须把视频转换为很多不同的格式

------

### 优酷解决方案

在 HTML 中显示视频的最简单的方法是使用优酷等视频网站。

如果您希望在网页中播放视频，那么您可以把视频上传到优酷等视频网站，然后在您的网页中插入 HTML 代码即可播放视频。

你可以在各大视频网站的分享入口，找到嵌入的 HTML 代码。

```
<embedsrc='https://player.youku.com/player.php/sid/XMTQ3MjM5Mjc0MA==/v.swf'allowFullScreen='true'quality='high'width='480'height='400'align='middle'allowScriptAccess='always'type='application/x-shockwave-flash'></embed>
```

------

### 使用超链接

如果网页包含指向媒体文件的超链接，大多数浏览器会使用”辅助应用程序”来播放文件。

以下代码片段显示指向 AVI 文件的链接。如果用户点击该链接，浏览器会启动”辅助应用程序”，比如 Windows Media Player 来播放这个 AVI 文件：

```
<ahref="intro.swf">Play a video file</a>
```

------

### 关于内联视频的说明

当视频被包含在网页中时，它被称为内联视频。

如果您打算在 web 应用程序中使用内联视频，您需要意识到很多人都觉得内联视频令人恼火。

同时请注意，用户可能已经关闭了浏览器中的内联视频选项。

我们最好的建议是只在用户希望看到内联视频的地方包含它们。一个正面的例子是，在用户需要看到视频并点击某个链接时，会打开页面然后播放视频。

------

### HTML 多媒体标签

New : HTML5新标签.

| 标签          | 描述                                                         |
| :------------ | :----------------------------------------------------------- |
| `<embed>`     | 定义内嵌对象。HTML4 中不赞成，HTML5 中允许。                 |
| `<object>`    | 定义内嵌对象。                                               |
| `<param>`     | 定义对象的参数。                                             |
| `<audio>`New  | 定义了声音内容                                               |
| `<video>`New  | 定义一个视频或者影片                                         |
| `<source>`New | 定义了media元素的多媒体资源(`<video> 和 <audio>`)            |
| `<track>`New  | 规定media元素的字幕文件或其他包含文本的文件 (`<video> 和 <audio>`) |