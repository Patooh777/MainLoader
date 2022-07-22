local ASSID = 8950974597
local SSID = 5055081323
local GameID = game.PlaceId

if (GameID == ASSID) then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Patooh777/Script-Run-Anime/main/README.md"))()
elseif (GameID == SSID) then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Patooh777/Swordman-Simulator/SunsetXHub/README.md"))()
else
    print("invalid Place")
    game.Players.LocalPlayer:Kick("Ur script dont support this shit ass game")
end
