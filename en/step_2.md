## Creating your kit

In this step you'll design the basics of the kit, and can add a background too.

--- task ---
Delete the cat sprite and create a sports kit, you could choose a sprite, or draw with the paint tool.

![Sprite selection menu in Scratch with the “Choose a Sprite” button highlighted](images/choose.png)

We searched for "shirt".

![Sprite selection screen in Scratch showing a shirt and a search for "shirt"](images/shirt.png)
--- /task ---


--- task ---
Change the design to how you want it, and add your first colour with the fill tool. We used the gradient fill to make the costume colours pop!

![Scratch costume editor showing a pink shirt with a gradient fill and the colour settings panel open](images/fill.png)
--- /task ---

--- task ---
Right click to duplicate the costume for each colour you want to use. 

![Scratch costume editor showing right click function on costumes](images/duplicate.png)
--- /task ---

--- task ---
Fill each costume with a new colour and name the costumes to match.

![Scratch costume editor showing series of shirts with different colours](images/costumes.png)
--- /task ---

--- task ---
Create colour picker sprites. These could be squares, circles, or draw them freehand with the paint tool. 

Duplicate a sprite, and change the fill for each colour. Then name them after the colour.

![Making new sprites for colour pickers in skratch, round balls in different colours](images/colour-sprite.png)

--- /task ---


--- task ---

Add a `when sprite clicked`{:class="block3events"} block and add a `broadcast`{:class="block3events"} message to each of the colour sprites.

Name the new message after the colour. 

```blocks3
when this sprite clicked
broadcast [blue]
``` 

--- /task ---


--- task ---
Add a `receive`{:class="block3events"} block that `switches`{:class="block3looks"} the kit costume for each colour

```blocks3
when I receive [blue]
switch costume to [blue]
```

--- /task ---

Test your project!

You should be able to click the colours to change your kit 👕

