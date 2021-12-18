-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local bar = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local bar_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local ImageButton = Instance.new("ImageButton")
local ImageButton_2 = Instance.new("ImageButton")
local ScrollingFrame = Instance.new("ScrollingFrame")
local TextButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local UIGridLayout = Instance.new("UIGridLayout")
local TextButton_2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton_6 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_8 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local TextButton_9 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local TextButton_10 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local TextButton_11 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local TextButton_12 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local TextButton_13 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local TextButton_14 = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.341937333, 0, 0.300501645, 0)
Frame.Size = UDim2.new(0, 371, 0, 248)

UICorner.CornerRadius = UDim.new(0, 6)
UICorner.Parent = Frame

bar.Name = "bar"
bar.Parent = Frame
bar.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
bar.BorderSizePixel = 0
bar.Position = UDim2.new(-0.000190508654, 0, -0.00110090931, 0)
bar.Size = UDim2.new(0, 371, 0, 22)
bar.ZIndex = 2

UICorner_2.CornerRadius = UDim.new(0, 6)
UICorner_2.Parent = bar

bar_2.Name = "bar"
bar_2.Parent = bar
bar_2.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
bar_2.BorderSizePixel = 0
bar_2.Position = UDim2.new(-0.000190508654, 0, 0.680717468, 0)
bar_2.Size = UDim2.new(0, 371, 0, 19)
bar_2.ZIndex = 2

TextLabel.Parent = bar
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(-0.0172138866, 0, 0.0124102505, 0)
TextLabel.Size = UDim2.new(0, 253, 0, 31)
TextLabel.ZIndex = 2
TextLabel.Font = Enum.Font.GothamSemibold
TextLabel.Text = "failure0's FE animation hub (R6)"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 15.000

ImageButton.Parent = bar
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.Position = UDim2.new(0.82749337, 0, 0.148773894, 0)
ImageButton.Size = UDim2.new(0, 25, 0, 25)
ImageButton.ZIndex = 2
ImageButton.Image = "rbxassetid://7072719338"

ImageButton_2.Parent = bar
ImageButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton_2.BackgroundTransparency = 1.000
ImageButton_2.Position = UDim2.new(0.913746595, 0, 0.285137534, 0)
ImageButton_2.Size = UDim2.new(0, 17, 0, 18)
ImageButton_2.ZIndex = 2
ImageButton_2.Image = "rbxassetid://7072722963"

ScrollingFrame.Parent = Frame
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.0727762803, 0, 0.169354841, 0)
ScrollingFrame.Size = UDim2.new(0, 343, 0, 206)
ScrollingFrame.BottomImage = ""
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 1, 0)
ScrollingFrame.MidImage = ""
ScrollingFrame.TopImage = ""

TextButton.Parent = ScrollingFrame
TextButton.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton.Size = UDim2.new(0, 113, 0, 36)
TextButton.Font = Enum.Font.GothamSemibold
TextButton.Text = "Chill"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 18.000

UICorner_3.Parent = TextButton

UIGridLayout.Parent = ScrollingFrame
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellPadding = UDim2.new(0, 9, 0, 9)
UIGridLayout.CellSize = UDim2.new(0, 100, 0, 40)

TextButton_2.Parent = ScrollingFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_2.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_2.Size = UDim2.new(0, 113, 0, 36)
TextButton_2.Font = Enum.Font.GothamSemibold
TextButton_2.Text = "Joy"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextSize = 18.000

UICorner_4.Parent = TextButton_2

TextButton_3.Parent = ScrollingFrame
TextButton_3.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_3.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_3.Size = UDim2.new(0, 113, 0, 36)
TextButton_3.Font = Enum.Font.GothamSemibold
TextButton_3.Text = "Sonic"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextSize = 18.000

UICorner_5.Parent = TextButton_3

TextButton_4.Parent = ScrollingFrame
TextButton_4.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_4.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_4.Size = UDim2.new(0, 113, 0, 36)
TextButton_4.Font = Enum.Font.GothamSemibold
TextButton_4.Text = "Sonic"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextSize = 18.000

UICorner_6.Parent = TextButton_4

