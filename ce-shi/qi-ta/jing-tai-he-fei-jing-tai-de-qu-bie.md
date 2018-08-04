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
pre
	{mso-style-link:"HTML 预设格式 Char";
	margin:0cm;
	margin-bottom:.0001pt;
	font-size:12.0pt;
	font-family:宋体;}
span.HTMLChar
	{mso-style-name:"HTML 预设格式 Char";
	mso-style-link:"HTML 预设格式";
	font-family:宋体;}
span.hljs-function
	{mso-style-name:hljs-function;}
span.hljs-keyword
	{mso-style-name:hljs-keyword;}
span.hljs-title
	{mso-style-name:hljs-title;}
span.hljs-string
	{mso-style-name:hljs-string;}
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

<p class=MsoNormal><b><span style='font-family:宋体'>一、静态的特点</span><span
lang=EN-US> <br>
1. </span></b><b><span style='font-family:宋体'>静态成员不属于对象，属于类；</span><span
lang=EN-US> <br>
2. </span></b><b><span style='font-family:宋体'>静态成员调用时，使用类名</span><span
lang=EN-US>.</span></b><b><span style='font-family:宋体'>成员；</span><span
lang=EN-US> <br>
3. </span></b><b><span style='font-family:宋体'>同类型的多个对象共享本类的静态成员；</span><span
lang=EN-US> <br>
4. </span></b><b><span style='font-family:宋体'>静态的内容，在内存中只有一份；</span><span
lang=EN-US> <br>
5. </span></b><b><span style='font-family:宋体'>静态的内容，在类第一次加载后，常驻内存，直到程序结束；</span><span
lang=EN-US> <br>
6. </span></b><b><span style='font-family:宋体'>静态的成员，可以在没有对象时就能使用。</span><span
lang=EN-US> <br>
</span></b><b><span style='font-family:宋体'>二、静态的作用</span><span lang=EN-US> <br>
1. </span></b><b><span style='font-family:宋体'>可以表示中立；</span><span lang=EN-US> <br>
2. </span></b><b><span style='font-family:宋体'>如果有多个对象共同维护同一个数据，可将该数据写为静态；</span><span
lang=EN-US> <br>
3. </span></b><b><span style='font-family:宋体'>如果某数据常用（常驻内存），且占用资源较多（内存中只有一份），适合作为静态；</span><span
lang=EN-US> <br>
4. </span></b><b><span style='font-family:宋体'>工具类适合作为静态类，工具类常用、通用、没有状态数据；</span><span
lang=EN-US> <br>
5. </span></b><b><span style='font-family:宋体'>使用方便，无须创建对象。</span><span
lang=EN-US> <br>
</span></b><b><span style='font-family:宋体'>三、静态成员</span><span lang=EN-US> <br>
1. </span></b><b><span style='font-family:宋体'>类的成员声明的</span><span lang=EN-US>static</span></b><b><span
style='font-family:宋体'>，属于类，对象间共享；</span><span lang=EN-US> <br>
2. </span></b><b><span style='font-family:宋体'>静态方法中只能访问静态成员，因为实例成员需要对象引用。</span><span
lang=EN-US> <br>
</span></b><b><span style='font-family:宋体'>四、静态类</span><span lang=EN-US> <br>
</span></b><b><span style='font-family:宋体'>将类声明为</span><span lang=EN-US>static</span></b><b><span
style='font-family:宋体'>，不能创建对象。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>使用：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>1)</span></b><b><span style='font-family:
宋体'>、如果你想要你的类当做一个</span><span lang=EN-US>&quot;</span></b><b><span
style='font-family:宋体'>工具类</span><span lang=EN-US>&quot;</span></b><b><span
style='font-family:宋体'>去使用，这个时候可以考虑将类写成静态的。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>2)</span></b><b><span style='font-family:
宋体'>、静态类在整个项目中资源共享。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>只有在程序全部结束之后，静态类才会释放资源。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>语法：</span></b></p>

<p class=MsoNormal align=left style='margin-left:10.5pt;text-align:left'><b><span
lang=EN-US style='font-size:12.0pt;font-family:宋体'>public static void M2() </span></b></p>

<p class=MsoNormal align=left style='margin-left:31.5pt;text-align:left'><b><span
lang=EN-US style='font-size:12.0pt;font-family:宋体'>{</span></b></p>

<p class=MsoNormal align=left style='margin-left:31.5pt;text-align:left'><b><span
lang=EN-US style='font-size:12.0pt;font-family:宋体'>&nbsp;&nbsp;&nbsp;
Console.WriteLine(&quot;M2&quot;);</span></b></p>

<p class=MsoNormal align=left style='margin-left:31.5pt;text-align:left'><b><span
lang=EN-US style='font-size:12.0pt;font-family:宋体'>}</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>堆</span><span lang=EN-US>&nbsp;
</span></b><b><span style='font-family:宋体'>栈</span><span lang=EN-US>&nbsp; </span></b><b><span
style='font-family:宋体'>静态存储区域</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>释放资源。</span><span
lang=EN-US>GC Garbage Collection</span></b><b><span style='font-family:宋体'>垃圾回收器</span></b></p>

</div>

</body>

</html>
