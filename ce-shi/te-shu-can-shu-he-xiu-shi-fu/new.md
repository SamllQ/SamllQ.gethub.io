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

<p class=MsoNormal><b><span style='font-family:宋体'>在</span><span lang=EN-US> C#
</span></b><b><span style='font-family:宋体'>中，</span><span lang=EN-US>new </span></b><b><span
style='font-family:宋体'>关键字可用作运算符、修饰符或约束。</span><span lang=EN-US><br>
1</span></b><b><span style='font-family:宋体'>）</span><span lang=EN-US>new </span></b><b><span
style='font-family:宋体'>运算符：用于创建对象和调用构造函数。这种大家都比较熟悉，没什么好说的了。</span><span
lang=EN-US><br>
2</span></b><b><span style='font-family:宋体'>）</span><span lang=EN-US>new </span></b><b><span
style='font-family:宋体'>修饰符：在用作修饰符时，</span><span lang=EN-US>new </span></b><b><span
style='font-family:宋体'>关键字可以显式隐藏从基类继承的成员。</span><span lang=EN-US><br>
3</span></b><b><span style='font-family:宋体'>）</span><span lang=EN-US>new </span></b><b><span
style='font-family:宋体'>约束：用于在泛型声明中约束可能用作类型参数的参数的类型。</span><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>4</span></b><b><span style='font-family:
宋体'>）</span><span lang=EN-US>new </span></b><b><span style='font-family:宋体'>隐藏从父类继承过来的成员</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span style='font-family:宋体'>隐藏的后果是子类调用不到父类的成员</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span style='font-family:宋体;
color:red'>语法：</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span style='font-family:宋体;
color:red'>子类：</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US
style='color:red'>Public new A()</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US
style='color:red'>{</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US
style='color:red'>&nbsp;</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US
style='color:red'>}</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span style='font-family:宋体;
color:red'>父类：</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US
style='color:red'>Public new A()</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US
style='color:red'>{</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US
style='color:red'>&nbsp;</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US
style='color:red'>}</span></b></p>

<p class=MsoNormal style='text-indent:21.0pt'><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>new</span></b><b><span style='font-family:
宋体'>帮助我们做了</span><span lang=EN-US>3</span></b><b><span style='font-family:宋体'>件事儿：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>1)</span></b><b><span style='font-family:
宋体'>、在内存中开辟一块空间</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>2)</span></b><b><span style='font-family:
宋体'>、在开辟的空间中创建对象</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>3)</span></b><b><span style='font-family:
宋体'>、调用对象的构造函数进行初始化对象</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>语法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Person zsPerson=new Person();</span></b></p>

<p class=MsoNormal><span lang=EN-US>&nbsp;</span></p>

</div>

</body>

</html>
