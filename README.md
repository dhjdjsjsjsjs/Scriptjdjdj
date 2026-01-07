-- CONFIGURE AQUI
local placeId = 109983668079237 -- PlaceId do jogo
local jobId = "fe02a504-390c-4550-be28-d8e32b783c9e" --

-- SCRIPT
local TeleportService = game:GetService("TeleportService")
local Players = game:GetService("Players")

local player = Players.LocalPlayer

TeleportService:TeleportToPlaceInstance(placeId, jobId, player)
