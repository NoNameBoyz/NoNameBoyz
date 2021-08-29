
local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local Label = Instance.new("TextLabel")
local Hacks = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
main.Position = UDim2.new(0.270072997, 0, 0.203672782, 0)
main.Size = UDim2.new(0, 397, 0, 183)
main.Active = true
main.Draggable = true

Label.Name = "Label"
Label.Parent = main
Label.BackgroundColor3 = Color3.fromRGB(109, 109, 109)
Label.Size = UDim2.new(0, 397, 0, 50)
Label.Font = Enum.Font.SourceSans
Label.Text = "Big Paintball Hacks   |   By NoNameBoyz"
Label.TextColor3 = Color3.fromRGB(0, 0, 0)
Label.TextSize = 14.000

Hacks.Name = "Hacks"
Hacks.Parent = main
Hacks.BackgroundColor3 = Color3.fromRGB(17, 21, 255)
Hacks.Position = UDim2.new(0, 0, 0.273224056, 0)
Hacks.Size = UDim2.new(0, 397, 0, 133)
Hacks.Font = Enum.Font.SourceSans
Hacks.Text = "Kill All"
Hacks.TextColor3 = Color3.fromRGB(0, 0, 0)
Hacks.TextSize = 40.000
Hacks.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/The3Bakers4565/Spicy-Bagel/main/Other_Scripts/Big_Paintball/Kill_All.lua"))()
end)
