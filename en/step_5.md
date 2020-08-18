## Add some fauna

**Fauna** means **animals**. In this step, you will add a moving grasshopper to your serene scene.

--- task ---

Set up the **Grasshopper** sprite so that it moves from left to right and appears behind the tree and flowers.

![image of grasshopper sprite](images/grasshopper-sprite.png)

```blocks3
when flag clicked
go to [back v] layer
set rotation style [left-right v]
```

--- /task ---

--- task ---

Now, make your **Grasshopper** sprite move back and forth across the screen.

![image of grasshopper sprite](images/grasshopper-sprite.png)

```blocks3
when flag clicked
go to [back v] layer
set rotation style [left-right v]
+ forever
move [5] steps
next costume
if on edge, bounce
```
--- /task ---

The **Grasshopper** sprite is moving a little quickly at the moment, but you can use a `variable`{:class="block3variables"} and a `wait`{:class="block3control"} block to slow it down.

--- task ---

Create a new variable and switch it to a slider. You can call the variable `grasshopper`.

--- /task ---

--- task ---

Now, you can use a `wait`{:class="block3control"} block to slow the grasshopper down.

![image of grasshopper sprite](images/grasshopper-sprite.png)

```blocks3
when flag clicked
go to [back v] layer
set rotation style [left-right v]
forever
move [5] steps
next costume
if on edge, bounce
+ wait (grasshopper) seconds
```

--- /task ---

If you click on the green flag and move the slider, you'll notice that the grasshopper moves very slowly. To fix this, you can multiply the `grasshopper`{:class="block3variables"} variable by a number smaller that 1.

--- task ---

Go to the `Operators`{:class="block3operators"} blocks menu and find the `/`{:class="block3operators"} block.

```blocks3
[] / []
```

--- /task ---

--- task ---

Now, drag this into your script to divide the `grasshopper`{:class="block3variables"} by `100`.

![image of grasshopper sprite](images/grasshopper-sprite.png)

```blocks3
when flag clicked
go to [back v] layer
set rotation style [left-right v]
forever
move [5] steps
next costume
if on edge, bounce
+ wait ((grasshopper) / [100]) seconds
```

--- /task ---

When you adjust the slider, the grasshopper will move at a different speed. You might also like to adjust the **slider range** down to between `0` and `20`.



