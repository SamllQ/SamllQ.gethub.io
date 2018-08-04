<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=gb2312">
<meta name=Generator content="Microsoft Word 15 (filtered)">
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:宋体;
	panose-1:2 1 6 0 3 1 1 1 1 1;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;}
@font-face
	{font-family:"\@宋体";
	panose-1:2 1 6 0 3 1 1 1 1 1;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin:0cm;
	margin-bottom:.0001pt;
	text-align:justify;
	text-justify:inter-ideograph;
	font-size:10.5pt;
	font-family:"Calibri","sans-serif";}
.MsoChpDefault
	{font-family:"Calibri","sans-serif";}
 /* Page Definitions */
 @page WordSection1
	{size:595.3pt 841.9pt;
	margin:72.0pt 90.0pt 72.0pt 90.0pt;
	layout-grid:15.6pt;}
div.WordSection1
	{page:WordSection1;}
-->
</style>

</head>

<body lang=ZH-CN style='text-justify-trim:punctuation'>

<div class=WordSection1 style='layout-grid:15.6pt'>

<p class=MsoNormal><b><span style='font-family:宋体'>作用：帮助我们初始化对象</span><span
lang=EN-US>(</span></b><b><span style='font-family:宋体'>给对象的每个属性依次的赋值</span><span
lang=EN-US>)</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>构造函数是一个特殊的方法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>1)</span></b><b><span style='font-family:
宋体'>、构造函数没有返回值，连</span><span lang=EN-US>void</span></b><b><span
style='font-family:宋体'>也不能写。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>2)</span></b><b><span style='font-family:
宋体'>、构造函数的名称必须跟类名一样。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>创建对象的时候会执行构造函数</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>构造函数是可以有重载的。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>***</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>类当中会有一个默认的无参数的构造函数，当你写一个新的构造函数之后，不管是有参数的还是</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>无参数的，那个默认的无参数的构造函数都被干掉了。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>语法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Public Class A()</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Public
A()</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Public
A(int a)</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Public
A(int a,string b)</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>//</span></b><b><span
style='font-family:宋体'>构造函数可重载</span></b></p>

<p class=MsoNormal style='margin-left:21.0pt'><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

</div>

</body>

</html>
