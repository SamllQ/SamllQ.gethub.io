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

<p class=MsoNormal><b><span style='font-family:宋体'>属性的作用就是保护字段、对字段的赋值和取值进行限定。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>属性的本质就是两个方法，一个叫</span><span
lang=EN-US>get()</span></b><b><span style='font-family:宋体'>一个叫</span><span
lang=EN-US>set()</span></b><b><span style='font-family:宋体'>。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>既有</span><span lang=EN-US>get()</span></b><b><span
style='font-family:宋体'>也有</span><span lang=EN-US>set()</span></b><b><span
style='font-family:宋体'>我们诚之为可读可写属性。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>只有</span><span lang=EN-US>get()</span></b><b><span
style='font-family:宋体'>没有</span><span lang=EN-US>set()</span></b><b><span
style='font-family:宋体'>我们称之为只读属性</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>没有</span><span lang=EN-US>get()</span></b><b><span
style='font-family:宋体'>只有</span><span lang=EN-US>set()</span></b><b><span
style='font-family:宋体'>我们称之为只写属性</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Field</span></b><b><span
style='font-family:宋体'>字段</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Method</span></b><b><span
style='font-family:宋体'>方法</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Property</span></b><b><span
style='font-family:宋体'>属性</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体;color:red'>语法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Public int num;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Public int a ()</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; get</span></b></p>

<p class=MsoNormal style='margin-left:31.5pt'><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal style='margin-left:31.5pt'><b><span lang=EN-US>&nbsp;&nbsp; Return
num;</span></b></p>

<p class=MsoNormal style='margin-left:31.5pt'><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; set</span></b></p>

<p class=MsoNormal style='margin-left:31.5pt'><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal style='margin-left:31.5pt'><b><span lang=EN-US>&nbsp;&nbsp;num
= value;</span></b></p>

<p class=MsoNormal style='margin-left:31.5pt'><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal style='margin-left:31.5pt'><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>****</span></b><b><span
style='font-family:宋体'>字段就是女人</span><span lang=EN-US>&nbsp; </span></b><b><span
style='font-family:宋体'>属性才是男人。</span></b></p>

</div>

</body>

</html>
