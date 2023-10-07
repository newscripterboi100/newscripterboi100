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
local HelicopterTransformButton = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local SnakeTransformButton = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local OrbitThingyTransform = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Disclaimer = Instance.new("TextLabel")
local UICorner_8 = Instance.new("UICorner")
local Sword = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local ChatBypasser = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local KickPanel = Instance.new("TextLabel")
local UICorner_12 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_14 = Instance.new("UICorner")

--Properties:

PurplesHub.Name = "Purple's Hub"
PurplesHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
PurplesHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainBackground.Name = "Main Background"
MainBackground.Parent = PurplesHub
MainBackground.BackgroundColor3 = Color3.fromRGB(125, 73, 255)
MainBackground.BorderColor3 = Color3.fromRGB(0, 0, 0)
MainBackground.BorderSizePixel = 0
MainBackground.Position = UDim2.new(0.553456604, 0, 0.288658887, 0)
MainBackground.Size = UDim2.new(0, 493, 0, 364)

UICorner.Parent = MainBackground

Name.Name = "Name"
Name.Parent = MainBackground
Name.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
Name.BorderColor3 = Color3.fromRGB(0, 0, 0)
Name.BorderSizePixel = 0
Name.Size = UDim2.new(0, 493, 0, 50)
Name.Font = Enum.Font.GothamBold
Name.Text = "Purple's Hub V0.0.1"
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
Credits.Position = UDim2.new(0.00257065706, 0, 0.850605726, 0)
Credits.Size = UDim2.new(0, 491, 0, 54)
Credits.Font = Enum.Font.GothamBold
Credits.Text = "Made by fgyhakajdna"
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
FlyButton.Position = UDim2.new(0, 0, 0.156459928, 0)
FlyButton.Size = UDim2.new(0, 493, 0, 26)
FlyButton.Font = Enum.Font.GothamBold
FlyButton.Text = "Fly"
FlyButton.TextColor3 = Color3.fromRGB(132, 87, 248)
FlyButton.TextScaled = true
FlyButton.TextSize = 14.000
FlyButton.TextStrokeTransparency = 0.500
FlyButton.TextWrapped = true

UICorner_4.Parent = FlyButton

HelicopterTransformButton.Name = "Helicopter Transform Button"
HelicopterTransformButton.Parent = MainBackground
HelicopterTransformButton.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
HelicopterTransformButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
HelicopterTransformButton.BorderSizePixel = 0
HelicopterTransformButton.Position = UDim2.new(-0.00148613798, 0, 0.254090101, 0)
HelicopterTransformButton.Size = UDim2.new(0, 494, 0, 30)
HelicopterTransformButton.Font = Enum.Font.GothamBold
HelicopterTransformButton.Text = "Transform into a Helicopter"
HelicopterTransformButton.TextColor3 = Color3.fromRGB(132, 87, 248)
HelicopterTransformButton.TextScaled = true
HelicopterTransformButton.TextSize = 14.000
HelicopterTransformButton.TextStrokeTransparency = 0.500
HelicopterTransformButton.TextWrapped = true

UICorner_5.Parent = HelicopterTransformButton

SnakeTransformButton.Name = "Snake Transform Button"
SnakeTransformButton.Parent = MainBackground
SnakeTransformButton.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
SnakeTransformButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
SnakeTransformButton.BorderSizePixel = 0
SnakeTransformButton.Position = UDim2.new(0.00227278587, 0, 0.360050589, 0)
SnakeTransformButton.Size = UDim2.new(0, 493, 0, 27)
SnakeTransformButton.Font = Enum.Font.GothamBold
SnakeTransformButton.Text = "Transform into a Snake"
SnakeTransformButton.TextColor3 = Color3.fromRGB(132, 87, 248)
SnakeTransformButton.TextScaled = true
SnakeTransformButton.TextSize = 14.000
SnakeTransformButton.TextStrokeTransparency = 0.500
SnakeTransformButton.TextWrapped = true

