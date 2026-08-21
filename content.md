# Task

Write a recursive function called `fibonacci`{.python} that takes one argument `n`{.python} and returns the value `F(n)`{.python}.
Use the definition:

$$
F(0)&=0\\
F(1)&=1\\
F(n)&=F(n-1)+F(n-2)\text{ for }n > 1
$$

You may assume that `n`{.python} is a non-negative integer.

# Reference values

<table>
  <thead>
    <tr><th>n</th><th>F(n)</th></tr>
  </thead>
  <tbody>
    <tr><td>0</td><td>0</td></tr>
    <tr><td>1</td><td>1</td></tr>
    <tr><td>2</td><td>1</td></tr>
    <tr><td>3</td><td>2</td></tr>
    <tr><td>4</td><td>3</td></tr>
    <tr><td>5</td><td>5</td></tr>
    <tr><td>6</td><td>8</td></tr>
    <tr><td>7</td><td>13</td></tr>
    <tr><td>8</td><td>21</td></tr>
  </tbody>
</table>

# Starter cell

```py-cell
# Write your recursive fibonacci function here

# Test on a few values
print(fibonacci(0)) # Should return 0
print(fibonacci(1)) # Should return 1
print(fibonacci(2)) # Should return 1
print(fibonacci(8)) # Should return 21
```
