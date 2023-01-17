local VLib = loadstring(game:HttpGet("https://pastebin.com/raw/Mb49kKTP"))()


		MAINTTL = "Lenda
		HUB" 

local win = VLib:Window("THREE PIECE", Color3.fromRGB(196, 40, 28))

local ss1 = win:Tab("Home")
local ss = win:Tab("MAIN")
local sss = win:Tab("MISC")
local cred = win:Tab("CREDITS")

ss1:Button("Destroy Gui",function()
game.CoreGui["Library"]:Destroy()
end)
