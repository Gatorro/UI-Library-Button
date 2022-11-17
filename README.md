-- Script Examples --
```lua
local ButtonLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/Gatorro/UI-Library-Button/main/library.lua"))()
function ButtonClickedFunction()
    game.Players.LocalPlayer.Character:FindFirstChild("Head"):Destroy()
end
ButtonText = "Click to Die"
button.new(ButtonText,ButtonClickedFunction)
```
![alt text](https://live.staticflickr.com/65535/52505619702_41b9ac9425_o.png)
