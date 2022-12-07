local player = game.Players.LocalPlayer

local White = {
    "RobinConway9",
    "KostyaTasher",
    "Her0brine404"
 

}


if not table.find(White,player.Name) then
    player:Kick("WTF R U DOING???")
    return;
end





local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Very Op script [Private]", "BloodTheme")
local Tab = Window:NewTab("!!!")
local Section = Tab:NewSection("ITS ONLY ONE SCRIPT EVER!!!")
local Section = Tab:NewSection("OTHERS ARE FAKE!!!")
local Section = Tab:NewSection("MY DISCORD!!!")
local Section = Tab:NewSection("Anha#4156")
local Tab = Window:NewTab("Main Script")
local Section = Tab:NewSection("Its buying Golden Ticket")
Section:NewButton("Buy Golden Ticket", "Buy", function()
    print("Soon!")
end)
