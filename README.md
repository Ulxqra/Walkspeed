# Walkspeed
Walkspeed script

local player = game:WaitForChild("Players")
local localplayer = player.LocalPlayer
local Character = localplayer

Character.Walkspeed = math.Random(16,22)

# Here is a little extra script

local player = game:WaitForChild("Players")
local localplayer = player.LocalPlayer
local Character = localplayer
local MarketPlaceService = game:GetService("MarketPlaceService")
local ID = 2983293

script.Parent.MouseButton1Down:Connect(function()
MarketPlaceService:PromptPurchase(game, ID)
Character.Walkspeed = math.Random(16,22)
end)
