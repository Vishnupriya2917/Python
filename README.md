<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>

<h1>Python Data Types</h1>

<p>We have <strong>3 main data types</strong> in Python:</p>

<h2>1. Integer (<code>int</code>)</h2>
<p>Whole numbers without decimals.</p>
<p><strong>Examples:</strong></p>
<ul>
    <li>12</li>
    <li>156</li>
    <li>2860</li>
</ul>

<h2>2. Float (<code>float</code>)</h2>
<p>Numbers with decimal values.</p>
<p><strong>Examples:</strong></p>
<ul>
    <li>12.5</li>
    <li>156.0</li>
    <li>2860.66</li>
</ul>

<h2>3. String (<code>str</code>)</h2>
<p>Anything written inside quotes.</p>
<p><strong>Examples:</strong></p>
<ul>
    <li>'vishnu'</li>
    <li>'vishnu12'</li>
    <li>'125'</li>
</ul>

<hr>

<h1>Variables in Python</h1>

<p>
If we directly pass data types to Python, it will check and give the output.
But if we want to use the data later, it is not possible because the data is
not stored in memory (temporary memory).
</p>

<p>
To save data in memory, we use a concept called <strong>Variables</strong>.
</p>

<p>
Variables allow us to store data types in memory so that we can reuse them later.
By default, variables store data in temporary memory during program execution.
</p>

<h2>Examples of Variables</h2>

<pre>
x = 10
price = 25.5
name = "Vishnu"
is_active = True
</pre>

<hr>

<h1>Rules to Create Variables</h1>

<h3>Rule 1</h3>
<p>
Variables should not start with a number.  
If needed, use an underscore (<code>_</code>).
</p>

<pre>
_valid = 10
# Invalid: 1value = 20
</pre>

<h3>Rule 2</h3>
<p>
Variable names should be a single word.
Spaces are not allowed.  
Use underscores instead.
</p>

<pre>
user_name = "Vishnu"
# Invalid: user name = "Vishnu"
</pre>

<h3>Rule 3</h3>
<p>
Python variables are case-sensitive.
</p>

<pre>
age = 20
Age = 30
# age and Age are different variables
</pre>

<h3>Rule 4</h3>
<p>
Do not use punctuation symbols in variable names:
</p>

<p>
<code>!"#$%&amp;'()*+,-./:;&lt;=&gt;?@[]^_{|}~`</code>
</p>

<pre>
# Invalid examples:
# my-name = 10
# total$ = 100
</pre>

</body>
</html>
