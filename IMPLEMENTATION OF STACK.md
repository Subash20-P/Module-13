
Skip to content

    sabarisun
    Module-13

Repository navigation

    Code
    Pull requests
    Actions
    Projects
    Security
    Insights

You’re making changes in a project you don’t have write access to. Submitting a change will write it to a new branch in your fork Subash20-P/Module-13, so you can send a pull request.

    Module-13

/
in
main

Indent mode
Indent size
Line wrap mode
Editing IMPLEMENTATION OF STACK.md file contents
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48

# Exp.No:13b  
## IMPLEMENTATION OF STACK

---

### AIM  
To write a Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`).

---

### ALGORITHM

1. **Start the program.**
2. **Define a class `st`** with the following methods:
   - `push(self, num)`: Adds the number `num` to the stack.
   - `pop(self)`: Removes and returns the top element from the stack.
3. **Create a stack object `s`** using the class `st`.
4. **Input the stack size**: Take an integer input `size` to define the size of the stack.
5. **Loop through numbers from 1 to size**: Add only the odd numbers to the stack using the `push()` method.
6. **Display the elements** in the stack after the loop completes.
7. **Call `pop()`** to remove the top element from the stack and display the popped element.
8. **Display the stack again** to show the remaining elements.
9. **End the program.**

---

### PROGRAM

```python
stack = []
for i in range(7):
    a=input()
    stack.append(a)
print("Stack before elements are popped")
print(stack)
for i in range(5):
    stack.pop()
print("\nStack after elements are popped:")
print(stack)
```

### OUTPUT
<img width="1185" height="358" alt="image" src="https://github.com/user-attachments/assets/1e16dc18-cfdf-4cf6-ae94-cd7cf8a8fd5c" />

### RESULT
Therefore, the output is the example to write a Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`).

Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
Attach files by dragging & dropping, selecting or pasting them.
Editing Module-13/IMPLEMENTATION OF STACK.md at main · sabarisun/Module-13
