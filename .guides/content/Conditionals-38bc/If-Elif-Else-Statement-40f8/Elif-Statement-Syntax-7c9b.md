----------

## Elif Syntax

The elif statement is written similarly to the if statement. There are few differences as well. Here are the rules for writing an elif statement:

* An if statement must come before the first elif statement
* `elif` is followed by a boolean expression and a `:`
* Indent four spaces and write the commands for when the elif statement is true
* You can write as many elif statements as you want
* An else statement must come after the last elif statement

<details>
  <summary><b>What does <code>elif</code> mean?</b></summary>
  <code>elif</code> is an abbreviation of <code>else</code> and <code>if</code>. Since <code>elif</code> statements are common, the command was simplified so programmers would not have to write <code>else if</code>.
</details>

![The image shows comments on the syntax of 7 lines of code:
a=17
if a < 10:
  print("less than 10")
elif a < 20:
  print("less than 20")
else:
  print("greater than 20")
The first comment points to if-statement and says "if statement and boolean expression". "elif a < 20" has the comment "elif statement and boolean expression". The "else" line is signed as "Else statement". At the end of the lines with "if", "elif" and "else" there is a colon with the comment "End with : " The spaces before the three print statements are circled and commented "Indent 4 spaces". The print statements after the "if" and "elif" lines are signed "Command to run if preceding boolean expression is true". The print statement after the else-line is signed "Command to run if all of the above is false".
](.guides/images/elif-statement.png)

```python
a = 20

if a < 10:
    print(str(a) + " is less than 10")
elif a < 20:
    print(str(a) + " is less than 20")
elif a < 30:
    print(str(a) + " less than 30")
else:
    print(str(a) + " is greater than 30")
```

[Code Visualizer](open_tutor code/selection/elif-syntax.py)
{try it}(python3 code/selection/elif-syntax.py 1)

|||challenge
## What happens if you:
* Change `a` to `0`?
* Change `a` to `100`?
* Change `a` to `30`? (How can you fix this?)

|||

[Code Visualizer](open_tutor code/selection/elif-syntax.py)
{try it}(python3 code/selection/elif-syntax.py 2)

{Check It!|assessment}(multiple-choice-1573332278)


