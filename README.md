local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("NoobX", "BloodTheme")
local Tab = Window:NewTab("Hack lv")
local Section = Tab:NewSection("Section Name")
Section:NewButton("EZ", "ButtonInfo", function()
    print("Clicked")
game:GetService("Players").LocalPlayer.Stamina.Value = 10000
wait()
game:GetService("Players").LocalPlayer.Defense.Value = 50
wait()
game:GetService("Players").LocalPlayer.Dribble.Value = 50
wait()
game:GetService("Players").LocalPlayer.Power.Value = 50
wait()
game:GetService("Players").LocalPlayer.Speed.Value = 50
wait()
game:GetService("Players").LocalPlayer.Intellect.Value = 50
wait()
game:GetService("Players").LocalPlayer.Level.Value = 100
end)
