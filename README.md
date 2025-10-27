local Version = "1.6.41"
local WindUI = loadstring(game:HttpGet("https://github.com/Footagesus/WindUI/releases/download/" .. Version .. "/main.lua"))()

local Window = WindUI:CreateWindow({
    Title = "Catholic Hub|Evade",
    Icon = "door-open", -- lucide icon. optional
    Author = "by Denolk", -- optional
})
--------------------------------------
---//TAB CREDITS
--------------------------------------
local Tab = Window:Tab({
    Title = "Credits",
    Icon = "List", -- optional
    Locked = false,
})
