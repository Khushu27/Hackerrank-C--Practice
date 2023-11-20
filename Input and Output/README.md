<!-- HackerRank Challenge: Sum of 3 Numbers -->

<h1><a href="#">Input and Output</a></h1>

<h2>Objective</h2>
<p>In this challenge, we practice reading input from stdin and printing output to stdout.</p>

<p>In C++, you can read a single whitespace-separated token of input using <code>cin</code>, and print output to <code>stdout</code> using <code>cout</code>. For example, let's say we declare the following variables:</p>

<pre><code>string s;
int n;
</code></pre>

<p>and we want to use <code>cin</code> to read the input "High 5" from stdin. We can do this with the following code:</p>

<pre><code>cin &gt;&gt; s &gt;&gt; n;
</code></pre>

<p>This reads the first word ("High") from stdin and saves it as string <code>s</code>, then reads the second word ("5") from stdin and saves it as integer <code>n</code>. If we want to print these values to stdout, separated by a space, we write the following code:</p>

<pre><code>cout &lt;&lt; s &lt;&lt; " " &lt;&lt; n &lt;&lt; endl;
</code></pre>

<p>This code prints the contents of string <code>s</code>, a single space (" "), then the integer <code>n</code>. We end our line of output with a newline using <code>endl</code>. This results in the following output:</p>

<pre><code>High 5
</code></pre>

<h2>Task</h2>
<p>Read 3 numbers from stdin and print their sum to stdout.</p>

<h3>Input Format</h3>
<p>One line that contains 3 space-separated integers: <code>a</code>, <code>b</code>, and <code>c</code>.</p>

<h3>Constraints</h3>
<p>1 <= a, b, c <= 1000</p>

<h3>Output Format</h3>
<p>Print the sum of the three numbers on a single line.</p>

<h3>Sample Input</h3>
<pre><code>1 2 7
</code></pre>

<h3>Sample Output</h3>
<pre><code>10
</code></pre>

<h3>Explanation</h3>
<p>The sum of the three numbers is 1 + 2 + 7 = 10.</p>
