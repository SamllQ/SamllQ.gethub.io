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

<p class=MsoNormal><b><span style='font-family:宋体'>用来处理多条件的定值的判断。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体;color:red'>语法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>switch(</span></b><b><span
style='font-family:宋体;color:red'>变量或者表达式的值</span><span lang=EN-US
style='color:red'>)</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case
</span></b><b><span style='font-family:宋体;color:red'>值</span><span lang=EN-US
style='color:red'>1:</span></b><b><span style='font-family:宋体;color:red'>要执行的代码</span><span
lang=EN-US style='color:red'>;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; break;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case
</span></b><b><span style='font-family:宋体;color:red'>值</span><span lang=EN-US
style='color:red'>2:</span></b><b><span style='font-family:宋体;color:red'>要执行的代码</span><span
lang=EN-US style='color:red'>;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; break;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case
</span></b><b><span style='font-family:宋体;color:red'>值</span><span lang=EN-US
style='color:red'>3:</span></b><b><span style='font-family:宋体;color:red'>要执行的代码</span><span
lang=EN-US style='color:red'>;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; break;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ..........</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; default:</span></b><b><span
style='font-family:宋体;color:red'>要执行的代码</span><span lang=EN-US
style='color:red'>;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; break;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>}</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>执行过程：程序执行到</span><span
lang=EN-US>switch</span></b><b><span style='font-family:宋体'>处，首先将括号中变量或者表达式的值计算出来，</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>然后拿着这个值依次跟每个</span><span
lang=EN-US>case</span></b><b><span style='font-family:宋体'>后面所带的值进行匹配，一旦匹配成功，则执行</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>该</span><span lang=EN-US>case</span></b><b><span
style='font-family:宋体'>所带的代码，执行完成后，遇到</span><span lang=EN-US>break</span></b><b><span
style='font-family:宋体'>。跳出</span><span lang=EN-US>switch-case</span></b><b><span
style='font-family:宋体'>结构。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>如果，跟每个</span><span
lang=EN-US>case</span></b><b><span style='font-family:宋体'>所带的值都不匹配。就看当前这个</span><span
lang=EN-US>switch-case</span></b><b><span style='font-family:宋体'>结构中是否存在</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>default</span></b><b><span
style='font-family:宋体'>，如果有</span><span lang=EN-US>default</span></b><b><span
style='font-family:宋体'>，则执行</span><span lang=EN-US>default</span></b><b><span
style='font-family:宋体'>中的语句，如果没有</span><span lang=EN-US>default</span></b><b><span
style='font-family:宋体'>，则该</span><span lang=EN-US>switch-case</span></b><b><span
style='font-family:宋体'>结构</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>什么都不做。</span></b></p>

</div>

</body>

</html>
