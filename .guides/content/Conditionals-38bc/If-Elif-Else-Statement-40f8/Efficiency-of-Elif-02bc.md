----------

## Efficiency of Elif

Take a look at the image below. It shows two programs that do the same thing, calculate a letter grade based on a numeric value. The blue arrows show the flow of the program, and the red star shows what happens when the boolean expression is true.

![The image shows two similar code blocks.
The block on the left has only if-statements. The arrows connect all the if-statements from the top downward. There is a star next to the print statement "You got a B". This code is provided later on this page in the section "Series of If Statements"
The code block on the right has if, elif, else statements. The arrows connect them from the top downward. There is a star next to the print statement "You got a B". But there is no arrow connecting the else-statement that goes after the starred line. This code is provided later on this page in the section "Series of Elif Statements"](.guides/images/efficiency-elif.png)


All of the if statements will run, even when the letter grade has been determined. The elif statements will stop once one of them is true. Use the code visualizers below to see how Python steps through the two programs below.

### Series of If Statements
```python
grade = 82

if grade < 60:
    print("You got an F.")
if grade >= 60 and grade < 70:
    print("You got a D.")
if grade >= 70 and grade < 80:
    print("You got a C.")
if grade >= 80 and grade < 90:
    print("You got a B.")
if grade >= 90 and grade <= 100:
    print("You got an A.")
```

[Code Visualizer](open_tutor code/selection/elif-efficiency.py)
{try it}(python3 code/selection/elif-efficiency.py 1)

### Series of Elif Statements
```python
grade = 82

if grade < 60:
    print("You got an F.")
elif grade < 70:
    print("You got a D.")
elif grade < 80:
    print("You got a C.")
elif grade < 90:
    print("You got a B.")
else:
    print("You got an A.")
```

[Code Visualizer](open_tutor code/selection/elif-efficiency.py)
{try it}(python3 code/selection/elif-efficiency.py 2)

|||challenge
## What happens if you:
* Change `grade` to `0` and then run both programs through the visualizer?
* Change `grade` to `100` and then run both programs through the visualizer?

|||

[Code Visualizer](open_tutor code/selection/elif-efficiency.py)
{try it}(python3 code/selection/elif-efficiency.py 3)

{Check It!|assessment}(fill-in-the-blanks-2639153112)