UICorner_6.Parent = SnakeTransformButton

OrbitThingyTransform.Name = "OrbitThingy Transform"
OrbitThingyTransform.Parent = MainBackground
OrbitThingyTransform.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
OrbitThingyTransform.BorderColor3 = Color3.fromRGB(0, 0, 0)
OrbitThingyTransform.BorderSizePixel = 0
OrbitThingyTransform.Position = UDim2.new(-0.00178400928, 0, 0.458109766, 0)
OrbitThingyTransform.Size = UDim2.new(0, 495, 0, 29)
OrbitThingyTransform.Font = Enum.Font.GothamBold
OrbitThingyTransform.Text = "Transform into a Orbit"
OrbitThingyTransform.TextColor3 = Color3.fromRGB(132, 87, 248)
OrbitThingyTransform.TextScaled = true
OrbitThingyTransform.TextSize = 14.000
OrbitThingyTransform.TextStrokeTransparency = 0.500
OrbitThingyTransform.TextWrapped = true

UICorner_7.Parent = OrbitThingyTransform

Disclaimer.Name = "Disclaimer"
Disclaimer.Parent = MainBackground
Disclaimer.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
Disclaimer.BackgroundTransparency = 1.000
Disclaimer.BorderColor3 = Color3.fromRGB(0, 0, 0)
Disclaimer.BorderSizePixel = 0
Disclaimer.Position = UDim2.new(-0.00148613798, 0, 0.741799831, 0)
Disclaimer.Size = UDim2.new(0, 491, 0, 39)
Disclaimer.Font = Enum.Font.GothamBold
Disclaimer.Text = "DISCLAIMER: Alot of those buttons dont work and wont be fixed, Also use a alternative account."
Disclaimer.TextColor3 = Color3.fromRGB(132, 87, 248)
Disclaimer.TextScaled = true
Disclaimer.TextSize = 14.000
Disclaimer.TextStrokeTransparency = 0.500
Disclaimer.TextWrapped = true

UICorner_8.Parent = Disclaimer

Sword.Name = "Sword"
Sword.Parent = MainBackground
Sword.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
Sword.BorderColor3 = Color3.fromRGB(0, 0, 0)
Sword.BorderSizePixel = 0
Sword.Position = UDim2.new(-0.00178400928, 0, 0.559758127, 0)
Sword.Size = UDim2.new(0, 493, 0, 28)
Sword.Font = Enum.Font.GothamBold
Sword.Text = "Sword"
Sword.TextColor3 = Color3.fromRGB(132, 87, 248)
Sword.TextScaled = true
Sword.TextSize = 14.000
Sword.TextStrokeTransparency = 0.500
Sword.TextWrapped = true

UICorner_9.Parent = Sword

ChatBypasser.Name = "Chat Bypasser"
ChatBypasser.Parent = MainBackground
ChatBypasser.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
ChatBypasser.BorderColor3 = Color3.fromRGB(0, 0, 0)
ChatBypasser.BorderSizePixel = 0
ChatBypasser.Position = UDim2.new(0.00024438824, 0, 0.664153695, 0)
ChatBypasser.Size = UDim2.new(0, 493, 0, 28)
ChatBypasser.Font = Enum.Font.GothamBold
ChatBypasser.Text = "Chat Bypasser"
ChatBypasser.TextColor3 = Color3.fromRGB(132, 87, 248)
ChatBypasser.TextScaled = true
ChatBypasser.TextSize = 14.000
ChatBypasser.TextStrokeTransparency = 0.500
ChatBypasser.TextWrapped = true

UICorner_10.Parent = ChatBypasser

Frame.Parent = MainBackground
Frame.BackgroundColor3 = Color3.fromRGB(125, 73, 255)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(-0.419878304, 0, 0, 0)
Frame.Size = UDim2.new(0, 208, 0, 231)

UICorner_11.Parent = Frame

