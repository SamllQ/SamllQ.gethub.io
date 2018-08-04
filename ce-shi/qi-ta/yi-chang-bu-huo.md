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

<p class=MsoNormal><b><span style='font-family:宋体'>我们在程序中经常会出现各种各样的异常，你如果想要你的程序变得坚强一些。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>在你的代码中应该经常性的使用</span><span
lang=EN-US>try-catch</span></b><b><span style='font-family:宋体'>来进行异常捕获。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>哪行代码有可能出现异常，你就踹它一脚。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>语法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>try</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></b><b><span
style='font-family:宋体'>可能会出现异常的代码</span><span lang=EN-US>;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ....</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ...</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ...</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>//try</span></b><b><span
style='font-family:宋体'>和</span><span lang=EN-US>catch</span></b><b><span
style='font-family:宋体'>之间不能有其他的代码</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>catch</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></b><b><span
style='font-family:宋体'>出现异常后要执行的代码</span><span lang=EN-US>;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>执行过程</span><span lang=EN-US>:</span></b><b><span
style='font-family:宋体'>如果</span><span lang=EN-US>try</span></b><b><span
style='font-family:宋体'>中的代码没有出现异常，那么</span><span lang=EN-US>catch</span></b><b><span
style='font-family:宋体'>中的代码不会执行。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>如果</span><span lang=EN-US>try</span></b><b><span
style='font-family:宋体'>中的代码出现了异常，那怕这行出现异常的代码后面还有一百行都不会执行了，</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>而是直接跳到</span><span
lang=EN-US>catch</span></b><b><span style='font-family:宋体'>中执行代码</span></b></p>

</div>

</body>

</html>
