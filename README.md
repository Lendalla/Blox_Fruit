local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()

local win = DiscordLib:Window("Lenda Hub")

local serv = win:Server("Preview", "")

local tgls = serv:Channel("Toggles")

tgls:Toggle("Fast Attack",false, function()
local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
Camera:Stop()
coroutine.wrap(function()
    local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
Camera:Stop()
coroutine.wrap(function()
    game:GetService("RunService").Stepped:Connect(function()
        if getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack then
        getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack = 0
        getupvalues(CombatFramework)[2]['activeController'].hitboxMagnitude = 30
        getupvalues(CombatFramework)[2]['activeController']:attack()
        end
        end)
end)()
local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
Camera:Stop()
coroutine.wrap(function()
    game:GetService("RunService").Stepped:Connect(function()
        if getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack then
        getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack = 0
        getupvalues(CombatFramework)[2]['activeController'].hitboxMagnitude = 30
        getupvalues(CombatFramework)[2]['activeController']:attack()
        end
        end)
end)()
local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
Camera:Stop()
coroutine.wrap(function()
    game:GetService("RunService").Stepped:Connect(function()
        if getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack then
        getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack = 0
        getupvalues(CombatFramework)[2]['activeController'].hitboxMagnitude = 30
        getupvalues(CombatFramework)[2]['activeController']:attack()
        end
        end)
end)()

end)