KickPanel.Name = "Kick Panel"
KickPanel.Parent = Frame
KickPanel.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
KickPanel.BorderColor3 = Color3.fromRGB(0, 0, 0)
KickPanel.BorderSizePixel = 0
KickPanel.Position = UDim2.new(-0.0016092154, 0, 0, 0)
KickPanel.Size = UDim2.new(1, 0, 0.151515156, 0)
KickPanel.Font = Enum.Font.GothamBold
KickPanel.Text = "Kick Panel"
KickPanel.TextColor3 = Color3.fromRGB(132, 87, 248)
KickPanel.TextScaled = true
KickPanel.TextSize = 14.000
KickPanel.TextStrokeTransparency = 0.500
KickPanel.TextWrapped = true

UICorner_12.Parent = KickPanel

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0192307699, 0, 0.718614697, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.GothamBold
TextButton.Text = "Kick"
TextButton.TextColor3 = Color3.fromRGB(132, 87, 248)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextStrokeTransparency = 0.500
TextButton.TextWrapped = true

UICorner_13.Parent = TextButton

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.014423077, 0, 0.246542931, 0)
TextBox.Size = UDim2.new(0, 200, 0, 92)
TextBox.Font = Enum.Font.GothamBold
TextBox.PlaceholderColor3 = Color3.fromRGB(137, 98, 209)
TextBox.PlaceholderText = "Target's Username"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(132, 87, 248)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextStrokeTransparency = 0.500
TextBox.TextWrapped = true

UICorner_14.Parent = TextBox

-- Scripts:

local function NXSHBHC_fake_script() -- FlyButton.LocalScript 
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
coroutine.wrap(NXSHBHC_fake_script)()
local function XMQCMOT_fake_script() -- MainBackground.LocalScript 
	local script = Instance.new('LocalScript', MainBackground)

	-- to make the script draggable, we can set the parent of script is draggable
	script.Parent.Draggable = true
	script.Parent.Active = true
end
coroutine.wrap(XMQCMOT_fake_script)()
local function ZTUNO_fake_script() -- HelicopterTransformButton.LocalScript 
	local script = Instance.new('LocalScript', HelicopterTransformButton)

	if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R6 then
		spawn(function()
			local speaker = game.Players.LocalPlayer
			local Anim = Instance.new("Animation")
			Anim.AnimationId = "rbxassetid://27432686"
			local bruh = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
			bruh:Play()
			bruh:AdjustSpeed(0)
			speaker.Character.Animate.Disabled = true
			local hi = Instance.new("Sound")
			hi.Name = "Sound"
			hi.SoundId = "http://www.roblox.com/asset/?id=165113352"
			hi.Volume = 2
			hi.Looped = true
			hi.archivable = false
			hi.Parent = game.Workspace
			hi:Play()
	
			local spinSpeed = 40
			local Spin = Instance.new("BodyAngularVelocity")
			Spin.Name = "Spinning"
			Spin.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
	
		end)
	else
		spawn(function()
			local speaker = game.Players.LocalPlayer
			local Anim = Instance.new("Animation")
			Anim.AnimationId = "rbxassetid://507776043"
			local bruh = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
			bruh:Play()
			bruh:AdjustSpeed(0)
			speaker.Character.Animate.Disabled = true
			local hi = Instance.new("Sound")
			hi.Name = "Sound"
			hi.SoundId = "http://www.roblox.com/asset/?id=165113352"
			hi.Volume = 2
			hi.Looped = true
			hi.archivable = false
			hi.Parent = game.Workspace
			hi:Play()
	
			local spinSpeed = 40
			local Spin = Instance.new("BodyAngularVelocity")
			Spin.Name = "Spinning"
			Spin.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
	
	
		end)    
	end
	local Mouse = game:GetService("Players").LocalPlayer:GetMouse()
	local u = game.Players.LocalPlayer
	local urchar = u.Character
	
	task.spawn(function()
	
	
		qUp = Mouse.KeyUp:Connect(function(KEY)
			if KEY == 'q' then
				urchar.Humanoid.HipHeight = urchar.Humanoid.HipHeight - 3
			end
		end)
		eUp = Mouse.KeyUp:Connect(function(KEY)
			if KEY == 'e' then
				urchar.Humanoid.HipHeight = urchar.Humanoid.HipHeight + 3
			end
		end)
	
	
	end)
	