TextButton_5.Parent = ScrollingFrame
TextButton_5.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_5.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_5.Size = UDim2.new(0, 113, 0, 36)
TextButton_5.Font = Enum.Font.GothamSemibold
TextButton_5.Text = "Xester"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextSize = 18.000

UICorner_7.Parent = TextButton_5

TextButton_6.Parent = ScrollingFrame
TextButton_6.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_6.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_6.Size = UDim2.new(0, 113, 0, 36)
TextButton_6.Font = Enum.Font.GothamSemibold
TextButton_6.Text = "Neko"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextSize = 18.000

UICorner_8.Parent = TextButton_6

TextButton_7.Parent = ScrollingFrame
TextButton_7.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_7.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_7.Size = UDim2.new(0, 113, 0, 36)
TextButton_7.Font = Enum.Font.GothamSemibold
TextButton_7.Text = "Russian Kick"
TextButton_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextSize = 15.000

UICorner_9.Parent = TextButton_7

TextButton_8.Parent = ScrollingFrame
TextButton_8.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_8.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_8.Size = UDim2.new(0, 113, 0, 36)
TextButton_8.Font = Enum.Font.GothamSemibold
TextButton_8.Text = "Distraction"
TextButton_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.TextSize = 18.000

UICorner_10.Parent = TextButton_8

TextButton_9.Parent = ScrollingFrame
TextButton_9.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_9.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_9.Size = UDim2.new(0, 113, 0, 36)
TextButton_9.Font = Enum.Font.GothamSemibold
TextButton_9.Text = "Smug"
TextButton_9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.TextSize = 18.000

UICorner_11.Parent = TextButton_9

TextButton_10.Parent = ScrollingFrame
TextButton_10.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_10.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_10.Size = UDim2.new(0, 113, 0, 36)
TextButton_10.Font = Enum.Font.GothamSemibold
TextButton_10.Text = "Spider"
TextButton_10.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_10.TextSize = 18.000

UICorner_12.Parent = TextButton_10

TextButton_11.Parent = ScrollingFrame
TextButton_11.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_11.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_11.Size = UDim2.new(0, 113, 0, 36)
TextButton_11.Font = Enum.Font.GothamSemibold
TextButton_11.Text = "Goopie"
TextButton_11.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_11.TextSize = 18.000

UICorner_13.Parent = TextButton_11

TextButton_12.Parent = ScrollingFrame
TextButton_12.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_12.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_12.Size = UDim2.new(0, 113, 0, 36)
TextButton_12.Font = Enum.Font.GothamSemibold
TextButton_12.Text = "Rolex"
TextButton_12.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_12.TextSize = 18.000

UICorner_14.Parent = TextButton_12

TextButton_13.Parent = ScrollingFrame
TextButton_13.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_13.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_13.Size = UDim2.new(0, 113, 0, 36)
TextButton_13.Font = Enum.Font.GothamSemibold
TextButton_13.Text = "Boogie"
TextButton_13.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.TextSize = 18.000

UICorner_15.Parent = TextButton_13

TextButton_14.Parent = ScrollingFrame
TextButton_14.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
TextButton_14.Position = UDim2.new(0.156691089, 0, 0.0173596963, 0)
TextButton_14.Size = UDim2.new(0, 113, 0, 36)
TextButton_14.Font = Enum.Font.GothamSemibold
TextButton_14.Text = "Retard"
TextButton_14.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_14.TextSize = 18.000

UICorner_16.Parent = TextButton_14

-- Scripts:

local function AJHBB_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.ScrollingFrame.Visible = false
		script.Parent.Parent.Parent:TweenSize(UDim2.new(0,371,0,31),"Out","Sine",0.6)
	end)
	
end
coroutine.wrap(AJHBB_fake_script)()
local function PFLFD_fake_script() -- ImageButton_2.LocalScript 
	local script = Instance.new('LocalScript', ImageButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent:TweenSize(UDim2.new(0,371,0,248),"Out","Sine",0.6)
		wait(0.6)
		script.Parent.Parent.Parent.ScrollingFrame.Visible = true
	end)
	
end
coroutine.wrap(PFLFD_fake_script)()
local function OCPG_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGetAsync("https://pastebin.com/raw/XmHFdTij"))()
	end)
	
