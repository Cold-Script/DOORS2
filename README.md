local function notify(text)
local Library =
loadstring(game:HttpGet('https://raw.gothubusercontent.com/mstudio45/LinoriaLib/main/Library.lua'))()
Library:Notify(text)
local Sound = Instance.new("Sound")
Sound.Parent = game.SoundService
Sound.SoundId = "rbxassetid://1409001904"
Sound.Volume = 2.5
Sound.PlayOnRemove = true
Sound:Destroy()
end
notify("[YPoint] : Disabled Giggle ツ⁠ ")
notify("[YPoint] : Disabled GloomPile ツ⁠ ")
notify("[YPoint] : Disabled Figure ツ⁠ ")
for _,v in pairs(workspace.CurrentRooms:GetDescendants()) do
if v.Name == "GiggleCeiling" then
v:Destroy()
elseif v.Name == "GloomPile" then
v:Destroy()
elseif v.Name == "DoorFake" then
v:Destroy()
elseif v.Name == "FigureRig" then
v:Destroy()
elseif v.Name == "TriggerEventCollision" then
v:Destroy()
elseif v.Name == "" then
v:Destroy()
end
end


