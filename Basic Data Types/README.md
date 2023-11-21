<!DOCTYPE html>
<html>

<head>
</head>

<body>

<h1><a href="https://www.hackerrank.com/challenges/c-tutorial-basic-data-types/problem?isFullScreen=true">Basic Data Types</a></h1>

<h2>Introduction</h2>
<p>Some C++ data types, their format specifiers, and their most common bit widths are as follows:</p>

<ul>
  <li><b>Int</b> ("%d"): 32 Bit integer</li>
  <li><b>Long</b> ("%ld"): 64 bit integer</li>
  <li><b>Char</b> ("%c"): Character type</li>
  <li><b>Float</b> ("%f"): 32 bit real value</li>
  <li><b>Double</b> ("%lf"): 64 bit real value</li>
</ul>

<h2>Reading</h2>
<p>To read a data type, use the following syntax:</p>

<pre>
<code>
scanf("`format_specifier`", &amp;val)
</code>
</pre>

<p>For example, to read a character followed by a double:</p>

<pre>
<code>
char ch;
double d;
scanf("%c %lf", &amp;ch, &amp;d);
</code>
</pre>

<p>For the moment, we can ignore the spacing between format specifiers.</p>

<h2>Printing</h2>
<p>To print a data type, use the following syntax:</p>

<pre>
<code>
printf("`format_specifier`", val)
</code>
</pre>

<p>For example, to print a character followed by a double:</p>

<pre>
<code>
char ch = 'd';
double d = 234.432;
printf("%c %lf", ch, d);
</code>
</pre>

<p>Note: You can also use cin and cout instead of scanf and printf; however, if you are taking a million numbers as input and printing a million lines, it is faster to use scanf and printf.</p>

<h2>Input Format</h2>

<p>Input consists of the following space-separated values: int, long, char, float, and double, respectively.</p>

<h2>Output Format</h2>

<p>Print each element on a new line in the same order it was received as input. Note that the floating point value should be correct up to 3 decimal places and the double to 9 decimal places.</p>

<h2>Sample Input</h2>

<pre>
<code>
3 12345678912345 a 334.23 14049.30493
</code>
</pre>

<h2>Sample Output</h2>

<pre>
<code>
3
12345678912345
a
334.230
14049.304930000
</code>
</pre>

<h2>Explanation</h2>

<p>Print int 3, followed by long 12345678912345, followed by char a, followed by float 334.230, followed by double 14049.304930000.</p>

</body>

</html>