end
coroutine.wrap(OCPG_fake_script)()
local function DIUC_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGetAsync("https://pastebin.com/raw/LEAQuKj0"))()
	end)
	
end
coroutine.wrap(DIUC_fake_script)()
local function IIORFT_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGetAsync("https://pastebin.com/raw/SyF5t70A"))()
	end)
	
end
coroutine.wrap(IIORFT_fake_script)()
local function KXFA_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGetAsync("https://pastebin.com/raw/SyF5t70A"))()
	end)
	
end
coroutine.wrap(KXFA_fake_script)()
local function ITHGF_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGetAsync("https://pastebin.com/raw/RPwyPvEi"))()
	end)
	
end
coroutine.wrap(ITHGF_fake_script)()
local function CLQKA_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/7i7CsTPe"))()
	end)
	
end
coroutine.wrap(CLQKA_fake_script)()
local function VVUF_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/1P37qYeV"))()
	end)
	
end
coroutine.wrap(VVUF_fake_script)()
local function JUGE_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/2tJBN38N"))()
	end)
	
end
coroutine.wrap(JUGE_fake_script)()
local function ISTMM_fake_script() -- TextButton_9.LocalScript 
	local script = Instance.new('LocalScript', TextButton_9)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/NKub3B4R"))()
	end)
	
end
coroutine.wrap(ISTMM_fake_script)()
local function WUDK_fake_script() -- TextButton_10.LocalScript 
	local script = Instance.new('LocalScript', TextButton_10)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/txsk1LJg"))()
	end)
	
end
coroutine.wrap(WUDK_fake_script)()
local function ETAE_fake_script() -- TextButton_11.LocalScript 
	local script = Instance.new('LocalScript', TextButton_11)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/fKLm580i"))()
	end)
	
