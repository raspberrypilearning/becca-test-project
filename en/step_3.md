## Make flag decoration


--- task ---
add flag decoration sprite to the kit in each colour
--- /task ---


--- task ---
add a selector sprite 
--- /task ---


--- task ---
add chooser code to selector sprite

when this sprite clicked
if <[button] = [kit]> then
set [button] to [flag]
else
set [button] to [kit] 
--- /task ---


--- task ---
add a selector sprite 

when flag clicked
set [button] to [kit] // reset to kit
forever
if <[button] = [kit]> then
broadcast [kit]
switch costume to [kit-button]
if <[button]=[flag]> then
broadcast [flag]
switch costume to [flag-button]
--- /task ---


--- task ---
checking the status of the chooser to broardcast a message and change the sprite

when flag clicked
set [button v] to [kit] // reset to kit
forever
if <(button) = [kit]> then
broadcast [kit]
switch costume to [kit-button v]
if <(button)=[flag]> then
broadcast [flag]
switch costume to [flag-button v]

--- /task ---

--- task ---
change the blocks in the sprites so that they are responding to the chooser

gif of moveing the blocks

when I receive [yellow v]
if <(button) = [flag]> then
 switch costume to [yellow v]

--- /task ---

