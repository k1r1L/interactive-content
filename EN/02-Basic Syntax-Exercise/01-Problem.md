[slide hideTitle]
# Problem: Ages
[code-task title="Ages" taskId="JF-01-01" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
## Description

Write a program that determines whether based on the given age a person is: 

**baby**, **child**, **teenager**, **adult**, **elder**. 

The bounders are:
•	0-2 – baby; 
•	3-13 – child; 
•	14-19 – teenager;
•	20-65 – adult;
•	>=66 – elder; 

All the values are inclusive

### Example
| **Input** | **Output** |
| --- | --- |
| 10 | child |

[/task-description]
[code-io /]
[tests]
[test]
[input]
20
[/input]
[output]
adult
[/output]
[/test]
[test]
[input]
15
[/input]
[output]
teenager
[/output]
[/test]
[test]
[input]
90
[/input]
[output]
elder
[/output]
[/test]
[test]
[input]
1
[/input]
[output]
baby
[/output]
[/test]
[test]
[input]
10
[/input]
[output]
child
[/output]
[/test]
[/tests]
[/code-task]
[/slide]