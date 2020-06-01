## Test yourself

--- collapse ---
---

title: Question 1

---

--- task ---

Which of the following blocks would set the size of a sprite to 50% using a variable?

### A
```blocks3
set size to (50) %
```

### B
```blocks3
set [tree v] to (50)
set size to (50) %
```

### C
```blocks3
set [tree v] to (50)
set size to (tree) %
```

### D
```blocks3
change [tree v] by (50)
set size to (tree) %
```

--- /task ---

--- /collapse ---

--- collapse ---
---

title: Question 2

---

--- task ---

Which of the following blocks would be used to change the position of a sprite, using a variable slider?

### A
```blocks3
when flag clicked
forever
set [color v] effect to (grass)
```

### B
```blocks3
when flag clicked
repeat (10)
set [color v] effect to (grass)
```

### C
```blocks3
when flag clicked
forever
set [color v] effect to (50)
```

### D
```blocks3
when flag clicked
set [color v] effect to (grass)
```
--- /task ---

--- /collapse ---

--- collapse ---
---

title: Question 3

---

--- task ---

Which blocks could be used to make a sprite pause for less than a second, using a variable slider?

### A
```blocks3
set [time v] to (0.01) 
wait (time) seconds
```

### B
```blocks3
wait ((time) * (0.01)) seconds
```

### C
```blocks
wait (time) seconds
```

### D
```blocks3
wait ((time) * (100)) seconds
```

--- /task ---

--- /collapse ---

--- collapse ---
---

title: Answers

---

### Question 1

The answer is **C**.

The first block sets the variable `tree`{:class="block3variables"} to `50`{:class="block3variables"}, and the second block uses this variable to set the size of ther sprite.

### Question 2

The answer is **A**.

The first block makes sure the blocks run when the `green flag`{:class="block3events"} is clicked.
The second block makes sure that the program checks the `grass`{:class="block3variables"} variable all the time.
The third block keeps the `color effect`{:class="block3looks"} the same as the `grass`{:class="block3variables"} variable's value.

### Question 3

The answer is **B**.

The `() * ()`{:class="block3operators"} block uses a number smaller than `1`{:class="block3operators"} to make the `wait`{:class="block3control"} smaller than the `time`{:class="block3variables"} slider value.
--- /collapse ---

