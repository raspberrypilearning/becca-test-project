## Make colour pickers

--- task ---
Create colour picker sprites. These could be squares, circles, or draw them freehand with the paintbrush tool. 

Right click to duplicate a sprite, and change the fill for each colour. Then name them after the colour.

![Making new sprites for colour pickers in skratch, round balls in different colours](images/colour-sprite.png)
--- /task ---


--- task ---
In the code `when sprite clicked`{:class="block3events"} block and add a `broadcast`{:class="block3events"} message to each of the colour sprites.

Name the new message after the colour. 

```blocks3
+when this sprite clicked
+broadcast [blue v]
```
--- /task ---

--- task ---
Select the kit sprite. 

![Making new sprites for colour pickers in skratch, round balls in different colours](images/kit-sprite.png)
--- /task ---

--- task ---
Add a `receive`{:class="block3events"} block that `switches`{:class="block3looks"} the kit costume for each colour

```blocks3
+when I receive [blue v]
+switch costume to [blue v]
```
--- /task ---

Test your project!

You should be able to click the colours to change your kit 👕



