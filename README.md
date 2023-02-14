local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Chaos Support", "Synapse")

--Tab--
local Discord = Window:NewTab("Discord")
local AttackGames = Window:NewTab("AttackGames")
local Executes = Window:NewTab("Executes")

--Section--
local Discord = Discord:NewSection("Discord")
local AttackGames = AttackGames:NewSection("AttackGames")
local Executes = Executes:NewSection("Executes")


--Buttons/Link--
Discord:NewButton("Discord", "Link Here https://discord.gg/y6BFQzHS ", function()
    
end)
AttackGames:NewButton("infinite Yield", "Alot Commands", function()
    
end)

--RemoteSpy/SimpleSpy--
Executes:NewButton("RemoteSpy", "This is Good! ", function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/ChaosOwnerHubScript/Remote-Spy-lol/main/README.md"), true))()
end)
