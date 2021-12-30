-- Vault is daddy ngl
-- Leaked everywhere by Maxy
-- Machport is a gaming gamer ong
-- Enjoy the script skids :)

local GetService = setmetatable({}, {
    __index = function(self, key)
        return game:GetService(key)
    end
})

local Library = loadstring(game:HttpGet("https://gist.githubusercontent.com/VaultGitos/87b2dc20ef97aaab08664d7b32d28125/raw/ff670b9cc91e4f3650fe7f620e164795d2bd9719/cattoware.lua"))()
local NotifyLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kinlei/Dynissimo/main/Scripts/AkaliNotif.lua"))()
local Notify = NotifyLibrary.Notify
Library.theme.accentcolor = Color3.new(0.603921, 0.011764, 1)

local RunService = GetService.RunService
local Players = GetService.Players
local LocalPlayer = Players.LocalPlayer
local Mouse = LocalPlayer:GetMouse()
local CurrentCamera = workspace.CurrentCamera
local UserInputService = GetService.UserInputService
local GuiInset = GetService.GuiService:GetGuiInset()
local AimbotFOV = Drawing.new("Circle")
AimbotFOV.Thickness = 1
local SilentAimFOV = Drawing.new("Circle")
SilentAimFOV.Thickness = 1
local Insert = table.insert
local Network = GetService.NetworkClient
local PuppywareFolder = Instance.new("Folder", workspace)
PuppywareFolder.Name = "PuppyWare-Folder"
local StarterGui = GetService.StarterGui
local ReplicatedStorage = GetService.ReplicatedStorage

local AnimationModule = {
    Astronaut = {
        "rbxassetid://891621366",
        "rbxassetid://891633237",
        "rbxassetid://891667138",
        "rbxassetid://891636393",
        "rbxassetid://891627522",
        "rbxassetid://891609353",
        "rbxassetid://891617961"
    },
    Bubbly = {
        "rbxassetid://910004836",
        "rbxassetid://910009958",
        "rbxassetid://910034870",
        "rbxassetid://910025107",
        "rbxassetid://910016857",
        "rbxassetid://910001910",
        "rbxassetid://910030921",
        "rbxassetid://910028158"
    },
    Cartoony = {
        "rbxassetid://742637544",
        "rbxassetid://742638445",
        "rbxassetid://742640026",
        "rbxassetid://742638842",
        "rbxassetid://742637942",
        "rbxassetid://742636889",
        "rbxassetid://742637151"
    },
    Confindent = {
        "rbxassetid://1069977950",
        "rbxassetid://1069987858",
        "rbxassetid://1070017263",
        "rbxassetid://1070001516",
        "rbxassetid://1069984524",
        "rbxassetid://1069946257",
        "rbxassetid://1069973677"
    },
    Cowboy = {
        "rbxassetid://1014390418",
        "rbxassetid://1014398616",
        "rbxassetid://1014421541",
        "rbxassetid://1014401683",
        "rbxassetid://1014394726",
        "rbxassetid://1014380606",
        "rbxassetid://1014384571"
    },
    Default = {
        "http://www.roblox.com/asset/?id=507766666",
        "http://www.roblox.com/asset/?id=507766951",
        "http://www.roblox.com/asset/?id=507777826",
        "http://www.roblox.com/asset/?id=507767714",
        "http://www.roblox.com/asset/?id=507765000",
        "http://www.roblox.com/asset/?id=507765644",
        "http://www.roblox.com/asset/?id=507767968"
    },
    Elder = {
        "rbxassetid://845397899",
        "rbxassetid://845400520",
        "rbxassetid://845403856",
        "rbxassetid://845386501",
        "rbxassetid://845398858",
        "rbxassetid://845392038",
        "rbxassetid://845396048" 
    },
    Ghost = {
        "rbxassetid://616006778",
        "rbxassetid://616008087",
        "rbxassetid://616013216",
        "rbxassetid://616013216",
        "rbxassetid://616008936",
        "rbxassetid://616005863",
        "rbxassetid://616012453",
        "rbxassetid://616011509"
    },
    Knight = {
        "rbxassetid://657595757",
        "rbxassetid://657568135",
        "rbxassetid://657552124",
        "rbxassetid://657564596",
        "rbxassetid://658409194",
        "rbxassetid://658360781",
        "rbxassetid://657600338"
    },
    Levitation = {
        "rbxassetid://616006778",
        "rbxassetid://616008087",
        "rbxassetid://616013216",
        "rbxassetid://616010382",
        "rbxassetid://616008936",
        "rbxassetid://616003713",
        "rbxassetid://616005863"
    },
    Mage = {
        "rbxassetid://707742142",
        "rbxassetid://707855907",
        "rbxassetid://707897309",
        "rbxassetid://707861613",
        "rbxassetid://707853694",
        "rbxassetid://707826056",
        "rbxassetid://707829716"
    },
    Ninja = {
        "rbxassetid://656117400",
        "rbxassetid://656118341",
        "rbxassetid://656121766",
        "rbxassetid://656118852",
        "rbxassetid://656117878",
        "rbxassetid://656114359",
        "rbxassetid://656115606"
    },
    OldSchool = {
        "rbxassetid://5319828216",
        "rbxassetid://5319831086",
        "rbxassetid://5319847204",
        "rbxassetid://5319844329",
        "rbxassetid://5319841935",
        "rbxassetid://5319839762",
        "rbxassetid://5319852613",
        "rbxassetid://5319850266"
    },
    Patrol = {
        "rbxassetid://1149612882",
        "rbxassetid://1150842221",
        "rbxassetid://1151231493",
        "rbxassetid://1150967949",
        "rbxassetid://1148811837",
        "rbxassetid://1148811837",
        "rbxassetid://1148863382"
    },
    Pirtate = {
        "rbxassetid://750781874",
        "rbxassetid://750782770",
        "rbxassetid://750785693",
        "rbxassetid://750783738",
        "rbxassetid://750782230",
        "rbxassetid://750779899",
        "rbxassetid://750780242"
    },
    Popstar = {
        "rbxassetid://1212900985",
        "rbxassetid://1150842221",
        "rbxassetid://1212980338",
        "rbxassetid://1212980348",
        "rbxassetid://1212954642",
        "rbxassetid://1213044953",
        "rbxassetid://1212900995"
    },
    Princess = {
        "rbxassetid://941003647",
        "rbxassetid://941013098",
        "rbxassetid://941028902",
        "rbxassetid://941015281",
        "rbxassetid://941008832",
        "rbxassetid://940996062",
        "rbxassetid://941000007"
    },
    Robot = {
        "rbxassetid://616088211",
        "rbxassetid://616089559",
        "rbxassetid://616095330",
        "rbxassetid://616091570",
        "rbxassetid://616090535",
        "rbxassetid://616086039",
        "rbxassetid://616087089"
    },
    Rthro = {
        "rbxassetid://2510196951",
        "rbxassetid://2510197257",
        "rbxassetid://2510202577",
        "rbxassetid://2510198475",
        "rbxassetid://2510197830",
        "rbxassetid://2510195892",
        "rbxassetid://02510201162",
        "rbxassetid://2510199791",
        "rbxassetid://2510192778"
    },
    Sneaky = {
        "rbxassetid://1132473842",
        "rbxassetid://1132477671",
        "rbxassetid://1132510133",
        "rbxassetid://1132494274",
        "rbxassetid://1132489853",
        "rbxassetid://1132461372",
        "rbxassetid://1132469004"
    },
    Stylish = {
        "rbxassetid://616136790",
        "rbxassetid://616138447",
        "rbxassetid://616146177",
        "rbxassetid://616140816",
        "rbxassetid://616139451",
        "rbxassetid://616133594",
        "rbxassetid://616134815"
    },
    Superhero = {
        "rbxassetid://782841498",
        "rbxassetid://782845736",
        "rbxassetid://782843345",
        "rbxassetid://782842708",
        "rbxassetid://782847020",
        "rbxassetid://782843869",
        "rbxassetid://782846423"
    },
    Toy = {
        "rbxassetid://782841498",
        "rbxassetid://782845736",
        "rbxassetid://782843345",
        "rbxassetid://782842708",
        "rbxassetid://782847020",
        "rbxassetid://782843869",
        "rbxassetid://782846423"
    },
    Vampire = {
        "rbxassetid://1083445855",
        "rbxassetid://1083450166",
        "rbxassetid://1083473930",
        "rbxassetid://1083462077",
        "rbxassetid://1083455352",
        "rbxassetid://1083439238",
        "rbxassetid://1083443587"
    },
    Werewolf = {
        "rbxassetid://1083195517",
        "rbxassetid://1083214717",
        "rbxassetid://1083178339",
        "rbxassetid://1083216690",
        "rbxassetid://1083218792",
        "rbxassetid://1083182000",
        "rbxassetid://1083189019"
    },
    Zombie = {
        "rbxassetid://616158929",
        "rbxassetid://616160636",
        "rbxassetid://616168032",
        "rbxassetid://616163682",
        "rbxassetid://616161997",
        "rbxassetid://616156119",
        "rbxassetid://616157476"
    }
}

local AnimationsName = {
    "Astronaut",
    "Bubbly",
    "Cartoony",
    "Confindent",
    "Cowboy",
    "Default",
    "Elder",
    "Ghost",
    "Knight",
    "Levitation",
    "Mage",
    "Ninja",
    "OldSchool",
    "Patrol",
    "Pirate",
    "Popstar",
    "Princess",
    "Robot",
    "Rthro",
    'Sneaky',
    "Stylish",
    "Superhero",
    "Toy",
    "Vampire",
    "Werewolf",
    "Zombie"
}

local AnimationState = {
    Idle = "Default",
    Walk = "Default",
    Run = "Default",
    Jump = "Default",
    Climb = "Default",
    Fall = "Default",
}

