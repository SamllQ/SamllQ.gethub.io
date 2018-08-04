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

<p class=MsoNormal><span style='font-family:宋体'>当程序结束时析构函数才调用，通常使用它来释放资源。</span></p>

<p class=MsoNormal><span style='font-family:宋体'>语法</span></p>

<p class=MsoNormal><span lang=EN-US>Public Class A()</span></p>

<p class=MsoNormal><span lang=EN-US>{</span></p>

<p class=MsoNormal><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~A()</span></p>

<p class=MsoNormal style='margin-left:31.5pt'><span lang=EN-US>{</span></p>

<p class=MsoNormal style='margin-left:31.5pt'><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp; //</span><span
style='font-family:宋体'>这里是析构函数</span></p>

<p class=MsoNormal style='margin-left:31.5pt'><span lang=EN-US>}</span></p>

<p class=MsoNormal><span lang=EN-US>}</span></p>

</div>

</body>

</html>
