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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>namespace</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> _09</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:black'>多态</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>class</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#2B91AF'>Program</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-indent:21.0pt;
text-autospace:none'><b><span lang=EN-US style='font-size:9.5pt;font-family:
新宋体;color:black'>{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-indent:21.0pt;
text-autospace:none'><b><span lang=EN-US style='font-size:9.5pt;font-family:
新宋体;color:black'>&nbsp;</span></b></p>

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
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>概念<span lang=EN-US>:</span>让一个对象能够表现出多种的状态<span lang=EN-US>(</span>类型<span
lang=EN-US>) </span></span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>实现多态的<span lang=EN-US>3</span>种手段：<span lang=EN-US>1</span>、虚方法 </span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; //</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>虚方法可以不被重写</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Chinese</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>cn1</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Chinese</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>韩梅梅<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Chinese</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>cn2</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Chinese</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>李雷<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Japanese</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>j1</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Japanese</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>树下君<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Japanese</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>j2</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Japanese</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>井边子<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Korea</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>k1</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Korea</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>金秀贤<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Korea</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>k2</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Korea</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>金贤秀<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>American</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>a1</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>American</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>科比布莱恩特<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>American</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>a2</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>American</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>奥尼尔<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Person</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>[] </span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:navy'>pers</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = { </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>cn1</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>cn2</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>j1</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>j2</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>k1</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>k2</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>a1</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>a2</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>English</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>格林<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>), </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>English</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>玛利亚<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>) };</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>for</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> (</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>int</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>i</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = 0; </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>i</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> &lt; </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>pers</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Length</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>; </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>i</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>++)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//if (pers[i] is Chinese)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//&nbsp;&nbsp;&nbsp; ((Chinese)pers[i]).SayHello();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//else if (pers[i] is Japanese)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//&nbsp;&nbsp;&nbsp; ((Japanese)pers[i]).SayHello();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//else if (pers[i] is Korea)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//&nbsp;&nbsp;&nbsp; ((Korea)pers[i]).SayHello();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//else</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//&nbsp;&nbsp;&nbsp; ((American)pers[i]).SayHello();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:navy'>pers</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>[</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>i</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>].</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>SayHello</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

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
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Person</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>private</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Name</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>get</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> { </span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:blue'>return</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>; }</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>set</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> { </span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:navy'>_name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>value</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>; }</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>Person</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>this</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>Name</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>virtual</span></b><b><span lang=EN-US
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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是人类<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Chinese</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Person</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>Chinese</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
: </span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>base</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>(</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是中国人，我叫<span lang=EN-US>{0}&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>this</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Japanese</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Person</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>Japanese</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
: </span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>base</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>(</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{ }</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是脚盆国人，我叫<span
lang=EN-US>{0}&quot;</span></span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:black'>, </span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:blue'>this</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Korea</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Person</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>Korea</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
: </span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>base</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>(</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是棒之思密达，我叫<span
lang=EN-US>{0}&quot;</span></span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:black'>, </span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:blue'>this</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>American</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Person</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>American</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
: </span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>base</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>(</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我叫<span lang=EN-US>{0}</span>，我是米国人<span
lang=EN-US>&quot;</span></span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>, </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>this</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Name</span></b><b><span
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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>English</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Person</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>English</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>(</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
: </span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>base</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>(</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>name</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{ }</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是英国人<span lang=EN-US>&quot;</span></span></b><b><span
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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

</div>

</body>

</html>
