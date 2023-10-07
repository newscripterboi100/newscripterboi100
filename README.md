-- Gui to Lua
-- Version: 3.2

-- Instances:

local PurplesHub = Instance.new("ScreenGui")
local MainBackground = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Name = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local Credits = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local FlyButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local NoclipButton = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")

--Properties:

PurplesHub.Name = "Purple's Hub"
PurplesHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
PurplesHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainBackground.Name = "Main Background"
MainBackground.Parent = PurplesHub
MainBackground.BackgroundColor3 = Color3.fromRGB(125, 73, 255)
MainBackground.BorderColor3 = Color3.fromRGB(0, 0, 0)
MainBackground.BorderSizePixel = 0
MainBackground.Position = UDim2.new(0.554334581, 0, 0.317230284, 0)
MainBackground.Size = UDim2.new(0, 281, 0, 266)

UICorner.Parent = MainBackground

Name.Name = "Name"
Name.Parent = MainBackground
Name.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
Name.BorderColor3 = Color3.fromRGB(0, 0, 0)
Name.BorderSizePixel = 0
Name.Size = UDim2.new(0, 281, 0, 50)
Name.Font = Enum.Font.GothamBold
Name.Text = "Purple's Hub"
Name.TextColor3 = Color3.fromRGB(132, 87, 248)
Name.TextScaled = true
Name.TextSize = 14.000
Name.TextStrokeTransparency = 0.500
Name.TextWrapped = true

UICorner_2.Parent = Name

Credits.Name = "Credits"
Credits.Parent = MainBackground
Credits.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
Credits.BorderColor3 = Color3.fromRGB(0, 0, 0)
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0, 0, 0.812030077, 0)
Credits.Size = UDim2.new(0, 281, 0, 50)
Credits.Font = Enum.Font.GothamBold
Credits.Text = "Made by MicrosoftBingTesting"
Credits.TextColor3 = Color3.fromRGB(132, 87, 248)
Credits.TextScaled = true
Credits.TextSize = 14.000
Credits.TextStrokeTransparency = 0.500
Credits.TextWrapped = true

UICorner_3.Parent = Credits

FlyButton.Name = "Fly Button"
FlyButton.Parent = MainBackground
FlyButton.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
FlyButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
FlyButton.BorderSizePixel = 0
FlyButton.Position = UDim2.new(0.0213523135, 0, 0.229323313, 0)
FlyButton.Size = UDim2.new(0, 268, 0, 68)
FlyButton.Font = Enum.Font.GothamBold
FlyButton.Text = "Fly"
FlyButton.TextColor3 = Color3.fromRGB(132, 87, 248)
FlyButton.TextScaled = true
FlyButton.TextSize = 14.000
FlyButton.TextStrokeTransparency = 0.500
FlyButton.TextWrapped = true

UICorner_4.Parent = FlyButton

NoclipButton.Name = "Noclip Button"
NoclipButton.Parent = MainBackground
NoclipButton.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
NoclipButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
NoclipButton.BorderSizePixel = 0
NoclipButton.Position = UDim2.new(0.0213523135, 0, 0.526315808, 0)
NoclipButton.Size = UDim2.new(0, 268, 0, 69)
NoclipButton.Font = Enum.Font.GothamBold
NoclipButton.Text = "Noclip (Rejoin if your done using)"
NoclipButton.TextColor3 = Color3.fromRGB(132, 87, 248)
NoclipButton.TextScaled = true
NoclipButton.TextSize = 14.000
NoclipButton.TextStrokeTransparency = 0.500
NoclipButton.TextWrapped = true

UICorner_5.Parent = NoclipButton

-- Scripts:

local function PXAVG_fake_script() -- FlyButton.LocalScript 
	local script = Instance.new('LocalScript', FlyButton)

	
	local runService = game:GetService("RunService")
	local userInputService = game:GetService("UserInputService")
	
	local character = game.Players.LocalPlayer.Character
	local hrp = character:WaitForChild("HumanoidRootPart")
	local camera = game.Workspace.CurrentCamera
	
	local bodyPos = Instance.new("BodyPosition", hrp)
	bodyPos.MaxForce = Vector3.new()
	bodyPos.D = 0
	
	local bodyGyro = Instance.new("BodyGyro", hrp)
	bodyGyro.MaxTorque = Vector3.new()
	bodyGyro.D = 10
	
	local speed = 1
	local isFlying = false
	
	local toggleKey = Enum.KeyCode.Q
	
	local button = script.Parent
	
	function fly()
		isFlying = true
		bodyPos.MaxForce = Vector3.new(100000, 100000, 100000)
		bodyGyro.MaxTorque = Vector3.new(100000, 100000, 100000)
		runService:BindToRenderStep("fly", 1, function()
			bodyPos.Position = hrp.Position + ((hrp.Position - camera.CFrame.p).unit * speed)
			bodyGyro.CFrame = CFrame.new(camera.CFrame.p, hrp.Position)
		end)
	end
	
	function stopFlying()
		isFlying = false
		runService:UnbindFromRenderStep("fly")
		bodyPos.MaxForce = Vector3.new()
		bodyGyro.MaxTorque = Vector3.new()
	end
	
	button.Activated:Connect(function()
		if not isFlying then
			fly()
		else
			stopFlying()
		end
	end)
	
	userInputService.InputBegan:Connect(function(input, isProcessed)
		if not isProcessed and input.KeyCode == toggleKey then
			stopFlying()
		end
	end)
	
end
coroutine.wrap(PXAVG_fake_script)()
local function YONPQZJ_fake_script() -- MainBackground.LocalScript 
	local script = Instance.new('LocalScript', MainBackground)

	-- to make the script draggable, we can set the parent of script is draggable
	script.Parent.Draggable = true
	script.Parent.Active = true
end
coroutine.wrap(YONPQZJ_fake_script)()
local function OQULOCL_fake_script() -- NoclipButton.LocalScript 
	local script = Instance.new('LocalScript', NoclipButton)

	-- The noclip script
	
	
	
	local runservice = game:GetService("RunService") -- This is the service for fps i think it handles all processing
	
	local player = game:GetService("Players").LocalPlayer
	
	runservice.Stepped:Connect(function()
		for i,v in pairs(player.Character:GetDescendants()) do
			if v:IsA("BasePart") then
				v.CanCollide = false -- This disables the collision in your character (ALL COLLISIONS are disabled except for standing)
			end
		end
	end)
	
	-- Noclip script is done...
end
coroutine.wrap(OQULOCL_fake_script)()
