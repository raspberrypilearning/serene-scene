## Grow a tree

--- task ---

**Online:** open the [starter project](http://rpf.io/serene-scene-on){:target="_blank"} in Scratch.
 
**Offline:** open the [project starter file](http://rpf.io/p/en/serene-scene-go){:target="_blank"} in the Scratch offline editor. If you need to, you can [download and install Scratch here](https://scratch.mit.edu/download){:target="_blank"}.

--- /task ---

You should see a forest scene with a tree, flowers, and a grasshopper.

![image of stage for the starter project containing a tree, some flowers, a grasshopper and a forest background](images/stage_1.png)

First, you will make the tree change its size.

--- task ---

Select the **Tree1** sprite from the Sprite list below the Stage.

![sprites shown with the tree selected](images/sprites.png)

--- /task ---

A **variable** is a way of storing numbers and/or text. 

--- task ---

To create a new `variable`{:class="block3variables"} in Scratch, click on the `Variables`{:class="block3variables"} blocks menu.

![image showing variable menu](images/variable.png) 

Then, click the **Make a Variable** button.

![image showing the make a variable button](images/make-a-variable.png)

You can give your `variable`{:class="block3variables"} a name. Call this variable `tree`.

![image showing dialogue box for creating and naming a variable, with the name field filled out with tree](images/name-variable.png)

--- /task ---

You should now see five new blocks that you can use.

```blocks3
(tree)

set [tree v] to [0]

change [tree v] by [1]

show variable [tree v]

hide variable [tree v]
```

You will also see that the `tree`{:class="block3variables"} variable is visible on the Stage.

![image showing the stage with the tree variable visible](images/stage_2.png)

--- task ---

There are many ways to control the **value** of a `variable`{:class="block3variables"}, but in this project, you will use **sliders**.

On the Stage, right-click on the `tree`{:class="block3variables"} variable, and a menu will appear.

![image showing context menu for the variable on the stage](images/variable-menu.png)

Select **slider** from the menu.

![image showing tree variable with slider](images/tree-slider.png)

--- /task ---

--- task ---

Move the slider forwards and backwards, and you will see that the value of the `tree`{:class="block3variables"} variable changes between `0`{:class="block3variables"} and `100`{:class="block3variables"} (percent).

--- /task ---

Now, you will use the value of the `tree`{:class="block3variables"} variable to change the size of the tree.

--- task ---

First, use a `when green flag clicked`{:class="block3events"} block with a `forever`{:class="block3control"} loop. Add a `set size to`{:class="block3looks"} block into the loop.

This means that once the flag is clicked, the `set size to`{:class="block3looks"} block in the `forever`{:class="block3control"} loop will keep the tree size at 100%.

![tree sprite image](images/tree-sprite.png)

```blocks3
when flag clicked
forever
set size to [100] %
```

--- /task ---

--- task ---

Now, add the `tree`{:class="block3variables"} variable into the `set size to`{:class="block3looks"} block.

--- no-print ---

![animate gif showing the tree variable placed inside the set size block](images/place-variable.gif)

--- /no-print ---

![tree sprite image](images/tree-sprite.png)

```blocks3
when flag clicked
forever
+ set size to (tree) %
```

--- /task ---

You can now move the slider to adjust the size of the tree.

--- no-print ---

![animated gif showing the tree slider being adjusted and the tree changing in size](images/change-tree.gif)

--- /no-print ---

At the moment, the tree size can only be changed from `0`{:class="block3variables"} to `100`{:class="block3variables"}.

--- task ---

On the Stage, right-click on the `tree`{:class="block3variables"} slider and select **change slider range**.

![image showing context menu for the slider, with change slider range visible](images/slider-range.png)

--- /task ---

--- task ---

Change the range to between `100` and `300`.

![image showing slider dialogue box with minimum set to 100 and maximum set to 300](images/adjusted-range.png)

Now, move the slider to watch your tree grow in size from 100% to 300%.

--- /task ---

--- save ---





