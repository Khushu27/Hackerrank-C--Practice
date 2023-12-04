<!DOCTYPE html>
<html>

<head>
</head>

<body>

<h1><a id="hackerrank-challenge-for-loop" href= "https://www.hackerrank.com/challenges/c-tutorial-for-loop/problem?isFullScreen=false">For Loop</a></h1>

<h2>Introduction</h2>
<p>A for loop is a programming language statement that allows code to be repeatedly executed.</p>

<p>The syntax is</p>

<pre>
<code>
for ( &lt;expression_1&gt; ; &lt;expression_2&gt; ; &lt;expression_3&gt; )
    &lt;statement&gt;
</code>
</pre>

<p>expression_1 is used for initializing variables which are generally used for controlling the terminating flag for the loop.</p>
<p>expression_2 is used to check for the terminating condition. If this evaluates to false, then the loop is terminated.</p>
<p>expression_3 is generally used to update the flags/variables.</p>

<p>A sample loop is</p>

<pre>
<code>
for(int i = 0; i < 10; i++) {
    ...
}
</code>
</pre>

<p>In this challenge, you will use a for loop to increment a variable through a range.</p>

<h2>Input Format</h2>

<p>You will be given two positive integers, <code>a</code> and <code>b</code> (<code>a <= b</code>), separated by a newline.</p>

<h2>Output Format</h2>

<p>For each integer <code>n</code> in the inclusive interval <code>[a, b]</code>:</p>

<ul>
  <li>If <code>1 <= n <= 9</code>, then print the English representation of it in lowercase. That is "one" for 1, "two" for 2, and so on.</li>
  
  <li>Else if <code>n > 9</code> and it is an even number, then print "even".</li>
  
  <li>Else if <code>n > 9</code> and it is an odd number, then print "odd".</li>
</ul>

<p>Note: <code>[a, b] = {x E Z | a <= x <= b} = {a, a+1, ..., b}</code></p>

<h2>Sample Input</h2>

<pre>
<code>
8
11
</code>
</pre>

<h2>Sample Output</h2>

<pre>
<code>
eight
nine
even
odd
</code>
</pre>

</body>

</html>
