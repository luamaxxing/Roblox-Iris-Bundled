Latest version of [Iris](https://github.com/SirMallard/Iris) bundled into a single script for loadstring purposes.

Can be loaded as:
```lua
local Iris = loadstring(game:HttpGet("https://raw.githubusercontent.com/luamaxxing/Roblox-Iris-Bundled/refs/heads/main/Bundle.lua"))().Init(game.CoreGui)
```
Example code:
```lua
local Iris = loadstring(game:HttpGet("https://raw.githubusercontent.com/luamaxxing/Roblox-Iris-Bundled/refs/heads/main/Bundle.lua"))().Init(game.CoreGui)

Iris:Connect(function()
    Iris.Window({"My First Window!"})
        Iris.Text({"Hello, World"})
        Iris.Button({"Save"})
        Iris.InputNum({"Input"})
    Iris.End()
end)
```
