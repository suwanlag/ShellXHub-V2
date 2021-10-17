local key = _G.Key
local check = "https://whitelistshellxhub.000webhostapp.com/check.php?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://whitelistshellxhub.000webhostapp.com/script.lua"))()
else
game.Players.LocalPlayer:Kick("ไม่มีคีย์ก็อย่ารันไอโง่")
end
