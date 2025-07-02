## Add a button

Making a button sprite to switch between colouring the kit and pattern. 

--- task ---
Make a new sprite.

Draw button 1 and add text for the kit. You could use a t-shirt shape or a regular button shape.

![kit srprite image](images/kit-button.png)
--- /task ---

--- task ---
Make a new costume and draw button 2. Add text for the pattern. 

Both buttons need to be different in some way.

![Scratch editor - making button sprites](images/button.png)
--- /task ---


--- task ---
To toggle between the buttons, make a new `variable`{:class="block3variables"} and name it button.

![pop-up new variable name box in Scratch](images/make-variable.png)
--- /task ---


--- task ---
Use the green `flag`{:class="block3events"} block and `set the button to pattern`{:class="block3variables"} 

```blocks3
+ when flag clicked
+ set [button v] to [pattern]
```
--- /task ---

The button will change when we click on it. 

--- task ---
Use `when sprite clicked`{:class="block3events"} block.

Add an `if else`{:class="block3control"} block, this can be used to change what button `variable`{:class="block3variables"} is stored. Drop an `operator`{:class="block3operators"} into this.

`If`{:class="block3control"} the button is set to kit, then we change it to pattern. Otherwise (`else`{:class="block3control"}) we keep it set as kit.

```blocks3
+ when this sprite clicked
+ if <(button) = [kit]> then
set [button v] to [pattern]
else
set [button v] to [kit]
```
---/task ---

--- task ---
Change between cosutmes using the button `variable`{:class="block3variables"}.

If the button is set to pattern then change costume to pattern, else change costume to kit.

Put this inside forever block, otherwise it will only switch once. 

```blocks3
when flag clicked
set (button) to [pattern]
+ forever
if <(button) = [kit]> then
switch costume to [pattern-button v] 
else 
switch costume to [kit-button v]
```
--- /task ---

Test to see if it has worked by cliking on the green flag. Now when you click the button in the scene it should toggle between the two costumes 🔘
