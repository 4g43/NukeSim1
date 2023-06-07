getgenv().autocollect = true
getgenv().autofire = true
getgenv().autoopennuke = false
getgenv().autochestdrop = true
getgenv().autoclainnormalchest = true
getgenv().T = true
getgenv().autofire = true
 
spawn(function()  
if game.PlaceId == 11599913094 then
repeat wait() until game:IsLoaded()
    
    spawn(function()
        while true do wait(60) if autoclainnormalchest then
            local args = {[1] = "NormalChest"} 
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.ChestService.RE.Claim:FireServer(unpack(args))    
        end end
    end)
    
    spawn(function()
        if game.Players.LocalPlayer.UserId == 1514743183 then
            getgenv().b = true
                local CFrame1 = CFrame.new(-2485.81152, 1292.12439, 17104.4961, -0.998829186, 0.0421183892, -0.0237987135, 0.0378614366, 0.986809969, 0.15739356, 0.0301139727, 0.156308219, -0.987249076)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame1
                wait(2)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame1
                wait(2)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame1
                wait(2)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame1
            spawn(function()
            while true do wait(60) if b then 
                local args = {[1] = "VipChest"}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.ChestService.RE.Claim:FireServer(unpack(args))    
            end end
            end)
        end
        if game.Players.LocalPlayer.UserId == 4489402726 then
            local CFrame2 = CFrame.new(-2486.29712, 1292.10303, 17360.752, 0.999872744, -0.0107828267, 0.0117595503, 0.0101867933, 0.998716235, 0.0496194921, -0.0122795291, -0.0494933799, 0.99869895)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame2
            wait(2)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame2
            wait(2)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame2
            wait(2)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame2
        end
    end)
    
    spawn(function()
        while true do wait() if autoopennuke then
            local args = {[1] = "anime 9"}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.EggService.RF.Buy3x:InvokeServer(unpack(args))
        end end
    end)
    
    spawn(function() wait(10)
        while T == true do wait(0.001)
        for i,v in pairs(workspace.Buildings["Reaper's Chamber"]:GetChildren()) do
            for _,part in pairs(workspace.Nukes:GetChildren()) do 
                local args = {[1] = {[1] = part.Name},[2] = v.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.Attack:FireServer(unpack(args))
                wait(0.01)
                local args = {[1] = part.Name,[2] = v.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.NukeCollision:FireServer(unpack(args))
				end
            end
        end
    end)
    
    spawn(function() wait(10)
        while X == true do wait(0.001)
        for i,v in pairs(workspace.Buildings["Reaper's Chamber"]:GetChildren()) do
            for _,part in pairs(workspace.Nukes:GetChildren()) do 
		        for _,link in pairs(workspace.Buildings["Reaper's Chamber"]:GetChildren()) do
	            for _,object in pairs(workspace.Nukes:GetChildren()) do 
        	        for _,priv in pairs(workspace.Buildings["Reaper's Chamber"]:GetChildren()) do
                    for _,nuke in pairs(workspace.Nukes:GetChildren()) do 
        		        for _,pig in pairs(workspace.Buildings["Reaper's Chamber"]:GetChildren()) do
                        for _,tix in pairs(workspace.Nukes:GetChildren()) do 
                local args = {[1] = {[1] = part.Name},[2] = v.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.Attack:FireServer(unpack(args))
                wait(0.00000001)
                local args = {[1] = part.Name,[2] = v.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.NukeCollision:FireServer(unpack(args))
                wait(0.00000001)
                local args = {[1] = {[1] = link.Name},[2] = object.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.Attack:FireServer(unpack(args))
                wait(0.00000001)
                local args = {[1] = link.Name,[2] = object.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.NukeCollision:FireServer(unpack(args))
                wait(0.00000001)
                local args = {[1] = {[1] = priv.Name},[2] = nuke.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.Attack:FireServer(unpack(args))
                wait(0.00000001)
                local args = {[1] = priv.Name,[2] = nuke.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.NukeCollision:FireServer(unpack(args))
                wait(0.00000001)
                local args = {[1] = {[1] = pig.Name},[2] = tix.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.Attack:FireServer(unpack(args))
                wait(0.00000001)
                local args = {[1] = pig.Name,[2] = tix.Name}
                game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.NukeService.RE.NukeCollision:FireServer(unpack(args))
                wait(0.00000001)
				end end end end end end end
            end
        end
    end)
    
    spawn(function()
        while autofire == true do wait(5)
            local args = {[1] = true}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.AutoFarmService.RE.ToggleAutoFarm:FireServer(unpack(args))
        end
    end)
    
    spawn(function()    
        while true do wait(0.001) if autocollect then
            for i,v in pairs(game:GetService("Workspace").CurrencyDrops:GetChildren())do
                v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
            end end
        end
    end)
    
    spawn(function()
        while true do wait(10) if autochestdrop then
            local args = {[1] = 1}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 1}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
    
            wait(1)
    
            local args = {[1] = 2}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 2}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
    
            wait(1)
    
            local args = {[1] = 3}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 3}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
    
            wait(1)
    
            local args = {[1] = 4}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 4}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
    
            wait(1)
    
            local args = {[1] = 5}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 5}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
    
            wait(1)
    
            local args = {[1] = 6}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 6}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
    
            wait(1)
    
            local args = {[1] = 7}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 7}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
    
            wait(1)
    
            local args = {[1] = 8}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 8}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
    
            wait(1)
    
            local args = {[1] = 9}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 9}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
            
            wait(1)
            
            local args = {[1] = 10}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimReward:FireServer(unpack(args))
            wait(1)
            local args = {[1] = 10}
            game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.TimeRewardsService.RE.ClaimRewardChest:FireServer(unpack(args))
        end end
    end)
end
end)


