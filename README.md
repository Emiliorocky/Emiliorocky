
loadstring(game:HttpGet(“https://raw.githubusercontent.com/StormSKz12/StirkeHub1/main/Gameincluded”))()
loadstring(game:HttpGet”https://raw.githubusercontent.com/HULKUexe/Free—Script/main/3GAME”)()
(getgenv()).Config = {
 [“FastAttack”] = true,
 [“ClickAttack”] = true
}coroutine.wrap(function()
local StopCamera = require(game.ReplicatedStorage.Util.CameraShaker)StopCamera:Stop()
    for v,v in pairs(getreg()) do
        if typeof(v) == “function” and getfenv(v).script == game:GetService(“Players”).LocalPlayer.PlayerScripts.CombatFramework then
             for v,v in pairs(debug.getupvalues(v)) do
                if typeof(v) == “table” then
                    spawn(function()
                        game:GetService(“RunService”).RenderStepped:Connect(function()
                            if getgenv().Config[‘FastAttack’] then
                                 pcall(function()
                                     v.activeController.timeToNextAttack = -(math.huge^math.huge^math.huge)
                                     v.activeController.attacking = false
                                     v.activeController.increment = 4
                                     v.activeController.blocking = false
                                     v.activeController.hitboxMagnitude = 150
                            v.activeController.humanoid.AutoRotate = true
                              v.activeController.focusStart = 0
                              v.activeController.currentAttackTrack = 0
                                     sethiddenproperty(game:GetService(“Players”).LocalPlayer, “SimulationRaxNerous”, math.huge)
                                 end)
                             end
                         end)
                    end)
                end
            end
        end
    end
end)();
spawn(function()
    game:GetService(“RunService”).RenderStepped:Connect(function()
        if getgenv().Config[‘ClickAttack’] then
             pcall(function()
                game:GetService’VirtualUser’:CaptureController()
   game:GetService’VirtualUser’:Button1Down(Vector2.new(0,1,0,1))
            end)
        end
    end)
end)
loadstring(game:HttpGet(‘https://raw.githubusercontent.com/SHAREHACK/script/main/fusion1’))()
loadstring(game:HttpGet(“https://raw.githubusercontent.com/spectrumok/RetroHub/main/Main.lua”))()
loadstring(game:HttpGet(“https://raw.githubusercontent.com/spectrumok/RetroHub/main/Main.lua”))()
loadstring(game:HttpGet(“https://rasputin-bf.glitch.me/bloxfruits.lua”))()
loadstring(game:HttpGet(“https://reaperking.xyz/bloxfruits”, true))()
getgenv().setting = {
Fov = 50,
Color = Color3.fromRGB(191, 255, 209),
LockPlayers = false,
LockPlayersBind = Enum.KeyCode.L,
resetPlayersBind = Enum.KeyCode.P,
}
loadstring(game:HttpGet(‘https://raw.githubusercontent.com/Besty191/MAZI-API/main/Blox_Fruit_Silent_Aim’))()
getgenv().setting = {
Fov = 50,
Color = Color3.fromRGB(191, 255, 209),
LockPlayers = false,
LockPlayersBind = Enum.KeyCode.L,
resetPlayersBind = Enum.KeyCode.P,
}
loadstring(game:HttpGet(‘https://raw.githubusercontent.com/Besty191/MAZI-API/main/Blox_Fruit_Silent_Aim’))()
loadstring(game:HttpGet((“https://raw.githubusercontent.com/koonpeatch/PeatEX/master/BKHAX/BloxFruits”),true))()
loadstring(game:HttpGet(“https://gist.githubusercontent.com/noob1ee1/5607f21c9874e3724f13a88109916896/raw/5a44dc988657f4eb23294b60aa64b874bc13253b”))()
loadstring(game:HttpGet(“http://skyhubking.xyz/script/free_script/main%20game.lua”))()
loadstring(game:HttpGet(“https://raw.githubusercontent.com/spectrumok/RetroHub/main/Main.lua”))()