end
coroutine.wrap(ZTUNO_fake_script)()
local function DNXZHV_fake_script() -- SnakeTransformButton.LocalScript 
	local script = Instance.new('LocalScript', SnakeTransformButton)

	LocalPlayer = game:GetService("Players").LocalPlayer
	RunService = game:GetService("RunService")
	
	Snake = Instance.new("Model", workspace)
	Snake.Name = "Snake"
	
	SnakeControl = Instance.new("Model", Snake)
	SnakeControl.Name = "SnakeControl"
	
	SegmentCount = 9
	LastSegment = nil
	for i = 1, SegmentCount, 1 do
		local Segment = Instance.new("Part", Snake)
		Segment.Name = "Segment"..tostring(i)
		Segment.Size = Vector3.new(1,1,1.8)
		Segment.Transparency = 1
		Segment.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame
	
		local FrontAttachment = Instance.new("Attachment", Segment)
		FrontAttachment.Name = "FrontAttachment"
		FrontAttachment.CFrame = CFrame.new(0,0,.9)
	
		local BackAttachment = Instance.new("Attachment", Segment)
		BackAttachment.Name = "BackAttachment"
		BackAttachment.CFrame = CFrame.new(0,0,-.9)
	
		local BallSocket = Instance.new("BallSocketConstraint", Segment)
		BallSocket.Name = "BallSocket"
		BallSocket.Attachment1 = FrontAttachment
	
		if LastSegment then
			BallSocket.Attachment0 = LastSegment.BackAttachment
		end
	
		LastSegment = Segment
	end
	
	Head = Instance.new("Part", SnakeControl)
	Head.Name = "HumanoidRootPart"
	Head.Size = Vector3.new(1,1,1)
	Head.CustomPhysicalProperties = PhysicalProperties.new(100,0.5,1,0.3,1)
	Head.Transparency = 1
	Head.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame
	
	Neck = Instance.new("Attachment", Head)
	Neck.CFrame = CFrame.new(0,0,.5)
	
	Snake.Segment1.BallSocket.Attachment0 = Neck
	
	Humanoid = Instance.new("Humanoid", SnakeControl)
	Humanoid.HipHeight = .25
	
	--Move Accessorys
	Character = nil
	
	function Loop(Number,Code)
		for i = 1, Number, 1 do
			Code()
		end
	end
	
	TailHats = {}
	
	function ResetCharacter()
		if LocalPlayer.Character == SnakeControl then return end
		table.clear(TailHats)
		Character = LocalPlayer.Character
		task.wait()
		LocalPlayer.Character = SnakeControl
		Character:WaitForChild("HumanoidRootPart").CFrame = Head.CFrame + Vector3.new(7,0,0)
		Loop(17, function()
			task.wait()
		end)
	
		Character:BreakJoints()
	
		while true do
			local Count = 0
			for i,v in pairs(Character:GetChildren()) do
				if v:IsA("Accessory") then
					Count += 1
				end
			end
			if Count == 10 then break end
			task.wait()
		end
	
		for i,v in pairs(Character:GetDescendants()) do
			if v.Name == "International Fedora" or v.Name == "InternationalFedora" or v.Name == "MeshPartAccessory" then
				table.insert(TailHats, v.Handle)
			end
		end
	end
	
	RunService.Heartbeat:Connect(function()
		if Character == nil or not Character:FindFirstChild("MediHood") or #TailHats ~= 9 then return end
		Character.MediHood.Handle.CFrame = Head.CFrame + Vector3.new(0,math.sin(tick()*30)*.01)
		Character.MediHood.Handle.Velocity = Vector3.new(0,25.1)
		for i, v in pairs(TailHats) do
			v.CFrame = Snake["Segment"..tostring(i)].CFrame + Vector3.new(0,math.sin(tick()*30)*.01)
			v.Velocity = Vector3.new(0,25.1)
		end
	end)
	ResetCharacter()
	
	LocalPlayer.CharacterAdded:Connect(ResetCharacter)
	
	Camera = workspace.CurrentCamera
	
	RememberCFrame = CFrame.new()
	RunService.RenderStepped:Connect(function()
		if Camera.CameraSubject ~= Head then
			Camera.CameraSubject = Head
			Camera.CFrame = RememberCFrame
		end
		RememberCFrame = Camera.CFrame
	end)
