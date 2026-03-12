# DefaultInput.ini

contains configurations for keyboard and mouse / controller inputs.<br>

## Keybind Structure

keybinds look like this: `.Bindings=(Name="",Command="")`.<br>
`Name=""` contains the key that should execute the command or name of the binding.<br>
`Command=""` contains the command to execute. commands can contain the name of a keybind if you wish to execute that keybind's command.<br>

here's an example of a keybind: `.Bindings=(Name="F1",Command="Camera Freecam")`.<br>
`Name="F1"` when you press the "F1" key. it executes the command.<br>
`Command="Camera Freecam"` when the "F1" key is pressed. it enables freecam.<br>

## Command Chaining

you can chain multiple commands together using the `|` symbol.<br>

here's a example of command chaining: `.Bindings=(Name="F1",Command="Camera Default | Show COLLISION")`.<br>
when F1 is pressed. freecam will be disabled and collision boxes will be shown.<br>

## SetBind

you can use this to change the "Command" of a keybind.<br>

an example of this would be toggling freecam:
```
.Bindings=(Name="F1",Command="Freecam")
.Bindings=(Name="Freecam",Command="Camera Freecam | SetBind F1 Normalcam")
.Bindings=(Name="Normalcam",Command="Camera Default | SetBind F1 Freecam")
```
the first keybind does so when "F1" is pressed. it executes the keybind with the name "Frecam".<br>
the second keybind enables freecam and sets the command of the "F1" keybind to "Normalcam".<br>
the third keybind disables freecam and sets the command of the "F1" keybind to "Freecam".<br>

by making the second and third keybinds set the command of the "F1" keybind to each other. it allows us to toggle between them everytime we press the "F1" key.<br>

## Class Varibles

you can set class varibles using the "set" keyword. here's an example of it: `set 'ClassName' 'VaribleName' 'Value'`.<br>
'ClassName' is the name of the class that contains the varible you want to modify.<br>
'VaribleName' is the name of the varible from the class.<br>
'Value' is the new value of the varible.<br>

here's an example where the set the Player's jump height: `.Bindings=(Name="F1",Command="set OLHero JumpClearanceWalking 800 | set OLHero JumpClearanceRunning 1000")`.<br>
when the "F1" key is pressed. the player's jump height when walking and running is changed to a higher number.<br>

## Additional Information

please visit the [Unreal Engine 3 Docs](https://docs.unrealengine.com/udk/Three/KeyBinds.html) for full docs, mappable keys, and additional examples of keybinds.<br>

## Commands

### Camera Commands

* Camera Freecam - enables Freecam.
* Camera Default - disables Freecam.

### Show Commads

* Show COLLISION - toggles whether or not to display hitboxes.
* Show POSTPROCESS - toggles Post Processing.
* Show LEVELCOLORATION - toggles whether or not textures should be rendered.
* Show FOG - toggles whether or not fog is rendered.
* Show VOLUMES - toggles volumes.
* Show PATHS - toggles whether or not to display enemy paths.
* Show SKELMESHES - toggles whether or not Skeletal Meshes should be rendered.
* Show DECALS - toggles whether or not decals should be rendered.
* Show BOUNDS - toggles whether or not bounding boxes should be displayed.
* Show BSP - ??
* Show COVER - ??
* Show TERRAIN - ??
* Show SPLINES - ??

#### ShowDebug Commands

* ShowDebug OLAI - dislays information about the player and AI characters.
* ShowDebug VOICEMANAGER - displays the currently played voices.

### Stat Commands

* Stat LEVELS - displays Level Streaming data.
* Stat FPS - displays FPS on screen.

### StreamMap Command

* StreamMap 'MapName' - loads the specified map.

### Other Commands

* Exit - ??
* FreezeAt - ??
* Open 'MapName' - ??

## OLA

??
