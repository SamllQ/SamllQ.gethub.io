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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>_12</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:blue'>接口特点</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//&nbsp;&nbsp;&nbsp;
</span></b><b><span style='font-size:9.5pt;font-family:新宋体;color:green'>接口是一种规范。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>面向对象：即是面向接口编程</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>只要一个类继承了一个接口，这个类就必须实现这个接口中所有的成员</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>为了多态。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>接口不能被实例化。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>也就是说，接口不能<span lang=EN-US>new(</span>不能创建对象<span
lang=EN-US>)</span></span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>接口中的成员不能加“访问修饰符”，接口中的成员访问修饰符为<span
lang=EN-US>public,</span>不能修改。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>（默认为<span lang=EN-US>public</span>）</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>接口中的成员不能有任何实现（“光说不做”，只是定义了一组未实现的成员）。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>接口中只能有方法、属性、索引器、事件，不能有“字段”和构造函数。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>接口与接口之间可以继承，并且可以多继承。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>接口并不能去继承一个类，而类可以继承接口<span
lang=EN-US>&nbsp; </span>（接口只能继承于接口，而类既可以继承接口，也可以继承类）</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>实现接口的子类必须实现该接口的全部成员。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:green'>一个类可以同时继承一个类并实现多个接口，如果一个子类同时继承了父类<span
lang=EN-US>A</span>，并实现了接口<span lang=EN-US>IA,</span>那么语法上<span lang=EN-US>A</span>必须写在<span
lang=EN-US>IA</span>的前面。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//class MyClass
: A, IA { }</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>，因为类是单继承的。</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>IFlyable</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>fly</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Bird</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//new
Person();// new IFlyable();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:navy'>fly</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span lang=EN-US
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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Person</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>:</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>IFlyable</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span
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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>人类在飞<span lang=EN-US>&quot;</span></span></b><b><span
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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Student</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span
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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>人类在飞<span lang=EN-US>&quot;</span></span></b><b><span
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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Bird</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>IFlyable</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span
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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>鸟在飞<span lang=EN-US>&quot;</span></span></b><b><span
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
9.5pt;font-family:新宋体;color:blue'>interface</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>IFlyable</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>不允许有访问修饰符 默认为<span lang=EN-US>public</span></span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>方法、自动属性</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>void</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>interface</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>M1</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>void</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#880000'>Test1</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

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
9.5pt;font-family:新宋体;color:blue'>interface</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>M2</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>void</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#880000'>Test2</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

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
9.5pt;font-family:新宋体;color:blue'>interface</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>M3</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>void</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#880000'>Test3</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

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
9.5pt;font-family:新宋体;color:blue'>interface</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>SupperInterface</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>M1</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>M2</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>, </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>M3</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{ </span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Car</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>SupperInterface</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Test1</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>throw</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>NotImplementedException</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

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
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Test2</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>throw</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>NotImplementedException</span></i></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

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
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Test3</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>()</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>throw</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>NotImplementedException</span></i></b><b><span
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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> _14_</span></b><b><span
style='font-size:9.5pt;font-family:新宋体;color:black'>显示实现接口</span></b></p>

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
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:green'>//</span></b><b><span style='font-size:9.5pt;font-family:新宋体;
color:green'>显示实现接口就是为了解决方法的重名问题</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>IFlyable</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>fly</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Bird</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:navy'>fly</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>Bird</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:navy'>bird</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> = </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Bird</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:navy'>bird</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>.</span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

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
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>class</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>Bird</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> : </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>IFlyable</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>public</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>void</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span
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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>鸟飞会<span lang=EN-US>&quot;</span></span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></b></p>

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
font-family:新宋体;color:green'>显示实现接口</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:gray'>///</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:gray'>&lt;/summary&gt;</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>void</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:blue'>IFlyable</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>.</span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span
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
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>我是接口的飞<span lang=EN-US>&quot;</span></span></b><b><span
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
9.5pt;font-family:新宋体;color:blue'>interface</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'> </span></b><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#2B91AF'>IFlyable</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
{</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></b><b><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;
color:blue'>void</span></b><b><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'> </span></b><b><span lang=EN-US style='font-size:
9.5pt;font-family:新宋体;color:#880000'>Fly</span></b><b><span lang=EN-US
style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>}</span></b></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><b><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;</span></b></p>

</div>

</body>

</html>