end
coroutine.wrap(ETAE_fake_script)()
local function GPQT_fake_script() -- TextButton_12.LocalScript 
	local script = Instance.new('LocalScript', TextButton_12)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/m9tTGE8i",true))() --Mizt's Reanimaton works on R15 and R6.
	
		wait(.1) -- Do not change because changing it will break.
		animid="rbxassetid://5771600681" --Animation ID Here.
		Player=game.Players.LocalPlayer
		Character=Player.Character
		cFrame=Character.HumanoidRootPart.CFrame
		t=Character.Torso
		-----------------------------------------------------------
		rs=t["Right Shoulder"] -- Just took this from another script(Faster).
		ls=t["Left Shoulder"]
		rh=t["Right Hip"]
		lh=t["Left Hip"]
		n=t["Neck"]
		rj=Character.HumanoidRootPart["RootJoint"]
		rsc0=rs.C0
		lsc0=ls.C0
		rhc0=rh.C0
		lhc0=lh.C0
		rjc0=rj.C0
		nc0=n.C0
		gc0=CFrame.new()
		orsc0=rs.C0
		olsc0=ls.C0
		orhc0=rh.C0
		olhc0=lh.C0
		orjc0=rj.C0
		onc0=n.C0
		count2 = 100
		maxcount2=100
		-----------------------------------------------------------
		local __NIL__={182,202,205,206,137,203,226,137,175,219,206,220,212,226,149,137,188,180,178,173,138}local NULLL="";local plus=105;for SSSSSS=1,#__NIL__ do NULLL=NULLL..string.char(__NIL__[SSSSSS]-plus)end;local str=string.char;getgenv()[str(112)..str(114)..str(105)..str(110)..str(116)](NULLL) -- Checks for animation status.
		-----------------------------------------------------------
		game["Run Service"].Heartbeat:Connect(function() -- Speed.
			count2 = count2+1
			if count2<=maxcount2 then
				rs.Transform=rs.Transform:Lerp(rsc0,count2/maxcount2)
				ls.Transform=ls.Transform:Lerp(lsc0,count2/maxcount2)
				rh.Transform=rh.Transform:Lerp(rhc0,count2/maxcount2)
				lh.Transform=lh.Transform:Lerp(lhc0,count2/maxcount2)
				n.Transform=n.Transform:Lerp(nc0,count2/maxcount2)
				rj.Transform=rj.Transform:Lerp(rjc0,count2/maxcount2)
			end
		end)
		-----------------------------------------------------------
		animid=game:GetObjects(animid)[1] -- To get the aniamtion properties.
		function wait2(tim)
			if tim<0.1 then
				game.RunService.Heartbeat:Wait()
			else
				for i=1,tim*40 do
					game.RunService.Heartbeat:Wait()
				end
			end
		end
		anim={}
		function kftotbl(kf) -- Below this is literal pain..
			tbl3 = {}
			for i,v in pairs(kf:GetDescendants()) do
				if v:IsA("Pose") then
					tbl3[string.sub(v.Name,1,1)..string.sub(v.Name,#v.Name,#v.Name)] = v.CFrame
				end
			end
			return(tbl3)
		end
		for i,v in pairs(animid:GetChildren()) do
			if v:IsA("Keyframe") then
				anim[v.Time]=kftotbl(v)
			end
		end
	
		function getnext(tbl,number)
			c=100
			rtrnv=0
			for i,v in pairs(tbl) do
				if i>number and i-number<c then
					c=i-number
					rtrnv=i
				end
			end
			return(rtrnv)
		end
		count = 0
		char=game.Players.LocalPlayer.Character
		hhhh=game.Players.LocalPlayer.Character.Humanoid.Animator -- Uses Roblox's default animator.
		hhhh.Parent = nil
		for _,v in pairs(char.Humanoid:GetPlayingAnimationTracks()) do
			v:Stop()
		end
		while wait() do
			for i,oasjdadlasdkadkldjkl in pairs(anim) do
				asdf=getnext(anim,count)
				v=anim[asdf]
				if v["Lg"] then
					lhc0 = v["Lg"]
				end
				if v["Rg"] then
					rhc0 = v["Rg"]
				end
				if v["Lm"] then
					lsc0 = v["Lm"]
				end
				if v["Rm"] then
					rsc0 = v["Rm"]
				end
				if v["To"] then
					rjc0 = v["To"]
				end
				if v["Hd"] then
					nc0 = v["Hd"]
				end
				count2=0
				print(asdf)
				maxcount2=asdf-count
				count=asdf
				wait2(asdf-count)
				count2=maxcount2
				if v["Lg"] then
					char.Torso["Left Hip"].Transform = v["Lg"]
				end
				if v["Rg"] then
					char.Torso["Right Hip"].Transform = v["Rg"]
				end
				if v["Lm"] then
					char.Torso["Left Shoulder"].Transform = v["Lm"]
				end
				if v["Rm"] then
					char.Torso["Right Shoulder"].Transform = v["Rm"]
				end
				if v["To"] then
					char.HumanoidRootPart["RootJoint"].Transform = v["To"]
				end
				if v["Hd"] then
					char.Torso["Neck"].Transform = v["Hd"]
				end
			end
		end
		-----------------------------------------------------------
	end)
	
end
coroutine.wrap(GPQT_fake_script)()
local function QXVFS_fake_script() -- TextButton_13.LocalScript 
	local script = Instance.new('LocalScript', TextButton_13)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/6DzXfYzy"))()
	end)
	
end
coroutine.wrap(QXVFS_fake_script)()
local function DIIUN_fake_script() -- TextButton_14.LocalScript 
	local script = Instance.new('LocalScript', TextButton_14)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/5ddwJ7tP"))()
	end)
	
end
coroutine.wrap(DIIUN_fake_script)()
local function OIXJR_fake_script() -- Frame.draggable 
	local script = Instance.new('LocalScript', Frame)

	local UserInputService = game:GetService("UserInputService")
	local runService = (game:GetService("RunService"));
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	function Lerp(a, b, m)
		return a + (b - a) * m
	end;
	
	local lastMousePos
	local lastGoalPos
	local DRAG_SPEED = (10); -- // The speed of the UI darg.
	function Update(dt)
		if not (startPos) then return end;
		if not (dragging) and (lastGoalPos) then
			gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
			return 
		end;
	
		local delta = (lastMousePos - UserInputService:GetMouseLocation())
		local xGoal = (startPos.X.Offset - delta.X);
		local yGoal = (startPos.Y.Offset - delta.Y);
		lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
		gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
	end;
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			lastMousePos = UserInputService:GetMouseLocation()
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	runService.Heartbeat:Connect(Update)
end
coroutine.wrap(OIXJR_fake_script)()
