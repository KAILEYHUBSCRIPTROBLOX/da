---Booting Up UI Library
	local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
	local Window = OrionLib:MakeWindow({Name = "Raze Hub | Made by Kailey ", HidePremium = false, IntroEnabled = false, SaveConfig = true, ConfigFolder = "OrionTest"})
	---Tab
	local UniversalTab = Window:MakeTab({
		Name = "Universal",
		Icon = "rbxassetid://4483345998",
		PremiumOnly = false
	})
	
	local CreditTab = Window:MakeTab({
		Name = "Credits",
		Icon = "rbxassetid://4483345998",
		PremiumOnly = false
	})
	local BloxTab = Window:MakeTab({
		Name = "Blox Fruits",
		Icon = "rbxassetid://4483345998",
		PremiumOnly = false
	})
    local MurderTab = Window:MakeTab({
		Name = "Murder Mystery 2",
		Icon = "rbxassetid://4483345998",
		PremiumOnly = false
	})
    local KingTab = Window:MakeTab({
        Name = "King Legacy",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })
    local AnimeTab = Window:MakeTab({
        Name = "Anime Dimensions",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })
    
	---Section
	local Section = UniversalTab:AddSection({
		Name = "Universal Scripts/Local Scripts"
	})
	
	local Section = BloxTab:AddSection({
		Name = "Blox Fruits Script"
	})
	---Blox Fruit Buttons
	BloxTab:AddButton({
		Name = "Zen Hub",
		Callback = function()
				loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/ZenHub/main/Loader", true))()
		end    
	})
	BloxTab:AddButton({
		Name = "CFrame Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/CFrame3310/CFrameHub/main/BloxFruit_Mobile.lua"))()
		end    
	})
	BloxTab:AddButton({
		Name = "Neva Hub",
		Callback = function()
			loadstring(game:HttpGet('https://raw.githubusercontent.com/VEZ2/NEVAHUB/main/2'))()
		end    
	})
	BloxTab:AddButton({
		Name = "Sxrge Script Hub (Support BloxFruits)",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/sxrge3k/sxrge_ssh_hub/main/sxrge_script_hub"))()
		end    
	})
	BloxTab:AddButton({
		Name = "Mukuro Hub",
		Callback = function()
			loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
		end    
	})
	BloxTab:AddButton({
		Name = "Hoho Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HohoV2/main/ScriptLoad.lua"))()
		end    
	})
	BloxTab:AddButton({
		Name = "Unique Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/AkiraNus/UniquehubKak/main/FreeCr.Xenonhub"))()
		end    
	})
	BloxTab:AddButton({
		Name = "PlayBack Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/NeaPchX2/Playback-X-HUB/main/Protected.lua.txt"))()
		end    
	})
	BloxTab:AddButton({
		Name = "String Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/StringV2/StringHub/main/BF.txt", true))()
		end    
	})
	BloxTab:AddButton({
		Name = "RTN Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/WindowsXp12/rtnhub/main/bloxfruit.lua"))()
		end    
	})
	BloxTab:AddButton({
		Name = "BloxFruits (idk what name)",
		Callback = function()
			loadstring(game:HttpGet("https://pastebin.com/raw/HSzQz2g3", true))()
		end    
	})
	BloxTab:AddButton({
		Name = "Mango Hub",
		Callback = function()
			getgenv().WaterMark = true
			loadstring(game:HttpGet("https://gitlab.com/L1ZOT/mango-hub/-/raw/main/Mango-Bloxf-Fruits-Beta"))()
		end    
	})
	BloxTab:AddButton({
		Name = "Ripper Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/RIPPERHUBV2.lua"))()
		end    
	})
	BloxTab:AddButton({
		Name = "ATR Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/ATR",true))()
		end    
	})
	BloxTab:AddButton({
		Name = "Maru Hub",
		Callback = function()
			loadstring(game:HttpGet('https://raw.githubusercontent.com/joi-droid/MaruHubBF/main/GOHANSSJ3'))()
		end
	})
	BloxTab:AddButton({
		Name = "Ripper Hub V1 (idk this will work)",
		Callback = function()
			_G.Color = Color3.fromRGB(52, 190, 255)
			loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/NEWBF.lua"))()
		end    
	})
	BloxTab:AddButton({
		Name = "Project Meow",
		Callback = function()
			loadstring(game:HttpGet"https://rawscripts.net/raw/Project-Meow_421")()
		end    
	})
	BloxTab:AddButton({
		Name = "Tawan X Hub",
		Callback = function()
			loadstring(game:HttpGet('https://raw.githubusercontent.com/kill55547/TAWAN_HUB/main/hub.lua.txt', true))()
		end    
	})
	BloxTab:AddButton({
		Name = "Astro Hub",
		Callback = function()
			loadstring(game:HttpGet'https://raw.githubusercontent.com/AstroScripter/ASTROHUB/main/Main/BloxFruit-1.lua')()
		end    
	})
	BloxTab:AddButton({
		Name = "SMZ Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/Frerfgzz/free-script/main/SMZHUBv2BETA"))()
		end    
	})
	BloxTab:AddButton({
		Name = "Mukuro Hub (Old UI)",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/xQuartyx/DonateMe/main/OldBf"))()
		end    
	})
	BloxTab:AddButton({
		Name = "Power X Hub",
		Callback = function()
			_G.Color = Color3.fromRGB(0, 255, 17)
			loadstring(game:HttpGet(("https://raw.githubusercontent.com/PowerxCANDYYY/BFFREE/main/POWERX.lua"),true))()
		end    
	})
	BloxTab:AddButton({
		Name = "Netnayay hub (idk whats the true name)",
		Callback = function()
			loadstring(game:HttpGet('https://raw.githubusercontent.com/NinoGod/NetnaYay/8d21ce23346c500c93bb8b4a71f7791e4058a70b/startload.lua'))()
		end    
	})
	BloxTab:AddButton({
		Name = "Ren Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/MxntyButDiff/Blox-Fruit/main/Bf-Obf.txt"))()
		end    
	})
	BloxTab:AddButton({
		Name = "Zaque Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/Mei2232/ZaqueHub/main/Zaque%20Hub"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Uranium Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/Augustzyzx/UraniumX/main/URANIUMMOBILE_V2.3.lua.txt", true))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Fiend Main Loader",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/Fiend1sh/FiendMain/main/FiendMainLoader", true))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Thunder Z Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-HUB/HUB/main/Mobile-V2"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Winnable Hub Next Gen",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/xlostpexz/tyuiop/Fps/Loading.lua"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Rein Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/Ren"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Ken Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/Ken"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Zeus X Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/BlodyXHub/ZeusHub/main/Loading_Ui"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Boe Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/Boe"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Chiba Hub Comeback",
		Callback = function()
			loadstring(game:HttpGet('https://raw.githubusercontent.com/KindIhave/ChibaHubcomeback/main/Chibacomebackbeta.txt'))()
		  end    
	})
	BloxTab:AddButton({
		Name = "CFrame Hub New",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/CFrame3310/CFrameHub/main/BloxFruit_Mobile.lua"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Zen Hub (PC Version)",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/ZenHub/main/Pcversion", true))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Ripper Hub V3 ",
		Callback = function()
			_G.Version = "V3" -- V2 or V3
            loadstring(game:HttpGet('https://raw.githubusercontent.com/xDestinyx/RipperHub/main/Loader.lua'))();
		  end    
	})
	BloxTab:AddButton({
		Name = "Ripper Hub V2",
		Callback = function()
			_G.Version = "V2" -- V2 or V3
            loadstring(game:HttpGet('https://raw.githubusercontent.com/xDestinyx/RipperHub/main/Loader.lua'))();
		  end    
	})
	BloxTab:AddButton({
		Name = "Unique Hub Crack",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/AkiraNus/UniquehubKak/main/FreeCr.Xenonhub"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Zama Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/RimuruScripter/ZamaHub/main/OnlyPc"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Saru Hub",
		Callback = function()
			loadstring(game:HttpGet"https://raw.githubusercontent.com/SaintGGHH/ScriptSaru/main/README.md")()
		  end    
	})
	BloxTab:AddButton({
		Name = "Yaretzi Hub",
		Callback = function()
			-- Script cant run join developer discord on pin comment
            loadstring(game:HttpGet("https://raw.githubusercontent.com/DeletedUserCode/Yaretzi/main/XyfIueHjd.lua"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "Sxnumz Hub",
		Callback = function()
			loadstring(game:HttpGet('https://raw.githubusercontent.com/SixnumzWOC/Sxnumz/main/SixnumFreeScript.lua'))()
		  end    
	})
	BloxTab:AddButton({
		Name = "TweedLeak Hub",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/LuaQLeak/Scripts/main/Blox-Fruits-UpdateV1"))()
		  end    
	})
	BloxTab:AddButton({
		Name = "NubXYZ Hub",
		Callback = function()
			loadstring(game:HttpGet('https://rawscripts.net/raw/UPDATE-16-Blox-Fruits-Nub-V1-Hub-4583'))()
		  end    
	})
	local Section = CreditTab:AddSection({
		Name = "Credits to Kailey"
	})
	local Section = CreditTab:AddSection({
		Name = "Facebook: Bernard Jr D. Delacruz"
	})
	local Section = CreditTab:AddSection({
		Name = "Roblox Name: Razemyt | King_noobpog "
	})
	local Section = CreditTab:AddSection({
		Name = "Note: Pm me on facebook if you want some more script"
	})
	local Section = CreditTab:AddSection({
		Name = "bloxfruit will be fix"
	})
	local Section = CreditTab:AddSection({
		Name = "I made this script december 2 2022"
	})
	local Section = CreditTab:AddSection({
		Name = "If u have Script and wanna put it on the script hub"
	})
	local Section = CreditTab:AddSection({
		Name = "Direct/Personal message me on Facebook"
	})
	local Section = CreditTab:AddSection({
		Name = "Support All Executors PC/Mobile"
	})
	local Section = CreditTab:AddSection({
		Name = "Press Right Shift to Close/Open GUI"
	})
	UniversalTab:AddButton({
		Name = "Keyboard Script (For Mobile)",
		Callback = function()
			loadstring(game:HttpGet("https://pastebin.com/raw/FeMGnC1i"))()
		  end    
	})
	
	UniversalTab:AddButton({
		Name = "Lag Script",
		Callback = function()
			loadstring(game:HttpGet("https://pastebin.com/raw/HxXiNGAB"))()
		  end    
	})
	UniversalTab:AddButton({
		Name = "FE Yeeter GUI",
		Callback = function()
			-- I DONT OWN THIS SCRIPT

local lp = game:FindService("Players").LocalPlayer

local function gplr(String)
	local Found = {}
	local strl = String:lower()
	if strl == "all" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			table.insert(Found,v)
		end
	elseif strl == "others" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name ~= lp.Name then
				table.insert(Found,v)
			end
		end 
	elseif strl == "me" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name == lp.Name then
				table.insert(Found,v)
			end
		end 
	else
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name:lower():sub(1, #String) == String:lower() then
				table.insert(Found,v)
			end
		end 
	end
	return Found 
end

local function notif(str,dur)
	game:FindService("StarterGui"):SetCore("SendNotification", {
		Title = "yeet gui",
		Text = str,
		Icon = "rbxassetid://2005276185",
		Duration = dur or 3
	})
end

--// sds

local h = Instance.new("ScreenGui")
local Main = Instance.new("ImageLabel")
local Top = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")

h.Name = "h"
h.Parent = game:GetService("CoreGui")
h.ResetOnSpawn = false

Main.Name = "Main"
Main.Parent = h
Main.Active = true
Main.Draggable = true
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.174545452, 0, 0.459574461, 0)
Main.Size = UDim2.new(0, 454, 0, 218)
Main.Image = "rbxassetid://2005276185"

Top.Name = "Top"
Top.Parent = Main
Top.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
Top.BorderSizePixel = 0
Top.Size = UDim2.new(0, 454, 0, 44)

Title.Name = "Title"
Title.Parent = Top
Title.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0, 0, 0.295454562, 0)
Title.Size = UDim2.new(0, 454, 0, 30)
Title.Font = Enum.Font.SourceSans
Title.Text = "FE Yeet Gui (trollface edition)"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

TextBox.Parent = Main
TextBox.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0704845786, 0, 0.270642221, 0)
TextBox.Size = UDim2.new(0, 388, 0, 62)
TextBox.Font = Enum.Font.SourceSans
TextBox.PlaceholderText = "Who do i destroy(can be shortened)"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

TextButton.Parent = Main
TextButton.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.10352423, 0, 0.596330225, 0)
TextButton.Size = UDim2.new(0, 359, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Cheese em'"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

TextButton.MouseButton1Click:Connect(function()
	local Target = gplr(TextBox.Text)
	if Target[1] then
		Target = Target[1]
		
		local Thrust = Instance.new('BodyThrust', lp.Character.HumanoidRootPart)
		Thrust.Force = Vector3.new(9999,9999,9999)
		Thrust.Name = "YeetForce"
		repeat
			lp.Character.HumanoidRootPart.CFrame = Target.Character.HumanoidRootPart.CFrame
			Thrust.Location = Target.Character.HumanoidRootPart.Position
			game:FindService("RunService").Heartbeat:wait()
		until not Target.Character:FindFirstChild("Head")
	else
		notif("Invalid player")
	end
end)

--//fsddfsdf
notif("Loaded successfully! Created by scuba#0001", 5)
		  end    
	})
	UniversalTab:AddButton({
		Name = "Shift Lock Script",
		Callback = function()
			loadstring(game:HttpGet("https://pastebin.com/Hd63rMKe"))()
		  end    
	})
	UniversalTab:AddButton({
		Name = "Infinite Yield (Best FE commands)",
		Callback = function()
			loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
		  end    
	})
	UniversalTab:AddButton({
		Name = "Unnamed ESP",
		Callback = function()
			loadstring(game:HttpGet("https://pastebin.com/sp0793ca"))()
		  end    
	})
	UniversalTab:AddButton({
		Name = "Owl Hub (Supports many games)",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
		  end    
	})
	UniversalTab:AddButton({
		Name = "Universal Aimbot (PC)",
		Callback = function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/Blissful4992/Miscellaneous/main/UNIVERSAL.lua"))()
		  end    
	})
	UniversalTab:AddButton({
		Name = "Universal FE Hub",
		Callback = function()
			loadstring(game:HttpGet('https://raw.githubusercontent.com/Dvrknvss/UniversalFEScriptHub/main/Script'))()
		  end    
	})
    MurderTab:AddButton({
        Name = "Vynixius MM2 (Old Ui)",
        Callback = function()
            loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
          end    
    })
    MurderTab:AddButton({
        Name = "Eclipse Hub (Best MM2 Hub)",
        Callback = function()
            getgenv().mainKey = "nil"

            local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https\58//api.eclipsehub.xyz/auth";c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)()            
          end    
    })
    KingTab:AddButton({
        Name = "Hub (Idk whats the name)",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xlostpexz/dasdokasdias/Fps/Loading.lua"))()
          end    
    })
    KingTab:AddButton({
        Name = "Noob Hub",
        Callback = function()
            loadstring(game:HttpGet('https://raw.githubusercontent.com/SHAREHACK/script/main/kl'))()
          end    
    })
    KingTab:AddButton({
        Name = "River Hub",
        Callback = function()
            pcall(function()
                loadstring(game:HttpGet("http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))()
              end)
          end    
    })
    KingTab:AddButton({
        Name = "Quartz Mukuro Hub",
        Callback = function()
            loadstring(game:HttpGet"https://raw.githubusercontent.com/xQuartyx/DonateMe/main/ScriptLoader")()
          end    
    })
    KingTab:AddButton({
        Name = "Maru Hub",
        Callback = function()
            loadstring(game:HttpGet('https://raw.githubusercontent.com/joi-droid/MaruHubBF/main/GOHANSSJ3'))()
          end    
    })
    KingTab:AddButton({
        Name = "Hyper Hub",
        Callback = function()
            repeat wait() until game:IsLoaded()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/Shisobad/new/main/script.lua"))()
          end    
    })
    KingTab:AddButton({
        Name = "Kaizen Hub",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/KaiZen/main/GameHub", true))()
          end    
    })
    KingTab:AddButton({
        Name = "No Assigned Function yet thank u",
        Callback = function()
                  print("button pressed")
          end    
    })
    AnimeTab:AddButton({
        Name = "SLH Hub | V1.52",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/SmellLikeHacker/MyEdit/main/Hub"))()
          end    
    })
