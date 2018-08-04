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
	{font-family:宋体;
	panose-1:2 1 6 0 3 1 1 1 1 1;}
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

<p class=MsoNormal><b><span style='font-family:宋体'>语法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>[public] enum </span></b><b><span
style='font-family:宋体'>枚举名</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></b><b><span
style='font-family:宋体'>值</span><span lang=EN-US>1,</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></b><b><span
style='font-family:宋体'>值</span><span lang=EN-US>2,</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></b><b><span
style='font-family:宋体'>值</span><span lang=EN-US>3,</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ........</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>public:</span></b><b><span
style='font-family:宋体'>访问修饰符。公开的公共的，哪都可以访问。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>enum</span></b><b><span
style='font-family:宋体'>：关键字，声明枚举的关键字</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>枚举名：要符合</span><span
lang=EN-US>Pascal</span></b><b><span style='font-family:宋体'>命名规范</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>将枚举声明到命名空间的下面，类的外面，表示这个命名空间下，所有的类都可以使用这个枚举。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>枚举就是一个变量类型</span> </b><b><span
style='font-family:宋体'>，</span><span lang=EN-US>int--double&nbsp; string&nbsp;
decimal.</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>只是枚举声明、赋值、使用的方式跟那些普通的变量类型不一样。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>我们可以将一个枚举类型的变量跟</span><span
lang=EN-US>int</span></b><b><span style='font-family:宋体'>类型和</span><span
lang=EN-US>string</span></b><b><span style='font-family:宋体'>类型互相转换。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>枚举类型默认是跟</span><span
lang=EN-US>int</span></b><b><span style='font-family:宋体'>类型相互兼容的，所以可以通过强制类型转换的语法互相转换。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>当转换一个枚举中没有的值的时候，不会抛异常，而是直接将数字显示出来。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>枚举同样也可以跟</span><span
lang=EN-US>string</span></b><b><span style='font-family:宋体'>类型互相转换，如果将枚举类型转换成</span><span
lang=EN-US>string</span></b><b><span style='font-family:宋体'>类型，则直接调用</span><span
lang=EN-US>ToString().</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>如果将字符串转换成枚举类型则需要下面这样一行代码：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (</span></b><b><span
style='font-family:宋体'>要转换的枚举类型</span><span lang=EN-US>)Enum.Parse(typeof(</span></b><b><span
style='font-family:宋体'>要转换的枚举类型</span><span lang=EN-US>),&quot;</span></b><b><span
style='font-family:宋体'>要转换的字符串</span><span lang=EN-US>&quot;);</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>如果转换的字符串是数字，则就算枚举中没有，也会不会抛异常。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>如果转换的字符串是文本，如果枚举中没有，则会抛出异常。</span></b></p>

</div>

</body>

</html>