end
coroutine.wrap(DNXZHV_fake_script)()
local function QJSGV_fake_script() -- OrbitThingyTransform.LocalScript 
	local script = Instance.new('LocalScript', OrbitThingyTransform)

	radius = 5
	speed = 2
	
	lp = game:GetService("Players").LocalPlayer
	char = lp.Character
	hrp = char.HumanoidRootPart
	
	char.Parent = nil
	hrp2 = hrp:Clone()
	hrp2.Parent = char
	hrp.Parent = hrp2
	char.Parent = workspace
	hrp2.RootJoint.Enabled = false
	
	char.Head.CanCollide = false
	
	function Move(part, cframe)
		part.Velocity = Vector3.new(0,0,0)
		local tween = game:GetService("TweenService"):Create(part, TweenInfo.new(0), {CFrame = cframe})
		tween:Play()
	end
	
	while task.wait() do
		Move(hrp, hrp2.CFrame + hrp2.CFrame.LookVector * (math.sin(tick()*speed) * radius) + hrp2.CFrame.RightVector * (math.cos(tick()*speed) * radius))
	end
end
coroutine.wrap(QJSGV_fake_script)()
local function XKKAJYM_fake_script() -- Sword.LocalScript 
	local script = Instance.new('LocalScript', Sword)

	radius = 5
	speed = 2
	
	lp = game:GetService("Players").LocalPlayer
	char = lp.Character
	hrp = char.HumanoidRootPart
	
	char.Parent = nil
	hrp2 = hrp:Clone()
	hrp2.Parent = char
	hrp.Parent = hrp2
	char.Parent = workspace
	hrp2.RootJoint.Enabled = false
	
	char.Head.CanCollide = false
	
	function Move(part, cframe)
		part.Velocity = Vector3.new(0,0,0)
		local tween = game:GetService("TweenService"):Create(part, TweenInfo.new(0), {CFrame = cframe})
		tween:Play()
	end
	
	while task.wait() do
		Move(hrp, hrp2.CFrame + hrp2.CFrame.LookVector * (math.sin(tick()*speed) * radius) + hrp2.CFrame.RightVector * (math.cos(tick()*speed) * radius))
	end
end
coroutine.wrap(XKKAJYM_fake_script)()
local function FPOQGVV_fake_script() -- ChatBypasser.LocalScript 
	local script = Instance.new('LocalScript', ChatBypasser)

	loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/ChatBypasser-AZY/main/Chat%20Bypass%20-%20ChatSplitter(Source).lua"))()
end
coroutine.wrap(FPOQGVV_fake_script)()
local function YNREWJ_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local buttonPart = script.Parent
	local clickDetector = buttonPart:FindFirstChild("ClickDetector")
	
	-- Function to kick a player
	local function kickPlayer(player)
		-- Check if the player is in the game
		if player and player:IsA("Player") then
			-- Kick the player
			player:Kick("You have been kicked from the game.")
		end
	end
	
	-- Connect the function to the button click event
	clickDetector.MouseClick:Connect(function(player)
		kickPlayer(player)
	end)
end
coroutine.wrap(YNREWJ_fake_script)()
