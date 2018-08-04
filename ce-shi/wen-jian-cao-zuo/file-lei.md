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
	{size:612.0pt 792.0pt;
	margin:72.0pt 90.0pt 72.0pt 90.0pt;}
div.WordSection1
	{page:WordSection1;}
-->
</style>

</head>

<body lang=ZH-CN style='text-justify-trim:punctuation'>

<div class=WordSection1>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>IO</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>namespace</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>File_</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:blue'>类</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>// File</span></b><b><span style='font-size:9.5pt;font-family:
新宋体;color:green'>类只能读小文件</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//1</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、创建文件方法</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>参数<span lang=EN-US>1</span>：要创建的文件路径</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.Create</span></b><b><span style='font-size:9.5pt;
font-family:新宋体;color:black'>（</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug1\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>.txt&quot;</span></span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:black'>）</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//2</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、打开文件方法</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>参数<span lang=EN-US>1</span>：要打开的文件路径，参数<span lang=EN-US>2</span>：打开的文件方式</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>Open</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug1\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>.txt&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>FileMode</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Append</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//3</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、追加文件方法</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>参数<span lang=EN-US>1</span>：要追加的文件路径，参数<span lang=EN-US>2</span>：追加的内容</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>AppendAllText</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug1\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>.txt&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>哈哈<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//4</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、复制文件方法</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>参数<span lang=EN-US>1</span>：要复制的源文件路径，参数<span lang=EN-US>2</span>：复制后的目标文件路径，参数<span
lang=EN-US>3</span>：是否覆盖相同文件名</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>Copy</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug1\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>.txt&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug2\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>1.txt&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>true</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//5</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、移动文件方法</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>参数<span lang=EN-US>1</span>：要移动的源文件路径，参数<span lang=EN-US>2</span>：移动后的目标文件路径</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#A000A0'>Move</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug1\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>.txt&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug3\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>2.txt&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>// 6</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、删除文件方法</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>参数<span lang=EN-US>1</span>：要删除的文件路径</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>Delete</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug1\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>.txt&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//7</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、设置文件属性方法</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>参数<span lang=EN-US>1</span>：要设置属性的文件路径，参数<span lang=EN-US>2</span>：设置的属性类型（只读、隐藏等）</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:navy'>SetAttributes</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:maroon'>@&quot;D:\Test\Debug1\</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:maroon'>测试<span lang=EN-US>.txt&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>FileAttributes</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A000A0'>Hidden</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//8</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、写入（需要将字符串转为字节数组）</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>string</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>str</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>写入的内容<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>byte</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>[] </span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:navy'>buffer</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Encoding</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Default</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>GetBytes</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>str</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteAllBytes</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>路径<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>,</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>buffer</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//9</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、以行的形式进行读取<span lang=EN-US>&nbsp; </span>只能读文本文件 读取返回一个字符数组</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>string</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>[] </span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:navy'>contents</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>File</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>ReadAllLines</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>文件路径<span lang=EN-US>/</span>文件<span
lang=EN-US>&quot;</span></span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>, </span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:blue'>Encoding</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Default</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>后面是编码格式</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//10</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、读取文本文件，读取返回字符串</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:#880000'>ReadAllText</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>文件路径<span lang=EN-US>/</span>文件<span
lang=EN-US>&quot;</span></span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>, </span></b><b><i><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:blue'>Encoding</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Default</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>后面是编码</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//11</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>、不覆盖写入</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>File</span></i></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>AppendAllText</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>路径<span lang=EN-US>/</span>文件名<span
lang=EN-US>.</span>后缀<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>,</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>内容<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

</div>

</body>

</html>
