# HTML
Study html

###Chapter 1

How to create a HTML file.

###Chapter 2

The basic knowledge:

结构化标记：描述标题和段落的元素
语义化标记：特定含义的标记，强调、缩写。。。
标题：<h1>,<h2>,<h3>,<h4>,<h5>,<h6>
段落：<p>
粗体：<b>
斜体：<i>
上标：<sup>
下标：<sub>
空白：增强代码阅读性，多个空格和换行，均为一个空格－－－－－－－白色空间折叠
换行：<br />
水平线：<hr />
加粗和强调：<strong>,<em>
标记引用：<blockquote>,<q>
缩写词和首字母缩写词：<abbr title="">
引用和定义：<cite>,<dfn>
设计者详细信息：<address>
内容的修改：删除<del>，插入<ins>，<s>不准确或不相关却并不应当予以删除的内容

###Chapter 3

Lists:

顺序列表：<ol>,<li>
无序列表：<ul>,<li>
自定义列表：<dl>,<dt>,<dd>

###Chapter 4

链接：<a>
邮箱：<mailto>
新窗口：<target>

###Chapter 5

图片：<img src:"图片路径" alt:"文本说明" title:"停留信息"/>
高度宽度：height，weight
代码插入头像
水平对其方式：align: right,left,top,middle,bottom

###Chapter 6

表：<table>
行：<tr> <td>
标题：<th> scope="col" scope="row"
跨列，跨行：colspan rowspan
长表格：<thead> <tbody> <tfoot>

表格宽度，单元格内边距，单元格间距：width,cellpadding,cellspacing
边框宽度，背景色：border，bgcolor

###Chapter 7

表单结构：<form> action method id size 
单行文本框: <input> type[text] name maxlength 
密码框：<input> type[password] name size maxlength
文本域；<textarea>
单选按钮：<input> type[radio] name value checked
复选框：<input> type[checkbox] name value checked
下拉列表框：<select> name <option> value selected
多选框：<select> size multiple
文件上传域：<input> type[file]
提交按钮：<input> type[submit] name value
头像按钮: <input> type[image]
按钮和隐藏控件：<button> <input> type[hidden]
标签表单控件：<label> for id 
组合表单元素： <fieldset> <legend>
HTML5:
表单验证：required
日期控件：<input> type[date]
电子邮件：<input> type[email]
URL: <input> type[url]
搜索输入控件：<input> type[search] placeholder

###Chapter 8

注释：<!--  -->
id: 元素唯一标识
class: 设置多个元素特性
块级元素： <h1> <p> <ul> <li>
内联元素： <a> <b> <em> <img>
将文本和元素集中在一个块级元素中：<div>
将文本和元素集中在一个内联元素中：<span>
内联框架：<iframe>
页面信息：<meta>
转义字符：

###Chapter 9

Flash 音视频
视频:<video> src poster width height controls autoplay loop preload[none auto metadata]
多个视频源：<source> src type codecs
音频：<audio> src controls autoplay preload loop
多个音频源：<source> src type

###Chapter 10

CSS
使用外部CSS：<link> href type[text/css] rel[stylesheet]
使用内部CSS：<style>
选择器：
通用：*{}
类型：h1, h2 {}
ID:#introduction {}
子元素：li>a{}
后代： p a {}
相邻兄弟：h1 + p {}
普通兄弟：h1~p {]

###Chapter 11

CSS Color

红绿蓝
色调
饱和度
亮度

RGB
HSL
十六进制
颜色名

###Chapter 12

Font
字体选用：font-family
字体大小：font-size 像素 百分数 em
选用更多字体：@font-face font-family src format
字体格式：eot woff ttf/otf svg
粗体：font-weight bold normal
斜体：font-style normal italic oblique
大小写：text-transform  uppercase  lowercase  capitalize 
下划线和删除线：text-decoration none underline overline line-through blink
行间距：line-height 
字母间距和单词间距：letter-spacing word-spacing
对齐方式：text-align left right center justify
垂直对齐：vertical-align baseline sub super top text-top middle bottom text-bottom
文本缩进：text-indent
投影：text-shadow
首字母、首行文本：first-letter first-line 
链接样式：:link :visitd :hover :active :focus 

特性选择器：
EXISTENCE（简单选择器）：p[class]
EQUALITY（精确选择器）：p[class="dog"]
SPACE（部分选择器）：p[class~="dog"]
PREFIX（开头选择器）：p[attr^"d"]
SUBSTRING（包含选择器）:p[attr*"do"]
SUFFIX（结尾选择器）：p[attr$"g"]




