local PuppywareSettings = {
    Aiming = {
        Aimbot = {
            Enabled = false,
            AimAssist = false,
            IsAiming = false,
            ShowFOV = false,
            FOVColor = Color3.new(0.603921, 0.011764, 1),
            UseNearestDistance = false,
            WallCheck = false,
            KnockedOutCheck = false,
            GrabbedCheck = false,
            Hitboxes = {"Head"}
        },
        TriggerBot = {
            Enabled = false,
            Delay = false,
            DelayAmount = 0
        },
        SilentAim = {
            Enabled = false,
            ShowFOV = false,
            FOVColor = Color3.new(0.603921, 0.011764, 1),
            WallCheck = false,
            KnockedOutCheck = false,
            UseNearestDistance = false,
            GrabbedCheck = false,
            Hitboxes = {"Head"}
        },
        TargetAim = {
            Enabled = false,
            ShowFOV = false,
            FOVColor = Color3.new(0.603921, 0.011764, 1),
            WallCheck = false,
            KnockedOutCheck = false,
            UseNearestDistance = false,
            GrabbedCheck = false,
            Hitboxes = {"Head"},
            Target = nil
        },
        AimingSettings = {
            MovementPrediction = false,
            MovementPredictionAmount = 0.165 * 1,
            HitChance = false,
            HitChanceAmount = {
                HitPercent = 100,
                NotHitPercent = 0
            },
            AimAssistType = "Camera",
            MovementPrediction = false,
            MovementPredictionAmount = 0.165 * 1,
            SmoothingTracing = false,
            SmoothingTracingAmount = 5,
            PingBasedPrediction = false,
            GetVelocity = 0.165
        },
        TargetAimSettings = {
            UnlockTargetKnocked = false,
            NotificationAlert = false,
        },
        FOV = {
            FOVFilled = false,
            AimAssistSize = 100,
            SilentAimSize = 100,
            TargetAimSize = 100
        },
        Whitelist = {
            Players = {},
            Friends = {},
            Holder = "",
            Enabled = false,
            CrewEnabled = false,
            FriendsWhitelist = false
        },
    },
    Blatant = {
        BlatantAA = {
            Enabled = false,
            NoAutoRotate = false,
            UndergroundWallbang = false,
            Underground = false,
            AntiAimType = "Jitter",
            AntiAimSpeed = 100,
            JitterAngle = 180
        },
        LegitAA = {
            Enabled = false,
            AntiAimAt = false,
            AntiAimAtDistance = 20
        },
        FakeLag = {
            Enabled = false,
            TriggerAmount = 5
        },
        Movement = {
            SpeedEnabled = false,
            SpeedType = "Default",
            SpeedRender = "Default",
            SpeedAmount = 5
        },
        Reaching = {
            FistReach = false,
            MeleeReach = false
        },
        Character = {
            AntiGrab = false,
            AntiStomp = false,
            AntiStompType = "Nil Char",
            AntiBag = false,
            AutoArmor = false,
            AutoLettuce = false,
            AutoReload = false
        },
        Farming = {
            ATMFarm = false,
            ShoeFarm = false,
            MuscleFarm = false,
            MuscleFarmingType = "Normal",
            BoxFarm = false,
            HospitalFarm = false,
            ATMPick = false
        },
        Cash = {
            AutoDrop = false,
            AutoDropAmount = 5000,
            AutoPickCash = false
        }
    },
    Teleport = {
        TeleportReturn = false,
        ReturnDelay = false,
        AutoPurchase = false,
        AmmoPurchaseAmount = 1
    }
}

local PuppywareModule = {
    Old = {
        CFrame,
    },
    God = {
        MeleeAlive = false,
        GodMelee = false,
        GodBullet = false,
        AntiRagdoll = false
    },
    LagTick = 0,
    Ignores = {
        "UpperTorso",
        "LowerTorso",
        "Head",
        "LeftHand",
        "LeftUpperArm",
        "LeftLowerArm",
        "RightHand",
        "RightUpperArm",
        "RightLowerArm"
    },
    PingBasedPrediction = 0.165,
    Instance = {},
    Teleport = {
        Players = {},
        Food = {
            "Cranberry",
            "Donut",
            "Pizza",
            "Chicken",
            "Popcorn",
            "Hamburger",
            "Taco",
            "Starblox Latte",
            "Lettuce",
            "Lemonade"
        },
        Location = {
            "Bank",
            "Boxing Place",
            "Police Station",
            "Admin Base",
            "Sewers",
            "Shoe Store",
            "Hospital",
            "Phone Store",
            "Taco Shack",
            "Casino",
            "UFO",
            "Fire Station",
            "Church",
            "Downhill Shop",
            "Uphill Shop"
        },
        Gun = {
            "Glock",
            "SMG",
            "Silencer",
            "TacticalShotgun",
            "P90",
            "AUG",
            "Shotgun",
            "RPG",
            "AR",
            "Double-Barrel SG",
            "Flamethrower",
            "Revolver",
            "LMG",
            "AK47",
            "DrumGun",
            "Silencer",
            "GrenadeLauncher",
            "Taser",
            "SilencerAR",
            "Grenade"
        },
        Armor = {
            "High-Medium Armor",
            "Medium Armor"
        },
        Mask = {
            "Surgeon Mask",
            "Riot Mask",
            "Pitchfork",
            "Hockey Mask",
            "Breathing Mask",
            "Pumpkin Mask",
            "Skull Mask",
            "Paintball Mask",
            "Ninja Mask"
        },
        Weight = {
            "Weights",
            "HeavyWeights"
        },
        Melee = {
            "Shovel",
            "Bat",
            "Pencil",
            "StopSign",
            "Knife",
            "Pitchfork"
        },
        Phone = {
            "iPhone",
            "iPhoneB",
            "iPhoneG",
            "iPhoneP",
            "Old Phone",
            "Orange Phone",
            "Original Phone",
        },
        Bike = {
            "DuoBike",
            "Solo Bike",
        },
        Extra = {
            "PepperSpray",
            "LockPicker",
            "Flashlight",
            "Flowers",
            "Money Gun",
            "Brown Bag",
            "Anti Bodies",
            "Firework"
        }
    }
}

local Window = Library:CreateWindow("Puppyware", Vector2.new(492, 598), Enum.KeyCode.RightShift)
local AimingTab = Window:CreateTab("Aiming")

-- Aimbot Setion --

local LegitSection = AimingTab:CreateSector("Aimbot", "left")
LegitSection:AddToggle('Enabled', false, function(Boolean)
    PuppywareSettings.Aiming.Aimbot.Enabled = Boolean
end)

local AimAssistToggle = LegitSection:AddToggle('Aim Assist', false, function(Boolean)
    PuppywareSettings.Aiming.Aimbot.AimAssist = Boolean
end)

AimAssistToggle:AddKeybind()

local AimbotFOVToggle = LegitSection:AddToggle('Show FOV', false, function(Boolean)
    PuppywareSettings.Aiming.Aimbot.ShowFOV = Boolean
end)

AimbotFOVToggle:AddColorpicker(PuppywareSettings.Aiming.Aimbot.FOVColor, function(Color)
    PuppywareSettings.Aiming.Aimbot.FOVColor = Color
end)

LegitSection:AddToggle('Use Nearest Distance', false, function(Boolean)
    PuppywareSettings.Aiming.Aimbot.UseNearestDistance = Boolean
end)

LegitSection:AddToggle('Wall Check', false, function(Boolean)
    PuppywareSettings.Aiming.Aimbot.WallCheck = Boolean
end)

LegitSection:AddToggle('Knock Out Check', false, function(Boolean)
    PuppywareSettings.Aiming.Aimbot.KnockedOutCheck = Boolean
end)

LegitSection:AddToggle('Grabbed Check', false, function(Boolean)
    PuppywareSettings.Aiming.Aimbot.GrabbedCheck = Boolean
end)

LegitSection:AddDropdown('Hitboxes', {"Head", "HumanoidRootPart"}, {"Head"}, true, function(Value)
    PuppywareSettings.Aiming.Aimbot.Hitboxes = Value
end)

-- Silent Aim Setion --

local RageSection = AimingTab:CreateSector("Silent Aim", "left")
local SilentAimToggle = RageSection:AddToggle('Silent Aim Enabled', false, function(Boolean)
    PuppywareSettings.Aiming.SilentAim.Enabled = Boolean
end)

SilentAimToggle:AddKeybind()

local SilentAimFOVToggle = RageSection:AddToggle('Show FOV', false, function(Boolean)
    PuppywareSettings.Aiming.SilentAim.ShowFOV = Boolean
end)

SilentAimFOVToggle:AddColorpicker(Color3.new(0.603921, 0.011764, 1), function(Color)
    PuppywareSettings.Aiming.SilentAim.FOVColor = Color
end)

RageSection:AddToggle('Use Nearest Distance', false, function(Boolean)
    PuppywareSettings.Aiming.SilentAim.NearestDistance = Boolean
end)

RageSection:AddToggle('Wall Check', false, function(Boolean)
    PuppywareSettings.Aiming.SilentAim.WallCheck = Boolean
end)

RageSection:AddToggle('Knock Out Check', false, function(Boolean)
    PuppywareSettings.Aiming.SilentAim.KnockedOutCheck = Boolean
end)

RageSection:AddToggle('Grabbed Check', false, function(Boolean)
    PuppywareSettings.Aiming.SilentAim.GrabbedCheck = Boolean
end)

RageSection:AddDropdown('Hitboxes', {"Head", "HumanoidRootPart"}, {"Head"}, true, function(Value)
    PuppywareSettings.Aiming.SilentAim.Hitboxes = Value
end)

-- Target Aim Setion --

local RageSection = AimingTab:CreateSector("Target Aim", "left")
local TargetAimToggle = RageSection:AddToggle('Target Aim Enabled', false, function(Boolean)
    PuppywareSettings.Aiming.TargetAim.Enabled = Boolean
end)

TargetAimToggle:AddKeybind()

local SilentAimFOVToggle = RageSection:AddToggle('Show FOV', false, function(Boolean)
    PuppywareSettings.Aiming.TargetAim.ShowFOV = Boolean
end)

SilentAimFOVToggle:AddColorpicker(Color3.new(0.603921, 0.011764, 1), function(Color)
    PuppywareSettings.Aiming.TargetAim.FOVColor = Color
end)

RageSection:AddToggle('Wall Check', false, function(Boolean)
    PuppywareSettings.Aiming.TargetAim.WallCheck = Boolean
end)

RageSection:AddToggle('Knock Out Check', false, function(Boolean)
    PuppywareSettings.Aiming.TargetAim.KnockedOutCheck = Boolean
end)

RageSection:AddToggle('Grabbed Check', false, function(Boolean)
    PuppywareSettings.Aiming.TargetAim.GrabbedCheck = Boolean
end)

RageSection:AddDropdown('Hitboxes', {"Head", "HumanoidRootPart"}, {"Head"}, true, function(Value)
    PuppywareSettings.Aiming.TargetAim.Hitboxes = Value
end)

-- Aim Assist FOV Section --

local AimbotFOVSection = AimingTab:CreateSector("FOV", "right")
AimbotFOVSection:AddToggle('FOV Filled', false, function(Boolean)
    PuppywareSettings.Aiming.FOV.FOVFilled = Boolean
end)

AimbotFOVSection:AddSlider("Aim Assist Size", 0, 100, 500, 1, function(Value)
    PuppywareSettings.Aiming.FOV.AimAssistSize = Value
end)

AimbotFOVSection:AddSlider("Silent Aim Size", 0, 100, 500, 1, function(Value)
    PuppywareSettings.Aiming.FOV.SilentAimSize = Value
end)

AimbotFOVSection:AddSlider("FOV Transparency", 0, 9, 9, 1, function(Value)
    PuppywareSettings.Aiming.FOV.Transparency = tonumber("0." .. Value)
end)

-- Trigger Bot Section -- 

local TriggerbotSection = AimingTab:CreateSector("Trigger Bot", "left")

local TriggerBotToggle = TriggerbotSection:AddToggle('Trigger Bot Enabled', false, function(State)
    PuppywareSettings.Aiming.TriggerBot.Enabled = State
end)

TriggerBotToggle:AddKeybind()

local TValue = TriggerbotSection:AddToggle('Trigger Bot Delay (ms)', false, function(State)
    PuppywareSettings.Aiming.TriggerBot.Delay = State
end)

TValue:AddSlider(1, 0, 60, 1, function(Value)
    PuppywareSettings.Aiming.TriggerBot.DelayAmount = Value
end)

-- Aiming Settings Section --

local AimingSettings = AimingTab:CreateSector("Aiming Settings", "right")

AimingSettings:AddToggle('Ping Based Prediction', false, function(Boolean)
    PuppywareSettings.Aiming.AimingSettings.PingBasedPrediction = Boolean
end)

