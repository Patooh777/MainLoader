local SSID = 5055081323
local AEVO = 10723695195
local GameID = game.PlaceId

if (GameID == SSID) then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Patooh777/Swordman-Simulator/SunsetXHub/README.md"))()
elseif (GameID == AEVO) then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Patooh777/Anime-Evolution-Sim-/SunsetXHub/Source"))()
else
    print("invalid Place")
    game.Players.LocalPlayer:Kick("Ur script dont support this shit ass game")
end
