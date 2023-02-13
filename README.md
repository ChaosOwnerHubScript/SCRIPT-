
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Chaos Support", "Synapse")
 
--Tab--
local Discord = Window:NewTab("Discord")
local AttackGames = Window:NewTab("AttackGames")
 
 
--Section--
local Section = Discord:NewSection("Others")
local Section = AttackGames:NewSection("AttackGames")
 
 
--Buttons/Link--
Section:NewButton("Discord", "Join ", function()
 
end)
Section:NewButton("infinite Yield", "Alot Commands", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)
