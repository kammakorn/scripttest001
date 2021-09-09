# scripttest001
kairobinandkaijame

-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local c = Instance.new("TextButton")
local coloss = Instance.new("TextButton")
local f = Instance.new("TextButton")
local zom = Instance.new("TextButton")
local dark = Instance.new("TextButton")
local cold = Instance.new("TextButton")
local green = Instance.new("TextButton")
local ship = Instance.new("TextButton")
local fac = Instance.new("TextButton")
local forgot = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.Position = UDim2.new(0.130434781, 0, 0.14314115, 0)
Main.Size = UDim2.new(0, 511, 0, 274)

c.Name = "c"
c.Parent = Main
c.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
c.Position = UDim2.new(0.0645792633, 0, 0.0802919716, 0)
c.Size = UDim2.new(0, 194, 0, 36)
c.Font = Enum.Font.SourceSans
c.Text = "c"
c.TextColor3 = Color3.fromRGB(0, 0, 0)
c.TextSize = 14.000
c.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-389.610443, 88.987236, 306.032288, -0.901004851, 0, 0.433809221, 0, 1.00000012, -0, -0.433809221, 0, -0.901004851)
end)

coloss.Name = "coloss"
coloss.Parent = Main
coloss.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
coloss.Position = UDim2.new(0.573385537, 0, 0.0802919716, 0)
coloss.Size = UDim2.new(0, 194, 0, 36)
coloss.Font = Enum.Font.SourceSans
coloss.Text = "coloss"
coloss.TextColor3 = Color3.fromRGB(0, 0, 0)
coloss.TextSize = 14.000
coloss.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1831.30054, 44.8527527, 1370.16992, 0.10913182, 0, 0.994027317, -0, 1, -0, -0.994027317, 0, 0.10913182)
end)
f.Name = "f"
f.Parent = Main
f.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
f.Position = UDim2.new(0.0645792559, 0, .251824796, 0)
f.Size = UDim2.new(0, 194, 0, 36)0
f.Font = Enum.Font.SourceSans
f.Text = "f"
f.TextColor3 = Color3.fromRGB(0, 0, 0)
f.TextSize = 14.000
f.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-11.3114557, 29.2767334, 2771.52246, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)

zom.Name = "zom"
zom.Parent = Main
zom.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
zom.Position = UDim2.new(0.573385537, 0, 0.251824796, 0)
zom.Size = UDim2.new(0, 194, 0, 36)
zom.Font = Enum.Font.SourceSans
zom.Text = "zom"
zom.TextColor3 = Color3.fromRGB(0, 0, 0)
zom.TextSize = 14.000
zom.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5462.54199, 73.6427307, -749.625, 0.9993819, 0, 0.0351559781, -0, 1.00000012, -0, -0.0351559781, 0, 0.9993819)
end)

dark.Name = "dark"
dark.Parent = Main
dark.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
dark.Position = UDim2.new(0.0645792559, 0, 0.434306592, 0)
dark.Size = UDim2.new(0, 194, 0, 36)
dark.Font = Enum.Font.SourceSans
dark.Text = "dark"
dark.TextColor3 = Color3.fromRGB(0, 0, 0)
dark.TextSize = 14.000
dark.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3745.10327, 13.7082357, -3474.61597, 0.832050323, 0, 0.554700196, -0, 1.00000012, -0, -0.554700196, 0, 0.832050323)
end)

cold.Name = "cold"
cold.Parent = Main
cold.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
cold.Position = UDim2.new(0.573385537, 0, 0.434306622, 0)
cold.Size = UDim2.new(0, 194, 0, 36)
cold.Font = Enum.Font.SourceSans
cold.Text = "cold"
cold.TextColor3 = Color3.fromRGB(0, 0, 0)
cold.TextSize = 14.000
cold.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6050.95459, 15.0098133, -4840.32813, -0.811052561, 0, 0.584973395, 0, 1, -0, -0.584973454, 0, -0.811052442)
end)

green.Name = "green"
green.Parent = Main
green.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
green.Position = UDim2.new(0.0645792559, 0, 0.613138676, 0)
green.Size = UDim2.new(0, 194, 0, 36)
green.Font = Enum.Font.SourceSans
green.Text = "green"
green.TextColor3 = Color3.fromRGB(0, 0, 0)
green.TextSize = 14.000
green.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2462.15967, 95.8736343, -3243.42456, 0.931113064, 0, -0.364730716, -0, 1, -0, 0.364730716, 0, 0.931113064)
end)

ship.Name = "ship"
ship.Parent = Main
ship.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ship.Position = UDim2.new(0.573385537, 0, 0.613138676, 0)
ship.Size = UDim2.new(0, 194, 0, 36)
ship.Font = Enum.Font.SourceSans
ship.Text = "ship"
ship.TextColor3 = Color3.fromRGB(0, 0, 0)
ship.TextSize = 14.000
ship.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(998.090393, 124.115166, 32906.6172, -0.175843477, -0, -0.984418094, -0, 1, -0, 0.984418213, 0, -0.175843462)
end)

fac.Name = "fac"
fac.Parent = Main
fac.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
fac.Position = UDim2.new(0.0645792559, 0, 0.784671545, 0)
fac.Size = UDim2.new(0, 194, 0, 36)
fac.Font = Enum.Font.SourceSans
fac.Text = "fac"
fac.TextColor3 = Color3.fromRGB(0, 0, 0)
fac.TextSize = 14.000
fac.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(424.126984, 211.161713, -427.540497, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)

forgot.Name = "forgot"
forgot.Parent = Main
forgot.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
forgot.Position = UDim2.new(0.573385537, 0, 0.784671545, 0)
forgot.Size = UDim2.new(0, 194, 0, 36)
forgot.Font = Enum.Font.SourceSans
forgot.Text = "forgot"
forgot.TextColor3 = Color3.fromRGB(0, 0, 0)
forgot.TextSize = 14.000
forgot.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3011.80469, 307.5336, -10163.6787, 0.989178538, 0, -0.146716759, -0, 1, -0, 0.146716759, 0, 0.989178538)
end)
