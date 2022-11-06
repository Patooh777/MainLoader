local ASSID = 8950974597
local SSID = 5055081323
local AEVO = 10723695195
local GameID = game.PlaceId

if (GameID == ASSID) then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Patooh777/Script-Run-Anime/main/README.md"))()
elseif (GameID == SSID) then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Patooh777/Swordman-Simulator/SunsetXHub/README.md"))()
elseif (GameID == AEVO) then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ThroySunsetX/SunsetX/main/SunsetXFree"))()
else
    print("invalid Place")
    game.Players.LocalPlayer:Kick("Ur script dont support this shit ass game")
end
