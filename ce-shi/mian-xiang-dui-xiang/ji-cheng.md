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

<p class=MsoNormal><b><span style='font-family:宋体'>我们可能会在一些类中，写一些重复的成员，我们可以将这些重复的成员，</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>单独的封装到一个类中，作为这些类的父类。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Student</span></b><b><span
style='font-family:宋体'>、</span><span lang=EN-US>Teacher</span></b><b><span
style='font-family:宋体'>、</span><span lang=EN-US>Driver&nbsp; </span></b><b><span
style='font-family:宋体'>子类</span><span lang=EN-US>&nbsp; </span></b><b><span
style='font-family:宋体'>派生类</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>Person&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;</span></b><b><span
style='font-family:宋体'>父类</span><span lang=EN-US>&nbsp; </span></b><b><span
style='font-family:宋体'>基类</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>子类继承了父类，那么子类从父类那里继承过来了什么？</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>首先，子类继承了父类的属性和方法，但是子类并没有继承父类的私有字段。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>问题：<span style='color:red'>子类有没有继承父类的构造函数？</span></span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>答：子类并没有继承父类的构造函数，但是。子类会默认的调用父类无参数的构造函数，</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>创建父类对象，让子类可以使用父类中的成员。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>所以，如果在父类中重新写了一个有参数的构造函数之后，那个无参数的就被干掉了，</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>子类就调用不到了，所以子类会报错。</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>解决办法：</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>1)</span></b><b><span
style='font-family:宋体;color:red'>、在父类中重新写一个无参数的构造函数。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='color:red'>2)</span></b><b><span
style='font-family:宋体;color:red'>、在子类中显示的调用父类的构造函数，使用关键字</span><span
lang=EN-US style='color:red'>:base()</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体;color:red'>继承的特性</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>1</span></b><b><span style='font-family:
宋体'>、继承的单根性：一个子类只能有一个父类。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>2</span></b><b><span style='font-family:
宋体'>、继承的传递性：子类可用父类的父类的所用东西</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>语法：</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp; </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>class</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Program</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>static</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Main</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>[] </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>args</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Student</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>s</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Student</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>s</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Age</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = 0;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>s</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Gender</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>'</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>男<span lang=EN-US>'</span></span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span><span
style='font-size:9.5pt;font-family:新宋体;color:green'>······</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span><span
style='font-size:9.5pt;font-family:新宋体;color:green'>子类继承父类可用父类成员以及方法，子类也可以单独拥有成员和方法</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>class</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Student</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>:</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Person</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>private</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>int</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_id</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>int</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ID</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>get</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>return</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_id</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>set</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_id</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>value</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Study</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>学习<span lang=EN-US>&quot;</span></span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>class</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Teacher</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Person</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;
</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>private</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>double</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_salary</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>double</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Salary</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>get</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>return</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_salary</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>set</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_salary</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>value</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>CHLSS</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>吃喝拉撒睡<span lang=EN-US>&quot;</span></span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>class</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Person</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>private</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_name</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>string</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Name</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>get</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>return</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_name</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>set</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_name</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>value</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>private</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>int</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_age</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>int</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Age</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>get</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>return</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_age</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>set</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_age</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>value</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>private</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>char</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_gender</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>char</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Gender</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>get</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>return</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_gender</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>set</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>_gender</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>value</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>public</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>void</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>CHLSS</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>吃喝拉撒睡<span lang=EN-US>&quot;</span></span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:black'>&nbsp;&nbsp;&nbsp; }</span></p>

</div>

</body>

</html>
