# Infinite While Loop

[slide]
# Video
 
[vimeo-video startTimeInSeconds="2968" endTimeInSeconds="3357"]
[stream language="EN" videoId="343587107" default /]
[stream language="RO" videoId="392266139" /]
[/vimeo-video]

[/slide]

[slide]
# Infinite While Loop
We call an infinite loop one that repeats infinitely the performance of its body. 

In `while` loops the end check is a conditional expression that always returns `True`. 

```py live
while True:
  print('Hello world!')
```

# Example: Infinite While Loop (Bug)
```py live
command = "Add"
while command != "End":
  print("Executing: ", command)
```

In the example above, the condition is always `True` because it is never changed.

# Example: Finite Loop (Bug Fixed)
```py live
command = "Add"
while command != "End":
  print("Executing: ", command)
  command = input()
```

Here, the value of the variable `command` is changed at each iteration and the **infinite loop** is avoided. 
[/slide]