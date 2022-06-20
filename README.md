-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.0067079463, 0, 0.0390243903, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

-- Scripts:

local function GFXDZBR_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	
	-- Teleport button script --
	 
	local plr = script.Parent.Parent.Parent.Parent -- if this doesnt work, use your own variables that targeting to Player
	local char = plr.Character
	 
	script.Parent.MouseButton1Click:Connect(function()
		local nos = Instance.new("Part")
		nos.Parent = workspace
		nos.Name = "nos" -- Change Part1 to Your Teleport brick name
		nos.Anchored = true
		nos.Position = Vector3.new(-45,36,1080)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-52,54,1647)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-63,70,2416)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-88,57,3977)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-74,50,4834)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-95,45,5531)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-121,50,6346)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-144,32,7081)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-58,50,7081)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-58,50,8027)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-46,50,8427)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-57,-332,9435)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos.Position = Vector3.new(-57,-352,9498)
		char.HumanoidRootPart.CFrame = workspace.nos.CFrame
		wait(0.1)
		nos:Destroy()
	end)
	 
	 
end
coroutine.wrap(GFXDZBR_fake_script)()
