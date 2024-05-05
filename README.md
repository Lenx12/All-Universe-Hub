local PabloLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/BatuKvi123/PabloLibV3/main/PabloLibV3"))()
local window = PabloLib:Create(
"All universe hub | blade slayer", -- Name here.
"Enabled", -- 
"p" -- 
)

-- Tabs

local tab1 = window:CreateTab("Main")
local tab2 = window:CreateTab("Teleport")

-- buttons

tab1:CreateButton("Lvl up Gem", function()
loadstring(game:HttpGet("https://pastebin.com/raw/rA0ehqfV"))()
end)
tab2:CreateButton("Seaside villa world 2", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Takatka/Teleport-/main/W2"))()
end)
