## Colour the flowers

You can use the same method with the tree, to change the colour of the flowers.

--- task ---

Click on the flowers sprite and then create a new variable called `flowers`{:class="block3variables"}

--- /task ---

--- task ---

You can change the `color effect`{:class="block3looks"} of the flowers, in the same way you changed the `size`{:class="block3looks"} of the tree.

![image of flowers sprite](images/flowers-sprite.png)

```blocks3
when flag clicked
forever
set [color v] effect to [0]
```

--- /task ---

--- task ---

Then add in your `flowers`{:class="block3variables"} variable.

![image of flowers sprite](images/flowers-sprite.png)

```blocks3
when flag clicked
forever
+ set [color v] effect to (flowers)
```

--- /task ---

Variables that store numbers don't always have to be greater than 0. You can use negative numbers as well.

--- task ---

Right click on the `flowers`{:class="block3variables"} variable on the stage and set it as a slider.

Now change the slider ranger from `-100`{:class="block3variables"} to `100`{:class="block3variables"}

![image showing the dialogue box for adjusting the range of the flowers variable with -100 as minimum and 100 as maximum](images/flowers-range.png)

--- /task ---

--- task ---

Click the green flag and then adjust your `flowers`{:class="block3variables"} slider to see the flowers change colour.

--- /task ---





