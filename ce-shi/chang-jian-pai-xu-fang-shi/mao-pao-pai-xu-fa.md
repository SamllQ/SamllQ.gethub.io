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

<p class=MsoNormal><b><span style='font-family:宋体'>就是将一个数组中的元素按照从大到小或者从小到大的顺序进行排列。</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>int[] nums={9,8,7,6,5,4,3,2,1,0}; 0 1 2
3 4 5 6 7 8 9</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第一趟比较：</span><span
lang=EN-US>8 7 6 5 4 3 2 1 0 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>9</span></b><b><span style='font-family:宋体'>次</span><span
lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp; i=0&nbsp; j=nums.Length-1-i</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第二趟比较：</span><span
lang=EN-US>7 6 5 4 3 2 1 0 8 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>8</span></b><b><span style='font-family:宋体'>次</span><span
lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp; i=1&nbsp; j=nums.Length-1-i</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第三趟比较：</span><span
lang=EN-US>6 5 4 3 2 1 0 7 8 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>7</span></b><b><span style='font-family:宋体'>次</span><span
lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp; i=2&nbsp; j=nums.Length-1-i</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第四趟比较：</span><span
lang=EN-US>5 4 3 2 1 0 6 7 8 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>6</span></b><b><span style='font-family:宋体'>次</span><span
lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp; i=3&nbsp; j=nums.Length-1-i</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第五趟比较：</span><span
lang=EN-US>4 3 2 1 0 5 6 7 8 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>5</span></b><b><span style='font-family:宋体'>次</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第六趟比较：</span><span
lang=EN-US>3 2 1 0 4 5 6 7 8 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>4</span></b><b><span style='font-family:宋体'>次</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第七趟比较：</span><span
lang=EN-US>2 1 0 3 4 5 6 7 8 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>3</span></b><b><span style='font-family:宋体'>次</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第八趟比较：</span><span
lang=EN-US>1 0 2 3 4 5 6 7 8 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>2</span></b><b><span style='font-family:宋体'>次</span></b></p>

<p class=MsoNormal><b><span style='font-family:宋体'>第九趟比较：</span><span
lang=EN-US>0 1 2 3 4 5 6 7 8 9 </span></b><b><span style='font-family:宋体'>交换了</span><span
lang=EN-US>1</span></b><b><span style='font-family:宋体'>次</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>for(int i=0;i&lt;number.Length-1;i++)</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>{</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for(int
j=0;j&lt;nums.Length-1-i;j++)</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if(nums[j]&gt;nums[j+1])</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int
temp=nums[j];</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; nums[j]=nums[j+1];</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; nums[j+1]=temp;</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</span></b></p>

<p class=MsoNormal><b><span lang=EN-US>}</span></b></p>

</div>

</body>

</html>
