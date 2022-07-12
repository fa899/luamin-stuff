# ROBLOX LUAMIN

## MADE FOR DEVELOPERS
This script was made for Developers, and other people.

## SAFE (NO IP-GRAB, COOKIE-GRAB OR TOKEN-LOG)
This script is just a ModuleScript for exploits (Customized like an API).

## HOW TO USE:
First, we need to grab the loadstring. Your code will look like this for a start (Exploiter Script):
```lua
local luamin = loadstring(game:HttpGet("https://raw.githubusercontent.com/fa899/luamin-stuff/main/Luamin%20(beaut%26minif-ier)"))()
```
For developers: Go to https://raw.githubusercontent.com/fa899/luamin-stuff/main/Luamin%20(beaut%26minif-ier)
And then copy everything, make an modulescript, and then paste it there.
And then you can use this:
```lua
local luaminDestination = (game:GetService("ReplicatedStorage"):FindFirstChild("luamin") and game:GetService("ReplicatedStorage").luamin or game:GetService("ReplicatedStorage"):WaitForChild("luamin"))
local luamin = require(luaminDestination)
-- luamin.Beautify, luamin.Minify ()
```
Here is how you can also use it (can help out):
luamin.Minify(code/src <string>, renameGlobals <boolean>) -- Minify
luamin.Beautify(code/src <string>, renameVars <boolean>, renameGlobals <boolean>) -- Beautify

booleans are basically like yes/no.
false = no
true = yes