AimingSettings:AddDropdown('Aim Assist Type', {"Camera", "Mouse"}, "Camera", false, function(Option)
    PuppywareSettings.Aiming.AimingSettings.AimAssistType = Option
end)

local SmoothingTracing = AimingSettings:AddToggle('Smoothing Tracing', false, function(Boolean)
    PuppywareSettings.Aiming.AimingSettings.SmoothingTracing = Boolean
end)

SmoothingTracing:AddSlider(2, 5, 10, 1, function(Value)
    PuppywareSettings.Aiming.AimingSettings.SmoothingTracingAmount = Value
end)

local MovementPredToggle2 = AimingSettings:AddToggle('Custom Prediction', false, function(Boolean)
    PuppywareSettings.Aiming.AimingSettings.MovementPrediction = Boolean
end)

MovementPredToggle2:AddSlider(1, 1, 5, 1, function(Value)
    PuppywareSettings.Aiming.AimingSettings.MovementPredictionAmount = 0.165 * tonumber("1." ..Value)
end)

local HitChanceToggle2 = AimingSettings:AddToggle('Hit Chance', false, function(Boolean)
    PuppywareSettings.Aiming.AimingSettings.HitChance = Boolean
end)

HitChanceToggle2:AddSlider(0, 100, 100, 1, function(Value)
    PuppywareSettings.Aiming.AimingSettings.HitChanceAmount.HitPercent = tonumber(Value)
    PuppywareSettings.Aiming.AimingSettings.HitChanceAmount.NotHitPercent = tonumber(100 - PuppywareSettings.Aiming.AimingSettings.HitChanceAmount.HitPercent)
end)

-- Target Aim Settings Section --

local TargetAimSettings = AimingTab:CreateSector("Target Aim Settings", "right")

local TargetBind = TargetAimSettings:AddKeybind("Bind", false, function()
    
end, function()
    if PuppywareSettings.Aiming.TargetAim.Enabled then
        local NearestTarget, NearestDistance = NearestMouse()
        if NearestTarget and Visible(NearestTarget.Character.HumanoidRootPart, LocalPlayer.Character.HumanoidRootPart) then
            PuppywareSettings.Aiming.TargetAim.Target = NearestTarget.Name
            if PuppywareSettings.Aiming.TargetAimSettings.NotificationAlert then
                Notify({
                    Title = "Puppyware 😳",
                    Description = "Target: " .. NearestTarget.Name,
                    Duration = 3
                })
            end
        end
    end
end)

TargetAimSettings:AddToggle('Unlock Target Knocked', false, function(State)
    PuppywareSettings.Aiming.TargetAimSettings.UnlockTargetKnocked = State
end)

TargetAimSettings:AddToggle('Notification Alert', false, function(State)
    PuppywareSettings.Aiming.TargetAimSettings.NotificationAlert = State
end)

local WhitelistSection = AimingTab:CreateSector("Whitelist", "right")

WhitelistSection:AddToggle('Whitelist Enabled', false, function(State)
    PuppywareSettings.Aiming.Whitelist.Enabled = State
end)

WhitelistSection:AddTextbox("Username", nil, function(Text)
    if Text ~= nil and Find(Text) ~= nil and Players:FindFirstChild(Find(Text)) then
        PuppywareSettings.Aiming.Whitelist.Holder = Find(Text)
    else
        Notify({
            Title = "Puppyware",
            Description = "Player is not found.",
            Duration = 3
        })
    end
end)

WhitelistSection:AddButton('Add', function(State)
    if PuppywareSettings.Aiming.Whitelist.Holder ~= nil and Players:FindFirstChild(PuppywareSettings.Aiming.Whitelist.Holder) then
        if table.find(PuppywareSettings.Aiming.Whitelist.Players, PuppywareSettings.Aiming.Whitelist.Holder) then
            Notify({
                Title = "Puppyware",
                Description = PuppywareSettings.Aiming.Whitelist.Holder .. " is whitelisted.",
                Duration = 3
            })
        else
            Insert(PuppywareSettings.Aiming.Whitelist.Players, PuppywareSettings.Aiming.Whitelist.Holder)
            Notify({
                Title = "Puppyware",
                Description = "Whitelisted " .. PuppywareSettings.Aiming.Whitelist.Holder,
                Duration = 3
            })
        end
    else
        Notify({
            Title = "Puppyware",
            Description = "Player is not found.",
            Duration = 3
        })
    end
end)

WhitelistSection:AddButton('Remove', function()
    if PuppywareSettings.Aiming.Whitelist.Holder ~= nil and Players:FindFirstChild(PuppywareSettings.Aiming.Whitelist.Holder) then
        if table.find(PuppywareSettings.Aiming.Whitelist.Players, PuppywareSettings.Aiming.Whitelist.Holder) then
            Remove(PuppywareSettings.Aiming.Whitelist.Players, PuppywareSettings.Aiming.Whitelist.Holder)
            Notify({
                Title = "Puppyware",
                Description = "Removed " .. PuppywareSettings.Aiming.Whitelist.Holder,
                Duration = 5
            })
        else
            Notify({
                Title = "Puppyware",
                Description = PuppywareSettings.Aiming.Whitelist.Holder .. " is not whitelisted.",
                Duration = 5
            })
        end
    else
        Notify({
            Title = "Puppyware",
            Description = "Player is not found.",
            Duration = 3
        })
    end
end)

WhitelistSection:AddToggle('Crew Whitelist', false, function(State)
    PuppywareSettings.Aiming.Whitelist.CrewEnabled = State
end)

WhitelistSection:AddToggle('Friends Whitelist', false, function(State)
    PuppywareSettings.Aiming.Whitelist.FriendsWhitelist = State
end)

-- Visuals Window --
--[[
    
local VisualsTab = Window:CreateTab("Visuals")
local ESPSection = VisualsTab:CreateSector("ESP", "left")

local ESPToggle = ESPSection:AddToggle('ESP Enabled', false, function(Boolean)
    
end)

ESPToggle:AddKeybind()

ESPSection:AddToggle('Box ESP', false, function(Boolean)
    
end)

ESPSection:AddToggle('Tracer ESP', false, function(Boolean)
    
end)

ESPSection:AddToggle('Name ESP', false, function(Boolean)
    
end)

ESPSection:AddToggle('Health Bar', false, function(Boolean)
    
end)

ESPSection:AddToggle('Armor Bar', false, function(Boolean)
    
end)

ESPSection:AddToggle("Wall Check", false, function()

end)

local LocalSection = VisualsTab:CreateSector("Local", "left")

local FOVToggle = LocalSection:AddToggle('FOV Changer', false, function(State)

end)

FOVToggle:AddSlider(70, 90, 120, 1, function(Value)
    
end)

local SelfChamToggle = LocalSection:AddToggle('Self Cham', false, function(State)

end)

SelfChamToggle:AddColorpicker(Color3.fromRGB(255, 255, 255), function()

end)

SelfChamToggle:AddDropdown({}, "Ghost", false, function(Option)
    
end)

local FakeLagChamToggle = LocalSection:AddToggle('Fake Lag Cham', false, function(State)

end)

FakeLagChamToggle:AddColorpicker(Color3.fromRGB(255, 255, 255), function()

end)

local CrosshairSection = VisualsTab:CreateSector("Drawing Crosshair", "left")

local DrawingCrosshairToggle = CrosshairSection:AddToggle("Crosshair Enabled", false, function()

end)

DrawingCrosshairToggle:AddColorpicker(Color3.fromRGB(255, 255, 255), function()

end)

CrosshairSection:AddSlider("Gap", 0, 1, 5, 1, function(Value)
    
end)

CrosshairSection:AddSlider("Size", 0, 3, 10, 1, function(Value)
    
end)

local MiscSection = VisualsTab:CreateSector("Misc", "left")

MiscSection:AddToggle("No Flashbag", false, function()

end)

MiscSection:AddToggle("No Recoil", false, function()

end)

local WorldSection = VisualsTab:CreateSector("World", "right")

WorldSection:AddToggle("Better Shadow", false, function()

end)

WorldSection:AddToggle("FullBright", false, function()

end)

local GridiantToggle = WorldSection:AddToggle("Gradiant", false, function()

end)

GridiantToggle:AddColorpicker(Color3.fromRGB(255, 255, 255), function()

end)

GridiantToggle:AddColorpicker(Color3.fromRGB(255, 255, 255), function()

end)

local SaturationToggle = WorldSection:AddToggle("Saturation", false, function()

end)

SaturationToggle:AddSlider(-10, 0, 10, 1, function(Value)
    
end)

local BrightnessToggle = WorldSection:AddToggle("Brightness", false, function()

end)

BrightnessToggle:AddSlider(-10, 0, 10, 1, function(Value)
    
end)

local ContrastToggle = WorldSection:AddToggle("Contrast", false, function()

end)

ContrastToggle:AddSlider(-10, 0, 10, 1, function(Value)
    
end)

local ESPSettings = VisualsTab:CreateSector("ESP Settings", "right")

ESPSettings:AddDropdown('Font', {}, "Plex", false, function(Option)
    
end)

ESPSettings:AddDropdown('Text Case', {"Normal", "Uppercase", "Lowercase"}, "Lowercase", false, function(Option)
    
end)

ESPSettings:AddToggle("Unlock Tracers", false, function()

end)

ESPSettings:AddSlider("Text Size", 5, 14, 20, 1, function(Value)
    
end)
]]

-- Blatant Tab --

local BlatantTab = Window:CreateTab("Blatant")

local MovementSector = BlatantTab:CreateSector("Movement", "right")

local BlatantAntiAimSector = BlatantTab:CreateSector("Blatant Anti Aim", "left")

local SpeedToggle = MovementSector:AddToggle('Speed Enabled', false, function(State)
    PuppywareSettings.Blatant.Movement.SpeedEnabled = State
end)

SpeedToggle:AddSlider(0, 5, 10, 1, function(Value)
    PuppywareSettings.Blatant.Movement.SpeedAmount = Value
end)

MovementSector:AddDropdown("Speed Type", {"CFrame"}, "CFrame", false, function(Value)
    PuppywareSettings.Blatant.Movement.SpeedType = Value
end)

MovementSector:AddDropdown("Speed Render Type", {"Default", "Fast"}, "Default", false, function(Value)
    PuppywareSettings.Blatant.Movement.SpeedRenderType = Value
end)

local AntiAimToggle = BlatantAntiAimSector:AddToggle('Blatant AA Enabled', false, function(State)
    PuppywareSettings.Blatant.BlatantAA.Enabled = State
end)

AntiAimToggle:AddKeybind()

BlatantAntiAimSector:AddToggle('No Auto Rotate', false, function(State)
    PuppywareSettings.Blatant.BlatantAA.NoAutoRotate = State
end)

local UndergroundWallBangToggle = BlatantAntiAimSector:AddToggle('Underground Wallbang', false, function(State)
    pcall(function()
        if State then
			wait(0.5)
			Float = Instance.new("BodyVelocity")
			Float.Parent = LocalPlayer.Character.HumanoidRootPart
			Float.MaxForce = Vector3.new(100000, 100000, 100000)
			Float.Velocity = Vector3.new(0, 0, 0)
			wait(0.25)
			LocalPlayer.Character.HumanoidRootPart.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0, -9.5, 0)
			Cham(LocalPlayer, true)
			PuppywareSettings.Blatant.BlatantAA.UndergroundWallbang = true
            SpeedToggle:Set(true)
		else
			LocalPlayer.Character.HumanoidRootPart.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0, 9.5, 0)
			Cham(LocalPlayer, false)
			Float:Destroy()
			PuppywareSettings.Blatant.BlatantAA.UndergroundWallbang = false
            SpeedToggle:Set(false)
		end
    end)
