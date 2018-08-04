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
	{font-family:"\@新宋体";
	panose-1:2 1 6 9 3 1 1 1 1 1;}
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

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>namespace</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> _03</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:black'>简单工厂设计模式</span></b></p>

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
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Console</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>请输入您想要的笔记本品牌<span
lang=EN-US>&quot;</span></span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>string</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>brand</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>ReadLine</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>NoteBook</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>nb</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetNoteBook</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>brand</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:navy'>nb</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:
新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:#880000'>SayHello</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
font-family:新宋体;color:green'>简单工厂的核心 根据用户的输入创建对象赋值给父类</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>brand</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:gray'>&quot;&gt;&lt;/param&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;returns&gt;&lt;/returns&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>static</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>NoteBook</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetNoteBook</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>brand</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>NoteBook</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>nb</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>null</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>switch</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> (</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>brand</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>case</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#A31515'>&quot;Lenovo&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>: </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>nb</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Lenovo</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>break</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>case</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#A31515'>&quot;IBM&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>: </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>nb</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>IBM</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>break</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>case</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#A31515'>&quot;Acer&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>: </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>nb</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Acer</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>break</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>case</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#A31515'>&quot;Dell&quot;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>: </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>nb</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Dell</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>break</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>return</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>nb</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

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
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>abstract</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>NoteBook</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>abstract</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>SayHello</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Lenovo</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>NoteBook</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>override</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>SayHello</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是联想笔记本，你联想也别想<span
lang=EN-US>&quot;</span></span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Acer</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>NoteBook</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>override</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>SayHello</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是鸿基笔记本<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

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
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Dell</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>NoteBook</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>override</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>SayHello</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是戴尔笔记本<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

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
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>IBM</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>NoteBook</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>override</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>SayHello</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是<span lang=EN-US>IBM</span>笔记本<span
lang=EN-US>&quot;</span></span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:black'>}</span></b></p>

</div>

</body>

</html>
