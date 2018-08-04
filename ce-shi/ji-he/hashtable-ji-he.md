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

<p class=MsoNormal><span lang=EN-US>Hastable </span><span style='font-family:
宋体'>键值对集合</span> <span style='font-family:宋体'>类似于字典</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Collections</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Collections</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Generic</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Linq</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Text</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>using</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>System</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Threading</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Tasks</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>namespace</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
style='font-size:9.5pt;font-family:新宋体;color:blue'>键值对集合<span lang=EN-US>__Hashtable</span></span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>class</span><span
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
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span><span
style='font-size:9.5pt;font-family:新宋体;color:green'>创建一个键值对集合对象</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Hashtable</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> = </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>new</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Hashtable</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Add</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(1,</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>张三<span lang=EN-US>&quot;</span></span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Add</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(2, </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>true</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Add</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>false</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>,</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>错误的<span lang=EN-US>&quot;</span></span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span><span
style='font-size:9.5pt;font-family:新宋体;color:green'>键是唯一的</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>[6] = </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>这也是一种赋值方式<span
lang=EN-US>&quot;</span></span><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:black'>;</span><span lang=EN-US style='font-size:9.5pt;
font-family:新宋体;color:green'>//</span><span style='font-size:9.5pt;font-family:
新宋体;color:green'>如果里面没有<span lang=EN-US>6</span>就加进去，如果有就替换掉</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span><span
style='font-size:9.5pt;font-family:新宋体;color:green'>在键值对集合中，是根据键找值的</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>[1]);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>[2]);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>[</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>false</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>]);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span><span
style='font-size:9.5pt;font-family:新宋体;color:green'>集合不可以用<span lang=EN-US>for</span>循环，但是可以用<span
lang=EN-US>foreach</span>遍历集合的键<span lang=EN-US> xx.keys</span></span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>foreach</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> (</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>var</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>item</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>in</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>Keys</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>)</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>WriteLine</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>[</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>item</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>]);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><i><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>Console</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>ReadKey</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>();</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span><span
style='font-size:9.5pt;font-family:新宋体;color:green'>用法：</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:blue'>if</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'> (</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>ContainsKey</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>是否包含<span lang=EN-US>&quot;</span></span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>))</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
{</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Clear</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(); </span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:green'>//</span><span
style='font-size:9.5pt;font-family:新宋体;color:green'>清空集合</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:navy'>ht</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>.</span><i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#880000'>Remove</span></i><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>(</span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:#A31515'>&quot;</span><span
style='font-size:9.5pt;font-family:新宋体;color:#A31515'>根据键移除<span lang=EN-US>&quot;</span></span><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>);</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style='font-size:9.5pt;font-family:新宋体;color:black'>···等等等等</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>&nbsp;&nbsp;&nbsp;
}</span></p>

<p class=MsoNormal align=left style='text-align:left;text-autospace:none'><span
lang=EN-US style='font-size:9.5pt;font-family:新宋体;color:black'>}</span></p>

<p class=MsoNormal><span lang=EN-US>&nbsp;</span></p>

</div>

</body>

</html>