end)

UndergroundWallBangToggle:AddKeybind()

BlatantAntiAimSector:AddToggle('Underground', false, function(State)
    PuppywareSettings.Blatant.BlatantAA.Underground = State
end)

BlatantAntiAimSector:AddDropdown("Anti Aim Type", {"Jitter", "Spin"}, "Jitter", false, function(Value)
    PuppywareSettings.Blatant.BlatantAA.AntiAimType = Value
end)

BlatantAntiAimSector:AddSlider("Anti Aim Speed", 0, 100, 300, 1, function(Value)
    PuppywareSettings.Blatant.BlatantAA.AntiAimSpeed = Value
end)

BlatantAntiAimSector:AddSlider("Jitter Angle", 0, 180, 360, 1, function(Value)
    PuppywareSettings.Blatant.BlatantAA.JitterAngle = Value
end)

local LegitAntiAimSector = BlatantTab:CreateSector("Legit Anti Aim", "left")

local LegitAntiAimToggle = LegitAntiAimSector:AddToggle('Legit AA Enabled', false, function(State)
    PuppywareSettings.Blatant.LegitAA.Enabled = Value
end)

LegitAntiAimSector:AddToggle('Anti Aim At', false, function(State)
    PuppywareSettings.Blatant.LegitAA.AntiAimAt = State
end)

LegitAntiAimSector:AddSlider("Anti Aim At Distance", 2.5, 20, 100, 1, function(Value)
    PuppywareSettings.Blatant.LegitAA.AntiAimAtDistance = Value
end)

local FakeLagSector = BlatantTab:CreateSector("Fake Lag", "left")

local FakeLagToggle = FakeLagSector:AddToggle('Fake Lag Enabled', false, function(State)
    PuppywareSettings.Blatant.FakeLag.Enabled = State
end)

FakeLagToggle:AddKeybind()

FakeLagToggle:AddSlider(1, 5, 10, 1, function(Value)
    PuppywareSettings.Blatant.FakeLag.TriggerAmount = Value
end)

local MiscSector = BlatantTab:CreateSector("Misc", "left")

MiscSector:AddButton('Invisible', function(State)
    Invisible()
end)

MiscSector:AddButton('Nil Char', function(State)
    NilBody()
end)

--[[
    MiscSector:AddButton('Unjail', function(State)

    end)
]]

local NilCharBind = MiscSector:AddKeybind("Nil Char Bind", false, function()
    
end, function()
    NilBody()
end)

local GodModeSector = BlatantTab:CreateSector("God Mode", "left")

GodModeSector:AddButton("Gun Only", function()
    PuppywareModule.God.GodBullet = true
    NilBody()
end)

GodModeSector:AddButton("Melee Only", function()
    PuppywareModule.God.GodMelee = true
    NilBody()
end)

GodModeSector:AddButton("Anti Ragdoll", function()
    PuppywareModule.God.AntiRagdoll = true
    NilBody()
end)

GodModeSector:AddButton("God Block", function()
    pcall(function()
        LocalPlayer.Character.BodyEffects.Defense.CurrentTimeBlock:Destroy()
    end)
end)

local ReachingSector = BlatantTab:CreateSector("Reaching", "right")

local FistReachToggle = ReachingSector:AddToggle('Fist Reach', false, function(State)
    PuppywareSettings.Blatant.Reaching.FistReach = State
end)

FistReachToggle:AddKeybind()

local MeleeReachToggle = ReachingSector:AddToggle('Melee Reach', false, function(State)
    PuppywareSettings.Blatant.Reaching.MeleeReach = State
end)

MeleeReachToggle:AddKeybind()

local CharacterSector = BlatantTab:CreateSector("Character", "right")

CharacterSector:AddToggle('Anti Stomp', false, function(State)
    PuppywareSettings.Blatant.Character.AntiStomp = State
end)

CharacterSector:AddDropdown("Anti Stomp Type", {"Show Body", "Nil Char"}, "Nil Char", false, function(State)
    PuppywareSettings.Blatant.Character.AntiStompType = State
end)

CharacterSector:AddToggle('Anti Bag', false, function(State)
    PuppywareSettings.Blatant.Character.AntiBag = State
end)

CharacterSector:AddToggle('Anti Grab', false, function(State)
    PuppywareSettings.Blatant.Character.AntiGrab = State
end)

CharacterSector:AddToggle('Auto Lettuce', false, function(State)
    PuppywareSettings.Blatant.Character.AutoLettuce = State
end)

CharacterSector:AddToggle('Auto Armor', false, function(State)
    PuppywareSettings.Blatant.Character.AutoArmor = State
end)

CharacterSector:AddToggle('Auto Reload', false, function(State)
    PuppywareSettings.Blatant.Character.AutoReload = State
end)

local FarmingSector = BlatantTab:CreateSector("Farming", "right")

FarmingSector:AddToggle('Shoe Farm', false, function(State)
    PuppywareSettings.Blatant.Farming.ShoeFarm = State
end)

FarmingSector:AddToggle('ATM Farm', false, function(State)
    PuppywareSettings.Blatant.Farming.ATMFarm = State
end)

FarmingSector:AddToggle('Hospital Farm', false, function(State)
    PuppywareSettings.Blatant.Farming.HospitalFarm = State
end)

local BoxFarmToggle = FarmingSector:AddToggle('Box Farm', false, function(State)
    PuppywareSettings.Blatant.Farming.BoxFarm = State
end)

BoxFarmToggle:AddKeybind()

FarmingSector:AddDropdown("Muscle Farming Type", {"Normal", "Heavy"}, "Normal", false, function(State)
    PuppywareSettings.Blatant.Farming.MuscleFarmingType = State
end)

FarmingSector:AddToggle('Muscle Farm', false, function(State)
    PuppywareSettings.Blatant.Farming.MuscleFarm = State
end)

local CashSector = BlatantTab:CreateSector("Cash", "right")

local AutoDropToggle = CashSector:AddToggle("Auto Drop", false, function(State)
    PuppywareSettings.Blatant.Cash.AutoDrop = State
end)

AutoDropToggle:AddSlider(1000, 5000, 10000, 1, function(Value)
    PuppywareSettings.Blatant.Cash.AutoDropAmount = Value
end)

CashSector:AddToggle("Auto Pick Cash", false, function(State)
    PuppywareSettings.Blatant.Cash.AutoPickCash = State
end)

-- Auto Buy Tab --

local TeleportTab = Window:CreateTab("Teleport")

local TeleportModule = {
    Food = PuppywareModule.Teleport.Food[1],
    Gun = PuppywareModule.Teleport.Gun[1],
    Location = PuppywareModule.Teleport.Location[1],
    Armor = PuppywareModule.Teleport.Armor[1],
    Melee = PuppywareModule.Teleport.Melee[1],
    Extra = PuppywareModule.Teleport.Extra[1],
    Bike = PuppywareModule.Teleport.Bike[1],
    Mask = PuppywareModule.Teleport.Mask[1],
    Phone = PuppywareModule.Teleport.Phone[1],
    Weight = PuppywareModule.Teleport.Weight[1],
    AutoSet = {
        Tools = {}
    }
}

local FoodSector = TeleportTab:CreateSector("Food Teleport", "left")
FoodSector:AddDropdown("Food Selection", PuppywareModule.Teleport.Food, PuppywareModule.Teleport.Food[1], false, function(Value)
    TeleportModule.Food = Value
end)

FoodSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Food))
end)

local GunSector = TeleportTab:CreateSector("Gun Teleport", "left")
GunSector:AddDropdown("Gun Selection", PuppywareModule.Teleport.Gun, PuppywareModule.Teleport.Gun[1], false, function(Value)
    TeleportModule.Gun = Value
end)

GunSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Gun))
    spawn(function()
        for i = 1, PuppywareSettings.Teleport.AmmoPurchaseAmount do
            TeleportBuy(ToolAmmo(TeleportModule.Gun))
            wait(1)
        end
    end)
end)

local LocationSector = TeleportTab:CreateSector("Location Teleport", "left")
LocationSector:AddDropdown("Location Selection", PuppywareModule.Teleport.Location, PuppywareModule.Teleport.Location[1], false, function(Value)
    TeleportModule.Location = Value
end)

LocationSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Location))
end)

local ArmorSector = TeleportTab:CreateSector("Armor Teleport", "left")
ArmorSector:AddDropdown("Armor Selection", PuppywareModule.Teleport.Armor, PuppywareModule.Teleport.Armor[1], false, function(Value)
    TeleportModule.Armor = Value
end)

ArmorSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Armor))
end)

local MeleeSector = TeleportTab:CreateSector("Melee Teleport", "left")
MeleeSector:AddDropdown("Melee Selection", PuppywareModule.Teleport.Melee, PuppywareModule.Teleport.Melee[1], false, function(Value)
    TeleportModule.Melee = Value
end)

MeleeSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Melee))
end)

local ExtraSector = TeleportTab:CreateSector("Extra Teleport", "left")
ExtraSector:AddDropdown("Extra Selection", PuppywareModule.Teleport.Extra, PuppywareModule.Teleport.Extra[1], false, function(Value)
    TeleportModule.Extra = Value
end)

ExtraSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Extra))
end)

local BikeSector = TeleportTab:CreateSector("Bike Teleport", "left")
BikeSector:AddDropdown("Bike Selection", PuppywareModule.Teleport.Bike, PuppywareModule.Teleport.Bike[1], false, function(Value)
    TeleportModule.Bike = Value
end)

BikeSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Bike))
end)

local MaskSector = TeleportTab:CreateSector("Mask Teleport", "left")
MaskSector:AddDropdown("Mask Selection", PuppywareModule.Teleport.Mask, PuppywareModule.Teleport.Mask[1], false, function(Value)
    TeleportModule.Mask = Value
end)

MaskSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Mask))
end)

local PhoneSector = TeleportTab:CreateSector("Phone Teleport", "left")
PhoneSector:AddDropdown("Phone Selection", PuppywareModule.Teleport.Phone, PuppywareModule.Teleport.Phone[1], false, function(Value)
    TeleportModule.Phone = Value
end)

PhoneSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Phone))
end)

local WeightSector = TeleportTab:CreateSector("Weight Teleport", "left")
WeightSector:AddDropdown("Weight Selection", PuppywareModule.Teleport.Weight, PuppywareModule.Teleport.Weight[1], false, function(Value)
    TeleportModule.Weight = Value
end)

WeightSector:AddButton("Teleport", function()
    TeleportBuy(ToolName(TeleportModule.Weight))
end)

local TeleportSettings = TeleportTab:CreateSector("Teleport Settings", "right")
TeleportSettings:AddToggle("Teleport Return", false, function(State)
    PuppywareSettings.Teleport.TeleportReturn = State
end)

TeleportSettings:AddSlider("Return Delay", 0, 1, 100, 1, function(Value)
    PuppywareSettings.Teleport.ReturnDelay = Value
end)

TeleportSettings:AddToggle("Auto Purchase", false, function(State)
    PuppywareSettings.Teleport.AutoPurchase = State
end)

