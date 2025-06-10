## Adding decoration

--- task ---
Add broadcast blocks 

when flag clicked
set [button] to [kit] // reset to kit
forever
if <[button] = [kit]> then
broadcast (kit)
switch costume to [kit-button]
if <[button]=[flag]> then
broadcast (flag)
switch costume to [flag-button]
--- /task ---


--- task ---
In the kit spite add an if block so that it only switches when the button is set as kit

// gif of moving the blocks

when I receive [yellow v]
if <(button) = [flag]> then
 switch costume to [yellow v]

--- /task ---

--- task ---
In the flag spite do the same - add an if block so that it only switches when the button is set as flag

gif of moveing the blocks

```blocks3
when I receive [yellow v]
if <(button) = [flag]> then
 switch costume to [yellow v]
```

--- /task ---

