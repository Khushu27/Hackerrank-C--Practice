<!DOCTYPE html>
<html>

<head>
</head>

<body>

<h1><a href = "https://www.hackerrank.com/challenges/c-tutorial-conditional-if-else/problem?isFullScreen=true">Conditional Statements</a></h1>

<h2>Introduction</h2>
<p><code>if</code> and <code>else</code> are two of the most frequently used conditionals in C/C++, and they enable you to execute zero or one conditional statement among many such dependent conditional statements. We use them in the following ways:</p>

<ol>
  <li><b>if:</b> This executes the body of bracketed code starting with statement1 if condition evaluates to true.</li>
  
  ```cpp
  if (condition) {
      statement1;
      ...
  }
```
<li><b>if - else:</b> This executes the body of bracketed code starting with statement1 if condition evaluates to true, or it executes the body of code starting with statement2 if condition evaluates to false. Note that only one of the bracketed code sections will ever be executed.</li>

```cpp
if (condition) {
    statement1;
    ...
}
else {
    statement2;
    ...
}
```

<li><b>if - else if - else:</b> In this structure, dependent statements are chained together and the condition for each statement is only checked if all prior conditions in the chain evaluated to false. Once a condition evaluates to true, the bracketed code associated with that statement is executed and the program then skips to the end of the chain of statements and continues executing. If each condition in the chain evaluates to false, then the body of bracketed code in the else block at the end is executed.</li>

```cpp
if (first_condition) {
    ...
}
else if (second_condition) {
    ...
}
.
.
.
else if ((n-1)'th_condition) {
    ....
}
else {
    ...
}
```

</ol>
<h2>Problem Statement</h2>
<p>Given a positive integer <code>n</code>, do the following:</p>
<ol>
  <li>If <code>1 <= n <= 9</code>, print the lowercase English word corresponding to the number (e.g., one for 1, two for 2, etc.).</li>
  <li>If <code>n > 9</code>, print Greater than 9.</li>
</ol>
<h2>Input Format</h2>
<p>A single integer, <code>n</code>.</p>
<h2>Constraints</h2>
<p><code>1 <= n <= 10^9</code></p>
<h2>Output Format</h2>
<p>If <code>1 <= n <= 9</code>, then print the lowercase English word corresponding to the number (e.g., one for 1, two for 2, etc.); otherwise, print <code>Greater than 9</code>.</p>
<h2>Sample Input 0</h2>
<pre>
<code>
5
</code>
</pre>
<h2>Sample Output 0</h2>
<pre>
<code>
five
</code>
</pre>
<h2>Explanation 0</h2>
<p><code>five</code> is the English word for the number 5.</p>
<h2>Sample Input 1</h2>
<pre>
<code>
8
</code>
</pre>
<h2>Sample Output 1</h2>
<pre>
<code>
eight
</code>
</pre>
<h2>Explanation 1</h2>
<p><code>eight</code> is the English word for the number 8.</p>
<h2>Sample Input 2</h2>
<pre>
<code>
44
</code>
</pre>
<h2>Sample Output 2</h2>
<pre>
<code>
Greater than 9
</code>
</pre>
<h2>Explanation 2</h2>
<p><code>n == 44</code> is greater than 9, so we print <code>Greater than 9</code>.</p>
</body>
</html>
