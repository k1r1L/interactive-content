[slide]
# Character Multiplier
[code-task title="Character Multiplier" taskId="java-fundamentals-text-processing-02" executionType="tests-execution" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        // Write your code here
    }
}
```
[/code-editor]
[task-description]
## Description
Create a **method that takes two strings** as arguments and **returns the sum of their character codes multiplied** (multiply str1\[0\] with str2\[0\] and add to the total sum).

Then **continue with the next two characters**.

**If one of the strings is longer than the other**, **add the remaining character codes** to the total sum without multiplication.

### Example
| **Input** | **Output** |
| --- | --- |
| Jeff, john45, ab, cd, peter-white, @smith | Jeff | 
| | John45 |
| | peter-white |

[/task-description]
[code-io /]
[tests]
[test]
[input]
Gosho Pesho
[/input]
[output]
53253
[/output]
[/test]
[test]
[input]
123 522
[/input]
[output]
7647
[/output]
[/test]
[test]
[input]
a aaaa
[/input]
[output]
9700
[/output]
[/test]
[test]
[input]
mnoji sabe
[/input]
[output]
44894
[/output]
[/test]
[test]
[input]
leet test
[/input]
[output]
47800
[/output]
[/test]
[test]
[input]
poKys ePyrviqStringTuka
[/input]
[output]
57885
[/output]
[/test]
[test]
[input]
zzzzzzzzzzzzzzzzzzzzzzzzzzzz zzzzzzzzzzzzzzzzzzzzzzzzzzzz
[/input]
[output]
416752
[/output]
[/test]
[test]
[input]
ioers;hiuesyv843sao384uyvP309308u 0s8o48eieoveatgo4rh;owia390'a92qa
[/input]
[output]
256134
[/output]
[/test]
[/tests]
[/code-task]
[/slide]