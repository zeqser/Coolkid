--// Coolkid Mode Activated \--

local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer
local StarterGui = game:GetService("StarterGui")

-- Cool UI Message
StarterGui:SetCore("SendNotification", {
    Title = "Coolkid Mode",
    Text = "You're now the coolest in the server.",
    Duration = 5
})

-- Epic Chat Entrance
wait(2)
game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Yo. Coolkid just joined the server. Try to keep up.", "All")

-- Cool Walkspeed + Jump
LocalPlayer.Character.Humanoid.WalkSpeed = 50
LocalPlayer.Character.Humanoid.JumpPower = 100

-- Drippy Sparkles
local sparkles = Instance.new("Sparkles", LocalPlayer.Character.Head)
sparkles.SparkleColor = Color3.fromRGB(255, 255, 0)

-- Looping Drip Sound
local drip = Instance.new("Sound", LocalPlayer.Character.Head)
drip.SoundId = "rbxassetid://9118823102" -- Drip sound
drip.Looped = true
drip.Volume = 2
drip:Play()

-- Extra Flex
while true do
    wait(5)
    game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Too fast. Too fresh. Too cool.", "All")
end
