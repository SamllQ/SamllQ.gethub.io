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

<p class=MsoNormal><span lang=EN-US>Out</span><span style='font-family:宋体'>参数</span></p>

<p class=MsoNormal><span style='font-family:宋体'>如果你在一个方法中，返回多个相同类型值的时候，可以考虑返回一个数组，</span></p>

<p class=MsoNormal><span style='font-family:宋体'>但是如果返回多个不同类型的值的时候，返回数组就不行了，那么这个时候</span></p>

<p class=MsoNormal><span style='font-family:宋体'>我们可以考虑使用</span><span
lang=EN-US>Out</span><span style='font-family:宋体'>参数。</span></p>

<p class=MsoNormal><span lang=EN-US>Out</span><span style='font-family:宋体'>侧重于在一个方法中返回多个不同类型的值，当然也可以返回多个相同</span></p>

<p class=MsoNormal><span style='font-family:宋体'>类型的值。</span></p>

<p class=MsoNormal><span lang=EN-US>Public void Test(out int max)</span></p>

<p class=MsoNormal><span lang=EN-US>{</span></p>

<p class=MsoNormal><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Out</span><span
style='font-family:宋体'>参数要求在方法内部必须为其赋值。</span></p>

<p class=MsoNormal><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Max
= 0;</span></p>

<p class=MsoNormal><span lang=EN-US>}</span></p>

<p class=MsoNormal><span lang=EN-US>Int max = 0;</span></p>

<p class=MsoNormal><span lang=EN-US>Test(out max);</span></p>

</div>

</body>

</html>

#ref

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

<p class=MsoNormal><b><span style='font-family:宋体'>能够将一个变量带入一个方法中进行改变，改变完成后，再讲改变后的值带出方法。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>ref</span></b><b><span style='font-family:
宋体'>参数要求在方法外必须为其赋值，而方法内可以不赋值。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>语法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Void Start()</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Int
b = 50;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a(ref
b);</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>print(b=550);</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Public void a(ref int b)</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; b+=500;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

</div>

</body>

</html>

#params

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

<p class=MsoNormal><b><span style='font-family:宋体'>将实参列表中跟可变参数数组类型一致的元素都当做数组的元素去处理。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>params</span></b><b><span
style='font-family:宋体'>可变参数必须是形参列表中的最后一个元素。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>语法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Public void Test(params int[] num)</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

</div>

</body>

</html>