TeleportSettings:AddSlider("Ammo Purchase Amount", 0, 1, 100, 1, function(Value)
    PuppywareSettings.Teleport.AmmoPurchaseAmount = Value
end)

local AutoSetTab = TeleportTab:CreateSector("Auto Set", "right")
for i, v in pairs(PuppywareModule.Teleport.Armor) do
    AutoSetTab:AddToggle(v, false, function(State)
        if State then
            if not table.find(TeleportModule.AutoSet.Tools, v) then
                table.insert(TeleportModule.AutoSet.Tools, v)
            end
        else
            Remove(TeleportModule.AutoSet.Tools, v)
        end
    end)
end

for i, v in pairs(PuppywareModule.Teleport.Gun) do
    AutoSetTab:AddToggle(v, false, function(State)
        if State then
            if not table.find(TeleportModule.AutoSet.Tools, v) then
                table.insert(TeleportModule.AutoSet.Tools, v)
            end
        else
            Remove(TeleportModule.AutoSet.Tools, v)
        end
    end)
end

AutoSetTab:AddButton("Teleport", function()
    if Alive(LocalPlayer) then
        for i, v in pairs(TeleportModule.AutoSet.Tools) do
            if string.find(v:lower(), "armor") then
                if PuppywareSettings.Teleport.ArmorValueCheck and LocalPlayer.Character.BodyEffects.Armor.Value < 0 then
                    TeleportBuy(ToolName(v, true))
                else
                    TeleportBuy(ToolName(v, true))
                end
            else
                TeleportBuy(ToolName(v, true))
                spawn(function()
                    for i = 1, PuppywareSettings.Teleport.AmmoPurchaseAmount do
                        TeleportBuy(ToolAmmo(v), true)
                        wait(1)
                    end
                end)
            end
        end
    end
end)

-- Miscellaneous Window --
local MiscellaneousTab = Window:CreateTab("Miscellaneous")

LocalPlayer.CharacterAdded:Connect(function()
    wait(0.5)
    PuppywareModule.God.GodMeleeAlive = false
    if LocalPlayer.Character:FindFirstChild("BodyEffects") then
        if PuppywareModule.God.GodBullet then
            GodFunction(PuppywareModule.God.GodBullet)
            LocalPlayer.Character.BodyEffects.BreakingParts:Destroy()
        end
        if PuppywareModule.God.GodMelee then
            GodFunction(PuppywareModule.God.GodMelee)
            PuppywareModule.God.GodMeleeAlive = true
            LocalPlayer.Character.BodyEffects.Armor:Destroy()
            LocalPlayer.Character.BodyEffects.Defense:Destroy()
        end
        if PuppywareModule.God.AntiRagdoll then
            GodFunction(PuppywareModule.God.AntiRagdoll)
        end
    end
    wait(0.5)
    if PuppywareSettings.Blatant.BlatantAA.Underground then
        Underground(true)
    end
    wait(0.4)
    if PuppywareSettings.Blatant.BlatantAA.UndergroundWallbang then
        Float = Instance.new("BodyVelocity")
        Float.Parent = LocalPlayer.Character.HumanoidRootPart
        Float.MaxForce = Vector3.new(100000, 100000, 100000)
        Float.Velocity = Vector3.new(0, 0, 0)
        wait(0.25)
        LocalPlayer.Character.HumanoidRootPart.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0, -11.5, 0)
        Cham(LocalPlayer, true)
        PuppywareSettings.Blatant.BlatantAA.UndergroundWallbang = true
    end
    LocalPlayer.Character.Animate.idle.Animation1.AnimationId = AnimationModule[AnimationState.Idle][1]
    LocalPlayer.Character.Animate.idle.Animation2.AnimationId = AnimationModule[AnimationState.Idle][2]
    LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = AnimationModule[AnimationState.Walk][3]
    LocalPlayer.Character.Animate.run.RunAnim.AnimationId = AnimationModule[AnimationState.Run][4]
    LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = AnimationModule[AnimationState.Jump][5]
    LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = AnimationModule[AnimationState.Climb][6]
    LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = AnimationModule[AnimationState.Fall][7]
    for i, v in pairs(AnimationState) do
        print(i, v)
    end
end)

local AnimationSector = MiscellaneousTab:CreateSector("Animation", "left")
AnimationSector:AddDropdown("Idle", AnimationsName, "Default", false, function(State)
    if Alive(LocalPlayer) then
        LocalPlayer.Character.Animate.idle.Animation1.AnimationId = AnimationModule[State][1]
        LocalPlayer.Character.Animate.idle.Animation2.AnimationId = AnimationModule[State][2]
        AnimationState.Idle = State
    end
end)

AnimationSector:AddDropdown("Walk", AnimationsName, "Default", false, function(State)
    if Alive(LocalPlayer) then
        LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = AnimationModule[State][3]
        AnimationState.Walk = State
    end
end)

AnimationSector:AddDropdown("Run", AnimationsName, "Default", false, function(State)
    if Alive(LocalPlayer) then
        LocalPlayer.Character.Animate.run.RunAnim.AnimationId = AnimationModule[State][4]
        AnimationState.Run = State
    end
end)

AnimationSector:AddDropdown("Jump", AnimationsName, "Default", false, function(State)
    if Alive(LocalPlayer) then
        LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = AnimationModule[State][5]
        AnimationState.Jump = State
    end
end)

AnimationSector:AddDropdown("Climb", AnimationsName, "Default", false, function(State)
    if Alive(LocalPlayer) then
        LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = AnimationModule[State][6]
        AnimationState.Climb = State
    end
end)

AnimationSector:AddDropdown("Fall", AnimationsName, "Default", false, function(State)
    if Alive(LocalPlayer) then
        LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = AnimationModule[State][7]
        AnimationState.Fall = State
    end
end)

--[[
local RadioSector = MiscellaneousTab:CreateSector("Radio Playlist", "left")

RadioSector:AddDropdown("Playlist", {}, "", false, function()

end)

RadioSector:AddLabel("Current Song: ")

RadioSector:AddButton("Add", function()

end)

RadioSector:AddButton("Remove", function()

end)

RadioSector:AddButton("Play", function()

end)

RadioSector:AddButton("Stop", function()

end)

local KillInsultsSector = MiscellaneousTab:CreateSector("Kill Insults", "right")

KillInsultsSector:AddToggle("Kill Insults Enabled", false, function()

end)

KillInsultsSector:AddToggle("Custom Message", false, function()

end)

KillInsultsSector:AddSlider("Delay (ms)", 0, 0, 5, 1, function(Value)
    
end)

KillInsultsSector:AddDropdown("Messages", {}, "", false, function()

end)

KillInsultsSector:AddTextbox("Message", "@Username is bad.", function(Text)
    
end)

KillInsultsSector:AddButton("Add", function()

end)

KillInsultsSector:AddButton("Remove", function()

end)

local CustomModelSector = MiscellaneousTab:CreateSector("Custom Model", "right")

CustomModelSector:AddToggle("Custom Model Enabled", false, function()

end)

CustomModelSector:AddDropdown("Models", {"Among Us", "19$ Fortnite Card"}, "Among Us", false, function()

end)

CustomModelSector:AddToggle("Edit Mode", false, function()

end)

CustomModelSector:AddSlider("Position X", 0, 0, 360, 1, function(Value)
    
end)

CustomModelSector:AddSlider("Position Y", 0, 0, 360, 1, function(Value)
    
end)

CustomModelSector:AddSlider("Position Z", 0, 0, 360, 1, function(Value)
    
end)

CustomModelSector:AddSlider("Position Rotation", 0, 0, 360, 1, function(Value)
    
end)

local ServerSector = MiscellaneousTab:CreateSector("Server", "left")

ServerSector:AddLabel("Crashing Rate: 0%")

ServerSector:AddToggle("Server Crash", false, function()

end)

ServerSector:AddButton("Rejoin", function()

end)

ServerSector:AddButton("Server Hop", function()

end)

local PanicSector = MiscellaneousTab:CreateSector("Panic", "right")

PanicSector:AddDropdown("Panic Type", {"Da Hood Moderator", "Player Joined"}, "Da Hood Moderator", false, function()

end)

PanicSector:AddToggle("Panic Enabled", false, function()

end)
]]

-- Settings Window --

local SettingsTab = Window:CreateTab("Settings")

if syn then
    SettingsTab:CreateConfigSystem("left")
else
    Notify({
        Title = "Puppyware",
        Description = "Your Executor Doesn't Support Config.",
        Duration = 3
    })
end

-- Init --

for _, v in next, Players:GetPlayers() do
    if v ~= LocalPlayer and v:IsFriendsWith(LocalPlayer.UserId) then
        Insert(PuppywareSettings.Aiming.Whitelist.Friends, v.Name)
    end
end

Players.PlayerAdded:Connect(function(_Player)
    if _Player ~= LocalPlayer and _Player:IsFriendsWith(LocalPlayer.UserId) then
        Insert(PuppywareSettings.Aiming.Whitelist.Friends, _Player.Name)
    end
end)

Players.PlayerRemoving:Connect(function(_Player)
    if _Player ~= LocalPlayer and _Player:IsFriendsWith(LocalPlayer.UserId) then
        Remove(PuppywareSettings.Aiming.Whitelist.Friends, _Player.Name)
    end
end)

function NoSpace(Data)
    return Data:gsub("%s+", "") or Data
end
    
function Find(Data)
    local Target = nil
    
    for i, v in next, Players:GetPlayers() do
        if v.Name ~= LocalPlayer.Name and v.Name:lower():match('^'.. NoSpace(Data):lower()) then
            Target = v.Name
        end
    end
    
    return Target
end

function Alive(Player)
    if Player and Player.Character and Player.Character:FindFirstChild("HumanoidRootPart") ~= nil and Player.Character:FindFirstChild("Humanoid") ~= nil and Player.Character:FindFirstChild("Head") ~= nil then
        return true
    end
    return false
end

function Knocked(Player)
    if Alive(Player) then
        if Player.Character.BodyEffects["K.O"].Value then
            return true
        end
        return false
    end
    return false
end

function Grabbing(Player)
    if Alive(Player) then
        if Player.Character:FindFirstChild("GRABBING_CONSTRAINT") then
            return true
        end
        return false
    end
    return false
end

