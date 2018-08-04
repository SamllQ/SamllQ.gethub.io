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
	{font-family:新宋体;
	panose-1:2 1 6 9 3 1 1 1 1 1;}
@font-face
	{font-family:"\@宋体";
	panose-1:2 1 6 0 3 1 1 1 1 1;}
@font-face
	{font-family:"\@新宋体";
	panose-1:2 1 6 9 3 1 1 1 1 1;}
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

<p class=MsoNormal><b><span style='font-family:宋体;color:red;background:yellow'>泛型类定义：</span></b><b><span
style='font-family:宋体;color:red'>一个泛型类是指的是，顶一个个嘞，这个类中的某些字段的类型是不确定的，这些类型可以在类构造的时候确定下来</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Collections</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Generic</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Linq</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Text</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Threading</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Tasks</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>namespace</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:blue'>泛型类</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>class</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#2B91AF'>Program</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>static</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Main</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>[] </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>args</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>var</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>ak</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>ClassA</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&lt;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&gt;(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;8888&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;77777&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Console</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ak</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetSum</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>());</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Console</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>ReadKey</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>class</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#2B91AF'>ClassA</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>&lt;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>T</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&gt;&nbsp; </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>泛型类定义的时候需要在类名后面加<span
lang=EN-US>&lt;T:</span>代表类型<span lang=EN-US>&gt;</span></span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;summary&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> T</span></b><b><span style='font-size:9.5pt;
font-family:新宋体;color:green'>类型的变量 （类型不知，需要在构造函数里面给<span lang=EN-US>T</span>指定类型）</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;/summary&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>T</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>num</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;summary&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> T</span></b><b><span style='font-size:9.5pt;
font-family:新宋体;color:green'>类型的变量（类型不知，需要在构造函数里面给<span lang=EN-US>T</span>指定类型）</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;/summary&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>T</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>num1</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;summary&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span style='font-size:9.5pt;
font-family:新宋体;color:green'>泛型类的构造函数</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;/summary&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;param name=&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>a</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:gray'>&quot;&gt;&lt;/param&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;param name=&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>b</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:gray'>&quot;&gt;&lt;/param&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>ClassA</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>T</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>a</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>T</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>b</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>this</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>num</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>a</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>this</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>num1</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>b</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetSum</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()&nbsp; </span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>return</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>num</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> +</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>+ </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>num1</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体;color:red;background:yellow'>泛型方法：</span></b><b><span
style='font-family:宋体;color:red'>定义泛型方法就是定义一个方法，这个方法的参数的类型可以是不确定的，当调用这个方法的时候再去确定方法的参数的类型</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Collections</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Generic</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Linq</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Text</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Threading</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Tasks</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>namespace</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:blue'>泛型类</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>class</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#2B91AF'>Program</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>static</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetAdd</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&lt;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>T</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&gt;(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>T</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>a</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>,</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>T</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>b</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>return</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>a</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> +</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>+ </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>b</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>static</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Main</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>[] </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>args</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Console</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetAdd</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(55,88));</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Console</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetAdd</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;5&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;ss&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>));</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Console</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetAdd</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;5655565&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>,</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;88dsd&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>));</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Console</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>ReadKey</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>}</span></b></p>

<p class=MsoNormal style='text-indent:10.55pt'><b><span lang=EN-US
style='color:red'>&nbsp;</span></b></p>

</div>

</body>

</html>