spawn (function()
repeat wait() until game:IsLoaded()
local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
wait(1)
vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
print("AFK")
end)

spawn (function()
repeat wait() until game:IsLoaded()
local Dir = game.CoreGui:FindFirstChild("RobloxPromptGui"):FindFirstChild("promptOverlay")
Dir.DescendantAdded:Connect(function(Err)
if Err.Name == "ErrorTitle" then
Err:GetPropertyChangedSignal("Text"):Connect(function()
if Err.Text:sub(0, 12) == "Disconnected" then
if #game.Players:GetPlayers() <= 1 then
game.Players.LocalPlayer:Kick("\nRejoining...")
wait()
game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
else
game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, game.JobId, game.Players.LocalPlayer)
end
print("AntiAFK")
end
end)
end
end)
print("AntiKick")


spawn(function()
local Knit = require(game:GetService("ReplicatedStorage").Packages.knit) -- // get the knit module
local Nuke = Knit.GetController("NukeController") -- // get the nuke controller
local AttackHook do -- // initialize the hook variable so we can return it later in the script
AttackHook = hookfunction(Nuke.Attack, function(Self, Target, ...) -- // hook the attack function
-- // the "Target" is just a bunch of info on the current target as a table
rawset(Target, "nextAttackCritical", true) -- // make "nextAttackCritical" true, and bypass the __newindex metamethod using rawset just in case they decide to make the "Target" readonly
return AttackHook(Self, Target, ...) -- // return & call the function with the newly edited nextAttackCritical value
end)
end
end)

spawn(function()
    while true do wait(2)
    local args = {[1] = "Only1ThisTime"}
    game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.CodeService.RF.VerifyCode:InvokeServer(unpack(args))
    wait(1)
    local args = {[1] = "NormalWheel"}
    game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.WheelService.RF.AttemptSpin:InvokeServer(unpack(args))
    wait(1)
    game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.4.7").knit.Services.DailyRewardService.RF.ClaimReward:InvokeServer()
    end
end)
end)