function NearestDistance()
    local Target = nil
    local Distance = math.huge
    
    for i, v in next, Players:GetPlayers() do
        if v ~= LocalPlayer and Alive(LocalPlayer) and Alive(v) then
            local DistanceFromPlayer = (v.Character.HumanoidRootPart.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
            if Distance > DistanceFromPlayer then
                if (not PuppywareSettings.Aiming.Whitelist.FriendsWhitelist or not table.find(PuppywareSettings.Aiming.Whitelist.Friends, v.Name)) and (not PuppywareSettings.Aiming.Whitelist.CrewEnabled or v:FindFirstChild("DataFolder") and v.DataFolder.Information:FindFirstChild("Crew") and not tonumber(v.DataFolder.Information.Crew.Value) == tonumber(LocalPlayer.DataFolder.Information.Crew.Value)) and (not PuppywareSettings.Aiming.Whitelist.Enabled or not table.find(PuppywareSettings.Aiming.Whitelist.Players, v.Name)) then
                    Target = v
                    Distance = DistanceFromPlayer
                end
            end
        end
    end

    return Target, Distance
end

function NearestMouse()
    local Target = nil
    local Distance = math.huge

    for i, v in next, Players:GetPlayers() do
        if v ~= LocalPlayer and Alive(LocalPlayer) and Alive(v) then
            local RootPosition, RootVisible = CurrentCamera:WorldToViewportPoint(v.Character.HumanoidRootPart.Position)
            local DistanceFromMouse = (Vector2.new(RootPosition.X, RootPosition.Y) - Vector2.new(Mouse.X, Mouse.Y)).Magnitude
            if RootVisible and Distance > DistanceFromMouse then
                if (not PuppywareSettings.Aiming.Whitelist.FriendsWhitelist or not table.find(PuppywareSettings.Aiming.Whitelist.Friends, v.Name)) and (not PuppywareSettings.Aiming.Whitelist.CrewEnabled or v:FindFirstChild("DataFolder") and v.DataFolder.Information:FindFirstChild("Crew") and not tonumber(v.DataFolder.Information.Crew.Value) == tonumber(LocalPlayer.DataFolder.Information.Crew.Value)) and (not PuppywareSettings.Aiming.Whitelist.Enabled or not table.find(PuppywareSettings.Aiming.Whitelist.Players, v.Name)) then
                    Target = v
                    Distance = DistanceFromMouse
                end
            end
        end
    end

    return Target, Distance
end

function NearestType(Type)
    if Type == "Distance" then
        return NearestDistance()
    elseif Type == "Mouse" then
        return NearestMouse()
    end
end

function Jitter(Speed, Angle)
    if Alive(LocalPlayer) then
        local Jit = Speed or math.random(30, 90)
        LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(LocalPlayer.Character.HumanoidRootPart.CFrame.Position) * CFrame.Angles(0, math.rad(Angle) + math.rad((math.random(1, 2) == 1 and Jit or -Jit)), 0) 
    end
end

function TableLowerFind(Table, CurrentName)
    local TableName
    for i, v in pairs(Table) do
        if string.find(CurrentName:gsub("%[", ""):gsub("%]", ""):lower(), v:lower()) then
            TableName = v
        end
    end
    return TableName
end
    
function Spin(Speed)
    if Alive(LocalPlayer) then
        LocalPlayer.Character.HumanoidRootPart.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.Angles(0, math.rad(Speed), 0)
    end
end

function TeleportBuy(Target, AutoSetDelay)
    if workspace.Ignored.Shop:FindFirstChild(Target) and Alive(LocalPlayer) then
        PuppywareModule.Old.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame
        wait(0.05)
        LocalPlayer.Character.HumanoidRootPart.CFrame = Workspace.Ignored.Shop[Target].Head.CFrame * CFrame.new(0, 3, 0)
        wait(0.15)
        if PuppywareSettings.Teleport.AutoPurchase then
            for i = 1, 10 do
                fireclickdetector(Workspace.Ignored.Shop[Target].ClickDetector)
            end
        end
        if PuppywareSettings.Teleport.TeleportReturn then
            wait(PuppywareSettings.Teleport.ReturnDelay)
            LocalPlayer.Character.HumanoidRootPart.CFrame = PuppywareModule.Old.CFrame  
        end
        if AutoSetDelay then
            wait(1)
        end
    end
end

function Buy(Target, Delay, LagBack)
    if workspace.Ignored.Shop:FindFirstChild(Target) and Alive(LocalPlayer) then
        PuppywareModule.Old.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame
        wait(0.05)
        LocalPlayer.Character.HumanoidRootPart.CFrame = Workspace.Ignored.Shop[Target].Head.CFrame * CFrame.new(0, 3, 0)
        wait(0.15)
        for i = 1, 3 do
            fireclickdetector(Workspace.Ignored.Shop[Target].ClickDetector)
        end
        if LagBack then
            wait(1)
            LocalPlayer.Character.HumanoidRootPart.CFrame = PuppywareModule.Old.CFrame  
        end
        if Delay ~= nil then
            wait(Delay)
        end
    end
end

function Visible(OriginPart, Part)
    if Alive(LocalPlayer) then
        local IgnoreList = {CurrentCamera, LocalPlayer.Character, OriginPart.Parent}
        local Parts = CurrentCamera:GetPartsObscuringTarget({OriginPart.Position, Part.Position}, IgnoreList)
    
        for i, v in pairs(Parts) do
            if v.Transparency >= 0.3 then
                PuppywareModule.Instance[#PuppywareModule.Instance + 1] = v
            end
    
            if v.Material == Enum.Material.Glass then
                PuppywareModule.Instance[#PuppywareModule.Instance + 1] = v
            end
        end
    
        return #Parts == 0
    end
    return true
end

function ToolName(Name)
    for Check = 1, 100000 do
        if Workspace.Ignored.Shop:FindFirstChild("[" .. Name .. "] - $" .. Check) then
            return tostring("[" .. Name .. "] - $" .. Check)
        end
    end
end

function ToolAmmo(Name)
    for Check1 = 1, 250 do
        for Check2 = 1, 250 do
            if Workspace.Ignored.Shop:FindFirstChild(Check1 .. " [" .. Name .. " Ammo] - $" .. Check2) then
                return tostring(Check1 .. " [" .. Name .. " Ammo] - $" .. Check2)
            end
        end
    end
end

function Invisible()
    if Alive(LocalPlayer) then
        PuppywareModule.Old.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame
        print(PuppywareModule.Old.CFrame)
        wait(0.1)
        LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 96995694596945934234234234, 0)
        wait(0.1)
        LocalPlayer.Character.LowerTorso.Root:Destroy()
        for _, v in pairs(LocalPlayer.Character:GetChildren()) do
            if v:IsA("MeshPart") and not table.find(PuppywareModule.Ignores, v.Name) then
                v:Destroy()
            end
        end
        wait(0.1)
        LocalPlayer.Character.HumanoidRootPart.CFrame = PuppywareModule.Old.CFrame
    end
end

function NilBody()
    if Alive(LocalPlayer) then
        for i, v in pairs(LocalPlayer.Character:GetChildren()) do
            if v:IsA("BasePart") or v:IsA("Part") or v:IsA("MeshPart") then
                if v.Name ~= "HumanoidRootPart" then
                    v:Destroy()
                end
            end
        end
    end
end

function ChanceTable(Table)
    local Chance = 0
    for i, v in pairs(Table) do
        Chance = Chance + v
    end
    Chance = math.random(0, Chance)
    for i, v in pairs(Table) do
        Chance = Chance - v
        if Chance <= 0 then
            return i
        end
    end	
end

function RandomTable(Table)
    local Values = 0
    for i, v in pairs(Table) do
        Values = i
    end
    
    return Table[math.random(1, Values)]
end

function Remove(Data, Data2)
    for i, v in pairs(Data) do
        if v == Data2 then
            table.remove(Data, i)
        end
    end
end

function IsVisible(GetPosition, IgnoreLists)
    return #CurrentCamera:GetPartsObscuringTarget({game.Players.LocalPlayer.Character.Head.Position, GetPosition}, IgnoreLists) == 0 and true or false
end

function GodFunction(Variable)
    LocalPlayer.Character.RagdollConstraints:Destroy()
    local Folder = Instance.new("Folder", LocalPlayer.Character)
    Folder.Name = "FULLY_LOADED_CHAR"
    wait()
    StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Backpack, true)
    Variable = false
end

function Cham(Data, State)
    local BoxVar = nil
    local GlowVar = nil
    if State then
        for _, v in pairs(Data.Character:GetChildren()) do
            if v:IsA("BasePart") and v.Transparency ~= 1 then
                if not v:FindFirstChild("Box") then
                    BoxVar = Instance.new("BoxHandleAdornment", v)
                    BoxVar.Name = "Box"
                    BoxVar.AlwaysOnTop = true
                    BoxVar.ZIndex = 4
                    BoxVar.Adornee = v
                    BoxVar.Color3 = Color3.fromRGB(0, 153, 153)
                    BoxVar.Transparency = 0.5
                    BoxVar.Size = v.Size + Vector3.new(0.02, 0.02, 0.02)
                end
            end
        end
    else
        for i, v in pairs(Data.Character:GetChildren()) do
            if v:IsA("BasePart") and v.Transparency ~= 1 then
                if v:FindFirstChild("Box") then
                    v["Box"]:Destroy()
                end
            end
        end
        
        return BoxVar, GlowVar
    end
end

UserInputService.InputBegan:Connect(function(Key, Event)
    if Key.UserInputType == Enum.UserInputType.MouseButton2 and not Event then
        PuppywareSettings.Aiming.Aimbot.IsAiming = true
    end
end)

UserInputService.InputEnded:Connect(function(Key, Event)
    if Key.UserInputType == Enum.UserInputType.MouseButton2 and not Event then
        PuppywareSettings.Aiming.Aimbot.IsAiming = false
    end
end)

RunService.Heartbeat:Connect(function()
    if Alive(LocalPlayer) then
        if PuppywareSettings.Blatant.Movement.SpeedEnabled and PuppywareSettings.Blatant.Movement.SpeedType == "CFrame" then
            if PuppywareSettings.Blatant.Movement.SpeedRenderType == "Default" then
                if LocalPlayer.Character.Humanoid.MoveDirection.Magnitude > 0 then
                    for i = 1, PuppywareSettings.Blatant.Movement.SpeedAmount do
                        LocalPlayer.Character:TranslateBy(LocalPlayer.Character.Humanoid.MoveDirection)
                    end
                end
            end
        end
        if PuppywareSettings.Blatant.Character.AntiStomp then
            if Knocked(LocalPlayer) then
                if PuppywareSettings.Blatant.Character.AntiStompType == "Nil Char" then
                    NilBody()
                end
                if PuppywareSettings.Blatant.Character.AntiStompType == "Show Body" then
                    pcall(function()
                        LocalPlayer.Character.Humanoid:Destroy()
                    end)
                end
            end
        end
        if PuppywareSettings.Blatant.Character.AntiBag then
            if LocalPlayer.Character:FindFirstChild("Christmas_Sock") then
                LocalPlayer.Character:FindFirstChild("Christmas_Sock"):Destroy()
            end
        end
        if PuppywareSettings.Blatant.Character.AntiGrab and LocalPlayer.Character:FindFirstChild("GRABBING_CONSTRAINT") then
            LocalPlayer.Character["GRABBING_CONSTRAINT"]:Destroy()
        end
    end
end)

RunService.Stepped:Connect(function()
	if PuppywareSettings.Blatant.BlatantAA.UndergroundWallbang then
		for i, v in pairs(LocalPlayer.Character:GetDescendants()) do
			if v:IsA("BasePart") and v.CanCollide == true then
				v.CanCollide = false
			end
		end
	end
end)

spawn(function()
    while wait() do
        if Alive(LocalPlayer) then
            if PuppywareSettings.Blatant.Character.AutoLettuce then
                pcall(function()
                    Buy("[Lettuce] - $5", 1)
                    if LocalPlayer.Backpack:FindFirstChild("[Lettuce]") then
                        LocalPlayer.Character.Humanoid:EquipTool(LocalPlayer.Backpack["[Lettuce]"])
                    end
                    wait(0.5)
                    LocalPlayer.Character["[Lettuce]"]:Activate()
                end)
            end
            if PuppywareSettings.Blatant.Character.AutoReload then
                local Gun = LocalPlayer.Character:FindFirstChildOfClass("Tool")
                if Gun ~= nil and Gun:FindFirstChild("MaxAmmo") then
                    if Gun.Ammo.Value == 0 then
                        ReplicatedStorage.MainEvent:FireServer("Reload", Gun)
                    end
                end
            end
            if PuppywareSettings.Blatant.Character.AutoArmor then
                if LocalPlayer.Character.BodyEffects.Armor.Value == 0 then
                    Buy("[High-Medium Armor] - $2300", 0.5, true)
                end
            end
            if PuppywareSettings.Blatant.Farming.MuscleFarm then
                pcall(function()
                    if PuppywareSettings.Blatant.Farming.MuscleFarmingType == "Normal" then
                        if not LocalPlayer.Backpack:FindFirstChild("[Weights]") then
                            Buy("[Weights] - $120", 1)
                        end
                        if LocalPlayer.Backpack:FindFirstChild("[Weights]") then
                            LocalPlayer.Character.Humanoid:EquipTool(LocalPlayer.Backpack["[Weights]"])
                        end
                        LocalPlayer.Character["[Weights]"]:Activate()
                    end
                    if PuppywareSettings.Blatant.Farming.MuscleFarmingType == "Heavy" then
                        if not LocalPlayer.Backpack:FindFirstChild("[HeavyWeights]") then
                            Buy("[HeavyWeights] - $250", 1)
                        end
                        if LocalPlayer.Backpack:FindFirstChild("[HeavyWeights]") then
                            LocalPlayer.Character.Humanoid:EquipTool(LocalPlayer.Backpack["[HeavyWeights]"])
                        end
                        LocalPlayer.Character["[HeavyWeights]"]:Activate()
                    end
                end)
            end
            if PuppywareSettings.Blatant.Farming.ShoeFarm then
                pcall(function()
                    for i, v in pairs(Workspace.Ignored.Drop:GetChildren()) do
                        if v.Name == "MeshPart" then
                            LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame * CFrame.new(0, 2, 0)
                            local ShoeDistance = (v.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                            if ShoeDistance < 25 then
                                fireclickdetector(v.ClickDetector)
                            end
                        else
                            fireclickdetector(Workspace.Ignored["Clean the shoes on the floor and come to me for cash"].ClickDetector)
                        end
                    end
                end)
            end
            if PuppywareSettings.Blatant.Farming.HospitalFarm then
                LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116, 23, -479)
                for _, v in pairs(Workspace.Ignored.HospitalJob:GetChildren()) do
                    if v.Name == "Can I get the Green bottle" then
                        fireclickdetector(v.Parent.Green.ClickDetector)
                        wait(1)
                        fireclickdetector(v.ClickDetector)
                    end
                    if v.Name == "Can I get the Blue bottle" then
                        fireclickdetector(v.Parent.Blue.ClickDetector)
                        wait(1)
                        fireclickdetector(v.ClickDetector)
                    end
                    if v.Name == "Can I get the Red bottle" then
                        fireclickdetector(v.Parent.Red.ClickDetector)
                        wait(1)
                        fireclickdetector(v.ClickDetector)
                    end
                end
            end
            if PuppywareSettings.Blatant.Farming.BoxFarm then
                pcall(function()
                    LocalPlayer.Character.HumanoidRootPart.CFrame = Workspace.MAP.Map.ArenaBOX.PunchingBagInGame["pretty ransom"].CFrame * CFrame.new(0, -1, 3)
                    if LocalPlayer.Backpack:FindFirstChild("Combat") then
                        LocalPlayer.Backpack.Combat.Parent = LocalPlayer.Character
                    end
                end)
                mouse1click()
            end
        end
    end
end)

spawn(function()
    while wait() do
        if PuppywareSettings.Blatant.Farming.ATMFarm then
            for _, v in pairs(Workspace.Cashiers:GetChildren()) do
                if v:FindFirstChild("Head") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                    repeat
                        PuppywareSettings.Blatant.Farming.ATMPick = false
                        wait()
                        if PuppywareSettings.Blatant.Farming.ATMFarm then
                            if Alive(LocalPlayer) then
                                LocalPlayer.Character.HumanoidRootPart.CFrame = v.Head.CFrame * CFrame.new(0, -1, 2.5)
                                if LocalPlayer.Backpack:FindFirstChild("Combat") then
                                    LocalPlayer.Backpack.Combat.Parent = LocalPlayer.Character
                                end
                                --if LocalPlayer.Character:FindFirstChild("Combat") then
                                    LocalPlayer.Character["Combat"]:Activate()
                                --end
                            end
                        end
                    until v.Humanoid.Health <= 0 or not PuppywareSettings.Blatant.Farming.ATMFarm
                    pcall(function()
                        LocalPlayer.Character:FindFirstChildOfClass("Tool").Parent = LocalPlayer.Backpack
                    end)
                    PuppywareSettings.Blatant.Farming.ATMPick = true
                    wait(5)
                end
            end
        end
    end
end)

RunService.RenderStepped:Connect(function()
    if Alive(LocalPlayer) then
        if PuppywareSettings.Aiming.AimingSettings.PingBasedPrediction then
            local PingStats = GetService.Stats.Network.ServerStatsItem["Data Ping"]:GetValueString()
            local Value = tostring(PingStats)
            local PingValue = Value:split(" ")
            local PingNumber = tonumber(PingValue[1])
    
            if PingNumber < 130 then
                PuppywareSettings.Aiming.AimingSettings.GetVelocity = PingNumber / 1000 + 0.037
            else
                PuppywareSettings.Aiming.AimingSettings.GetVelocity = PingNumber / 1000 + 0.033
            end
        else
            PuppywareSettings.Aiming.AimingSettings.GetVelocity = 0.165
        end
        if PuppywareSettings.Blatant.Cash.AutoDrop then
            ReplicatedStorage.MainEvent:FireServer("DropMoney", tostring(PuppywareSettings.Blatant.Cash.AutoDropAmount))
        end
        if PuppywareSettings.Blatant.Cash.AutoPickCash then
            pcall(function()
                for _, v in pairs(Workspace.Ignored.Drop:GetChildren()) do
                    if v.Name == "MoneyDrop" then
                        local MoneyMagnitude = (v.Position - LocalPlayer.Character.HumanoidRootPart.Position).magnitude
                        if MoneyMagnitude < 25 then
                            fireclickdetector(v.ClickDetector)
                        end 
                    end
                end
            end)
        end
        if PuppywareSettings.Blatant.Farming.ATMPick then
            pcall(function()
                for _, v in pairs(Workspace.Ignored.Drop:GetChildren()) do
                    if v.Name == "MoneyDrop" then
                        local MoneyMagnitude = (v.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                        if MoneyMagnitude < 25 then
                            fireclickdetector(v.ClickDetector)
                        end 
                    end
                end
            end)
        end
        if PuppywareSettings.Blatant.Movement.SpeedEnabled and PuppywareSettings.Blatant.Movement.SpeedType == "CFrame" then
            if PuppywareSettings.Blatant.Movement.SpeedRenderType == "Fast" and Alive(LocalPlayer) then
                if LocalPlayer.Character.Humanoid.MoveDirection.Magnitude > 0 then
                    for i = 1, PuppywareSettings.Blatant.Movement.SpeedAmount do
                        LocalPlayer.Character:TranslateBy(LocalPlayer.Character.Humanoid.MoveDirection)
                    end
                end
            end
        end
        if PuppywareSettings.Blatant.Reaching.FistReach and LocalPlayer.Character.LeftHand.Transparency ~= 1 then
            LocalPlayer.Character.LeftHand.Size = Vector3.new(45, 45, 45)
            LocalPlayer.Character.RightHand.Size = Vector3.new(45, 45, 45)
            LocalPlayer.Character.RightHand.Massless = true
            LocalPlayer.Character.LeftHand.Massless = true
            LocalPlayer.Character.RightHand.Transparency = 1
            LocalPlayer.Character.LeftHand.Transparency = 1
        end
        if PuppywareSettings.Blatant.Reaching.MeleeReach then
            local Tool = LocalPlayer.Character:FindFirstChildOfClass("Tool")
            if Tool ~= nil and not Tool:FindFirstChild("Ammo") and TableLowerFind(PuppywareModule.Teleport.Melee, Tool.Name) ~= nil and Tool:FindFirstChild("Handle") then
                if Tool.Handle.Transparency ~= 1 then
                    Tool.Handle.Size = Vector3.new(45, 45, 45)
                    Tool.Handle.Transparency = 1
                end
            end
        else
            local Tool = LocalPlayer.Character:FindFirstChildOfClass("Tool")
            if Tool ~= nil and not Tool:FindFirstChild("Ammo") and TableLowerFind(PuppywareModule.Teleport.Melee, Tool.Name) ~= nil and Tool:FindFirstChild("Handle") then
                if Tool.Handle.Transparency == 1 then
                    if Tool.Name == "knife" then
                        Tool.Handle.Size = Vector3.new(2.19574, 0.449288, 0.102495)
                    end
                    if Tool.Name == "bat" then
                        Tool.Handle.Size = Vector3.new(0.559523, 4.68133, 0.559523)
                    end
                    if Tool.Name == "pencil" then
                        Tool.Handle.Size = Vector3.new(0.375586, 1.9, 0.375587)
                    end
                    if Tool.Name == "pitchfork" then
                        Tool.Handle.Size = Vector3.new(1.0553, 5.86135, 0.316619)
                    end
                    if Tool.Name == "shovel" then
                        Tool.Handle.Size = Vector3.new(1.68383, 5.903, 0.337731)
                    end
                    Tool.Handle.Transparency = 0
                end
            end
        end
        if PuppywareSettings.Blatant.LegitAA.Enabled then
            if PuppywareSettings.Blatant.LegitAA.AntiPointAt then
                for i, v in next, Players:GetPlayers() do
                    if v ~= LocalPlayer and Alive(v) and Alive(LocalPlayer) then
                        local BodyEffects = v.Character:FindFirstChild("BodyEffects")
                        local MousePos = BodyEffects:FindFirstChild("MousePos")
                        if BodyEffects ~= nil and MousePos ~= nil then
                            local EnemyMouseMagnitude = (LocalPlayer.Character.HumanoidRootPart.Position - MousePos.Value).Magnitude
                            if PuppywareSettings.Blatant.LegitAA.AntiAimAtDistance > EnemyMouseMagnitude then
                                Root.CFrame = Root.CFrame * CFrame.new(math.random(1, 2) == 1 and 2 or -2, 0, 0)
                            end
                        end
                    end
                end
            end
        end
        if PuppywareSettings.Blatant.BlatantAA.Enabled then
                if PuppywareSettings.Blatant.BlatantAA.AntiAimType == "Jitter" then
                    Jitter(PuppywareSettings.Blatant.BlatantAA.AntiAimSpeed, PuppywareSettings.Blatant.BlatantAA.JitterAngle)
                else
                    Spin(PuppywareSettings.Blatant.BlatantAA.AntiAimSpeed)
                end
                if PuppywareSettings.Blatant.BlatantAA.NoAutoRotate then
                    LocalPlayer.Character.Humanoid.AutoRotate = false
                else
                    LocalPlayer.Character.Humanoid.AutoRotate = true
                end
        else
            LocalPlayer.Character.Humanoid.AutoRotate = true
        end
    end
    if PuppywareSettings.Aiming.TargetAimSettings.UnlockTargetKnocked then
        if PuppywareSettings.Aiming.TargetAimSettings.Target ~= nil and Players:FindFirstChild(PuppywareSettings.Aiming.TargetAimSettings.Target) then
            if Knocked(Players:FindFirstChild(PuppywareSettings.Aiming.TargetAimSettings.Target)) then
                PuppywareSettings.Aiming.TargetAimSettings.Target = nil
            end
        end
    end
    if PuppywareSettings.Aiming.SilentAim.ShowFOV then
        SilentAimFOV.Visible = true
        SilentAimFOV.Radius = PuppywareSettings.Aiming.FOV.SilentAimSize
        SilentAimFOV.Filled = PuppywareSettings.Aiming.FOV.FOVFilled
        SilentAimFOV.Transparency = PuppywareSettings.Aiming.FOV.Transparency
        SilentAimFOV.NumSides = 100
        SilentAimFOV.Color = PuppywareSettings.Aiming.SilentAim.FOVColor
        SilentAimFOV.Position = Vector2.new(Mouse.X, Mouse.Y + GuiInset.Y)
    else
        SilentAimFOV.Visible = false
    end
    if PuppywareSettings.Aiming.Aimbot.Enabled then
        if PuppywareSettings.Aiming.Aimbot.ShowFOV then
            AimbotFOV.Visible = true
            AimbotFOV.Radius = PuppywareSettings.Aiming.FOV.AimAssistSize
            AimbotFOV.Filled = PuppywareSettings.Aiming.FOV.FOVFilled
            AimbotFOV.Transparency = PuppywareSettings.Aiming.FOV.Transparency
            AimbotFOV.NumSides = 100
            AimbotFOV.Color = PuppywareSettings.Aiming.Aimbot.FOVColor
            AimbotFOV.Position = Vector2.new(Mouse.X, Mouse.Y + GuiInset.Y)
        else
            AimbotFOV.Visible = false
        end
        if PuppywareSettings.Aiming.Aimbot.AimAssist and PuppywareSettings.Aiming.Aimbot.IsAiming then
            local NearestTarget, NearestDistance = NearestType(PuppywareSettings.Aiming.Aimbot.UseNearestDistance and "Distance" or "Mouse")

            if NearestTarget and (not PuppywareSettings.Aiming.Aimbot.GrabbedCheck or not Grabbing(NearestTarget)) and (not PuppywareSettings.Aiming.Aimbot.KnockedOutCheck or not Knocked(NearestTarget)) and (not PuppywareSettings.Aiming.Aimbot.ShowFOV or PuppywareSettings.Aiming.FOV.AimAssistSize > NearestDistance) and (not PuppywareSettings.Aiming.Aimbot.WallCheck or Visible(NearestTarget.Character.HumanoidRootPart, LocalPlayer.Character.HumanoidRootPart)) then
                local TargetPart = (NearestTarget.Character.Humanoid:GetState() == Enum.HumanoidStateType.Freefall and NearestTarget.Character.LeftFoot or NearestTarget.Character[RandomTable(PuppywareSettings.Aiming.Aimbot.Hitboxes)])
                local Prediction = (PuppywareSettings.Aiming.TargetAimSettings.MovementPrediction and TargetPart.CFrame + (TargetPart.Velocity * PuppywareSettings.Aiming.TargetAimSettings.MovementPredictionAmount) or TargetPart.CFrame + (TargetPart.Velocity * PuppywareSettings.Aiming.AimingSettings.GetVelocity))
                
                if PuppywareSettings.Aiming.AimbotSettings.AimAssistType == "Mouse" then
                    local NearestPosition, NearestVisible = CurrentCamera:WorldToScreenPoint(Prediction.Position)
                    local MouseLocation = CurrentCamera:WorldToScreenPoint(Mouse.Hit.Position)
                    local EndPosition = (PuppywareSettings.Aiming.AimbotSettings.SmoothingTracing and Vector2.new((NearestPosition.X - MouseLocation.X) / PuppywareSettings.Aiming.AimbotSettings.SmoothingTracingAmount, (NearestPosition.Y - MouseLocation.Y) / PuppywareSettings.Aiming.AimbotSettings.SmoothingTracingAmount) or Vector2.new((NearestPosition.X - MouseLocation.X) / 1.4, (NearestPosition.Y - MouseLocation.Y) / 1.4))
                    
                    if NearestVisible then
                        mousemoverel(EndPosition.X, EndPosition.Y)
                    end
                elseif PuppywareSettings.Aiming.AimbotSettings.AimAssistType == "Camera" then
                    CurrentCamera.CFrame = CFrame.lookAt(CurrentCamera.CFrame.Position, Prediction.Position)
                end
            end
        end
    else
        AimbotFOV.Visible = false
    end
end)

spawn(function()
    while wait(1 / 16) do
        LagTick = math.clamp(PuppywareModule.LagTick + 1, 0, PuppywareSettings.Blatant.FakeLag.TriggerAmount)
        if Alive(Player) and PuppywareSettings.Blatant.FakeLag.Enabled then
            if LagTick == math.random(1, PuppywareSettings.Blatant.FakeLag.TriggerAmount) then
                Network:SetOutgoingKBPSLimit(9e9)
                PuppywareFolder:ClearAllChildren()
                LagTick = 0
                --[[
                    if Settings.Visuals.PlayerESP.FakeLag.Cham then
                        for i, v in pairs(Player.Character:GetChildren()) do
                            if v:IsA("BasePart") and v.Name ~= "HumanoidRootPart" then
                                local ShadowPart = Instance.new("Part")
                                ShadowPart.CFrame = v.CFrame
                                ShadowPart.Anchored = true
                                ShadowPart.CanCollide = false
                                ShadowPart.Material = Enum.Material.ForceField
                                ShadowPart.Color = Settings.Visuals.PlayerESP.FakeLag.Color
                                ShadowPart.Name = v.Name
                                ShadowPart.Transparency = 0
                                ShadowPart.Size = v.Size
                                ShadowPart.Parent = FakeLagFolder
                            end
                        end
                    end
                ]]
            else
                if PuppywareSettings.Blatant.FakeLag.Enabled then
                    Network:SetOutgoingKBPSLimit(1)
                end
            end
        else
            PuppywareFolder:ClearAllChildren()
            Network:SetOutgoingKBPSLimit(9e9)
        end
    end
end)

local __namecall -- cock ;)
__namecall = hookmetamethod(game, "__namecall", function(self, ...)
    local Args = {...}
    local Method = getnamecallmethod()

    if tostring(self.Name) == "MainEvent" and tostring(Method) == "FireServer" then
        if Args[1] == "TeleportDetect" or Args[1] == "CHECKER_1" or Args[1] == "OneMoreTime" then
            return
        end
    end

    return __namecall(self, ...)
end)

local __index -- <3
__index = hookmetamethod(game, "__index", function(self, key)
    if self == Mouse and (tostring(key) == "Hit" or tostring(key) == "Target") then
        if PuppywareSettings.Aiming.TargetAim.Enabled then
            if PuppywareSettings.Aiming.TargetAim.Target ~= nil and ChanceTable(PuppywareSettings.Aiming.AimingSettings.HitChanceAmount) == "HitPercent" then
                if Players:FindFirstChild(PuppywareSettings.Aiming.TargetAim.Target) ~= nil and (not PuppywareSettings.Aiming.TargetAim.GrabbedCheck or not Grabbing(Players[PuppywareSettings.Aiming.TargetAim.Target])) and (not PuppywareSettings.Aiming.TargetAim.KnockedOutCheck or not Knocked(Players[PuppywareSettings.Aiming.TargetAim.Target])) and (not PuppywareSettings.Aiming.TargetAim.ShowFOV or PuppywareSettings.Aiming.FOV.TargetAimSize > (LocalPlayer.Character.Head.Position - Players[PuppywareSettings.Aiming.TargetAim.Target].Character.Head.Position).Magnitude) and (not PuppywareSettings.Aiming.TargetAim.WallCheck or Visible(Players[PuppywareSettings.Aiming.TargetAim.Target].Character.HumanoidRootPart, LocalPlayer.Character.HumanoidRootPart)) then
                    local TargetPart = (Players[PuppywareSettings.Aiming.TargetAim.Target].Character.Humanoid:GetState() == Enum.HumanoidStateType.Freefall and Players[PuppywareSettings.Aiming.TargetAim.Target].Character.LeftFoot or Players[PuppywareSettings.Aiming.TargetAim.Target].Character[RandomTable(PuppywareSettings.Aiming.TargetAim.Hitboxes)])
                    local Prediction = (PuppywareSettings.Aiming.TargetAimSettings.MovementPrediction and TargetPart.CFrame + (TargetPart.Velocity * PuppywareSettings.Aiming.TargetAimSettings.MovementPredictionAmount) or TargetPart.CFrame + (TargetPart.Velocity * PuppywareSettings.Aiming.AimingSettings.GetVelocity))

                    return (tostring(key) == "Hit" and Prediction or tostring(key) == "Target" and TargetPart)
                end
            end
        else    
            if PuppywareSettings.Aiming.SilentAim.Enabled and ChanceTable(PuppywareSettings.Aiming.AimingSettings.HitChanceAmount) == "HitPercent" then
                local NearestTarget, NearestDistance = NearestType(PuppywareSettings.Aiming.SilentAim.UseNearestDistance and "Distance" or "Mouse")
    
                if NearestTarget and (not PuppywareSettings.Aiming.SilentAim.GrabbedCheck or not Grabbing(NearestTarget)) and (not PuppywareSettings.Aiming.SilentAim.KnockedOutCheck or not Knocked(NearestTarget)) and (not PuppywareSettings.Aiming.SilentAim.ShowFOV or PuppywareSettings.Aiming.FOV.SilentAimSize > NearestDistance) and (not PuppywareSettings.Aiming.SilentAim.WallCheck or IsVisible(NearestTarget.Character.Head.Position, {NearestTarget.Character, LocalPlayer.Character, CurrentCamera}) == true) then
                    local TargetPart = (NearestTarget.Character.Humanoid:GetState() == Enum.HumanoidStateType.Freefall and NearestTarget.Character.LeftFoot or NearestTarget.Character[RandomTable(PuppywareSettings.Aiming.SilentAim.Hitboxes)])
                    local Prediction = (PuppywareSettings.Aiming.TargetAimSettings.MovementPrediction and TargetPart.CFrame + (TargetPart.Velocity * PuppywareSettings.Aiming.TargetAimSettings.MovementPredictionAmount) or TargetPart.CFrame + (TargetPart.Velocity * PuppywareSettings.Aiming.AimingSettings.GetVelocity))
    
                    return (tostring(key) == "Hit" and Prediction or tostring(key) == "Target" and TargetPart)
                end
            end
        end
        
    end

    return __index(self, key)
end)

while wait() do
    if PuppywareSettings.Aiming.TriggerBot.Enabled then
        for i, v in next, Players:GetPlayers() do 
            if Alive(v) then 
                if Mouse.Target:IsDescendantOf(v.Character) then 
                    mouse1press()
                    wait()
                    mouse1release()
                    if PuppywareSettings.Aiming.TriggerBot.Delay then
                        wait(PuppywareSettings.Aiming.TriggerBot.DelayAmount)
                    end
                end 
            end
        end
    end
end 
