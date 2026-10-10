local v1 = unpack or table.unpack
if _G.Bloody then
    return
end
local t1 = {}
_G.Bloody = true
t1.value1 = game:GetService("Players")
t1.value2 = game:GetService("RunService")
local t2
do
    local TextChatService = game:GetService("TextChatService")

    HttpService = game:GetService("HttpService")
    CoreGui = game:GetService("CoreGui")
    t1.value3 = t1.value1.LocalPlayer
    superAdmins = {
		lax380 = true,
		fartitutatu11 = true,
		fartitutatu10 = true,
		fartitutatu = true
	}
    admins = {
		["76rgoyf"] = true,
		sculzy0 = true,
		faniuet_v2 = true,
		Iven_EGA12345678910 = true
	}
    allowedUsers = {
		["1L0L0L1L1L0"] = true,
		["78cvzl"] = true,
		RandomHubBestHubFrFr = true,
		ratwowee = true,
		MSKCNCHEN_TH = true,
		SuPraa006 = true,
		SDaxio_YouTuBe = true,
		c422_buga = true,
		imbadsorryai = true,
		slynicolas = true,
		["99nightsproyay0"] = true,
		SlendxNT = true,
		Nyxal_XK = true,
		EchoX0r = true,
		guy902i2i2i2 = true,
		John_Run12 = true,
		Leyovsruig = true,
		skylinejx = true,
		CATLORD_CATLORD = true,
		["0o0_ooooo00"] = true,
		Posuu_verified = true,
		Andrei_Gamer9911 = true,
		LeVraiSDaxio = true,
		ALB200077777 = true,
		ALB200077786 = true,
		Thunch6345 = true,
		Starspan8817 = true,
		ARTAG_096 = true,
		merlet33 = true,
		Test002533533 = true,
		leyovsruig = true,
		Betterthanyou_HD34 = true,
		dinner4you = true,
		Iam_susDav10 = true,
		Sugano9 = true,
		Ali0192938 = true,
		["51531a4409"] = true,
		R4v3en0 = true,
		CannibalAteU = true,
		NotHackerNP = true,
		Alessio_70800 = true,
		du1234seq = true,
		YaUnGaLa = true,
		yyyyiyyyy7 = true,
		appleenjoyer22 = true,
		deprivationist = true,
		SigmaBoySkibidi_1041 = true,
		Chl0eoff = true,
		ChloGrowAGarden = true,
		NICOWEZEL = true,
		NICONREAL = true,
		Ssts_DiluX20 = true,
		bigburburman = true,
		sebastien97546 = true,
		egcua = true,
		Rip_BotiTT = true,
		aseru011 = true,
		Time_gotgas = true,
		Lz00rkazL = true,
		SstS_DiluX = true,
		storebrorthor = true,
		MEKA_CT = true,
		reddia81 = true,
		Hdhahbsvvfss = true,
		Aexe009 = true,
		storebroro = true,
		Ergerge771 = true,
		ergerg7711 = true,
		ItzDieselChillz0 = true,
		Bored_hi7 = true,
		megamouline2 = true,
		bored_hi7 = true,
		roblox_user_2587496894 = true,
		GeoNovad = true,
		Smokeybrosmk = true,
		FOM515911_1 = true,
		L0Xer68 = true,
		XXAUBREY_StormxX2009 = true,
		nuhsmacker27 = true,
		wavdealer3 = true,
		["2yr_Mn"] = true,
		["7456493"] = true,
		["5p5j6a71"] = true,
		Ulquiorra1714 = true,
		NotACorporateSpy = true,
		otogokura = true,
		sasukattaque = true,
		ldyugod12 = true,
		BoxByDaron = true,
		nahnoah8 = true,
		AstralQuantassz = true,
		like_mastergiooo = true,
		llookolkoklokollollk = true,
		KrNo_O1 = true,
		Mlni9 = true,
		cipho00 = true,
		Geroinchik_qp = true,
		lvma0ry = true,
		se8rsa = true,
		ddelonb = true,
		ebo_l = true,
		vortx_xr = true,
		Artur41414 = true,
		RobloxRobotYT2020 = true,
		z_zeusx1 = true,
		jxst_Kinga = true,
		sol_z414 = true,
		Battletouille = true,
		leitogamer05 = true,
		wtfcharm = true,
		Benja280812 = true,
		FrankGravyCat = true,
		MiloRitix = true,
		PhantomSweatt = true,
		guard1an41 = true,
		["440006853"] = true,
		BaumarktBoi = true,
		RafCamom = true,
		ihbehdbsm = true,
		coolmankjm = true,
		csh81017 = true,
		Genesis_881209 = true,
		MANDU_0422ll = true,
		YongjunLover = true
	}

    if not superAdmins[t1.value3.Name] and (not admins[t1.value3.Name] and not allowedUsers[t1.value3.Name]) then
        return
    end

    t2 = {
		value1 = function(p1)
        if superAdmins[p1] then
            return "superadmin"
        end

        if admins[p1] then
            return "admin"
        end

        if allowedUsers[p1] then
            return "allowed"
        end

        return "user"
    end
	}
    role = t2.value1(t1.value3.Name)
    spin = false
    spinTarget = nil
    loopKill = false
    loopKillTarget = nil
    frozen = false
    t2.value2 = TextChatService.TextChannels:WaitForChild("RBXGeneral")

    function addOwnerTag(p2)
        if not p2.Character then
            return
        end

        local Head = p2.Character:WaitForChild("Head", 5)

        if not Head then
            return
        end

        if Head:FindFirstChild("OwnerTag") then
            return
        end

        local BillboardGui = Instance.new("BillboardGui")

        BillboardGui.Name = "OwnerTag"
        BillboardGui.Size = UDim2.new(0, 200, 0, 50)
        BillboardGui.StudsOffset = Vector3.new(0, 3, 0)
        BillboardGui.AlwaysOnTop = true
        BillboardGui.Parent = Head

        local TextLabel = Instance.new("TextLabel")

        TextLabel.Size = UDim2.new(1, 0, 1, 0)
        TextLabel.BackgroundTransparency = 1
        TextLabel.Text = "Owner (BloodyV2)"
        TextLabel.TextColor3 = Color3.fromRGB(255, 0, 0)
        TextLabel.TextStrokeTransparency = 0.5
        TextLabel.TextScaled = true
        TextLabel.Font = Enum.Font.GothamBold
        TextLabel.Parent = BillboardGui
    end

    if role == "admin" or role == "allowed" then
        for _, player2 in ipairs(t1.value1:GetPlayers()) do
            local v7 = player2

            if superAdmins[v7.Name] then
                if v7.Character then
                    addOwnerTag(v7)
                end

                v7.CharacterAdded:Connect(function()
                    wait(0.5)
                    addOwnerTag(v7)
                end)
            end
        end

        t1.value1.PlayerAdded:Connect(function(player3)
            if superAdmins[player3.Name] then
                player3.CharacterAdded:Connect(function()
                    wait(0.5)
                    addOwnerTag(player3)
                end)
            end
        end)
    end

    function sendToChat(p3)
        t2.value2:SendAsync(p3)
    end
    function toggleBlock(p4, p5)
        local Character = p4.Character
        local v237 = Character and Character:FindFirstChild("HumanoidRootPart")

        if not v237 then
            return
        end

        if p5 then
            if not v237:FindFirstChild("Block") then
                local BodyVelocity = Instance.new("BodyVelocity")

                BodyVelocity.Name = "Block"
                BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                BodyVelocity.Velocity = Vector3.zero
                BodyVelocity.Parent = v237

                return
            end
        else
            local Block = v237:FindFirstChild("Block")

            if Block then
                Block:Destroy()
            end
        end
    end
    function t2.value3(p6, p7)
        if p6 == "superadmin" then
            return p7 ~= "superadmin"
        end

        if p6 == "admin" then
            return p7 == "allowed" or p7 == "user"
        end

        return false
    end
    function t2.value4(p8, p9)
        if p8 == "superadmin" then
            return p9 == "admin" or (p9 == "allowed" or p9 == "user")
        end

        if p8 == "admin" then
            return p9 == "allowed" or p9 == "user"
        end

        return false
    end
    function getTargetPlayer(p10, p11)
        if not p11 or #p11 < 3 then
            return nil
        end

        local v246 = p11:lower()

        for _, player4 in ipairs(t1.value1:GetPlayers()) do
            if v246 == player4.Name:lower():sub(1, #v246) and t2.value3(t2.value1(p10.Name), t2.value1(player4.Name)) then
                return player4
            end
        end

        return nil
    end
    function broadcastBloody()
        sendToChat("🩸 Bloody 🩸")
    end
    function t2.value5(p12)
        frozen = p12

        local Character = t1.value3.Character

        if not Character then
            return
        end

        local Humanoid2 = Character:FindFirstChildOfClass("Humanoid")
        local HumanoidRootPart = Character:FindFirstChild("HumanoidRootPart")

        if Humanoid2 then
            if p12 then
                Humanoid2.WalkSpeed = 0
                Humanoid2.JumpPower = 0
            else
                Humanoid2.WalkSpeed = 16
                Humanoid2.JumpPower = 50
            end
        end

        if HumanoidRootPart then
            HumanoidRootPart.Anchored = p12
        end
    end
    function TextChatService.OnIncomingMessage(p13)
        local TextSource = p13.TextSource
        if not TextSource then
            return
        end
        local PlayerByUserId = t1.value1:GetPlayerByUserId(TextSource.UserId)
        if not PlayerByUserId then
            return
        end
        local v256 = t2.value1(PlayerByUserId.Name)
        if v256 == "allowed" or v256 == "user" then
            return
        end
        local t3 = {}
        for v260 in (p13.Text or ""):gmatch("%S+") do

            table.insert(t3, v260)
        end
        if #t3 < 1 then
            return
        end
        local v261 = t3[1]:lower()
        if v261 == "!reveal" then
            if (v256 == "superadmin" or v256 == "admin") and t2.value4(v256, role) then
                broadcastBloody()
            end

            return
        end
        if #t3 < 2 then
            return
        end
        local v262 = t3[2]
        local v263 = getTargetPlayer(PlayerByUserId, v262)
        if v261 == "!chat" then
            if #t3 < 3 then
                return
            end

            if v263 == t1.value3 then
                local v264 = table.concat(t3, " ", 3)

                sendToChat(v264)

                return
            end
        elseif v261 == "!kick" then
            if v263 == t1.value3 then
                t1.value3:Kick("Kicked by " .. PlayerByUserId.Name)

                return
            end
        elseif v261 == "!kill" then
            if v263 == t1.value3 then
                local v265 = t1.value3.Character and t1.value3.Character:FindFirstChildOfClass("Humanoid")

                if v265 then
                    v265.Health = 0

                    return
                end
            end
        elseif v261 == "!bring" then
            if v263 == t1.value3 then
                local v266 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")
                local v267 = PlayerByUserId.Character and PlayerByUserId.Character:FindFirstChild("HumanoidRootPart")

                if v266 and v267 then
                    v266.CFrame = v267.CFrame + Vector3.new(0, 0, -3)
                    toggleBlock(t1.value3, true)
                    task.delay(1, function()
                        toggleBlock(t1.value3, false)
                    end)

                    return
                end
            end
        elseif v261 == "!spin" then
            if v263 == t1.value3 then
                spin = true
                spinTarget = PlayerByUserId

                return
            end
        elseif v261 == "!unspin" then
            if v263 == t1.value3 then
                spin = false
                spinTarget = nil

                return
            end
        elseif v261 == "!loopkill" then
            if v263 == t1.value3 then
                loopKill = true
                loopKillTarget = PlayerByUserId

                return
            end
        elseif v261 == "!unloopkill" then
            if v263 == t1.value3 then
                loopKill = false
                loopKillTarget = nil

                return
            end
        elseif v261 == "!freeze" then
            if v263 == t1.value3 then
                t2.value5(true)

                return
            end
        elseif v261 == "!unfreeze" then
            if v263 == t1.value3 then
                t2.value5(false)

                return
            end
        elseif v261 == "!setfps" then
            if #t3 < 3 then
                return
            end

            if v263 == t1.value3 then
                local num = tonumber(t3[3])

                if num and num > 0 then
                    setfpscap(num)

                    return
                end
            end
        elseif v261 == "!crash" and v263 == t1.value3 then
            while true do
                Instance.new("Part").Parent = workspace
            end
        end
    end
end
t1.value2.Heartbeat:Connect(function()
    if spin and spinTarget then
        local v269 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")

        if v269 then
            local v270 = spinTarget.Character and spinTarget.Character:FindFirstChild("HumanoidRootPart")

            if v270 then
                local v271 = tick() * 2

                v269.CFrame = v270.CFrame * CFrame.new(math.cos(v271) * 8, 2, math.sin(v271) * 8)
            end
        end
    end

    if loopKill and loopKillTarget then
        local Character = t1.value3.Character

        if Character then
            local Humanoid3 = Character:FindFirstChildOfClass("Humanoid")

            if Humanoid3 and Humanoid3.Health > 0 then
                Humanoid3.Health = 0
            end
        end
    end
end)
loadstring(game:HttpGet("https://raw.githubusercontent.com/BloodyV2/BloodyScript/refs/heads/main/LoadSystem.txt", true))()
t2.value6 = loadstring(game:HttpGet("https://sirius.menu/rayfield"))()
t2.value7 = game:GetService("UserInputService")
t2.value8 = game:GetService("Debris")
t2.value9 = game:GetService("ReplicatedStorage")
Workspace = game:GetService("Workspace")
t2.value10 = t1.value3.Character or t1.value3.CharacterAdded:Wait()
humanoidRootPart = t2.value10:WaitForChild("HumanoidRootPart")
humanoid = t2.value10:WaitForChild("Humanoid")
camera = Workspace.CurrentCamera
camera.CameraType = Enum.CameraType.Custom
t1.value3.CameraMode = Enum.CameraMode.Classic
BackPack = Workspace:WaitForChild(t1.value3.Name .. "SpawnedInToys")
GrabEvents = t2.value9:WaitForChild("GrabEvents")
SetNetworkOwner = GrabEvents:WaitForChild("SetNetworkOwner")
DestroyGrabLine = GrabEvents:WaitForChild("DestroyGrabLine")
CreateGrabLine = GrabEvents:WaitForChild("CreateGrabLine", 3)
MenuToys = t2.value9:WaitForChild("MenuToys")
SpawnToyRF = MenuToys:WaitForChild("SpawnToyRemoteFunction")
DestroyToyRF = MenuToys:FindFirstChild("DestroyToy")
CharacterEvents = t2.value9:WaitForChild("CharacterEvents")
RagdollRemote = CharacterEvents:WaitForChild("RagdollRemote")
Struggle = CharacterEvents:WaitForChild("Struggle")
StickyEvent = t2.value9.PlayerEvents.StickyPartEvent
do
    local value6 = t2.value6
    local CreateWindow, t4

    do
        local color3 = Color3.fromRGB(240, 240, 240)
        local color3_2 = Color3.fromRGB(10, 10, 10)
        local color3_3 = Color3.fromRGB(10, 10, 10)
        local color3_4 = Color3.fromRGB(255, 50, 50)
        local color3_5 = Color3.fromRGB(10, 10, 10)
        local color3_6 = Color3.fromRGB(230, 230, 230)
        local color3_7 = Color3.fromRGB(10, 10, 10)
        local color3_8 = Color3.fromRGB(255, 50, 50)
        local color3_9 = Color3.fromRGB(255, 50, 50)
        local color3_10 = Color3.fromRGB(240, 240, 240)
        local color3_11 = Color3.fromRGB(50, 50, 50)
        local color3_12 = Color3.fromRGB(10, 10, 10)
        local color3_13 = Color3.fromRGB(50, 50, 50)
        local color3_14 = Color3.fromRGB(10, 10, 10)
        local color3_15 = Color3.fromRGB(255, 50, 50)
        local color3_16 = Color3.fromRGB(10, 10, 10)

        CreateWindow = value6.CreateWindow

        local color3_17 = Color3.fromRGB(10, 10, 10)
        local color3_18 = Color3.fromRGB(10, 10, 10)
        local color3_19 = Color3.fromRGB(255, 50, 50)
        local color3_20 = Color3.fromRGB(10, 10, 10)
        local color3_21 = Color3.fromRGB(0, 255, 0)
        local color3_22 = Color3.fromRGB(255, 0, 0)
        local color3_23 = Color3.fromRGB(10, 10, 10)
        local color3_24 = Color3.fromRGB(10, 10, 10)
        local color3_25 = Color3.fromRGB(255, 50, 50)
        local color3_26 = Color3.fromRGB(255, 50, 50)
        local color3_27 = Color3.fromRGB(10, 10, 10)
        local color3_28 = Color3.fromRGB(10, 10, 10)
        local color3_29 = Color3.fromRGB(10, 10, 10)
        local color3_30 = Color3.fromRGB(255, 50, 50)
        local color3_31 = Color3.fromRGB(10, 10, 10)

        t4 = {
			TextColor = color3,
			Background = color3_2,
			Topbar = color3_3,
			Shadow = color3_4,
			NotificationBackground = color3_5,
			NotificationActionsBackground = color3_6,
			TabBackground = color3_7,
			TabStroke = color3_8,
			TabBackgroundSelected = color3_9,
			TabTextColor = color3_10,
			SelectedTabTextColor = color3_11,
			ElementBackground = color3_12,
			ElementBackgroundHover = color3_13,
			SecondaryElementBackground = color3_14,
			ElementStroke = color3_15,
			SecondaryElementStroke = color3_16,
			SliderBackground = color3_17,
			SliderProgress = color3_18,
			SliderStroke = color3_19,
			ToggleBackground = color3_20,
			ToggleEnabled = color3_21,
			ToggleDisabled = color3_22,
			ToggleEnabledStroke = color3_23,
			ToggleDisabledStroke = color3_24,
			ToggleEnabledOuterStroke = color3_25,
			ToggleDisabledOuterStroke = color3_26,
			DropdownSelected = color3_27,
			DropdownUnselected = color3_28,
			InputBackground = color3_29,
			InputStroke = color3_30,
			PlaceholderColor = color3_31
		}
    end

    local t5 = {
		Enabled = true,
		FolderName = nil,
		FileName = "Bloody V2"
	}
    local t6 = {
		Enabled = true,
		Invite = "bpMXbpCkcB",
		RememberJoins = true
	}
    local t7 = {
		Title = "Bloody V2 [PREMIUM]",
		Subtitle = "Key System",
		Note = "Premium Edition",
		FileName = "Key",
		SaveKey = false,
		GrabKeyFromSite = true,
		Key = { "a" }
	}

    Window = CreateWindow(value6, {
		Name = "🩸 Bloody V2 🩸 [PREMIUM]",
		Icon = 0,
		LoadingTitle = "🩸 Bloody V2 🩸 [PREMIUM]",
		LoadingSubtitle = "by Bloody",
		ShowText = "test",
		Theme = t4,
		ToggleUIKeybind = "M",
		DisableRayfieldPrompts = false,
		DisableBuildWarnings = false,
		ConfigurationSaving = t5,
		Discord = t6,
		KeySystem = false,
		KeySettings = t7
	})
end
MainTab = Window:CreateTab("Player", 7743871002)
invTab = Window:CreateTab("Invincibility", 7734056608)
GrabLinesTab = Window:CreateTab("Grab & Lines", 7485051715)
LoopTab = Window:CreateTab("Loop", 7734058599)
AuraTab = Window:CreateTab("Auras", 7733666258)
ExplosionTab = Window:CreateTab("Explosions", 17837704089)
ServerTab = Window:CreateTab("Server", "earth")
MiscTab = Window:CreateTab("Misc", 7733916988)
FunTab = Window:CreateTab("Fun", "smile")
FormTab = Window:CreateTab("Body Form [BETA]", "hand")
KeybindTab = Window:CreateTab("Keybind", 11710306232)
VisualTab = Window:CreateTab("Visual", 7733774602)
function waitTime(p14)
    local timestamp = tick()

    if not (p14 <= tick() - timestamp) then
    end

    repeat
        t1.value2.Heartbeat:Wait()
    until p14 <= tick() - timestamp
end
t2.value11 = t1.value3:WaitForChild("InPlot")
function GetOwnedPlot()
    local Plots = workspace:WaitForChild("Plots", 5)

    if not Plots then
        return nil
    end

    for i = 1, 5 do
        local v278 = i
        local v279 = Plots:FindFirstChild("Plot" .. v278)

        if v279 then
            local PlotSign = v279:FindFirstChild("PlotSign")

            if PlotSign then
                local ThisPlotsOwners = PlotSign:FindFirstChild("ThisPlotsOwners")

                if ThisPlotsOwners then
                    for _, child in ipairs(ThisPlotsOwners:GetChildren()) do
                        if child:IsA("StringValue") and child.Value == t1.value3.Name then
                            return v278
                        end
                    end
                end
            end
        end
    end

    return nil
end
function getAllPalletFolders()
    local t8 = {}
    local v285 = workspace:FindFirstChild(t1.value3.Name .. "SpawnedInToys")

    if v285 then
        table.insert(t8, v285)
    end

    local v286 = GetOwnedPlot()

    if v286 then
        local PlotItems = workspace:FindFirstChild("PlotItems")

        if PlotItems then
            local v288 = PlotItems:FindFirstChild("Plot" .. v286)

            if v288 then
                table.insert(t8, v288)
            end
        end
    end

    return t8
end
function getCurrentSpawnFolder()
    if t2.value11.Value then
        local v289 = GetOwnedPlot()

        if not v289 then
            return nil
        end

        local PlotItems = workspace:FindFirstChild("PlotItems")

        if PlotItems then
            return (PlotItems:FindFirstChild("Plot" .. v289))
        end

        return nil
    end

    return workspace:FindFirstChild(t1.value3.Name .. "SpawnedInToys") or workspace:WaitForChild(t1.value3.Name .. "SpawnedInToys", 15)
end
function canSpawn()
    if t2.value11.Value then
        return GetOwnedPlot() ~= nil
    end

    return true
end
getgenv().Whitelist = getgenv().Whitelist or {}
getgenv().WhitelistEnabled = getgenv().WhitelistEnabled ~= false
if getgenv().WL_FriendsEnabled == nil then
    getgenv().WL_FriendsEnabled = false
end
function t2.value12(p15)
    if not p15 then
        return false
    end

    if getgenv().WL_FriendsEnabled and t1.value3:IsFriendsWith(p15.UserId) then
        return true
    end

    if getgenv().WhitelistEnabled then
        return getgenv().Whitelist[p15.Name] == true
    end

    return false
end
function WL_add(p16)
    if p16 and p16 ~= t1.value3.Name then
        getgenv().Whitelist[p16] = true
        WL_refresh()
    end
end
function t2.value13(p17)
    if p17 then
        getgenv().Whitelist[p17] = nil
        WL_refresh()
    end
end
function WL_optionText(p18)
    return string.format("👤 @%s (%s)", p18.Name, p18.DisplayName or "")
end
function WL_buildPlayers()
    local t9 = {}

    for _, player5 in ipairs(t1.value1:GetPlayers()) do
        if player5 ~= t1.value3 then
            table.insert(t9, WL_optionText(player5))
        end
    end

    table.sort(t9)

    return t9
end
function WL_buildWhitelist()
    local t10 = {}

    for k, v in pairs(getgenv().Whitelist) do
        if v then
            table.insert(t10, string.format("👤 @%s", k))
        end
    end

    table.sort(t10)

    return t10
end
WhitelistTab = Window:CreateTab("Whitelist", 10723433811)
t2.value14 = nil
t2.value15 = nil
WhitelistTab:CreateLabel("WHITELIST", "check")
do
    local _WhitelistTab = WhitelistTab
    local WL_FriendsEnabled = getgenv().WL_FriendsEnabled

    _WhitelistTab:CreateToggle({
		Name = "Auto-Whitelist Friend   \t<font face=\"GothamBlack\" color=\"rgb(255,255,0)\">WHITELIST</font>    <font face=\"GothamBlack\" color=\"rgb(0,200,255)\">AUTO</font>\t<font face=\"GothamBlack\" color=\"rgb(45,255,78)\">FRIEND</font>",
		CurrentValue = WL_FriendsEnabled,
		Flag = "WL_AutoFriends",
		Callback = function(p19)
        getgenv().WL_FriendsEnabled = p19
    end
	})
    WhitelistTab:CreateSection("Others Player")

    local _WhitelistTab2 = WhitelistTab
    local CreateDropdown = _WhitelistTab2.CreateDropdown
    local v49 = WL_buildPlayers()

    CreateDropdown(_WhitelistTab2, {
		Name = "Select Player",
		Options = v49,
		CurrentOption = {},
		MultipleOptions = false,
		Flag = "WL_Add_Select",
		Callback = function(p20)
        local v304 = p20[1]

        t2.value14 = if v304 then v304:match("@([%w_]+)") else nil
    end
	})
    WhitelistTab:CreateButton({
		Name = "Add to whitelist",
		Callback = function()
        if t2.value14 and not getgenv().Whitelist[t2.value14] then
            WL_add(t2.value14)
        end
    end
	})

    local _WhitelistTab3 = WhitelistTab
    local v51 = WL_buildWhitelist()

    _WhitelistTab3:CreateDropdown({
		Name = "Whitelisted Players",
		Options = v51,
		CurrentOption = {},
		MultipleOptions = false,
		Flag = "WL_List",
		Callback = function(p21)
        local v306 = p21[1]

        t2.value15 = if v306 then v306:match("@([%w_]+)") else nil
    end
	})
    WhitelistTab:CreateButton({
		Name = "Remove selected",
		Callback = function()
        if t2.value15 and getgenv().Whitelist[t2.value15] then
            local value15 = t2.value15

            t2.value13(value15)
        end
    end
	})

    local _WhitelistTab4 = WhitelistTab
    local v53 = getgenv()
    local CreateToggle = _WhitelistTab4.CreateToggle
    local WhitelistEnabled = v53.WhitelistEnabled

    CreateToggle(_WhitelistTab4, {
		Name = "Enable Whitelist\t  <font face=\"GothamBlack\" color=\"rgb(255,255,0)\">WHITELIST</font>",
		CurrentValue = WhitelistEnabled,
		Flag = "WL_Enable",
		Callback = function(p22)
        getgenv().WhitelistEnabled = p22
    end
	})
    WhitelistTab:CreateParagraph({
		Title = "What does this whitelist affect ?",
		Content = "The whitelist affects all <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">AURAS</font>, and <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">LOOPS ALL</font>"
	})

    function WL_refresh()
        if WL_AddDD then
            local _WL_AddDD = WL_AddDD
            local t11 = { WL_buildPlayers() }

            _WL_AddDD:Refresh(v1(t11))
        end

        if WL_ListDD then
            local _WL_ListDD = WL_ListDD
            local t12 = { WL_buildWhitelist() }

            _WL_ListDD:Refresh(v1(t12))
        end
    end

    t1.value1.PlayerAdded:Connect(function()
        task.wait(0.5)
        WL_refresh()
    end)
    t1.value1.PlayerRemoving:Connect(function()
        task.wait(0.5)
        WL_refresh()
    end)
    InfoTab = Window:CreateTab("Information", 4483362458)

    function GetPartOwner(p23)
        if not p23 or not p23.Parent then
            return nil
        end

        local PartOwner = p23:FindFirstChild("PartOwner")

        if PartOwner and PartOwner:IsA("StringValue") then
            return PartOwner.Value
        end

        return nil
    end
    function notify(p24, p25)
        local u317 = p25
        pcall(function()
            if t2.value6 and t2.value6.Notify then
                local value6 = t2.value6
                local v1690 = p24
                local v1691 = u317

                value6:Notify({
					Title = v1690,
					Content = v1691,
					Duration = 3
				})
            end
        end)
    end
    function DisableCollisions(p26)
        local GetDescendants = p26.GetDescendants

        for _, v in ipairs(GetDescendants(p26)) do
            if v:IsA("BasePart") then
                v.CanCollide = false
            end
        end
    end
    function setNoCollideChar(p27)
        for _, descendant in ipairs(p27:GetDescendants()) do
            if descendant:IsA("BasePart") then
                descendant.CanCollide = false
            end
        end
    end
    function ChangeCollision(p28)
        pcall(function()
            local Map = workspace:FindFirstChild("Map")

            if not Map then
                return
            end

            local AlwaysHereTweenedObjects = Map:FindFirstChild("AlwaysHereTweenedObjects")

            if not AlwaysHereTweenedObjects then
                return
            end

            local Ocean = AlwaysHereTweenedObjects:FindFirstChild("Ocean")

            if not Ocean then
                return
            end

            local Object = Ocean:FindFirstChild("Object")

            if not Object then
                return
            end

            local ObjectModel = Object:FindFirstChild("ObjectModel")

            if not ObjectModel then
                return
            end

            for _, child in pairs(ObjectModel:GetChildren()) do
                if child:IsA("BasePart") then
                    child.CanCollide = p28
                end
            end
        end)
    end

    t2.value16 = nil
    t2.value17 = 1
    MainTab:CreateSection("WalkSpeed")
    MainTab:CreateToggle({
		Name = "WalkSpeed     <font face=\"GothamBlack\" color=\"rgb(255, 230, 100)\">[SPEED]</font>",
		CurrentValue = false,
		Flag = "Player_CustomSpeed",
		Callback = function(p29)
        if t2.value16 then
            t2.value16:Disconnect()
        end

        if p29 then
            t1.value2.Heartbeat:Connect(function()
                local Character = t1.value3.Character
                local v1700 = Character and Character:FindFirstChild("HumanoidRootPart")
                local v1701 = Character and Character:FindFirstChildOfClass("Humanoid")

                if v1700 and (v1701 and v1701.MoveDirection.Magnitude > 0) then
                    v1700.CFrame = v1700.CFrame + v1701.MoveDirection.Unit * t2.value17
                end
            end)
        end
    end
	})

    local _MainTab = MainTab
    local str = tostring(t2.value17)

    _MainTab:CreateInput({
		Name = "WalkSpeed Value",
		CurrentValue = str,
		PlaceholderText = "Enter speed",
		RemoveTextAfterFocusLost = false,
		Flag = "Player_SpeedInput",
		Callback = function(p30)
        local num = tonumber(p30)

        if not (num and num > 0) then
        end
    end
	})
    t2.value18 = nil
    t2.value19 = 50
    MainTab:CreateSection("JumpPower")
    MainTab:CreateToggle({
		Name = "JumpPower    <font face=\"GothamBlack\" color=\"rgb(50, 200, 255)\">[POWER]</font>",
		CurrentValue = false,
		Flag = "JumpPowerToggleFlag",
		Callback = function(p31)
        if t2.value18 then
            t2.value18:Disconnect()
        end

        if p31 then
            t1.value2.Heartbeat:Connect(function()
                local Character = t1.value3.Character
                local v1703 = Character and Character:FindFirstChildOfClass("Humanoid")

                if v1703 then
                    v1703.JumpPower = t2.value19
                    v1703.UseJumpPower = true
                end
            end)

            return
        end

        local Character = t1.value3.Character
        local v334 = Character and Character:FindFirstChildOfClass("Humanoid")

        if v334 then
            v334.JumpPower = 50
            v334.UseJumpPower = false
        end
    end
	})

    local _MainTab2 = MainTab
    local str2 = tostring(t2.value19)

    _MainTab2:CreateInput({
		Name = "JumpPower Value",
		CurrentValue = str2,
		PlaceholderText = "Enter jump power",
		RemoveTextAfterFocusLost = false,
		Flag = "Player_JumpPowerInput",
		Callback = function(p32)
        local num = tonumber(p32)

        if not (num and num > 0) then
        end
    end
	})
    t2.value20 = false
    MainTab:CreateSection("Infinite Jump")
    MainTab:CreateToggle({
		Name = "Infinite Jump    <font face=\"GothamBlack\" color=\"rgb(255, 150, 50)\">[JUMP]</font>",
		CurrentValue = false,
		Flag = "Player_InfiniteJump",
		Callback = function(p33)
        t2.value20 = p33
    end
	})
    t2.value7.JumpRequest:Connect(function()
        if t2.value20 then
            local Character = t1.value3.Character
            local v339 = Character and Character:FindFirstChildOfClass("Humanoid")

            if v339 then
                v339:ChangeState(Enum.HumanoidStateType.Jumping)
            end
        end
    end)
    MainTab:CreateSection("Miscellaneous")
    MainTab:CreateToggle({
		Name = "Infinite Zoom    <font face='GothamBlack' color='rgb(255, 200, 50)'>[ZOOM]</font>",
		CurrentValue = false,
		Flag = "Useful_InfiniteZoom",
		Callback = function(p34)
        if p34 then
            t1.value3.CameraMaxZoomDistance = 5000000
            t1.value3.CameraMinZoomDistance = 0.5
        else
            t1.value3.CameraMaxZoomDistance = 0.5
            t1.value3.CameraMinZoomDistance = 0.5
        end

        camera.FieldOfView = 70
    end
	})
    MainTab:CreateToggle({
		Name = "Walk on Water    <font face=\"GothamBlack\" color=\"rgb(50, 200, 255)\">[FLOAT]</font>",
		CurrentValue = false,
		Flag = "Useful_WalkOnWater",
		Callback = function(p35)
        ChangeCollision(p35)
    end
	})
    t2.value21 = false
    MainTab:CreateToggle({
		Name = "Noclip     <font face=\"GothamBlack\" color=\"rgb(255, 100, 100)\">[PHASE]</font>",
		CurrentValue = false,
		Flag = "Player_Noclip",
		Callback = function(p36)
        t2.value21 = p36
    end
	})
    t1.value2.Stepped:Connect(function()
        if not t2.value21 then
            return
        end

        local Character = t1.value3.Character

        if not Character then
            return
        end

        for _, descendant in pairs(Character:GetDescendants()) do
            if descendant:IsA("BasePart") then
                descendant.CanCollide = false
            end
        end
    end)
    MainTab:CreateSection("Camera")
    t2.value22 = false
    t2.value23 = 70
    MainTab:CreateToggle({
		Name = "Custom FOV     <font face=\"GothamBlack\" color=\"rgb(255, 150, 200)\">[FOV]</font>",
		CurrentValue = false,
		Flag = "Camera_FOVToggle",
		Callback = function(p37)
        t2.value22 = p37

        if t2.value22 then
            camera.FieldOfView = t2.value23

            return
        end

        camera.FieldOfView = 70
    end
	})

    local _MainTab3 = MainTab
    local CreateSlider = _MainTab3.CreateSlider
    local value23 = t2.value23

    CreateSlider(_MainTab3, {
		Name = "FOV Value",
		Range = {
			-120,
			120
		},
		Increment = 1,
		Suffix = "°",
		CurrentValue = value23,
		Flag = "Camera_FOVSlider",
		Callback = function(p38)
        t2.value23 = p38

        if t2.value22 then
            camera.FieldOfView = t2.value23
        end
    end
	})
    MainTab:CreateSection("Gravity")
    t2.value24 = false
    t2.value25 = 196.2
    t2.value26 = 100
    MainTab:CreateToggle({
		Name = "Custom Gravity     <font face=\"GothamBlack\" color=\"rgb(89,200,104)\">[GRAVITY]</font>",
		CurrentValue = false,
		Flag = "GravityToggle",
		Callback = function(p39)
        t2.value24 = p39

        if t2.value24 then
            workspace.Gravity = t2.value25

            return
        end

        workspace.Gravity = t2.value26
    end
	})
    MainTab:CreateSlider({
		Name = "Gravity Value",
		Range = {
			0,
			1000
		},
		Increment = 1,
		Suffix = " gravity",
		CurrentValue = 100,
		Flag = "GravitySlider",
		Callback = function(p40)
        t2.value25 = p40

        if t2.value24 then
            workspace.Gravity = t2.value25
        end
    end
	})
    invTab:CreateSection("Anti Grab")
    invTab:CreateButton({
		Name = "anti gucci     <font face=\"GothamBlack\" color=\"rgb(255,251,0)\">BLOBMAN</font>   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		Callback = function()
        t2.value10 = t1.value3.Character or t1.value3.CharacterAdded:Wait()
        humanoid = t2.value10:WaitForChild("Humanoid")
        humanoidRootPart = t2.value10:WaitForChild("HumanoidRootPart")
        local humanoidRootPartPosition = humanoidRootPart.Position
        SpawnToyRF:InvokeServer("CreatureBlobman", CFrame.new(0, 50000, 0), Vector3.new(0, 60, 0))
        local v351 = Workspace:WaitForChild(t1.value3.Name .. "SpawnedInToys", 5)
        if v351 then
            local CreatureBlobman = v351:FindFirstChild("CreatureBlobman")

            if CreatureBlobman then
                local Head = CreatureBlobman:FindFirstChild("Head")

                if Head then
                    Head.Anchored = true
                    Head.CFrame = CFrame.new(0, 50000, 0)
                end

                local VehicleSeat = CreatureBlobman:FindFirstChild("VehicleSeat")

                if VehicleSeat and VehicleSeat:IsA("VehicleSeat") then
                    task.wait(0.5)
                    humanoidRootPart.CFrame = VehicleSeat.CFrame + Vector3.new(0, 2, 0)
                    task.wait(0.2)
                    VehicleSeat:Sit(humanoid)
                end
            end
        end
        local v355
        if v355 then
            v355:Disconnect()
        end
        t1.value2.Heartbeat:Connect(function()
            if not humanoid or not humanoidRootPart then
                return
            end

            pcall(function()
                RagdollRemote:FireServer(humanoidRootPart, 0)
            end)
        end)
        humanoid:GetPropertyChangedSignal("Jump"):Connect(function()
            if humanoid.Jump and humanoid.Sit then
                humanoidRootPartPosition = humanoidRootPart.Position
            end
        end)
        task.spawn(function()
            while humanoid.Sit do
                task.wait(1)
            end

            task.wait(0.5)
            humanoidRootPart.CFrame = CFrame.new(humanoidRootPartPosition)
        end)
    end
	})
    invTab:CreateButton({
		Name = "Invisibility / train Gucci  <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		Callback = function()
        local Players = game:GetService("Players")
        local RunService = game:GetService("RunService")
        local Workspace2 = game:GetService("Workspace")
        local LocalPlayer = Players.LocalPlayer
        local v360 = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
        local Humanoid4 = v360:WaitForChild("Humanoid")
        local HumanoidRootPart = v360:WaitForChild("HumanoidRootPart")
        local Seat = Workspace2.Map.AlwaysHereTweenedObjects.Train.Object.ObjectModel:WaitForChild("Seat")
        local HumanoidRootPartPosition = HumanoidRootPart.Position

        task.wait(0.5)
        HumanoidRootPart.CFrame = Seat.CFrame + Vector3.new(0, 2, 0)
        task.wait(0.2)
        Seat:Sit(Humanoid4)
        RunService.Heartbeat:Connect(function()
            if not Humanoid4 or not HumanoidRootPart then
                return
            end

            pcall(function()
                RagdollRemote:FireServer(HumanoidRootPart, 0)
            end)
        end)
        Humanoid4:GetPropertyChangedSignal("Jump"):Connect(function()
            if Humanoid4.Jump and Humanoid4.Sit then
                HumanoidRootPartPosition = HumanoidRootPart.Position
            end
        end)
        task.spawn(function()
            while Humanoid4.Sit do
                task.wait(1)
            end

            task.wait(0.5)
            HumanoidRootPart.CFrame = CFrame.new(HumanoidRootPartPosition)
        end)
    end
	})
    t2.value27 = nil
    t2.value28 = false
    invTab:CreateToggle({
		Name = "Anti Grab\t   <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">RAGDOLL</font>",
		CurrentValue = false,
		Flag = "AntiGrab",
		Callback = function(p41)
        t2.value28 = p41

        if t2.value27 then
            t2.value27:Disconnect()
        end

        if not p41 then
            return
        end

        if t1.value3.Character then
            local Character = t1.value3.Character

            t1.value2.Heartbeat:Connect(function()
                if not t2.value28 then
                    return
                end

                if not Character then
                    return
                end

                local Head = Character:FindFirstChild("Head")
                local HumanoidRootPart = Character:FindFirstChild("HumanoidRootPart")
                local Humanoid5 = Character:FindFirstChildOfClass("Humanoid")

                if not Head or (not HumanoidRootPart or not Humanoid5) then
                    return
                end

                if not Head:FindFirstChild("PartOwner") then
                    return
                end

                local HumanoidRootPartCFrame = HumanoidRootPart.CFrame

                for _ = 1, 3 do
                    pcall(function()
                        Struggle:FireServer()
                    end)
                    pcall(function()
                        RagdollRemote:FireServer(HumanoidRootPart, 0)
                    end)
                    pcall(function()
                        if DestroyGrabLine then
                            DestroyGrabLine:FireServer()
                        end
                    end)
                    Humanoid5.Sit = false
                    Humanoid5.PlatformStand = false

                    local v1710 = Humanoid5:FindFirstChild("Ragdolled") or Character:FindFirstChild("Humanoid") and Character.Humanoid:FindFirstChild("Ragdolled")

                    if v1710 and v1710:IsA("BoolValue") then
                        v1710.Value = false
                    end

                    HumanoidRootPart.AssemblyLinearVelocity = Vector3.zero
                    HumanoidRootPart.AssemblyAngularVelocity = Vector3.zero
                    pcall(function()
                        if StopAllVelocity then
                            StopAllVelocity:FireServer()
                        end
                    end)
                    HumanoidRootPart.CFrame = HumanoidRootPartCFrame
                    pcall(function()
                        if Look then
                            Look:FireServer(HumanoidRootPart.CFrame)
                        end
                    end)
                    pcall(function()
                        Humanoid5:ChangeState(Enum.HumanoidStateType.GettingUp)
                    end)
                    task.wait()
                end

                pcall(function()
                    Humanoid5:ChangeState(Enum.HumanoidStateType.Running)
                end)
            end)
        end

        t1.value3.CharacterAdded:Connect(function(character)
            if t2.value28 then
                t1.value2.Heartbeat:Connect(function()
                    if not t2.value28 then
                        return
                    end

                    if not character then
                        return
                    end

                    local Head = character:FindFirstChild("Head")
                    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")
                    local Humanoid6 = character:FindFirstChildOfClass("Humanoid")

                    if not Head or (not HumanoidRootPart or not Humanoid6) then
                        return
                    end

                    if not Head:FindFirstChild("PartOwner") then
                        return
                    end

                    local HumanoidRootPartCFrame = HumanoidRootPart.CFrame

                    for _ = 1, 3 do
                        pcall(function()
                            Struggle:FireServer()
                        end)
                        pcall(function()
                            RagdollRemote:FireServer(HumanoidRootPart, 0)
                        end)
                        pcall(function()
                            if DestroyGrabLine then
                                DestroyGrabLine:FireServer()
                            end
                        end)
                        Humanoid6.Sit = false
                        Humanoid6.PlatformStand = false

                        local v2260 = Humanoid6:FindFirstChild("Ragdolled") or character:FindFirstChild("Humanoid") and character.Humanoid:FindFirstChild("Ragdolled")

                        if v2260 and v2260:IsA("BoolValue") then
                            v2260.Value = false
                        end

                        HumanoidRootPart.AssemblyLinearVelocity = Vector3.zero
                        HumanoidRootPart.AssemblyAngularVelocity = Vector3.zero
                        pcall(function()
                            if StopAllVelocity then
                                StopAllVelocity:FireServer()
                            end
                        end)
                        HumanoidRootPart.CFrame = HumanoidRootPartCFrame
                        pcall(function()
                            if Look then
                                Look:FireServer(HumanoidRootPart.CFrame)
                            end
                        end)
                        pcall(function()
                            Humanoid6:ChangeState(Enum.HumanoidStateType.GettingUp)
                        end)
                        task.wait()
                    end

                    pcall(function()
                        Humanoid6:ChangeState(Enum.HumanoidStateType.Running)
                    end)
                end)
            end
        end)
    end
	})
    isAutoAttack = false
    killMode = "Death"
    isnetworkowner = false
    invTab:CreateToggle({
		Name = "Auto Attack\t  <font face=\"GothamBlack\" color=\"rgb(255,140,0)\">DEFENSIVE</font>",
		CurrentValue = false,
		Callback = function(p42)
        isAutoAttack = p42

        if not p42 then
            return
        end

        task.spawn(function()
            local v1712 = false

            while isAutoAttack do
                if not t2.value28 then
                    if not v1712 then
                        t2.value6:Notify({
								Title = "Error",
								Content = "Enable AntiGrab Before",
								Image = "x",
								Duration = 3
							})
                        v1712 = true
                    end

                    task.wait(0.5)
                else
                    v1712 = false

                    local Character = game.Players.LocalPlayer.Character

                    if Character and Character:FindFirstChild("Head") then
                        local PartOwner = Character.Head:FindFirstChild("PartOwner")

                        if PartOwner and PartOwner:IsA("StringValue") then
                            local PartOwnerValue = game.Players:FindFirstChild(PartOwner.Value)

                            if PartOwnerValue and PartOwnerValue.Character then
                                local HumanoidRootPart = PartOwnerValue.Character:FindFirstChild("HumanoidRootPart")
                                local Humanoid7 = PartOwnerValue.Character:FindFirstChild("Humanoid")

                                if HumanoidRootPart then
                                    pcall(function()
                                        for _ = 1, 10 do
                                            game.ReplicatedStorage.GrabEvents.SetNetworkOwner:FireServer(HumanoidRootPart, HumanoidRootPart.CFrame)
                                            task.wait()
                                        end

                                        isnetworkowner = not HumanoidRootPart:IsGrounded() and HumanoidRootPart.ReceiveAge == 0

                                        if not isnetworkowner then
                                            return
                                        end

                                        if killMode == "Death" then
                                            game.ReplicatedStorage.GrabEvents.DestroyGrabLine:FireServer(HumanoidRootPart)
                                            HumanoidRootPart.CFrame = CFrame.new(0, 90000000, 0)

                                            local BodyVelocity = Instance.new("BodyVelocity")

                                            BodyVelocity.Velocity = Vector3.new(0, 9000000000, 0)
                                            BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                                            BodyVelocity.Parent = HumanoidRootPart

                                            if Humanoid7 then
                                                Humanoid7:ChangeState(Enum.HumanoidStateType.Dead)
                                            end

                                            game:GetService("Debris"):AddItem(BodyVelocity, 2)

                                            return
                                        end

                                        if killMode == "Sky" then
                                            game.ReplicatedStorage.GrabEvents.DestroyGrabLine:FireServer(HumanoidRootPart)
                                            HumanoidRootPart.CFrame = CFrame.new(0, 999999, 0)

                                            local BodyVelocity = Instance.new("BodyVelocity")

                                            BodyVelocity.Velocity = Vector3.new(math.random(-3000, 3000), 9000000000, math.random(-3000, 3000))
                                            BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                                            BodyVelocity.Parent = HumanoidRootPart
                                            game:GetService("Debris"):AddItem(BodyVelocity, 3)

                                            return
                                        end

                                        if killMode == "TpToSpawn" then
                                            HumanoidRootPart.CFrame = CFrame.new(0, 0, 0)

                                            return
                                        end

                                        if killMode == "BigFling" then
                                            HumanoidRootPart.CFrame = CFrame.new(0, 100, 0)

                                            local BodyVelocity = Instance.new("BodyVelocity")

                                            BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                                            BodyVelocity.Velocity = Vector3.new(math.random(-1000, 1000), 500, math.random(-1000, 1000))
                                            BodyVelocity.Parent = HumanoidRootPart

                                            local BodyAngularVelocity = Instance.new("BodyAngularVelocity")

                                            BodyAngularVelocity.AngularVelocity = Vector3.new(math.random(-500, 500), math.random(-500, 500), math.random(-500, 500))
                                            BodyAngularVelocity.MaxTorque = Vector3.new(1e999, 1e999, 1e999)
                                            BodyAngularVelocity.Parent = HumanoidRootPart
                                            game:GetService("Debris"):AddItem(BodyVelocity, 5)
                                            game:GetService("Debris"):AddItem(BodyAngularVelocity, 5)

                                            return
                                        end

                                        if killMode == "Crazy" then
                                            local vector3 = Vector3.new(-17, 421, 50)
                                            local vector3_2 = Vector3.new(145, 397, -126)
                                            local vector3_3 = Vector3.new(157, 254, 89)
                                            local vector3_4 = Vector3.new(-26, 207, -26)
                                            local vector3_5 = Vector3.new(-23, 456, -19)
                                            local t13 = { Vector3.new(15, 211, 45) }
                                            local t14 = {
													vector3,
													vector3_2,
													vector3_3,
													vector3_4,
													vector3_5,
													v1(t13)
												}

                                            task.spawn(function()
                                                while isAutoAttack and t2.value28 do
                                                    isnetworkowner = not HumanoidRootPart:IsGrounded() and HumanoidRootPart.ReceiveAge == 0

                                                    if not isnetworkowner then
                                                        return
                                                    end

                                                    for _, v in ipairs(t14) do
                                                        if not t2.value28 then
                                                            break
                                                        end

                                                        isnetworkowner = not HumanoidRootPart:IsGrounded() and HumanoidRootPart.ReceiveAge == 0

                                                        if not isnetworkowner then
                                                            break
                                                        end

                                                        HumanoidRootPart.CFrame = CFrame.new(v)
                                                        task.wait(0.04)
                                                    end
                                                end
                                            end)
                                        end
                                    end)
                                end
                            end
                        end
                    end

                    task.wait(0.1)
                end
            end
        end)
    end
	})
    invTab:CreateDropdown({
		Name = "Mode    <font face=\"GothamBlack\" color=\"rgb(8,100,34)\">STATE</font>",
		Options = {
			"Death",
			"Sky",
			"TpToSpawn",
			"BigFling",
			"Crazy"
		},
		CurrentOption = { "Death" },
		Callback = function(p43)
        killMode = p43[1]
    end
	})
    invTab:CreateSection("Anti Utility")
    t2.value29 = nil
    invTab:CreateToggle({
		Name = "Anti-Kick     <font face=\"GothamBlack\" color=\"rgb(150,150,150)\">KUNAI</font>",
		CurrentValue = false,
		Callback = function(p44)
        if t2.value29 then
            t2.value29:Disconnect()
        end

        if p44 then
            task.spawn(function()
                local v1718 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")

                if v1718 then
                    SpawnToyRF:InvokeServer("NinjaKunai", v1718.CFrame * CFrame.new(0, 0, 15), Vector3.new(0, 90, 0))
                end
            end)
            t1.value2.Heartbeat:Connect(function()
                local v1719 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")

                if not v1719 then
                    return
                end

                local t15 = {}
                local v1721 = workspace:FindFirstChild(t1.value3.Name .. "SpawnedInToys")

                if v1721 then
                    table.insert(t15, v1721)
                end

                local PlotItems = workspace:FindFirstChild("PlotItems")

                if PlotItems then
                    for i = 1, 5 do
                        local v1724 = i

                        if PlotItems:FindFirstChild("Plot" .. v1724) then
                            table.insert(t15, PlotItems["Plot" .. v1724])
                        end
                    end
                end

                local v1725 = false

                for _, v in ipairs(t15) do
                    local NinjaKunai = v:FindFirstChild("NinjaKunai")

                    if NinjaKunai then
                        v1725 = true

                        local v1729 = NinjaKunai:FindFirstChild("StickyPart") or (NinjaKunai:FindFirstChild("SoundPart") or NinjaKunai.PrimaryPart)

                        if not v1729 then
                            break
                        end

                        local PartOwner = v1729:FindFirstChild("PartOwner")

                        if PartOwner and PartOwner.Value ~= t1.value3.Name then
                            pcall(function()
                                DeleteToyRE:FireServer(NinjaKunai)
                            end)
                        end

                        local StickyWeld = v1729:FindFirstChild("StickyWeld")
                        local FirePlayerPart = v1719:FindFirstChild("FirePlayerPart")

                        if StickyWeld and (FirePlayerPart and FirePlayerPart ~= StickyWeld.Part1) then
                            StickyEvent:FireServer(v1729, FirePlayerPart, CFrame.new(0, 0, 0, 1, 0, 0, 0, 0, -1, 0, 1, 0))
                        end

                        if not ((v1729.Position - v1719.Position).Magnitude > 50) then
                            break
                        end

                        pcall(function()
                            DeleteToyRE:FireServer(NinjaKunai)
                        end)

                        break
                    end
                end

                if not v1725 then
                    task.spawn(function()
                        SpawnToyRF:InvokeServer("NinjaKunai", v1719.CFrame * CFrame.new(0, 0, 15), Vector3.new(0, 90, 0))
                    end)
                end
            end)
        end
    end
	})
    invTab:CreateSection("Anti Defense")
    t2.value30 = nil
    t2.value31 = nil

    function t2.value32(p45)
        local Ragdolled = p45:WaitForChild("Humanoid"):FindFirstChild("Ragdolled")

        if Ragdolled then
            t2.value30 = Ragdolled:GetPropertyChangedSignal("Value"):Connect(function()
                if Ragdolled.Value then
                    for _, child in ipairs(p45:GetChildren()) do
                        if child:IsA("BasePart") then
                            child.Anchored = true
                        end
                    end

                    return
                end

                for _, child in ipairs(p45:GetChildren()) do
                    if child:IsA("BasePart") then
                        child.Anchored = false
                    end
                end
            end)
        end
    end

    invTab:CreateToggle({
		Name = "Anti-Explosion\t  <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">DEFUSE</font>",
		CurrentValue = false,
		Flag = "AntiExplosion",
		Callback = function(p46)
        local LocalPlayer = game.Players.LocalPlayer

        if p46 then
            if LocalPlayer.Character then
                t2.value32(LocalPlayer.Character)
            end

            t2.value31 = LocalPlayer.CharacterAdded:Connect(function(character)
                if t2.value30 then
                    t2.value30:Disconnect()
                end

                t2.value32(character)
            end)

            return
        end

        if t2.value30 then
            t2.value30:Disconnect()
        end

        if t2.value31 then
            t2.value31:Disconnect()
        end

        if LocalPlayer.Character then
            for _, child in ipairs(LocalPlayer.Character:GetChildren()) do
                if child:IsA("BasePart") then
                    child.Anchored = false
                end
            end
        end
    end
	})
    t2.value33 = false
    t2.value34 = {}
    invTab:CreateToggle({
		Name = "Anti Poison   <font face=\"GothamBlack\" color=\"rgb(100, 200, 255)\">PROTECT</font>",
		CurrentValue = false,
		Flag = "AntiPoison",
		Callback = function(p47)
        t2.value33 = p47

        if p47 then
            t2.value34 = {}

            for _, descendant in ipairs(workspace:GetDescendants()) do
                if descendant:IsA("BasePart") and descendant.Name == "PoisonHurtPart" then
                    t2.value34[descendant] = descendant.CFrame
                    descendant.CFrame = descendant.CFrame + Vector3.new(0, 10000, 0)
                end
            end

            return
        end

        for k, v in pairs(t2.value34) do
            local v381 = k

            if v381 and v381.Parent then
                v381.CFrame = v
            end
        end
    end
	})
    t2.value35 = workspace.Map.FactoryIsland.PoisonContainer.ExtinguishPart
    t2.value36 = t2.value35.Position
    t2.value37 = nil
    t2.value38 = nil
    invTab:CreateToggle({
		Name = "Anti Burn    <font face=\"GothamBlack\" color=\"rgb(255, 165, 0)\">FIRE</font>",
		CurrentValue = false,
		Flag = "AntiBurnToggle",
		Callback = function(p48)
        if p48 then
            t2.value35.Transparency = 1

            local function v383(p49)
                local Humanoid8 = p49:WaitForChild("Humanoid")
                local HumanoidRootPart = p49:WaitForChild("HumanoidRootPart")
                local FireDebounce = Humanoid8:WaitForChild("FireDebounce", 5)

                if t2.value37 then
                    t2.value37:Disconnect()
                end

                t2.value37 = t1.value2.Heartbeat:Connect(function()
                    if not p49:IsDescendantOf(workspace) then
                        t2.value37:Disconnect()
                        t2.value37 = nil

                        return
                    end

                    if FireDebounce and FireDebounce.Value then
                        local HumanoidRootPartPosition = HumanoidRootPart.Position
                        local v2274 = tick() * 3 % 3
                        local v2275 = v2274 < 1 and HumanoidRootPartPosition or (v2274 < 2 and t2.value36 or HumanoidRootPartPosition)
                        local vector3 = Vector3.new(math.sin(tick() * 5) * 3, math.cos(tick() * 3) * 2, math.sin(tick() * 4) * 3)

                        t2.value35.Position = v2275 + vector3
                        t2.value35.CFrame = t2.value35.CFrame * CFrame.Angles(math.rad((math.random(-10, 10))), math.rad((math.random(-10, 10))), (math.rad((math.random(-10, 10)))))

                        return
                    end

                    t2.value35.Position = t2.value35.Position:Lerp(t2.value36, 0.1)
                end)
            end

            if t2.value38 then
                t2.value38:Disconnect()
            end

            t2.value38 = t1.value3.CharacterAdded:Connect(v383)

            if t1.value3.Character then
                v383(t1.value3.Character)

                return
            end
        else
            if t2.value37 then
                t2.value37:Disconnect()
            end

            if t2.value38 then
                t2.value38:Disconnect()
            end

            t2.value35.Position = t2.value36
            t2.value35.Transparency = 0
        end
    end
	})
    t2.value39 = nil
    t2.value40 = nil
    t2.value41 = false
    invTab:CreateToggle({
		Name = "Anti Banana    <font face='GothamBlack' color='rgb(255, 230, 100)'>REMOVE-LEGS</font>",
		CurrentValue = false,
		Flag = "RemoveLegs",
		Callback = function(p50)
        t2.value41 = p50

        local function v385(p51)
            if t2.value39 then
                t2.value39:Disconnect()
            end

            t2.value39 = t1.value2.Heartbeat:Connect(function()
                if not t2.value41 then
                    return
                end

                local v2277 = p51 or t1.value3.Character

                if not v2277 then
                    return
                end

                local Humanoid9 = v2277:FindFirstChild("Humanoid")
                local HumanoidRootPart = v2277:FindFirstChild("HumanoidRootPart")

                if not Humanoid9 or not HumanoidRootPart then
                    return
                end

                local v2280 = v2277:FindFirstChild("Right Leg")
                local v2281 = v2277:FindFirstChild("Left Leg")

                if v2280 or v2281 then
                    workspace.FallenPartsDestroyHeight = -10
                    Humanoid9:ChangeState(Enum.HumanoidStateType.GettingUp)

                    if t2.value9:FindFirstChild("CharacterEvents") then
                        local RagdollRemote2 = t2.value9.CharacterEvents:FindFirstChild("RagdollRemote")

                        if RagdollRemote2 then
                            RagdollRemote2:FireServer(HumanoidRootPart, 1)
                        end
                    end

                    task.wait(0.2)

                    if v2280 then
                        v2280:PivotTo(CFrame.new(-9999, -99999999, -9999))
                    end

                    if v2281 then
                        v2281:PivotTo(CFrame.new(-9999, -99999999, -9999))
                    end

                    task.wait(2)
                    HumanoidRootPart.CFrame = CFrame.new(-86.8966, -10.1004, 7.777)

                    return
                end

                Humanoid9.HipHeight = 2
                workspace.FallenPartsDestroyHeight = -500
            end)
        end

        function onCharacterAdded(p52)
            if not t2.value41 then
                return
            end

            p52.ChildAdded:Connect(function(child)
                if (child.Name == "Right Leg" or child.Name == "Left Leg") and t2.value41 then
                    local v2284 = p52

                    v385(v2284)
                end
            end)
            p52.ChildRemoved:Connect(function(child)
                if child.Name == "Right Leg" or child.Name == "Left Leg" then
                    local Humanoid10 = p52:FindFirstChild("Humanoid")

                    if Humanoid10 then
                        Humanoid10.HipHeight = 2
                    end
                end
            end)
            v385(p52)
        end

        if t2.value41 and t1.value3.Character then
            onCharacterAdded(t1.value3.Character)
        end

        if t2.value41 then
            t2.value40 = t1.value3.CharacterAdded:Connect(function(character)
                if t2.value41 then
                    onCharacterAdded(character)
                end
            end)

            return
        end

        if not t2.value41 then
            if t2.value39 then
                t2.value39:Disconnect()
            end

            if t2.value40 then
                t2.value40:Disconnect()
            end

            workspace.FallenPartsDestroyHeight = -500
        end
    end
	})
    invTab:CreateToggle({
		Name = "Anti Banana v2   <font face=\"GothamBlack\" color=\"rgb(255,255,0)\">EAT BANANA</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Callback = function(p53)
        local n1 = 0

        if p53 then
            task.spawn(function()
                while p53 do
                    local timestamp = tick()

                    if timestamp - n1 < 0.2 then
                        t1.value2.Heartbeat:Wait()
                    else
                        n1 = timestamp

                        for _, child in ipairs(workspace:GetChildren()) do
                            local v1748 = child

                            if not (v1748.Parent.Name == t1.value3.Name .. "SpawnedInToys") then
                                local v1749 = v1748:IsA("Model")

                                if v1749 then
                                    v1749 = v1748.Name == "FoodBanana"

                                    if v1749 then
                                        v1749 = v1748:FindFirstChild("HoldPart")
                                    end
                                end

                                if v1749 then
                                    local HoldPart = v1748.HoldPart
                                    local HoldItemRemoteFunction = HoldPart:FindFirstChild("HoldItemRemoteFunction")

                                    if HoldItemRemoteFunction then
                                        pcall(function()
                                            HoldItemRemoteFunction:InvokeServer(v1748, t1.value3.Character)
                                        end)
                                    end

                                    task.wait(0.01)

                                    local DropItemRemoteFunction = HoldPart:FindFirstChild("DropItemRemoteFunction")

                                    if DropItemRemoteFunction then
                                        pcall(function()
                                            DropItemRemoteFunction:InvokeServer(v1748, CFrame.new(0, -500, 0), Vector3.new(0, 97.69, 0))
                                        end)
                                    end
                                end

                                for _, child2 in ipairs(v1748:GetChildren()) do
                                    local v1755 = child2

                                    if v1755:IsA("Model") and (v1755.Name == "FoodBanana" and v1755:FindFirstChild("HoldPart")) then
                                        if v1755.Parent.Name == t1.value3.Name .. "SpawnedInToys" then
                                            continue
                                        end

                                        local HoldPart = v1755.HoldPart
                                        local HoldItemRemoteFunction = HoldPart:FindFirstChild("HoldItemRemoteFunction")

                                        if HoldItemRemoteFunction then
                                            pcall(function()
                                                HoldItemRemoteFunction:InvokeServer(v1755, t1.value3.Character)
                                            end)
                                        end

                                        task.wait(0.01)

                                        local DropItemRemoteFunction = HoldPart:FindFirstChild("DropItemRemoteFunction")

                                        if DropItemRemoteFunction then
                                            pcall(function()
                                                DropItemRemoteFunction:InvokeServer(v1755, CFrame.new(0, -500, 0), Vector3.new(0, 97.69, 0))
                                            end)
                                        end
                                    end
                                end
                            end
                        end

                        t1.value2.Heartbeat:Wait()
                    end
                end
            end)
        end

        n1 = 0
    end
	})
    t2.value42 = nil
    invTab:CreateToggle({
		Name = "Anti Paint \t <font face=\"GothamBlack\" color=\"rgb(255, 105, 180)\">PAINT</font>",
		CurrentValue = false,
		Flag = "AntiPaintToggle",
		Callback = function(p54)
        if p54 then
            function deletePaintParts()
                for _, descendant in pairs(workspace:GetDescendants()) do
                    if descendant.Name == "PaintPlayerPart" then
                        descendant:Destroy()
                    end
                end
            end

            deletePaintParts()

            if t2.value42 then
                t2.value42:Disconnect()
            end

            t2.value42 = workspace.DescendantAdded:Connect(function(descendant)
                if descendant.Name == "PaintPlayerPart" then
                    task.wait()
                    descendant:Destroy()
                end
            end)

            return
        end

        if t2.value42 then
            t2.value42:Disconnect()
        end
    end
	})
    invTab:CreateSection("Stability")
    invTab:CreateToggle({
		Name = "Anti Lag      <font face=\"GothamBlack\" color=\"rgb(0, 255, 0)\">MOVEMENT</font>",
		CurrentValue = false,
		Flag = "AntiLag",
		Callback = function(p55)
        local PlayerScripts2 = t1.value3:FindFirstChild("PlayerScripts")

        if PlayerScripts2 then
            local CharacterAndBeamMove = PlayerScripts2:FindFirstChild("CharacterAndBeamMove")

            if CharacterAndBeamMove then
                CharacterAndBeamMove.Enabled = not p55
            end
        end
    end
	})
    t2.value43 = false
    invTab:CreateToggle({
		Name = "Anti Void      <font face=\"GothamBlack\" color=\"rgb(25, 25, 25)\">D̶I̶E</font>",
		CurrentValue = false,
		Flag = "AntiVoid",
		Callback = function(p56)
        t2.value43 = p56

        if p56 then
            workspace.FallenPartsDestroyHeight = -100000
            task.spawn(function()
                while t2.value43 do
                    local Character = t1.value3.Character
                    local v1763 = Character and Character:FindFirstChild("HumanoidRootPart")

                    if v1763 and v1763.Position.Y < -500 then
                        v1763.CFrame = CFrame.new(2, -7, -4)
                    end

                    task.wait(0.2)
                end
            end)

            return
        end

        workspace.FallenPartsDestroyHeight = -100
    end
	})
    invTab:CreateSection("Anti Character")
    t2.value44 = "StickyPartsTouchDetection"
    invTab:CreateToggle({
		Name = "Anti Sticky     <font face=\"GothamBlack\" color=\"rgb(180, 0, 255)\">CHARACTER</font>",
		CurrentValue = false,
		Flag = "AntiStickyToggle",
		Callback = function(p57)
        local PlayerScripts3 = t1.value3:WaitForChild("PlayerScripts")

        if p57 then
            local t2value44 = PlayerScripts3:FindFirstChild(t2.value44)

            if t2value44 then
                t2value44.Disabled = true

                return
            end
        else
            local t2value44 = PlayerScripts3:FindFirstChild(t2.value44)

            if t2value44 then
                t2value44:Destroy()
            end

            local t2value44_2 = t2.value9:FindFirstChild(t2.value44)

            if t2value44_2 then
                t2value44_2:Clone().Parent = PlayerScripts3
            end
        end
    end
	})
    invTab:CreateSection("Anti Blobman")
    t2.value45 = false
    invTab:CreateToggle({
		Name = "Anti Blobman   <font face=\"GothamBlack\" color=\"rgb(255, 100, 100)\">PROTECT</font>",
		CurrentValue = false,
		Flag = "AntiBlobman",
		Callback = function(p58)
        t2.value45 = p58

        if p58 then
            task.spawn(function()
                while t2.value45 do
                    for _, player6 in ipairs(game:GetService("Players"):GetPlayers()) do
                        if player6 ~= game.Players.LocalPlayer then
                            local v1766 = workspace:FindFirstChild(player6.Name .. "SpawnedInToys")

                            if v1766 then
                                for _, child in ipairs(v1766:GetChildren()) do
                                    if child:IsA("Model") and child.Name == "CreatureBlobman" then
                                        child:Destroy()
                                    end
                                end
                            end
                        end
                    end

                    task.wait(0.2)
                end
            end)
        end
    end
	})
    invTab:CreateSection("Anti Loop")
    t2.value46 = false
    t2.value47 = nil
    t2.value48 = Vector3.new(264, -7, 440)
    invTab:CreateToggle({
		Name = "Anti Loop Ownership    <font face=\"GothamBlack\" color=\"rgb(255, 150, 50)\">HOUSE</font>",
		CurrentValue = false,
		Flag = "AntiLoopOwnership",
		Callback = function(p59)
        t2.value46 = p59

        if t2.value47 then
            t2.value47:Disconnect()
        end

        if p59 then
            local Character = t1.value3.Character
            local v401 = Character and Character:FindFirstChild("HumanoidRootPart")

            if v401 then
                v401.CFrame = CFrame.new(t2.value48)
            end

            t1.value2.Heartbeat:Connect(function()
                local Character2 = t1.value3.Character
                local v1770 = Character2 and Character2:FindFirstChild("HumanoidRootPart")

                if v1770 then
                    v1770.CFrame = CFrame.new(t2.value48)
                end
            end)
        end
    end
	})
    t1.value3.CharacterAdded:Connect(function(character)
        if t2.value46 then
            task.wait(0.05)
            character:WaitForChild("HumanoidRootPart").CFrame = CFrame.new(t2.value48)
        end
    end)
    invTab:CreateToggle({
		Name = "Anti Loop Ownership V2   <font face=\"GothamBlack\" color=\"rgb(57,255,90)\">TELEPORT EVERYWHERE</font>",
		CurrentValue = false,
		Flag = "AntiLoopV2",
		Callback = function(p60)
        local t16 = {
				Vector3.new(264, -7, 440),
				Vector3.new(0, 50, 0),
				Vector3.new(-500, 20, -500),
				Vector3.new(500, 20, 500),
				Vector3.new(0, 100, 0),
				Vector3.new(264, 50, 440)
			}

        _G.AntiLoopV2Enabled = p60

        if p60 then
            local Character = t1.value3.Character
            local v406 = Character and Character:FindFirstChild("HumanoidRootPart")

            if v406 then
                v406.CFrame = CFrame.new(t16[1])
            end

            t1.value2.Heartbeat:Connect(function()
                local Character3 = t1.value3.Character
                local v1772 = Character3 and Character3:FindFirstChild("HumanoidRootPart")

                if v1772 and _G.AntiLoopV2Enabled then
                    local v1773 = t16[math.random(1, #t16)]

                    v1772.CFrame = CFrame.new(v1773 + Vector3.new(math.random(-10, 10), 0, math.random(-10, 10)))
                end
            end)
        end
    end
	})
    t1.value3.CharacterAdded:Connect(function(character)
        if _G.AntiLoopV2Enabled then
            task.wait(0.05)
            character:WaitForChild("HumanoidRootPart").CFrame = CFrame.new(teleportPositions[math.random(1, #teleportPositions)])
        end
    end)
    t2.value49 = false
    t2.value50 = nil
    t2.value51 = {}
    t2.value52 = nil
    invTab:CreateToggle({
		Name = "Anti BlobKill    <font face=\"GothamBlack\" color=\"rgb(255, 100, 255)\">FOOD</font>    <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Flag = "AntiBlobKill",
		Callback = function(p61)
        t2.value49 = p61
        local Players = game:GetService("Players")
        local ReplicatedStorage = game:GetService("ReplicatedStorage")
        local RunService = game:GetService("RunService")
        local LocalPlayer = Players.LocalPlayer
        local u413
        function gethrp()
            if LocalPlayer.Character then
                local HumanoidRootPart = LocalPlayer.Character:FindFirstChild("HumanoidRootPart")

                if HumanoidRootPart then
                    u413 = HumanoidRootPart
                end
            end

            return u413
        end
        function spawnfood()
            if not canSpawn() then
                return
            end

            if tick() - 0 < 0.5 then
                return
            end

            tick()

            if not u413 then
                return
            end

            local t17 = {
					"FoodHamburger",
					u413.CFrame * CFrame.new(5, 0, 5),
					Vector3.new(0, 33.088, 0)
				}

            ReplicatedStorage.MenuToys.SpawnToyRemoteFunction:InvokeServer(unpack(t17))
        end
        function hold(p62)
            if not p62 or not p62.Parent then
                return
            end

            local HoldPart = p62:FindFirstChild("HoldPart")

            if not HoldPart then
                return
            end

            local t18 = {
					p62,
					LocalPlayer.Character
				}
            local t19 = {
					p62,
					CFrame.new(-128.375, -10.35, 72.18),
					Vector3.new(0, 154.777, 0)
				}
            local HoldItemRemoteFunction = HoldPart.HoldItemRemoteFunction
            local t20 = { unpack(t18) }

            HoldItemRemoteFunction:InvokeServer(v1(t20))

            local DropItemRemoteFunction = HoldPart.DropItemRemoteFunction
            local t21 = { unpack(t19) }

            DropItemRemoteFunction:InvokeServer(v1(t21))
        end
        function findFoodInAllFolders()
            local v1784 = getAllPalletFolders()

            for _, v in ipairs(v1784) do
                for _, child in ipairs(v:GetChildren()) do
                    if child.Name == "FoodHamburger" then
                        return child
                    end
                end
            end

            return nil
        end
        function watchFoodFolder(p63)
            if not p63 or t2.value51[p63] then
                return
            end

            t2.value51[p63] = p63.ChildAdded:Connect(function(child)
                if child.Name == "FoodHamburger" and not t2.value52 then
                    t2.value52 = child
                end
            end)
        end
        if t2.value50 then
            t2.value50:Disconnect()
        end
        for v416, v417 in pairs(t2.value51) do

            if v417 then
                v417:Disconnect()
            end
        end
        t2.value51 = {}
        if t2.value49 then
            local v418 = getAllPalletFolders()

            for _, v in ipairs(v418) do
                watchFoodFolder(v)
            end

            task.spawn(function()
                while t2.value49 do
                    task.wait(2)

                    local v1790 = getAllPalletFolders()

                    for _, v in ipairs(v1790) do
                        watchFoodFolder(v)
                    end
                end
            end)
            RunService.Heartbeat:Connect(function()
                gethrp()

                if not t2.value52 or not t2.value52.Parent then
                    t2.value52 = findFoodInAllFolders()

                    if not t2.value52 then
                        spawnfood()

                        return
                    end
                else
                    hold(t2.value52)
                end
            end)
            spawnfood()
        end
    end
	})
    GrabLinesTab:CreateLabel("Grab", "Hand")
    t2.value53 = false
    t2.value54 = nil
    GrabLinesTab:CreateToggle({
		Name = "Kill Grab\t <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">KILL</font>\t<font face=\"GothamBlack\" color=\"rgb(255,255,255)\">(PLAYER)</font>",
		CurrentValue = false,
		Flag = "KillGrabToggle",
		Callback = function(p64)
        if p64 then
            if t2.value53 then
                return
            end

            t2.value53 = true
            t2.value54 = coroutine.create(function()
                while t2.value53 do
                    pcall(function()
                        local GrabParts = workspace:FindFirstChild("GrabParts")
                        local v2289 = GrabParts and GrabParts:FindFirstChild("GrabPart")
                        local v2290 = v2289 and v2289:FindFirstChildOfClass("WeldConstraint")
                        local v2291 = v2290 and v2290.Part1
                        local v2292 = v2291 and v2291:FindFirstAncestorOfClass("Model")
                        local v2293 = v2292 and v2292:FindFirstChild("Humanoid")

                        if v2293 then
                            task.wait(0.4)
                            v2293.Health = 0
                        end
                    end)
                    task.wait()
                end
            end)
            coroutine.resume(t2.value54)
        end
    end
	})
    getgenv().NoclipGrabConnection = nil
    GrabLinesTab:CreateToggle({
		Name = "Noclip Grab\t  <font face=\"GothamBlack\" color=\"rgb(0,150,255)\">NOCLIP</font>\t<font face=\"GothamBlack\" color=\"rgb(255,255,255)\">(PLAYER & OBJECT)</font>",
		CurrentValue = false,
		Flag = "ToggleNoclipGrab",
		Callback = function(p65)
        if getgenv().NoclipGrabConnection then
            getgenv().NoclipGrabConnection:Disconnect()
            getgenv().NoclipGrabConnection = nil
        end

        local function v423()
            local GrabParts = workspace:FindFirstChild("GrabParts")

            if not GrabParts then
                return nil
            end

            local GrabPart = GrabParts:FindFirstChild("GrabPart")

            if not GrabPart then
                return nil
            end

            local v1795 = GrabPart:FindFirstChild("WeldConstraint") or GrabPart:FindFirstChild("Weld")

            if not v1795 then
                return nil
            end

            return v1795.Part1 and v1795.Part1.Parent or nil
        end

        if not p65 then
            local v424 = v423()

            if v424 then
                local GetDescendants = v424.GetDescendants

                for _, v in ipairs(GetDescendants(v424)) do
                    if v:IsA("BasePart") and not v.Anchored then
                        v.CanCollide = true
                    end
                end
            end

            return
        end

        getgenv().NoclipGrabConnection = t1.value2.Heartbeat:Connect(function()
            local v1796 = v423()

            if v1796 then
                for _, descendant in ipairs(v1796:GetDescendants()) do
                    if descendant:IsA("BasePart") and not descendant.Anchored then
                        descendant.CanCollide = false
                    end
                end
            end
        end)
    end
	})
    getgenv().VoidGrabConnection = nil
    GrabLinesTab:CreateToggle({
		Name = "kick Grab \t<font face=\"GothamBlack\" color=\"rgb(70,70,70)\">KICK</font>   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP++</font>   <font face=\"GothamBlack\" color=\"rgb(255,255,255)\">(PLAYER)</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Flag = "ToggleVoidGrab",
		Callback = function(p66)
        if getgenv().VoidGrabConnection then
            getgenv().VoidGrabConnection:Disconnect()
            getgenv().VoidGrabConnection = nil
        end
        if not p66 then
            return
        end
        local clone
        local n2 = 0
        getgenv().VoidGrabConnection = t1.value2.Heartbeat:Connect(function(_)
            local Character = t1.value3.Character
            local g1815
            if Character then
                Character = Character:FindFirstChild("Torso") or (Character:FindFirstChild("UpperTorso") or Character:FindFirstChild("HumanoidRootPart"))
            end
            if not Character then
                return
            end
            local GrabParts = Workspace:FindFirstChild("GrabParts")
            if not GrabParts then
                return
            end
            local v1802 = false
            local timestamp = tick()
            for v1806, v1807 in ipairs(GrabParts:GetChildren()) do

                if v1807.Name == "GrabPart" then
                    local WeldConstraint = v1807:FindFirstChildOfClass("WeldConstraint")

                    if WeldConstraint and WeldConstraint.Part1 then
                        local WeldConstraintPart1 = WeldConstraint.Part1
                        local v1810
                        local v1811, v1812, v1813 = ipairs(t1.value1:GetPlayers())
                        local v1814
                        repeat
                            v1813, v1814 = v1811(v1812, v1813)

                            if not v1813 then
                                g1815 = true
                            end

                            if g1815 then
                                break
                            end
                        until v1814 ~= t1.value3 and (v1814.Character and WeldConstraintPart1:IsDescendantOf(v1814.Character))
                        if not g1815 then
                            v1810 = v1814
                        end
                        g1815 = false
                        if v1810 then
                            local v1816 = v1810.Character and v1810.Character:FindFirstChild("HumanoidRootPart")

                            if v1816 then
                                local v1817 = not clone

                                v1802 = true

                                if v1817 then
                                    v1817 = t2.value9.GrabEvents:FindFirstChild("EndGrabEarly")
                                end

                                if v1817 then
                                    clone = t2.value9.GrabEvents.EndGrabEarly:Clone()
                                    t2.value9.GrabEvents.EndGrabEarly:Destroy()
                                end

                                t2.value9.GrabEvents.SetNetworkOwner:FireServer(v1816, v1816.CFrame)

                                local IsHeld = v1810:FindFirstChild("IsHeld")
                                local v1819 = not not IsHeld and (IsHeld.Value or false)

                                v1816.AssemblyLinearVelocity = Vector3.zero
                                v1816.AssemblyAngularVelocity = Vector3.zero

                                if v1819 then
                                    t2.value9.GrabEvents.DestroyGrabLine:FireServer(v1816)
                                else
                                    t2.value9.GrabEvents.SetNetworkOwner:FireServer(v1816, Character.CFrame)
                                    t2.value9.GrabEvents.DestroyGrabLine:FireServer(v1816)
                                end

                                if timestamp - n2 >= 0.01 then
                                    n2 = timestamp
                                end
                            end
                        end
                    end
                end
            end
            if not v1802 and (clone and not t2.value9.GrabEvents:FindFirstChild("EndGrabEarly")) then
                clone.Parent = t2.value9.GrabEvents
            end
        end)
    end
	})
    GrabLinesTab:CreateParagraph({
		Title = "<font face=\"GothamBlack\" color=\"rgb(255,255,255)\">Credits</font>",
		Content = "Thanks to <b>netherlandson_top0</b> for creating this kick Grab and sharing it."
	})
    RagdollGrab = false
    scriptRagdollGrabToy = nil
    ragdollGrabMonitor = nil
    RAGDOLLGRAB_UNIQUE_ID = nil
    isRagdollGrabRespawning = false

    function UpdateRagdollGrabPalletMenu()
        task.spawn(function()
            local PlayerGui = t1.value3:FindFirstChild("PlayerGui")
            if not PlayerGui then
                return
            end
            local MenuGui = PlayerGui:FindFirstChild("MenuGui")
            if not MenuGui or (not scriptRagdollGrabToy or not scriptRagdollGrabToy:FindFirstChild("ScriptRagdollID")) then
                return
            end
            local Contents = MenuGui.Menu.TabContents.ToyDestroy.Contents
            local ScriptRagdollIDValue = scriptRagdollGrabToy.ScriptRagdollID.Value
            local t22 = {}
            local v1825, v1826, v1827 = ipairs(BackPack:GetChildren())
            local g1834
            while true do
                local v1828

                v1827, v1828 = v1825(v1826, v1827)

                if not v1827 then
                    break
                end

                if v1828.Name == "RagdollGrab" or v1828.Name == "PalletLightBrown" then
                    table.insert(t22, v1828)
                end
            end
            local n3 = 0
            local v1830, v1831, v1832 = ipairs(t22)
            repeat
                local v1833

                v1832, v1833 = v1830(v1831, v1832)

                if not v1832 then
                    g1834 = true
                end

                if g1834 then
                    break
                end
            until v1833:FindFirstChild("ScriptRagdollID") and ScriptRagdollIDValue == v1833.ScriptRagdollID.Value
            if not g1834 then
                n3 = v1832
            end
            g1834 = false
            if n3 == 0 then
                return
            end
            local n4 = 0
            for _, child in ipairs(Contents:GetChildren()) do
                if not (child.Name == "PalletLightBrown" and child:FindFirstChild("ViewItemButton")) then
                    continue
                end

                n4 += 1

                if n4 == n3 then
                    local ViewItemButton = child.ViewItemButton

                    ViewItemButton.Text = "Ragdoll Grab (DO NOT DELETE)"
                    ViewItemButton.TextScaled = true

                    if ViewItemButton:FindFirstChild("LowResImage") then
                        ViewItemButton.LowResImage.Image = ""
                    end

                    return
                end
            end
        end)
    end
    function PrepareRagdollGrab()
        if scriptRagdollGrabToy or isRagdollGrabRespawning then
            return
        end

        isRagdollGrabRespawning = true

        for _, child in ipairs(BackPack:GetChildren()) do
            local v433 = child

            if v433.Name == "RagdollGrab" then
                pcall(function()
                    t2.value9.MenuToys.DestroyToy:FireServer(v433)
                end)
            end
        end

        local guid = HttpService:GenerateGUID(false)
        local SpawnToyRemoteFunction = t2.value9.MenuToys.SpawnToyRemoteFunction

        for _ = 1, 3 do
            local v437 = t1.value3.Character and t1.value3.Character:FindFirstChild("Head")

            if v437 then
                task.spawn(function()
                    SpawnToyRemoteFunction:InvokeServer("PalletLightBrown", CFrame.new(v437.Position + Vector3.new(0, 1, 0), v437.Position) * CFrame.Angles(3.141592653589793, 0, 0), Vector3.new(0, 0, 0))
                end)
                local u438
                local connection = BackPack.ChildAdded:Connect(function(child)
                    if child.Name == "PalletLightBrown" then
                        u438 = child
                    end
                end)
                local timestamp = tick()
                if not u438 then
                    if not (tick() - timestamp > 8) then
                    end
                end
                repeat
                    task.wait()
                until u438 or tick() - timestamp > 8
                connection:Disconnect()
                local v441 = u438
                if v441 then
                    if v441:FindFirstChild("ScriptRagdollID") then
                        v441.ScriptRagdollID:Destroy()
                    end

                    local StringValue = Instance.new("StringValue")

                    StringValue.Name = "ScriptRagdollID"
                    StringValue.Value = guid
                    StringValue.Parent = v441
                    v441.Name = "RagdollGrab"

                    local SoundPart = v441:WaitForChild("SoundPart", 5)

                    if SoundPart then
                        task.spawn(function()
                            while RagdollGrab and (SoundPart and SoundPart.Parent) do
                                if not SoundPart:FindFirstChild("PartOwner") or SoundPart.PartOwner.Value ~= t1.value3.Name then
                                    t2.value9.GrabEvents.SetNetworkOwner:FireServer(SoundPart, SoundPart.CFrame)
                                end

                                task.wait(0.1)
                            end
                        end)

                        local BodyVelocity = Instance.new("BodyVelocity")

                        BodyVelocity.Parent = SoundPart
                        BodyVelocity.MaxForce = Vector3.new(0, 1e999, 0)
                        BodyVelocity.Velocity = Vector3.new(0, 1000, 0)

                        local GetChildren = v441.GetChildren

                        for _, v in pairs(GetChildren(v441)) do
                            if v:IsA("BasePart") then
                                v.Transparency = 1
                                v.Size = Vector3.new(0.5, 0.5, 0.5)
                                v.CanCollide = false
                            end
                        end

                        if SoundPart:FindFirstChild("Wood") then
                            SoundPart.Wood:Destroy()
                        end

                        scriptRagdollGrabToy = v441
                        RAGDOLLGRAB_UNIQUE_ID = guid
                        isRagdollGrabRespawning = false
                        UpdateRagdollGrabPalletMenu()

                        return
                    end

                    v441:Destroy()
                end
                task.wait(0.5)

                continue
            end

            task.wait(0.5)
        end

        isRagdollGrabRespawning = false
    end
    function DestroyRagdollGrab()
        if scriptRagdollGrabToy and scriptRagdollGrabToy.Parent then
            pcall(function()
                t2.value9.MenuToys.DestroyToy:FireServer(scriptRagdollGrabToy)
            end)
            task.wait(0.1)
        end

        scriptRagdollGrabToy = nil
        RAGDOLLGRAB_UNIQUE_ID = nil
    end
    function StartRagdollGrabMonitor()
        if ragdollGrabMonitor then
            task.cancel(ragdollGrabMonitor)
        end

        ragdollGrabMonitor = task.spawn(function()
            while RagdollGrab do
                task.wait(2)

                local v1840 = not scriptRagdollGrabToy

                if not v1840 then
                    v1840 = not scriptRagdollGrabToy.Parent or (not scriptRagdollGrabToy:FindFirstChild("ScriptRagdollID") or scriptRagdollGrabToy.ScriptRagdollID.Value ~= RAGDOLLGRAB_UNIQUE_ID)
                end

                if v1840 then
                    scriptRagdollGrabToy = nil
                    PrepareRagdollGrab()
                end
            end
        end)
    end

    GrabLinesTab:CreateToggle({
		Name = "Ragdoll Grab  <font face=\"GothamBlack\" color=\"rgb(240,184,111)\">PALLET</font>",
		CurrentValue = false,
		Flag = "RagdollGrabToggle",
		Callback = function(p68)
        RagdollGrab = p68

        if p68 then
            task.wait(0.2)
            PrepareRagdollGrab()
            StartRagdollGrabMonitor()

            return
        end

        DestroyRagdollGrab()

        if ragdollGrabMonitor then
            task.cancel(ragdollGrabMonitor)
            ragdollGrabMonitor = nil
        end
    end
	})
    Workspace.ChildAdded:Connect(function(child)
        if RagdollGrab and child.Name == "GrabParts" then
            task.wait(0.05)

            local v450 = child:FindFirstChild("GrabPart") and child.GrabPart:FindFirstChild("WeldConstraint")

            if v450 and v450.Part1 then
                local Head = v450.Part1.Parent:FindFirstChild("Head")
                local RagdollGrab2 = BackPack:FindFirstChild("RagdollGrab")

                if Head and (RagdollGrab2 and RagdollGrab2:FindFirstChild("SoundPart")) then
                    firetouchinterest(RagdollGrab2.SoundPart, Head, 0)
                    task.wait()
                    firetouchinterest(RagdollGrab2.SoundPart, Head, 1)
                end
            end
        end
    end)
    BackPack.ChildAdded:Connect(function(child)
        if not RagdollGrab then
            return
        end

        task.wait(0.05)

        if child:FindFirstChild("ScriptRagdollID") and child.ScriptRagdollID.Value == RAGDOLLGRAB_UNIQUE_ID then
            scriptRagdollGrabToy = child
            UpdateRagdollGrabPalletMenu()
        end
    end)
    BackPack.ChildRemoved:Connect(function(child)
        if RagdollGrab and child == scriptRagdollGrabToy then
            scriptRagdollGrabToy = nil
            task.wait(0.5)

            if RagdollGrab and not scriptRagdollGrabToy then
                PrepareRagdollGrab()
            end
        end
    end)
    t2.value55 = 30
    t2.value56 = nil
    t2.value57 = false
    GrabLinesTab:CreateToggle({
		Name = "Massless Grab    <font face=\"GothamBlack\" color=\"rgb(0,255,0)\">MASSLESS</font>   <font face=\"GothamBlack\" color=\"rgb(255,255,255)\">(PLAYER & OBJECT)</font>",
		CurrentValue = false,
		Flag = "Toggle1",
		Callback = function(p69)
        t2.value57 = p69

        if p69 then
            t2.value56 = workspace.ChildAdded:Connect(function(child)
                if child.Name ~= "GrabParts" or not t2.value57 then
                    return
                end

                task.wait(0.1)

                if not child.Parent then
                    return
                end

                local DragPart = child:FindFirstChild("DragPart")

                if DragPart and (DragPart:FindFirstChild("AlignPosition") and DragPart:FindFirstChild("AlignOrientation")) then
                    DragPart.AlignPosition.Responsiveness = t2.value55
                    DragPart.AlignPosition.MaxForce = 1e999
                    DragPart.AlignPosition.MaxVelocity = 1e999
                    DragPart.AlignOrientation.Responsiveness = t2.value55
                    DragPart.AlignOrientation.MaxTorque = 1e999
                end
            end)

            return
        end

        if t2.value56 then
            t2.value56:Disconnect()
        end
    end
	})

    local _GrabLinesTab = GrabLinesTab
    local str3 = tostring(t2.value55)

    _GrabLinesTab:CreateInput({
		Name = "Massless Sense",
		CurrentValue = str3,
		PlaceholderText = "Enter sense value",
		RemoveTextAfterFocusLost = false,
		Flag = "MasslessSenseInput",
		Callback = function(p70)
        local num = tonumber(p70)

        if not (num and num > 0) then
        end
    end
	})
    t2.value58 = false
    t2.value59 = 0.1
    GrabLinesTab:CreateToggle({
		Name = "Crazy Grab\t\t<font face=\"GothamBlack\" color=\"rgb(150,0,255)\">CRAZY</font>\t<font face=\"GothamBlack\" color=\"rgb(255,255,255)\">(PLAYER)</font>",
		CurrentValue = false,
		Callback = function(p71)
        if p71 then
            if t2.value58 then
                return
            end

            t2.value58 = true
            task.spawn(function()
                while t2.value58 do
                    pcall(function()
                        local GrabParts = workspace:FindFirstChild("GrabParts")
                        local v2295 = GrabParts and GrabParts:FindFirstChild("GrabPart")
                        local v2296 = v2295 and v2295:FindFirstChild("WeldConstraint")
                        local v2297 = v2296 and v2296.Part1
                        local v2298 = v2297 and v2297.Parent
                        local v2299 = v2298 and v2298:FindFirstChild("HumanoidRootPart")

                        if v2299 then
                            local vector3 = Vector3.new(-17, 421, 50)
                            local vector3_6 = Vector3.new(145, 397, -126)
                            local vector3_7 = Vector3.new(157, 254, 89)
                            local vector3_8 = Vector3.new(-26, 207, -26)
                            local vector3_9 = Vector3.new(-23, 456, -19)
                            local t23 = { Vector3.new(15, 211, 45) }
                            local t24 = {
									vector3,
									vector3_6,
									vector3_7,
									vector3_8,
									vector3_9,
									v1(t23)
								}

                            for _, v in ipairs(t24) do
                                if not t2.value58 then
                                    return
                                end

                                v2299.CFrame = CFrame.new(v)
                                task.wait(t2.value59)
                            end
                        end
                    end)
                    task.wait()
                end
            end)
        end
    end
	})
    getgenv().FlingGrabConnection = nil
    GrabLinesTab:CreateToggle({
		Name = "Fling Air Grab\t  <font face=\"GothamBlack\" color=\"rgb(0,255,255)\">FLING</font>\t<font face=\"GothamBlack\" color=\"rgb(255,255,255)\">(PLAYER)</font>",
		CurrentValue = false,
		Flag = "ToggleFlingGrab",
		Callback = function(p72)
        if getgenv().FlingGrabConnection then
            getgenv().FlingGrabConnection:Disconnect()
            getgenv().FlingGrabConnection = nil
        end

        function GetGrabbedCharacter()
            local GrabParts = workspace:FindFirstChild("GrabParts")

            if not GrabParts then
                return nil
            end

            local GrabPart = GrabParts:FindFirstChild("GrabPart")

            if not GrabPart then
                return nil
            end

            local v1845 = GrabPart:FindFirstChild("WeldConstraint") or GrabPart:FindFirstChild("Weld")

            if not v1845 then
                return nil
            end

            return v1845.Part1 and v1845.Part1.Parent or nil
        end

        if not p72 then
            return
        end

        getgenv().FlingGrabConnection = t1.value2.Heartbeat:Connect(function()
            local v1846 = GetGrabbedCharacter()

            if v1846 and v1846:FindFirstChild("HumanoidRootPart") then
                v1846.HumanoidRootPart.Velocity = Vector3.new(0, 500, 0)
            end
        end)
    end
	})
    t2.value60 = false
    t2.value61 = 5
    t2.value62 = {}
    GrabLinesTab:CreateToggle({
		Name = "Spin Grab    <font face=\"GothamBlack\" color=\"rgb(108,76,0)\">SPIN</font>   <font face=\"GothamBlack\" color=\"rgb(255,255,255)\">(PLAYER & OBJECT)</font>",
		CurrentValue = false,
		Flag = "SpinTogglePermanent",
		Callback = function(p73)
        t2.value60 = p73

        if p73 then
            task.spawn(function()
                while t2.value60 do
                    pcall(function()
                        local GrabParts = workspace:FindFirstChild("GrabParts")

                        if GrabParts then
                            local GrabPart = GrabParts:FindFirstChild("GrabPart")

                            if GrabPart then
                                local WeldConstraint = GrabPart:FindFirstChild("WeldConstraint")

                                if WeldConstraint and WeldConstraint.Part1 then
                                    local v2312 = WeldConstraint.Part1.Name == "SoundPart" and WeldConstraint.Part1 or (WeldConstraint.Part1.Parent:FindFirstChild("SoundPart") or (WeldConstraint.Part1.Parent.PrimaryPart or WeldConstraint.Part1))

                                    if v2312 and not t2.value62[v2312] then
                                        t2.value62[v2312] = true

                                        if not v2312:FindFirstChild("BodyGyro") then
                                            local BodyGyro = Instance.new("BodyGyro")

                                            BodyGyro.P = 15000
                                            BodyGyro.D = 200
                                            BodyGyro.MaxTorque = Vector3.new(5000000, 5000000, 5000000)
                                            BodyGyro.CFrame = v2312.CFrame
                                            BodyGyro.Parent = v2312
                                        end
                                    end
                                end
                            end
                        end

                        for k, _ in pairs(t2.value62) do
                            local v2316 = k

                            if v2316 and (v2316.Parent and v2316:FindFirstChild("BodyGyro")) then
                                v2316.BodyGyro.CFrame = v2316.BodyGyro.CFrame * CFrame.Angles(0, math.rad(t2.value61), 0)
                            end
                        end
                    end)
                    task.wait()
                end
            end)
        end
    end
	})

    local _GrabLinesTab2 = GrabLinesTab
    local str4 = tostring(t2.value61)

    _GrabLinesTab2:CreateInput({
		Name = "Spin Speed",
		CurrentValue = str4,
		PlaceholderText = "Enter spin speed",
		RemoveTextAfterFocusLost = false,
		Flag = "SpinSpeedInput",
		Callback = function(p74)
        local num = tonumber(p74)

        if not (num and num > 0) then
        end
    end
	})
    t2.value63 = 10
    t2.value64 = false
    CamPart = Instance.new("Part")
    CamPart.Size = Vector3.new(1, 1, 1)
    CamPart.Anchored = false
    CamPart.CanCollide = false
    CamPart.Transparency = 1
    CamPart.Parent = Workspace
    Vel = Instance.new("BodyVelocity")
    t2.value65 = nil
    Vel.MaxForce = Vector3.new(1000000000, 1000000000, 1000000000)
    Vel.Parent = CamPart
    Gui = Instance.new("ScreenGui", t1.value3:WaitForChild("PlayerGui"))
    Gui.ResetOnSpawn = false
    t2.value66 = {}
    t2.value67 = false

    function Btn(p75, p76, p77)
        if not t2.value64 then
            return
        end

        local TextButton = Instance.new("TextButton", Gui)

        TextButton.Size = UDim2.new(0, 100, 0, 50)
        TextButton.Position = p76
        TextButton.Text = p75
        TextButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
        TextButton.TextColor3 = Color3.new(1, 1, 1)
        TextButton.Font = Enum.Font.SourceSansBold
        TextButton.TextSize = 20
        TextButton.AutoButtonColor = true

        local u467 = false
        local u468 = true

        TextButton.MouseButton1Down:Connect(function()
            if not t2.value64 then
                return
            end

            u467 = true
            u468 = true
            coroutine.wrap(function()
                while t2.value64 and (u468 and u467) do
                    p77(true)
                    task.wait(0.025)
                end
            end)()
        end)
        TextButton.MouseButton1Up:Connect(function()
            if not t2.value64 then
                return
            end

            p77(false)
        end)
        table.insert(t2.value66, TextButton)
    end
    function UI()
        if t2.value67 or not t2.value64 then
            return
        end

        local ContextButtonFrame = t1.value3.PlayerGui:WaitForChild("ContextActionGui"):WaitForChild("ContextButtonFrame")

        if not (#ContextButtonFrame:GetChildren() >= 5) then
        end

        repeat
            task.wait()
        until #ContextButtonFrame:GetChildren() >= 5

        local children = ContextButtonFrame:GetChildren()

        if children[5] and children[4] then
            local Position = children[5].Position
            local Position2 = children[4].Position

            Btn("Front", Position, function(p78)
                if p78 then
                    p78 = t2.value64
                end

                if p78 then
                    t2.value63 = math.clamp(t2.value63 + 10, 10, 500)
                end
            end)
            Btn("Back", Position2, function(p79)
                if p79 then
                    p79 = t2.value64
                end

                if p79 then
                    t2.value63 = math.clamp(t2.value63 - 10, 5, 500)
                end
            end)
            children[4].Parent = nil
            children[5].Parent = nil
            t2.value67 = true
        end
    end
    function Reset()
        Gui:ClearAllChildren()
        table.clear(t2.value66)
        t2.value67 = false
    end
    function Hide(p80)
        if not t2.value64 then
            return
        end

        for _, descendant in pairs(p80:GetDescendants()) do
            if descendant:IsA("BasePart") and descendant.Name ~= "HumanoidRootPart" then
                local GetChildren = descendant.GetChildren

                descendant.Transparency = 0

                for _, v in pairs(GetChildren(descendant)) do
                    if v:IsA("Decal") then
                        v.Transparency = 0
                    end
                end
            elseif descendant:IsA("Accessory") then
                local Handle = descendant:FindFirstChild("Handle")

                if Handle then
                    Handle.Transparency = 0
                end
            end
        end
    end
    function Cam()
        if not t2.value64 then
            return
        end

        local LookVector = camera.CFrame.LookVector
        local v481 = LookVector * t2.value63 + Vector3.new(0, 20, 0)
        local v482 = humanoidRootPart.Position + v481

        CamPart.Position = CamPart.Position:Lerp(v482, 0.25)
        Vel.Velocity = (v482 - CamPart.Position) * 10
        camera.CFrame = camera.CFrame:Lerp(CFrame.new(CamPart.Position, CamPart.Position + LookVector), 0.25)
    end

    t2.value10:GetPropertyChangedSignal("Parent"):Connect(function()
        if t2.value64 then
            Hide(t2.value10)
            camera.CameraSubject = humanoid
            camera.CameraType = Enum.CameraType.Custom

            if not t2.value67 then
                UI()
            end
        end
    end)
    t1.value2.Heartbeat:Connect(function()
        if t2.value64 then
            Cam()

            if Workspace:FindFirstChild("GrabParts") then
            end
        end
    end)
    t2.value68 = 1000
    t2.value69 = false
    t2.value70 = nil
    t2.value71 = nil
    t2.value72 = nil
    t2.value72 = nil

    function t2.value73()
        t2.value69 = false

        if t2.value71 then
            t2.value71:Disconnect()
        end

        if t2.value72 then
            t2.value72:Disconnect()
            t2.value72 = nil
        end
    end

    t2.value70 = false
    t2.value65 = nil

    function t2.value74()
        t2.value70 = false

        if t2.value65 then
            t2.value65:Disconnect()
            t2.value65 = nil
        end
    end
    function t2.value75()
        t2.value65 = Workspace.ChildAdded:Connect(function(child)
            if not t2.value70 then
                return
            end

            if child.Name == "GrabParts" then
                local GrabPart = child:FindFirstChild("GrabPart")
                local v1851 = GrabPart and GrabPart:FindFirstChild("WeldConstraint")
                local u1852 = v1851 and v1851.Part1

                if u1852 then
                    child:GetPropertyChangedSignal("Parent"):Connect(function()
                        if not child.Parent and t2.value70 then
                            local BodyVelocity = Instance.new("BodyVelocity")

                            BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                            BodyVelocity.Velocity = camera.CFrame.LookVector * t2.value68
                            BodyVelocity.Parent = u1852
                            t2.value8:AddItem(BodyVelocity, 1)
                        end
                    end)
                end
            end
        end)
    end

    GrabLinesTab:CreateSection("Stregth")
    GrabLinesTab:CreateToggle({
		Name = "Strength (PC)  <font face=\"GothamBlack\" color=\"rgb(255, 255, 255)\">(PLAYER & OBJECT)</font>    <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>\t<font face=\"GothamBlack\" color=\"rgb(255,0,50)\">POWER</font>",
		CurrentValue = false,
		Flag = "StrengthPC",
		Callback = function(p81)
        if not p81 then
            t2.value73()

            return
        end

        local Character = t1.value3.Character

        if not Character then
            return
        end

        Character:WaitForChild("HumanoidRootPart")
        Workspace.ChildAdded:Connect(function(child)
            if not t2.value69 then
                return
            end

            if child.Name == "GrabParts" then
                local GrabPart = child:FindFirstChild("GrabPart")
                local v1859 = GrabPart and GrabPart:FindFirstChild("WeldConstraint")
                local u1860 = v1859 and v1859.Part1

                if u1860 then
                    child:GetPropertyChangedSignal("Parent"):Connect(function()
                        if not child.Parent and t2.value69 then
                            if t2.value72 then
                                t2.value72:Disconnect()
                            end

                            t2.value7.InputBegan:Connect(function(input)
                                if input.UserInputType == Enum.UserInputType.MouseButton2 then
                                    local BodyVelocity = Instance.new("BodyVelocity")

                                    BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                                    BodyVelocity.Velocity = camera.CFrame.LookVector * t2.value68
                                    BodyVelocity.Parent = u1860
                                    t2.value8:AddItem(BodyVelocity, 1)
                                end
                            end)
                        end
                    end)
                end
            end
        end)
    end
	})
    GrabLinesTab:CreateToggle({
		Name = "Strength (Mobile)  <font face=\"GothamBlack\" color=\"rgb(255, 255, 255)\">(PLAYER & OBJECT)</font>    <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>\t<font face=\"GothamBlack\" color=\"rgb(255,255,0)\">POWER</font>",
		CurrentValue = false,
		Flag = "StrengthMobile",
		Callback = function(p82)
        if not p82 then
            t2.value74()

            return
        end

        t2.value75()
    end
	})
    GrabLinesTab:CreateSlider({
		Name = "Strength Force",
		Range = {
			100,
			10000
		},
		Increment = 100,
		Suffix = "Force",
		CurrentValue = 1000,
		Flag = "StrengthForce",
		Callback = function(p83)
        t2.value68 = p83
    end
	})
    anchoredParts = {}
    anchoredConnections = {}
    compiledGroups = {}
    compileConnections = {}
    renderSteppedConnections = {}
    groupBillboardGuis = {}
    partHighlights = {}
    selectedGroupIndex = 1
    GroupDropdown = nil

    local function v67(p84)
        for _, v in ipairs(p84) do
            if v then
                v:Disconnect()
            end
        end

        table.clear(p84)
    end

    function getHighlight(p85)
        return p85:FindFirstChild("Highlight") or p85.Parent and p85.Parent:FindFirstChild("Highlight")
    end
    function FindFirstAncestorOfType(p86, p87)
        local p86Parent = p86.Parent

        while p86Parent do
            if p86Parent:IsA(p87) then
                return p86Parent
            end

            p86Parent = p86Parent.Parent
        end

        return nil
    end
    function createHighlight(p88)
        local Highlight = Instance.new("Highlight")

        Highlight.DepthMode = Enum.HighlightDepthMode.Occluded
        Highlight.FillTransparency = 1
        Highlight.Name = "Highlight"
        Highlight.OutlineColor = Color3.new(0, 0, 1)
        Highlight.OutlineTransparency = 0
        Highlight.Parent = p88

        return Highlight
    end
    function rmGroupBillboard(p89)
        if groupBillboardGuis[p89] then
            groupBillboardGuis[p89]:Destroy()
            groupBillboardGuis[p89] = nil
        end
    end
    function mkGroupBillboard(p90, p91, p92)
        rmGroupBillboard(p91)

        local BillboardGui = Instance.new("BillboardGui")

        BillboardGui.Adornee = p90
        BillboardGui.Size = UDim2.new(0, 120, 0, 60)
        BillboardGui.AlwaysOnTop = true
        BillboardGui.StudsOffset = Vector3.new(0, 3, 0)
        BillboardGui.Parent = CoreGui

        local TextLabel = Instance.new("TextLabel")

        TextLabel.Size = UDim2.new(1, 0, 0.6, 0)
        TextLabel.BackgroundTransparency = 1
        TextLabel.Text = "GROUP " .. p91
        TextLabel.TextColor3 = Color3.new(0, 1, 0)
        TextLabel.TextStrokeTransparency = 0
        TextLabel.Font = Enum.Font.GothamBold
        TextLabel.TextScaled = true
        TextLabel.Parent = BillboardGui

        local TextLabel2 = Instance.new("TextLabel")

        TextLabel2.Size = UDim2.new(1, 0, 0.4, 0)
        TextLabel2.Position = UDim2.new(0, 0, 0.6, 0)
        TextLabel2.BackgroundTransparency = 1
        TextLabel2.Text = p92 .. " parts"
        TextLabel2.TextColor3 = Color3.new(1, 1, 1)
        TextLabel2.TextStrokeTransparency = 0
        TextLabel2.Font = Enum.Font.Gotham
        TextLabel2.TextScaled = true
        TextLabel2.Parent = BillboardGui
        groupBillboardGuis[p91] = BillboardGui
    end
    function updatePartHighlight(p93, p94)
        local v506 = getHighlight(p93)

        if v506 then
            if p94 and p94 ~= localPlayer.Name then
                v506.OutlineColor = Color3.new(1, 0, 0)
            else
                v506.OutlineColor = Color3.new(0, 0, 1)
            end

            partHighlights[p93] = p94
        end
    end
    function onPartOwnerChanged(p95, p96)
        if p95.Name == "PartOwner" then
            updatePartHighlight(p96, p95.Value)
        end
    end
    function createBodyMovers(p97, p98, p99)
        for _, child in ipairs(p97:GetChildren()) do
            if child:IsA("BodyPosition") or child:IsA("BodyGyro") then
                child:Destroy()
            end
        end

        local BodyPosition = Instance.new("BodyPosition")
        local BodyGyro = Instance.new("BodyGyro")

        BodyPosition.P = 15000
        BodyPosition.D = 200
        BodyPosition.MaxForce = Vector3.new(5000000, 5000000, 5000000)
        BodyPosition.Position = p98
        BodyPosition.Parent = p97
        BodyGyro.P = 15000
        BodyGyro.D = 200
        BodyGyro.MaxTorque = Vector3.new(5000000, 5000000, 5000000)
        BodyGyro.CFrame = p99
        BodyGyro.Parent = p97
    end
    function anchorGrab()
        while true do
            pcall(function()
                local GrabParts = workspace:FindFirstChild("GrabParts")
                if not GrabParts then
                    return
                end
                local GrabPart = GrabParts:FindFirstChild("GrabPart")
                if not GrabPart then
                    return
                end
                local WeldConstraint = GrabPart:FindFirstChild("WeldConstraint")
                if not WeldConstraint or not WeldConstraint.Part1 then
                    return
                end
                local v1864 = WeldConstraint.Part1.Name == "SoundPart" and WeldConstraint.Part1 or (WeldConstraint.Part1.Parent:FindFirstChild("SoundPart") or (WeldConstraint.Part1.Parent.PrimaryPart or WeldConstraint.Part1))
                local v1865 = not v1864
                local g1880
                if not v1865 then
                    v1865 = workspace.Map

                    if v1865 then
                        v1865 = v1864:IsDescendantOf(workspace.Map)
                    end
                end
                if v1865 then
                    return
                end
                local v1866 = false
                local v1867, v1868, v1869 = ipairs(compiledGroups)
                repeat
                    local v1870

                    v1869, v1870 = v1867(v1868, v1869)

                    if not v1869 then
                        break
                    end

                    if v1864 == v1870.primaryPart then
                        v1866 = true

                        break
                    end

                    for _, v in ipairs(v1870.group) do
                        if v1864 == v.part then
                            v1866 = true

                            break
                        end
                    end
                until v1866
                if v1866 then
                    return
                end
                for _, player7 in pairs(t1.value1:GetPlayers()) do
                    if v1864:IsDescendantOf(player7.Character) then
                        return
                    end
                end
                local v1875 = true
                local v1876, v1877, v1878 = pairs(v1864:GetDescendants())
                repeat
                    local v1879

                    v1878, v1879 = v1876(v1877, v1878)

                    if not v1878 then
                        g1880 = true
                    end

                    if g1880 then
                        break
                    end
                until table.find(anchoredParts, v1879)
                if not g1880 then
                    v1875 = false
                end
                g1880 = false
                if v1875 and not table.find(anchoredParts, v1864) then
                    local v1881 = FindFirstAncestorOfType(v1864, "Model") or v1864

                    createHighlight(v1881)
                    table.insert(anchoredParts, v1864)

                    local connection = v1881.DescendantAdded:Connect(function(descendant)
                        onPartOwnerChanged(descendant, v1864)
                    end)

                    for _, descendant in ipairs(v1881:GetDescendants()) do
                        onPartOwnerChanged(descendant, v1864)
                    end

                    table.insert(anchoredConnections, connection)
                end
                local v1885 = FindFirstAncestorOfType(v1864, "Model")
                if v1885 and v1885 ~= workspace then
                    local GetDescendants = v1885.GetDescendants

                    for _, v in ipairs(GetDescendants(v1885)) do
                        if v:IsA("BodyPosition") or v:IsA("BodyGyro") then
                            v:Destroy()
                        end
                    end
                else
                    for _, child in ipairs(v1864:GetChildren()) do
                        if child:IsA("BodyPosition") or child:IsA("BodyGyro") then
                            child:Destroy()
                        end
                    end
                end
                while workspace:FindFirstChild("GrabParts") do
                    task.wait()
                end
                createBodyMovers(v1864, v1864.Position, v1864.CFrame)
            end)
            task.wait()
        end
    end
    function cleanupAnchoredParts()
        for _, v in ipairs(anchoredParts) do
            if v and v.Parent then
                if v:FindFirstChild("BodyPosition") then
                    v.BodyPosition:Destroy()
                end

                if v:FindFirstChild("BodyGyro") then
                    v.BodyGyro:Destroy()
                end

                local v518 = getHighlight(v)

                if v518 then
                    v518:Destroy()
                end
            end
        end

        v67(anchoredConnections)
        table.clear(anchoredParts)
    end
    function updateBodyMovers(p100)
        for i, v in ipairs(compiledGroups) do
            if p100 == v.primaryPart then
                for _, v2 in ipairs(v.group) do
                    if v2.part and v2.part.Parent then
                        local BodyPosition = v2.part:FindFirstChild("BodyPosition")
                        local BodyGyro = v2.part:FindFirstChild("BodyGyro")

                        if BodyPosition then
                            BodyPosition.Position = (p100.CFrame * v2.offset).Position
                        end

                        if BodyGyro then
                            BodyGyro.CFrame = p100.CFrame * v2.offset
                        end
                    end
                end

                mkGroupBillboard(p100, i, #v.group + 1)

                return
            end
        end
    end
    function updateGroupDropdown()
        local t25 = {}

        for i = 1, #compiledGroups do
            table.insert(t25, "Group " .. i)
        end

        if #t25 == 0 then
            t25 = { "No groups" }
            selectedGroupIndex = 1
        else
            selectedGroupIndex = math.clamp(selectedGroupIndex, 1, #compiledGroups)
        end

        pcall(function()
            if GroupDropdown then
                GroupDropdown:Refresh(t25)
                GroupDropdown:Set({ "Group " .. selectedGroupIndex })
            end
        end)
    end
    function compileGroup()
        if #anchoredParts == 0 then
            return
        end
        for i = #anchoredParts, 1, -1 do
            local v529 = i
            local v530 = anchoredParts[v529]
            local v531 = false

            for _, v in ipairs(compiledGroups) do
                if v530 == v.primaryPart then
                    v531 = true

                    break
                end

                for _, v3 in ipairs(v.group) do
                    if v530 == v3.part then
                        v531 = true

                        break
                    end
                end

                if v531 then
                    break
                end
            end

            if v531 then
                table.remove(anchoredParts, v529)
            end
        end
        if #anchoredParts == 0 then
            return
        end
        local u536
        local t26 = {}
        for v540, v541 in ipairs(anchoredParts) do

            if v541 and v541.Parent then
                if not u536 then
                    u536 = v541
                else
                    table.insert(t26, v541)
                end
            end
        end
        if not u536 then
            table.clear(anchoredParts)

            return
        end
        anchoredParts = { u536 }
        for v544, v545 in ipairs(t26) do

            table.insert(anchoredParts, v545)
        end
        local Anchored = u536.Anchored
        u536.Anchored = false
        if u536:FindFirstChild("BodyPosition") then
            u536.BodyPosition:Destroy()
        end
        if u536:FindFirstChild("BodyGyro") then
            u536.BodyGyro:Destroy()
        end
        local v547 = getHighlight(u536)
        if not v547 then
            local v548 = u536.Parent and (not not u536.Parent:IsA("Model") and u536.Parent) or u536

            v547 = createHighlight(v548)
        end
        v547.OutlineColor = Color3.new(0, 1, 0)
        local t27 = {}
        for _, v in ipairs(anchoredParts) do
            if v ~= u536 and (v and v.Parent) then
                local v552 = FindFirstAncestorOfType(v, "Model")

                if v552 and v552 ~= workspace then
                    local GetDescendants = v552.GetDescendants

                    for _, v4 in ipairs(GetDescendants(v552)) do
                        if v4:IsA("BasePart") then
                            v4.CanCollide = false
                        end
                    end
                else
                    v.CanCollide = false
                end

                local insert = table.insert
                local v557 = u536.CFrame:ToObjectSpace(v.CFrame)

                insert(t27, {
					part = v,
					offset = v557
				})
            end
        end
        local v558 = #compiledGroups + 1
        table.insert(compiledGroups, {
			primaryPart = u536,
			group = t27,
			wasAnchored = Anchored,
			groupId = v558
		})
        local connection = u536:GetPropertyChangedSignal("CFrame"):Connect(function()
            updateBodyMovers(u536)
        end)
        table.insert(compileConnections, connection)
        local connection2 = t1.value2.Heartbeat:Connect(function()
            updateBodyMovers(u536)
        end)
        table.insert(renderSteppedConnections, connection2)
        for _, v in ipairs(t27) do
            local v563 = v

            if v563.part and v563.part.Parent then
                local connection3 = (v563.part.Parent and (not not v563.part.Parent:IsA("Model") and v563.part.Parent) or v563.part).DescendantAdded:Connect(function(descendant)
                    onPartOwnerChanged(descendant, v563.part)
                end)

                table.insert(compileConnections, connection3)
            end
        end
        mkGroupBillboard(u536, v558, #t27 + 1)
        table.clear(anchoredParts)
        v67(anchoredConnections)
        selectedGroupIndex = #compiledGroups
        updateGroupDropdown()
    end
    function deleteSelectedGroup()
        if #compiledGroups == 0 or (not selectedGroupIndex or selectedGroupIndex > #compiledGroups) then
            return
        end
        local v565 = compiledGroups[selectedGroupIndex]
        for v568, v569 in ipairs(v565.group) do

            if v569.part and v569.part.Parent then
                if v569.part:FindFirstChild("BodyPosition") then
                    v569.part.BodyPosition:Destroy()
                end

                if v569.part:FindFirstChild("BodyGyro") then
                    v569.part.BodyGyro:Destroy()
                end

                v569.part.CanCollide = true

                local v570 = getHighlight(v569.part)

                if v570 then
                    v570:Destroy()
                end
            end
        end
        if v565.primaryPart and v565.primaryPart.Parent then
            if v565.primaryPart:FindFirstChild("BodyPosition") then
                v565.primaryPart.BodyPosition:Destroy()
            end

            if v565.primaryPart:FindFirstChild("BodyGyro") then
                v565.primaryPart.BodyGyro:Destroy()
            end

            v565.primaryPart.CanCollide = true

            local v571 = getHighlight(v565.primaryPart)

            if v571 then
                v571:Destroy()
            end

            if v565.wasAnchored then
                v565.primaryPart.Anchored = true
            end
        end
        rmGroupBillboard(v565.groupId)
        table.remove(compiledGroups, selectedGroupIndex)
        for i, v in ipairs(compiledGroups) do
            v.groupId = i
        end
        if #compiledGroups > 0 then
            selectedGroupIndex = math.min(selectedGroupIndex, #compiledGroups)
        else
            selectedGroupIndex = 1
        end
        updateGroupDropdown()
    end
    function cleanupCompiledGroups()
        for i, v in ipairs(compiledGroups) do
            for _, v5 in ipairs(v.group) do
                if v5.part and v5.part.Parent then
                    if v5.part:FindFirstChild("BodyPosition") then
                        v5.part.BodyPosition:Destroy()
                    end

                    if v5.part:FindFirstChild("BodyGyro") then
                        v5.part.BodyGyro:Destroy()
                    end

                    v5.part.CanCollide = true

                    local v578 = getHighlight(v5.part)

                    if v578 then
                        v578:Destroy()
                    end
                end
            end

            if v.primaryPart and v.primaryPart.Parent then
                if v.primaryPart:FindFirstChild("BodyPosition") then
                    v.primaryPart.BodyPosition:Destroy()
                end

                if v.primaryPart:FindFirstChild("BodyGyro") then
                    v.primaryPart.BodyGyro:Destroy()
                end

                v.primaryPart.CanCollide = true

                local v579 = getHighlight(v.primaryPart)

                if v579 then
                    v579:Destroy()
                end

                if v.wasAnchored then
                    v.primaryPart.Anchored = true
                end
            end

            rmGroupBillboard(i)
        end

        v67(compileConnections)
        v67(renderSteppedConnections)
        table.clear(compiledGroups)
        groupBillboardGuis = {}
        partHighlights = {}
        selectedGroupIndex = 1
        updateGroupDropdown()
    end

    t2.value76 = nil
    GrabLinesTab:CreateSection("Anchor")
    GrabLinesTab:CreateToggle({
		Name = "Anchor Grab\t <font face=\"GothamBlack\" color=\"rgb(255,40,40)\">FREEZE</font>\t\t<font face=\"GothamBlack\" color=\"rgb(255, 255, 255)\">(OBJECT)</font>",
		CurrentValue = false,
		Flag = "AnchorGrab",
		Callback = function(p101)
        if p101 then
            t2.value76 = coroutine.create(anchorGrab)
            coroutine.resume(t2.value76)

            return
        end

        if t2.value76 then
            coroutine.close(t2.value76)
        end
    end
	})
    GrabLinesTab:CreateButton({
		Name = "Unanchor Parts\t<font face=\"GothamBlack\" color=\"rgb(255,90,0)\">UNFREEZE</font>",
		Callback = cleanupAnchoredParts
	})
    GrabLinesTab:CreateSection("Groups")

    local _GrabLinesTab3 = GrabLinesTab
    local _compileGroup = compileGroup

    _GrabLinesTab3:CreateButton({
		Name = "Compile Parts\t  <font face=\"GothamBlack\" color=\"rgb(155,0,255)\">ASSEMBLE</font>",
		Callback = _compileGroup
	})
    GroupDropdown = GrabLinesTab:CreateDropdown({
		Name = "Select Group\t<font face=\"GothamBlack\" color=\"rgb(255,0,130)\">PICK</font>",
		Options = { "No groups" },
		CurrentOption = { "No groups" },
		Flag = "SelectedGroup",
		Callback = function(p102)
        for i = 1, #compiledGroups do
            local v583 = i

            if "Group " .. v583 == p102[1] then
                selectedGroupIndex = v583

                return
            end
        end
    end
	})
    GrabLinesTab:CreateButton({
		Name = "Delete Selected Group\t <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">REMOVE</font>",
		Callback = deleteSelectedGroup
	})
    GrabLinesTab:CreateButton({
		Name = "Delete All Group\t  <font face=\"GothamBlack\" color=\"rgb(180,0,20)\">DELETE</font>",
		Callback = cleanupCompiledGroups
	})
    GrabLinesTab:CreateLabel("Line", "pencil")
    GrabLinesTab:CreateToggle({
		Name = "Extend Line (Mobile)  <font face=\"GothamBlack\" color=\"rgb(255, 255, 255)\">(PLAYER & OBJECT)</font>    <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>\t<font face=\"GothamBlack\" color=\"rgb(35,60,79)\">STRETCH</font>",
		CurrentValue = false,
		Flag = "ExtendLineMobile",
		Callback = function(p103)
        t2.value64 = p103

        if p103 then
            if not t2.value67 then
                UI()
            end

            Hide(t2.value10)
            camera.CameraSubject = humanoid
            camera.CameraType = Enum.CameraType.Custom

            return
        end

        Reset()
    end
	})

    local t28 = {
		d = 11,
		inc = 7,
		on = false,
		i = nil,
		c = nil
	}

    t2.value77 = nil
    t2.value77 = t28

    function t2.value78()
        if t2.value77.i then
            t2.value77.i:Disconnect()
            t2.value77.i = nil
        end

        if t2.value77.c then
            t2.value77.c:Disconnect()
            t2.value77.c = nil
        end

        t2.value77.d = 11
    end
    function t2.value79()
        local CurrentCamera = Workspace.CurrentCamera

        t2.value77.i = t2.value7.InputChanged:Connect(function(input)
            if not t2.value77.on then
                return
            end

            if input.UserInputType == Enum.UserInputType.MouseWheel then
                if t2.value77.d < 11 then
                    t2.value77.d = 11
                end

                if input.Position.Z > 0 then
                    local value77 = t2.value77
                    local s1 = "d"
                    local inc = t2.value77.inc

                    value77[s1] = value77[s1] + inc

                    return
                end

                if input.Position.Z < 0 then
                    local value77 = t2.value77
                    local s2 = "d"
                    local inc = t2.value77.inc

                    value77[s2] = value77[s2] - inc
                end
            end
        end)
        t2.value77.c = workspace.ChildAdded:Connect(function(child)
            if not t2.value77.on or (child.Name ~= "GrabParts" or not child:IsA("Model")) then
                return
            end

            task.wait(0.2)

            if not child.Parent then
                return
            end

            local DragPart = child:FindFirstChild("DragPart")

            if not DragPart then
                return
            end

            local clone = DragPart:Clone()

            clone.Name = "DragPart_scroll"

            local DragAttach = clone:FindFirstChild("DragAttach")

            if clone:FindFirstChild("AlignPosition") and DragAttach then
                clone.AlignPosition.Attachment1 = DragAttach
            end

            clone.Parent = child
            t2.value77.d = (clone.Position - CurrentCamera.CFrame.Position).Magnitude

            if clone:FindFirstChild("AlignOrientation") then
                clone.AlignOrientation.Enabled = false
            end

            if DragPart:FindFirstChild("AlignPosition") then
                DragPart.AlignPosition.Enabled = false
            end

            task.spawn(function()
                while child.Parent and t2.value77.on do
                    clone.Position = CurrentCamera.CFrame.Position + CurrentCamera.CFrame.LookVector * t2.value77.d
                    t1.value2.RenderStepped:Wait()
                end

                if clone then
                    clone:Destroy()
                end

                t2.value77.d = 11
            end)
        end)
    end

    GrabLinesTab:CreateToggle({
		Name = "Extend Line (PC)  <font face=\"GothamBlack\" color=\"rgb(255, 255, 255)\">(PLAYER & OBJECT)</font>    <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>   <font face=\"GothamBlack\" color=\"rgb(255,60,0)\">STRETCH</font>",
		CurrentValue = false,
		Flag = "extendLineToggleFlag",
		Callback = function(p104)
        t2.value77.on = p104

        if p104 then
            t2.value79()

            return
        end

        t2.value78()
    end
	})

    local _GrabLinesTab4 = GrabLinesTab
    local _tostring = tostring
    local value77 = t2.value77
    local CreateInput = _GrabLinesTab4.CreateInput
    local v75 = _tostring(value77.inc)

    CreateInput(_GrabLinesTab4, {
		Name = "Scroll Force",
		CurrentValue = v75,
		PlaceholderText = "Default: 7",
		RemoveTextAfterFocusLost = false,
		Flag = "extendLineInputFlag",
		Callback = function(p105)
        local num = tonumber(p105)

        if num then
            t2.value77.inc = num
        end
    end
	})
    GrabLinesTab:CreateSection("Others Lines")
    GrabLinesTab:CreateToggle({
		Name = "Invisble Line\t<font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>",
		CurrentValue = false,
		Flag = "InvisbleLine",
		Callback = function(p106)
        invisline = p106

        while invisline do
            CreateGrabLine:FireServer()
            task.wait()
        end
    end
	})
    GrabLinesTab:CreateToggle({
		Name = "Crazy Line\t <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>",
		CurrentValue = false,
		Flag = "CrazyLine",
		Callback = function(p107)
        crazyline = p107

        while crazyline do
            for _, player8 in ipairs(game:GetService("Players"):GetPlayers()) do
                local Character = player8.Character

                if Character then
                    local Head = Character:FindFirstChild("Head")

                    if Head and CreateGrabLine then
                        CreateGrabLine:FireServer(Head, Head.CFrame)
                        task.wait()
                    end
                end
            end
        end
    end
	})
    GrabLinesTab:CreateToggle({
		Name = "Spinning <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">R</font><font face=\"GothamBlack\" color=\"rgb(255,127,0)\">A</font><font face=\"GothamBlack\" color=\"rgb(255,255,0)\">I</font><font face=\"GothamBlack\" color=\"rgb(0,255,0)\">N</font><font face=\"GothamBlack\" color=\"rgb(0,255,255)\">B</font><font face=\"GothamBlack\" color=\"rgb(0,0,255)\">O</font><font face=\"GothamBlack\" color=\"rgb(255,0,255)\">W</font> Line   <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>",
		CurrentValue = false,
		Flag = "SpinningRainbowLine",
		Callback = function(p108)
        spinningLine = p108

        if spinningLine then
            local Players = game:GetService("Players")
            local ReplicatedStorage = game:GetService("ReplicatedStorage")
            local RunService = game:GetService("RunService")
            local LocalPlayer = Players.LocalPlayer
            local v600 = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
            local v601 = v600:WaitForChild("Torso", 5) or v600:WaitForChild("UpperTorso", 5)

            if not v601 then
                return
            end

            local GrabEvents2 = ReplicatedStorage:WaitForChild("GrabEvents")
            local CreateGrabLine2 = GrabEvents2:WaitForChild("CreateGrabLine")
            local ExtendGrabLine = GrabEvents2:WaitForChild("ExtendGrabLine")
            local UpdateLineColorsEvent = ReplicatedStorage:WaitForChild("DataEvents"):WaitForChild("UpdateLineColorsEvent")
            local huge = math.huge
            local n5 = 0
            local Position = v601.Position

            local function v609(p109)
                local timestamp = tick()
                local _Color3 = Color3
                local v1906 = (timestamp * 0.2 + p109) % 1

                return _Color3.fromHSV(v1906, 1, 1)
            end

            rainbowConnection = RunService.Heartbeat:Connect(function(dt)
                if not spinningLine then
                    if rainbowConnection then
                        rainbowConnection:Disconnect()
                    end

                    return
                end

                n5 = (n5 + 3.141592653589793 * dt) % 6.283185307179586

                local v1908 = math.sin(tick() * 0) * 0 + 10
                local vector3 = Vector3.new(math.cos(n5) * v1908, math.sin(tick() * 2) * 1.5, math.sin(n5) * v1908)
                local v1910 = v601.Position + vector3

                Position = Position:Lerp(v1910, math.clamp(dt * huge, 0, 1))

                local v1911 = Position - v601.Position

                CreateGrabLine2:FireServer(v601, CFrame.new(v1911 * -1))
                ExtendGrabLine:FireServer(0)

                local v1912 = UpdateLineColorsEvent
                local colorSequence = ColorSequence.new({
						ColorSequenceKeypoint.new(0, v609(0)),
						ColorSequenceKeypoint.new(1, v609(0.5))
					})
                local timestamp = tick()
                local _Color3 = Color3
                local v1916 = (timestamp * 0.2 + 0) % 1
                local v1917 = _Color3.fromHSV(v1916, 1, 1)
                local timestamp2 = tick()
                local _Color3_2 = Color3
                local v1920 = (timestamp2 * 0.2 + 0.125) % 1
                local v1921 = _Color3_2.fromHSV(v1920, 1, 1)
                local timestamp3 = tick()
                local _Color3_3 = Color3
                local v1924 = (timestamp3 * 0.2 + 0.25) % 1
                local v1925 = _Color3_3.fromHSV(v1924, 1, 1)
                local timestamp4 = tick()
                local _Color3_4 = Color3
                local v1928 = (timestamp4 * 0.2 + 0.375) % 1
                local v1929 = _Color3_4.fromHSV(v1928, 1, 1)
                local timestamp5 = tick()
                local _Color3_5 = Color3
                local v1932 = (timestamp5 * 0.2 + 0.5) % 1
                local v1933 = _Color3_5.fromHSV(v1932, 1, 1)
                local timestamp6 = tick()
                local _Color3_6 = Color3
                local v1936 = (timestamp6 * 0.2 + 0.625) % 1
                local v1937 = _Color3_6.fromHSV(v1936, 1, 1)
                local timestamp7 = tick()
                local _Color3_7 = Color3
                local v1940 = (timestamp7 * 0.2 + 0.75) % 1
                local v1941 = _Color3_7.fromHSV(v1940, 1, 1)
                local timestamp8 = tick()
                local _Color3_8 = Color3
                local v1944 = (timestamp8 * 0.2 + 0.875) % 1
                local v1945 = _Color3_8.fromHSV(v1944, 1, 1)
                local timestamp9 = tick()
                local _Color3_9 = Color3
                local v1948 = (timestamp9 * 0.2 + 0) % 1

                v1912:FireServer(colorSequence, v1917, v1921, v1925, v1929, v1933, v1937, v1941, v1945, _Color3_9.fromHSV(v1948, 1, 1), v609(0))
            end)

            return
        end

        if rainbowConnection then
            rainbowConnection:Disconnect()
        end
    end
	})
    GrabLinesTab:CreateLabel("Others Lines : You can't see it, but other players can.", Color3.fromRGB(255, 255, 255), false)
    GrabLinesTab:CreateSection("Lag")
    t2.value80 = false
    t2.value81 = 10

    function lagF()
        while t2.value80 do
            local v610 = t1.value3.Character or t1.value3.CharacterAdded:Wait()

            v610:WaitForChild("HumanoidRootPart")
            v610:WaitForChild("Humanoid")

            if CreateGrabLine then
                for _ = 0, t2.value81 do
                    for _, player9 in ipairs(t1.value1:GetPlayers()) do
                        if player9 ~= t1.value3 and player9.Character then
                            local v614 = player9.Character:FindFirstChild("Torso") or player9.Character:FindFirstChild("HumanoidRootPart")

                            if v614 then
                                CreateGrabLine:FireServer(v614, v614.CFrame)
                            end
                        end
                    end
                end
            end

            task.wait(1)
        end
    end

    GrabLinesTab:CreateToggle({
		Name = "Lag\t  <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Flag = "LagToggle",
		Callback = function(p110)
        t2.value80 = p110

        if p110 then
            task.spawn(lagF)
        end
    end
	})

    local _GrabLinesTab5 = GrabLinesTab
    local str5 = tostring(t2.value81)

    _GrabLinesTab5:CreateInput({
		Name = "Lag Intensity",
		CurrentValue = str5,
		PlaceholderText = "Enter number of lines",
		RemoveTextAfterFocusLost = false,
		Flag = "LinesInput",
		Callback = function(p111)
        local num = tonumber(p111)

        if not (num and num > 0) then
        end
    end
	})
    t2.value82 = nil
    t2.value83 = nil
    t2.value84 = nil
    t2.value85 = false
    t2.value86 = Vector3.new(6, -18.5, 0)

    function DisableCollisions(p112)
        for _, descendant in ipairs(p112:GetDescendants()) do
            if descendant:IsA("BasePart") then
                descendant.CanCollide = false
            end
        end
    end
    function setNoCollideChar(p113)
        local GetDescendants = p113.GetDescendants

        for _, v in ipairs(GetDescendants(p113)) do
            if v:IsA("BasePart") then
                v.CanCollide = false
            end
        end
    end
    function isTooHigh(p114)
        local Character = p114.Character
        local v628 = Character and Character:FindFirstChild("HumanoidRootPart")

        return not v628 or v628.Position.Y > 100000
    end

    local function v78()
        local Character = t1.value3.Character

        if Character then
            local Humanoid11 = Character:FindFirstChildOfClass("Humanoid")

            if Humanoid11 and Humanoid11.SeatPart then
                local SeatPartParent = Humanoid11.SeatPart.Parent

                if SeatPartParent and SeatPartParent.Name == "CreatureBlobman" then
                    return SeatPartParent
                end
            end
        end

        local v632 = Workspace:FindFirstChild(t1.value3.Name .. "SpawnedInToys")

        if v632 then
            local CreatureBlobman = v632:FindFirstChild("CreatureBlobman")

            if CreatureBlobman then
                return CreatureBlobman
            end
        end

        return nil
    end

    t2.value87 = nil

    function t2.value87()
        local Character = t1.value3.Character

        if not Character then
            return false
        end

        return Character:FindFirstChild("HumanoidRootPart") ~= nil
    end

    t2.value88 = nil

    function t2.value88()
        if not t2.value87() then
            return
        end

        local v634 = t1.value3.Character.HumanoidRootPart.CFrame * CFrame.new(0, -8, 8)

        task.spawn(function()
            pcall(function()
                local SpawnToyRemoteFunction = t2.value9.MenuToys.SpawnToyRemoteFunction
                local v2320 = v634
                local t29 = { Vector3.new(0, 177.22, 0) }

                SpawnToyRemoteFunction:InvokeServer("CreatureBlobman", v2320, v1(t29))
            end)
        end)
    end
    function t2.value89()
        local v635 = v78()

        if v635 then
            return v635
        end

        t2.value88()

        for _ = 1, 30 do
            task.wait(0.1)

            local v637 = v78()

            if v637 then
                return v637
            end
        end

        return nil
    end

    t2.value90 = {}
    t2.value90.__index = t2.value90

    function t2.value90.new()
        return (setmetatable({}, t2.value90))
    end
    function t2.value90.attach(p115, p116)
        p115:detach()

        local Part = Instance.new("Part")
        local vector3 = Vector3.new(0.2, 0.2, 0.2)
        local _Workspace = Workspace

        Part.Name = "CameraAnchor"
        Part.Size = vector3
        Part.Transparency = 1
        Part.Anchored = true
        Part.CanCollide = false
        Part.CFrame = p116
        Part.Parent = _Workspace
        p115.part = Part

        local CurrentCamera = Workspace.CurrentCamera

        CurrentCamera.CameraType = Enum.CameraType.Custom
        CurrentCamera.CameraSubject = Part
    end
    function t2.value90.detach(p117)
        if p117.part then
            p117.part:Destroy()
            p117.part = nil
        end

        local CurrentCamera = Workspace.CurrentCamera
        local Character = t1.value3.Character

        if Character and Character:FindFirstChild("Humanoid") then
            CurrentCamera.CameraSubject = Character.Humanoid

            return
        end

        CurrentCamera.CameraType = Enum.CameraType.Custom
        CurrentCamera.CameraSubject = CurrentCamera
    end

    t2.value91 = t2.value90.new()

    function saveOriginalPosAttr()
        local Character = t1.value3.Character
        local v648 = Character and Character:FindFirstChild("HumanoidRootPart")

        if v648 then
            Character:SetAttribute("OriginalPosition", v648:GetPivot())
        end
    end
    function getOriginalPosAttr()
        local Character = t1.value3.Character

        return Character and Character:GetAttribute("OriginalPosition") or nil
    end
    function initCharAttrs()
        local Character = t1.value3.Character

        if Character and Character:FindFirstChild("HumanoidRootPart") then
            Character:SetAttribute("OriginalPosition", Character.HumanoidRootPart:GetPivot())
            Character:SetAttribute("SavingOriginalPos", false)
        end
    end
    function scheduleReturnHome()
        local v651 = getOriginalPosAttr()
        if not v651 then
            return
        end
        local connection
        connection = t1.value2.Heartbeat:Connect(function()
            local Character = t1.value3.Character
            local v1950 = Character and Character:FindFirstChild("HumanoidRootPart")

            if v1950 then
                v1950:PivotTo(v651)

                if getgenv().originalFallenHeight then
                    Workspace.FallenPartsDestroyHeight = getgenv().originalFallenHeight
                end

                Character:SetAttribute("SavingOriginalPos", false)
            end

            t2.value91:detach()
            connection:Disconnect()
        end)
    end
    function modifyTarget(p118, p119, p120)
        if not (p118 and p119) or p119.Health <= 0 then
            return
        end

        if p120 then
            local v656 = t2.value89()

            if v656 and v656:FindFirstChild("BlobmanSeatAndOwnerScript") then
                local CreatureDrop = v656.BlobmanSeatAndOwnerScript:FindFirstChild("CreatureDrop")

                if CreatureDrop then
                    for _, descendant in ipairs(p119.Parent:GetDescendants()) do
                        if descendant:IsA("Weld") or descendant:IsA("BallSocketConstraint") then
                            CreatureDrop:FireServer(descendant, descendant)
                        end
                    end
                end
            end
        end

        p119.Sit = false
        p119:ChangeState(Enum.HumanoidStateType.Running)
        p119:SetStateEnabled(Enum.HumanoidStateType.Seated, false)
        p119:ChangeState(Enum.HumanoidStateType.GettingUp)

        local player10 = t1.value1:GetPlayerFromCharacter(p119.Parent)

        if player10 and player10:FindFirstChild("IsHeld") then
            player10.IsHeld.Value = false
        end

        local Ragdolled = p119:FindFirstChild("Ragdolled")

        if Ragdolled then
            Ragdolled.Value = false
        end

        local BodyVelocity = Instance.new("BodyVelocity")
        local BodyAngularVelocity = Instance.new("BodyAngularVelocity")

        BodyVelocity.MaxForce = Vector3.new(10000000, -10000000, 10000000)
        BodyVelocity.P = 1000000
        BodyVelocity.Velocity = Vector3.new(math.random(-500, 50), -50, math.random(-50, 50))
        BodyAngularVelocity.MaxTorque = Vector3.new(-10000000, -10000000, -10000000)
        BodyAngularVelocity.P = 1000000
        BodyAngularVelocity.AngularVelocity = Vector3.new(math.random(-500, 300), math.random(-300, 300), math.random(-500, 500))
        BodyVelocity.Parent = p118
        BodyAngularVelocity.Parent = p118
        p119.BreakJointsOnDeath = false
        p119:ChangeState(Enum.HumanoidStateType.Dead)
        p119.RigType = Enum.HumanoidRigType.R15
        task.delay(2, function()
            if BodyVelocity.Parent then
                BodyVelocity:Destroy()
            end

            if BodyAngularVelocity.Parent then
                BodyAngularVelocity:Destroy()
            end
        end)
    end
    function performKill()
        if not t2.value82 then
            return
        end

        local t2value82 = t1.value1:FindFirstChild(t2.value82)
        local v665 = t2value82 and t2value82.Character
        local v666 = v665 and v665:FindFirstChild("HumanoidRootPart")
        local v667 = v665 and v665:FindFirstChild("Humanoid")
        local v668 = v665 and v665:FindFirstChild("Head")

        if not t2value82 or (not v666 or (not v667 or not v668)) then
            return
        end

        if isTooHigh(t2value82) then
            return
        end

        if t2value82:FindFirstChild("InPlot") and t2value82.InPlot.Value then
            return
        end

        if v667:GetState() == Enum.HumanoidStateType.Dead then
            return
        end

        local Character = t1.value3.Character
        local v670 = Character and Character:FindFirstChild("HumanoidRootPart")

        if not Character or not v670 then
            return
        end

        if not Character:GetAttribute("SavingOriginalPos") then
            saveOriginalPosAttr()
        end

        Character:SetAttribute("SavingOriginalPos", true)
        getgenv().originalFallenHeight = Workspace.FallenPartsDestroyHeight
        Workspace.FallenPartsDestroyHeight = (0/0)

        local v671 = getOriginalPosAttr()

        if v671 then
            t2.value91:attach(v671)
        end

        v670:PivotTo((CFrame.new(v666.Position + t2.value86)))
        setNoCollideChar(v665)
        SetNetworkOwner:FireServer(v666, v666.CFrame)
        task.wait(0.05)
        DestroyGrabLine:FireServer(v666)
        task.wait(0.05)

        if v668:FindFirstChild("PartOwner") and v668.PartOwner.Value == t1.value3.Name then
            task.wait(0.05)
            modifyTarget(v666, v667, false)
        end

        scheduleReturnHome()
    end
    function StartLoopKill()
        if t2.value83 then
            t2.value83:Disconnect()
        end

        t2.value83 = t1.value2.Heartbeat:Connect(performKill)
    end
    function StopLoopKill()
        if t2.value83 then
            t2.value83:Disconnect()
        end

        t2.value91:detach()
    end
    function sendToSky(p121, p122)
        DisableCollisions(p122.Parent)

        local BodyVelocity = Instance.new("BodyVelocity")

        BodyVelocity.Velocity = Vector3.new(0, 1000000000, 0)
        BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
        BodyVelocity.P = 100000000
        BodyVelocity.Parent = p121
        p122.Sit = false
        p122.Jump = true
        task.delay(3, function()
            if BodyVelocity.Parent then
                BodyVelocity:Destroy()
            end
        end)
    end
    function executeKick()
        if not t2.value82 then
            return
        end

        local t2value82 = t1.value1:FindFirstChild(t2.value82)
        local v676 = t2value82 and t2value82.Character
        local v677 = v676 and v676:FindFirstChild("HumanoidRootPart")
        local v678 = v676 and v676:FindFirstChild("Head")
        local v679 = v676 and v676:FindFirstChild("Humanoid")

        if not v677 and (not not v678 and v679) or v679.Health <= 0 then
            return
        end

        if isTooHigh(t2value82) then
            return
        end

        if t2value82:FindFirstChild("InPlot") and t2value82.InPlot.Value then
            return
        end

        local Character = t1.value3.Character

        if not Character or not Character:FindFirstChild("HumanoidRootPart") then
            return
        end

        local Pivot = Character:GetPivot()
        local new = CFrame.new
        local Position = v677.Position
        local new2 = Vector3.new
        local PivotTo = Character.PivotTo
        local t30 = { new(Position + new2(0, 0, -3)) }

        PivotTo(Character, v1(t30))
        DisableCollisions(v676)
        SetNetworkOwner:FireServer(v677, v677.CFrame)
        task.wait()
        Character:PivotTo(Pivot)
        task.wait(0.1)
        DestroyGrabLine:FireServer(v677)
        task.wait(0.1)

        local PartOwner = v678:FindFirstChild("PartOwner")

        if PartOwner and PartOwner.Value == t1.value3.Name then
            sendToSky(v677, v679)
        end
    end
    function StartLoopKick()
        if t2.value84 then
            t2.value84:Disconnect()
        end

        t2.value85 = true
        t2.value84 = t1.value2.Heartbeat:Connect(function()
            if t2.value85 then
                executeKick()
            end
        end)
    end
    function StopLoopKick()
        if t2.value84 then
            t2.value84:Disconnect()
        end
    end

    t2.value92 = nil
    LoopFling = {
		on = false,
		targets = {},
		tpSpeed = 0.3,
		magnetRange = 5,
		stay = 0.5,
		back = 0.5
	}

    function tpTo(p123)
        local Character = t1.value3.Character
        local v690 = Character and Character:FindFirstChild("HumanoidRootPart")

        if not v690 then
            return
        end

        for _ = 1, 5 do
            v690.CFrame = v690.CFrame:Lerp(p123, LoopFling.tpSpeed)
            task.wait(0.02)
        end
    end
    function stick(p124)
        local Character = t1.value3.Character
        local v694 = Character and Character:FindFirstChild("HumanoidRootPart")

        if not v694 then
            return
        end

        if (v694.Position - p124.Position).Magnitude < LoopFling.magnetRange then
            v694.CFrame = p124.CFrame + Vector3.new(0, 0, -1)
            v694.Velocity = Vector3.new(0, 0, 0)
        end
    end
    function execFling(p125)
        local Humanoid12 = p125:FindFirstChildOfClass("Humanoid")
        local HumanoidRootPart = p125:FindFirstChild("HumanoidRootPart")

        if not Humanoid12 or not HumanoidRootPart then
            return
        end

        SetNetworkOwner:FireServer(HumanoidRootPart, HumanoidRootPart.CFrame)

        local BodyVelocity = Instance.new("BodyVelocity")

        BodyVelocity.MaxForce = Vector3.new(100000, 100000, 100000)
        BodyVelocity.Velocity = Vector3.new(0, 1000, 0)
        BodyVelocity.Parent = HumanoidRootPart

        local v699 = true

        while LoopFling.on do
            BodyVelocity.Velocity = v699 and Vector3.new(0, 1000, 0) or Vector3.new(0, -1000, 0)
            v699 = not v699
            task.wait(0.5)
        end

        BodyVelocity:Destroy()
    end
    function startFlingFor(p126)
        if not p126 then
            return
        end

        while LoopFling.on do
            local Character = p126.Character
            local v702 = Character and Character:FindFirstChild("HumanoidRootPart")

            if v702 then
                tpTo(v702.CFrame + Vector3.new(0, 0, -2))
                task.wait(0.1)
                stick(v702)
                execFling(Character)
                task.wait(LoopFling.stay)
            end

            if t2.value92 then
                tpTo(t2.value92)
                task.wait(LoopFling.back)
            end

            task.wait()
        end
    end
    function autoFlingLoop()
        while LoopFling.on do
            for _, v in ipairs(LoopFling.targets) do
                local v6 = t1.value1:FindFirstChild(v)

                if v6 and v6.Character then
                    task.spawn(function()
                        startFlingFor(v6)
                    end)
                end
            end

            task.wait(0.1)
        end
    end
    function StartLoopBounce(p127)
        if not p127 or p127 == "" then
            return
        end

        local Character = t1.value3.Character
        local v708 = Character and Character:FindFirstChild("HumanoidRootPart")

        if v708 then
            t2.value92 = v708.CFrame
        end

        LoopFling.on = true
        LoopFling.targets = { p127 }
        task.spawn(autoFlingLoop)
    end
    function StopLoopBounce()
        LoopFling.on = false

        local value92 = t2.value92

        task.wait(0.1)

        local Character = t1.value3.Character
        local v711 = Character and Character:FindFirstChild("HumanoidRootPart")

        if v711 and value92 then
            v711.CFrame = value92
        end
    end

    LoopTab:CreateLabel("TARGET", "user")
    LoopPlayerDropdown = LoopTab:CreateDropdown({
		Name = "Select Player",
		Options = {},
		CurrentOption = {},
		MultipleOptions = false,
		Flag = "LoopPlayerDropdown",
		Callback = function(p128)
        t2.value82 = p128[1]:match("@([%w_]+)")
    end
	})

    function LoopGetRole(p129)
        local v714 = string.lower(p129)

        if superAdmins[v714] then
            return "superadmin"
        end

        if admins[v714] then
            return "admin"
        end

        return "user"
    end
    function LoopOptionText(p130)
        return string.format("👤 @%s (%s)", p130.Name, p130.DisplayName or "")
    end
    function LoopRefreshDropdown()
        local t31 = {}

        for _, player11 in ipairs(t1.value1:GetPlayers()) do
            if player11 ~= t1.value3 and LoopGetRole(player11.Name) ~= "superadmin" then
                table.insert(t31, LoopOptionText(player11))
            end
        end

        LoopPlayerDropdown:Refresh(t31)
    end

    t1.value1.PlayerAdded:Connect(function()
        task.wait(0.5)
        LoopRefreshDropdown()
    end)
    t1.value1.PlayerRemoving:Connect(function()
        task.wait(0.5)
        LoopRefreshDropdown()
    end)
    LoopRefreshDropdown()
    LoopTab:CreateLabel("Harmless", "shield")
    LoopTab:CreateButton({
		Name = "Bring   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">GRAB</font>   <font face=\"GothamBlack\" color=\"rgb(210,8,255)\">SUMMON</font>",
		Callback = function()
        if not t2.value82 then
            return
        end

        local Players = game:GetService("Players")
        local ReplicatedStorage = game:GetService("ReplicatedStorage")
        local LocalPlayer = Players.LocalPlayer
        local HumanoidRootPart = (LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()):WaitForChild("HumanoidRootPart")
        local HumanoidRootPartCFrame = HumanoidRootPart.CFrame
        local t2value82 = Players:FindFirstChild(t2.value82)

        if not t2value82 then
            return
        end

        if t2value82:FindFirstChild("InPlot") and t2value82.InPlot.Value then
            return
        end

        if not t2value82.Character or not t2value82.Character:FindFirstChild("Head") then
            return
        end

        local Head = t2value82.Character.Head
        local n6 = 10
        local n7 = 0

        if not Head:FindFirstChild("PartOwner") or Head.PartOwner.Value ~= LocalPlayer.Name then
            if not (n6 <= n7) then
            end
        end

        while t2value82.Character and t2value82.Character:FindFirstChild("Head") do
            HumanoidRootPart.CFrame = Head.CFrame * CFrame.new(2, 0, 0)
            ReplicatedStorage:WaitForChild("GrabEvents"):WaitForChild("SetNetworkOwner"):FireServer(Head, HumanoidRootPart.CFrame)
            task.wait(0.15)
            n7 += 1

            if Head:FindFirstChild("PartOwner") and Head.PartOwner.Value == LocalPlayer.Name or n6 <= n7 then
                break
            end
        end

        HumanoidRootPart.CFrame = HumanoidRootPartCFrame

        local v728 = HumanoidRootPartCFrame.LookVector * 5

        Head.CFrame = CFrame.new(HumanoidRootPartCFrame.Position + v728)
        ReplicatedStorage:WaitForChild("GrabEvents"):WaitForChild("DestroyGrabLine"):FireServer(Head)
    end
	})

    function t2.value93(p131)
        local LocalPlayer = t1.value1.LocalPlayer

        if not LocalPlayer then
            return
        end

        local Character = LocalPlayer.Character

        if not Character then
            return
        end

        local Humanoid13 = Character:FindFirstChildOfClass("Humanoid")
        local HumanoidRootPart = Character:FindFirstChild("HumanoidRootPart")

        if not Humanoid13 or not HumanoidRootPart then
            return
        end

        local p131_2 = t1.value1:FindFirstChild(p131)

        if not p131_2 or not p131_2.Character then
            return
        end

        local HumanoidRootPart2 = p131_2.Character:FindFirstChild("HumanoidRootPart")

        if not HumanoidRootPart2 then
            return
        end

        local HumanoidRootPartCFrame = HumanoidRootPart.CFrame
        local timestamp = tick()
        local u738 = v78()

        if not u738 then
            t2.value89()
            task.wait(0.6)
            u738 = v78()
        end

        if not u738 then
            t2.value88()
            task.wait(1.7)
            u738 = v78()
        end

        if not u738 or not u738.PrimaryPart then
            return
        end

        local VehicleSeat = u738:FindFirstChild("VehicleSeat")

        if not VehicleSeat then
            return
        end

        pcall(function()
            VehicleSeat:Sit(Humanoid13)
        end)
        task.wait(0.4)

        if VehicleSeat ~= Humanoid13.SeatPart then
            return
        end

        local v740 = false
        local BlobmanSeatAndOwnerScript = u738:FindFirstChild("BlobmanSeatAndOwnerScript")

        while tick() - timestamp < 10 and (p131_2.Character and HumanoidRootPart2) do
            pcall(function()
                u738:SetPrimaryPartCFrame(HumanoidRootPart2.CFrame * CFrame.new(0, 0, -4))
            end)

            local v742 = u738:FindFirstChild("LeftDetector") or u738:FindFirstChild("RightDetector")
            local v743 = v742 and v742:FindFirstChild("LeftWeld") or v742:FindFirstChild("RightWeld")

            if v742 and (v743 and BlobmanSeatAndOwnerScript) then
                local CreatureGrab = BlobmanSeatAndOwnerScript:FindFirstChild("CreatureGrab")

                if CreatureGrab then
                    pcall(function()
                        CreatureGrab:FireServer(v742, HumanoidRootPart2, v743)
                    end)
                end
            end

            if v743 and (v743.Attachment0 and HumanoidRootPart2 == v743.Attachment0.Parent) then
                v740 = true

                break
            end

            task.wait(0.1)
        end

        if not v740 then
            t2.value6:Notify({
				Title = "Error",
				Content = "Cannot Grab the person.",
				Duration = 5,
				Image = "x"
			})
            pcall(function()
                t2.value9.MenuToys.DestroyToy:FireServer(u738)
            end)
            HumanoidRootPart.CFrame = HumanoidRootPartCFrame

            return
        end

        pcall(function()
            HumanoidRootPart2.CFrame = CFrame.new(HumanoidRootPartCFrame.Position + HumanoidRootPartCFrame.LookVector * 5)
        end)
        HumanoidRootPart.CFrame = HumanoidRootPartCFrame
        task.wait(0.4)

        if BlobmanSeatAndOwnerScript then
            local CreatureDrop = BlobmanSeatAndOwnerScript:FindFirstChild("CreatureDrop")
            local v746 = u738:FindFirstChild("LeftDetector") or u738:FindFirstChild("RightDetector")
            local v747 = v746 and v746:FindFirstChild("LeftWeld") or v746:FindFirstChild("RightWeld")

            if CreatureDrop and v747 then
                pcall(function()
                    CreatureDrop:FireServer(v747)
                end)
            end
        end

        task.delay(0.25, function()
            pcall(function()
                t2.value9.MenuToys.DestroyToy:FireServer(u738)
            end)
        end)
    end

    LoopTab:CreateButton({
		Name = "Bring  <font face=\"GothamBlack\" color=\"rgb(255,251,0)\">BLOBMAN</font>   <font face=\"GothamBlack\" color=\"rgb(12,8,234)\">SUMMON</font>",
		Callback = function()
        if t2.value82 then
            t2.value93(t2.value82)
        end
    end
	})
    LoopTab:CreateToggle({
		Name = "Spectate   <font face=\"GothamBlack\" color=\"rgb(0,145,255)\">VIEW</font>",
		CurrentValue = false,
		Flag = "ViewPlayer",
		Callback = function(p132)
        local Players = game:GetService("Players")
        local LocalPlayer = Players.LocalPlayer
        local CurrentCamera = workspace.CurrentCamera

        if not t2.value82 then
            return
        end

        local t2value82 = Players:FindFirstChild(t2.value82)

        if p132 then
            p132 = t2value82 and (t2value82.Character and t2value82.Character:FindFirstChild("Head"))
        end

        if p132 then
            CurrentCamera.CameraSubject = t2value82.Character:FindFirstChild("Humanoid")
            CurrentCamera.CameraType = Enum.CameraType.Custom

            return
        end

        CurrentCamera.CameraSubject = LocalPlayer.Character:FindFirstChild("Humanoid")
        CurrentCamera.CameraType = Enum.CameraType.Custom
    end
	})
    t2.value94 = false
    t2.value95 = nil
    LoopTab:CreateToggle({
		Name = "Loop Teleport   <font face=\"GothamBlack\" color=\"rgb(8,240,45)\">SMOOTH</font>    <font face=\"GothamBlack\" color=\"rgb(255,255,38)\">TP</font>",
		CurrentValue = false,
		Flag = "LoopTeleport",
		Callback = function(p133)
        local Players = game:GetService("Players")
        local LocalPlayer = Players.LocalPlayer
        local HumanoidRootPart = (LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()):WaitForChild("HumanoidRootPart")

        t2.value94 = p133

        if t2.value95 then
            t2.value95:Disconnect()
        end

        if t2.value94 then
            game:GetService("RunService").RenderStepped:Connect(function(_)
                if not t2.value82 then
                    return
                end

                local t2value82 = Players:FindFirstChild(t2.value82)

                if t2value82 and (t2value82.Character and t2value82.Character:FindFirstChild("HumanoidRootPart")) then
                    local HumanoidRootPart3 = t2value82.Character.HumanoidRootPart

                    HumanoidRootPart.CFrame = HumanoidRootPart.CFrame:Lerp(HumanoidRootPart3.CFrame * CFrame.new(2, 0, 0), 0.2)
                end
            end)
        end
    end
	})
    Label = LoopTab:CreateLabel("Kill", "flame")
    t2.value96 = game:GetService("Players")
    t2.value97 = nil
    t2.value97 = false

    function t2.value98()
        if not t2.value97 then
            return
        end

        if not t2.value82 then
            return
        end

        local LocalPlayer = t2.value96.LocalPlayer

        if not LocalPlayer or not LocalPlayer.Character then
            return
        end

        local Character = LocalPlayer.Character
        local Humanoid14 = Character:FindFirstChildOfClass("Humanoid")
        local HumanoidRootPart = Character:FindFirstChild("HumanoidRootPart")

        if not Humanoid14 or not HumanoidRootPart then
            return
        end

        local t2value82 = t2.value96:FindFirstChild(t2.value82)

        if not t2value82 or not t2value82.Character then
            return
        end

        local Humanoid15 = t2value82.Character:FindFirstChildOfClass("Humanoid")
        local HumanoidRootPart4 = t2value82.Character:FindFirstChild("HumanoidRootPart")

        if not Humanoid15 or (not HumanoidRootPart4 or Humanoid15.Health <= 0) then
            return
        end

        if HumanoidRootPart4.Position.Y > 100000 then
            return
        end

        local HumanoidRootPartCFrame = HumanoidRootPart.CFrame
        local u765 = Humanoid14.SeatPart and Humanoid14.SeatPart.Parent

        if not u765 or u765.Name ~= "CreatureBlobman" then
            u765 = v78()

            if not u765 then
                t2.value88()
                task.wait(1.6)
                u765 = v78()
            end

            if not u765 or not u765.PrimaryPart then
                return
            end

            local VehicleSeat = u765:FindFirstChild("VehicleSeat")

            if not VehicleSeat then
                return
            end

            pcall(function()
                VehicleSeat:Sit(Humanoid14)
            end)
            task.wait(0.35)

            if VehicleSeat ~= Humanoid14.SeatPart then
                return
            end
        end

        if not u765 or not u765.PrimaryPart then
            return
        end

        local PrimaryPartCFrame = u765.PrimaryPart.CFrame

        pcall(function()
            u765:SetPrimaryPartCFrame(HumanoidRootPart4.CFrame * CFrame.new(0, 0, -3))
        end)
        task.wait(0.15)

        local v768 = u765:FindFirstChild("LeftDetector") or u765:FindFirstChild("RightDetector")
        local v769 = v768 and v768:FindFirstChild("LeftWeld") or v768:FindFirstChild("RightWeld")
        local BlobmanSeatAndOwnerScript = u765:FindFirstChild("BlobmanSeatAndOwnerScript")
        local v771 = BlobmanSeatAndOwnerScript and BlobmanSeatAndOwnerScript:FindFirstChild("CreatureGrab")
        local v772 = BlobmanSeatAndOwnerScript and BlobmanSeatAndOwnerScript:FindFirstChild("CreatureRelease")

        if v768 and (v769 and (v771 and v772)) then
            for _ = 1, 4 do
                if not t2.value97 or not t2value82.Character then
                    break
                end

                pcall(function()
                    v771:FireServer(v768, HumanoidRootPart4, v769)
                end)
                task.wait(0.05)
                pcall(function()
                    Humanoid15.RigType = Enum.HumanoidRigType.R15
                    Humanoid15.PlatformStand = true
                    Humanoid15:ChangeState(Enum.HumanoidStateType.Physics)
                    Humanoid15:TakeDamage(100)
                    Humanoid15.Health = 0
                end)
                task.wait(0.05)
                task.wait(0.05)
                pcall(function()
                    v772:FireServer(v769, HumanoidRootPart4)
                end)
                task.wait(0.08)
            end
        end

        task.wait(0.1)
        pcall(function()
            HumanoidRootPart.CFrame = HumanoidRootPartCFrame
        end)
        pcall(function()
            u765:SetPrimaryPartCFrame(PrimaryPartCFrame)
        end)
    end

    LoopTab:CreateToggle({
		Name = "Loop BlobKill   <font face=\"GothamBlack\" color=\"rgb(255,251,0)\">BLOBMAN</font>  <font face=\"GothamBlack\" color=\"rgb(255,100,0)\">PURGE</font>   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Flag = "LoopBlobKillToggle",
		Callback = function(p135)
        t2.value97 = p135

        if p135 then
            task.spawn(function()
                while t2.value97 do
                    t2.value98()
                    task.wait(0.25)
                end
            end)
        end
    end
	})
    LoopTab:CreateToggle({
		Name = "Loop Kill   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">GRAB</font>   <font face=\"GothamBlack\" color=\"rgb(8,0,255)\">KILL</font>",
		CurrentValue = false,
		Flag = "LoopKillToggle",
		Callback = function(p136)
        if p136 then
            StartLoopKill()

            return
        end

        StopLoopKill()
    end
	})
    Label = LoopTab:CreateLabel("Kick", "ban")
    LoopTab:CreateToggle({
		Name = "Loop Kick   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">GRAB</font>   <font face=\"GothamBlack\" color=\"rgb(255,100,200)\">KICK</font>",
		CurrentValue = false,
		Flag = "LoopKickToggle",
		Callback = function(p137)
        if p137 then
            StartLoopKick()

            return
        end

        StopLoopKick()
    end
	})
    t2.value96.LocalPlayer.CharacterAdded:Connect(function(character)
        initCharAttrs()

        local Humanoid16 = character:WaitForChild("Humanoid", 5)

        if Humanoid16 then
            Humanoid16.Died:Connect(function()
                t2.value91:detach()
            end)
        end
    end)

    if t2.value96.LocalPlayer.Character then
        initCharAttrs()
    end

    t2.value99 = false
    KickGrabConnection = nil

    if kickbp then
        kickbp:Destroy()
        kickbp = nil
    end

    if kickbg then
        kickbg:Destroy()
        kickbg = nil
    end

    LoopTab:CreateToggle({
		Name = "Spam Kick Grab   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">GRAB</font>    <font face=\"GothamBlack\" color=\"rgb(120,0,0)\">OP+</font>   <font face=\"GothamBlack\" color=\"rgb(0,255,0)\">KICK</font>\t<font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Flag = "KickGrabToggle",
		Callback = function(p138)
        t2.value99 = p138

        if t2.value99 then
            task.spawn(function()
                while t2.value99 do
                    if not t2.value82 then
                        task.wait(0.1)
                    else
                        local t2value82 = t2.value96:FindFirstChild(t2.value82)

                        if not t2value82 then
                            task.wait(0.1)
                        elseif t2value82:FindFirstChild("InPlot") and t2value82.InPlot.Value then
                            task.wait(0.1)
                        else
                            local Character = t2value82.Character
                            local v1956 = Character and Character:FindFirstChild("HumanoidRootPart")
                            local v1957 = Character and Character:FindFirstChild("Head")
                            local v1958 = Character and Character:FindFirstChild("Humanoid")
                            local Character4 = t1.value3.Character
                            local v1960 = Character4 and Character4:FindFirstChild("HumanoidRootPart")

                            if not v1956 and (not not v1957 and (not not v1958 and v1960)) or v1958.Health <= 0 then
                                task.wait(0.1)
                            else
                                local Magnitude = (v1956.Position - v1960.Position).Magnitude
                                local v1962 = GetPartOwner(v1957)

                                if Magnitude > 30 and v1962 ~= t1.value3.Name then
                                    local CFrame2 = v1960.CFrame

                                    v1960.CFrame = v1956.CFrame * CFrame.new(0, 5, 0)
                                    task.wait(0.05)

                                    for _ = 1, 20 do
                                        SetNetworkOwner:FireServer(v1956, v1956.CFrame)

                                        if GetPartOwner(v1957) == t1.value3.Name then
                                            break
                                        end

                                        task.wait()
                                    end

                                    v1960.CFrame = CFrame2
                                elseif v1962 ~= t1.value3.Name then
                                    SetNetworkOwner:FireServer(v1956, v1956.CFrame)
                                end

                                for _ = 1, 4 do
                                    DestroyGrabLine:FireServer(v1956)
                                    task.wait()
                                    SetNetworkOwner:FireServer(v1956, v1956.CFrame)
                                end

                                local vector3 = Vector3.new(0, 20, 0)

                                if not kickbp or v1956 ~= kickbp.Parent then
                                    kickbp = Instance.new("BodyPosition")
                                    kickbp.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                                    kickbp.D = 200
                                    kickbp.Parent = v1956
                                end

                                kickbp.Position = v1960.Position + vector3

                                if not kickbg or v1956 ~= kickbg.Parent then
                                    kickbg = Instance.new("BodyGyro")
                                    kickbg.MaxTorque = Vector3.new(1e999, 1e999, 1e999)
                                    kickbg.D = 100
                                    kickbg.CFrame = CFrame.new(0, 0, 0)
                                    kickbg.Parent = v1956
                                end

                                t1.value2.RenderStepped:Wait()
                            end
                        end
                    end
                end
            end)

            return
        end

        task.spawn(function()
            for _ = 1, 10 do
                if kickbp then
                    kickbp:Destroy()
                    kickbp = nil
                end

                if kickbg then
                    kickbg:Destroy()
                    kickbg = nil
                end

                task.wait(0.1)
            end
        end)

        if KickGrabConnection then
            KickGrabConnection:Disconnect()
            KickGrabConnection = nil
        end
    end
	})
    LoopTab:CreateButton({
		Name = "Silent Kick    <font face=\"GothamBlack\" color=\"rgb(255,251,0)\">BLOBMAN</font>   <font face=\"GothamBlack\" color=\"rgb(150,150,150)\">GHOST</font>   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>",
		Callback = function()
        local Players = game:GetService("Players")
        local ReplicatedStorage = game:GetService("ReplicatedStorage")
        local Character = Players.LocalPlayer.Character

        if not Character then
            return
        end

        local Humanoid17 = Character:FindFirstChildOfClass("Humanoid")
        local HumanoidRootPart = Character:FindFirstChild("HumanoidRootPart")

        if not Humanoid17 or not HumanoidRootPart then
            return
        end

        if not t2.value82 then
            return
        end

        local t2value82 = Players:FindFirstChild(t2.value82)

        if not t2value82 or not t2value82.Character then
            return
        end

        local HumanoidRootPart5 = t2value82.Character:FindFirstChild("HumanoidRootPart")

        if not HumanoidRootPart5 then
            return
        end

        local function v787(p139)
            return p139.ReceiveAge == 0
        end

        if v787(HumanoidRootPart5) then
            return
        end

        local v788 = v78() or t2.value89()

        if not v788 then
            t2.value88()
            v788 = v78()
        end

        if not v788 or not v788.PrimaryPart then
            return
        end

        local HumanoidRootPartCFrame = HumanoidRootPart.CFrame
        local PrimaryPartCFrame = v788.PrimaryPart.CFrame
        local VehicleSeat = v788:FindFirstChild("VehicleSeat")

        if VehicleSeat then
            task.wait(0.1)
            pcall(function()
                VehicleSeat:Sit(Humanoid17)
            end)
        end

        v788:SetPrimaryPartCFrame(HumanoidRootPart5.CFrame * CFrame.new(0, 0, -4))
        task.wait(0.2)

        local HumanoidRootPart5CFrame = HumanoidRootPart5.CFrame

        pcall(function()
            ReplicatedStorage.GrabEvents.SetNetworkOwner:FireServer(HumanoidRootPart5, HumanoidRootPart5.CFrame)
        end)
        task.wait(0.15)

        local n8 = 0

        while n8 < 40 do
            task.wait(0.05)
            n8 += 1

            if v787(HumanoidRootPart5) then
                break
            end
        end

        if not v787(HumanoidRootPart5) then
            HumanoidRootPart.CFrame = HumanoidRootPartCFrame

            if v788.PrimaryPart then
                v788:SetPrimaryPartCFrame(PrimaryPartCFrame)
            end

            return
        end

        HumanoidRootPart5.CFrame = HumanoidRootPart5CFrame + Vector3.new(0, 30, 0)
        task.wait(0.1)
        pcall(function()
            ReplicatedStorage.GrabEvents.DestroyGrabLine:FireServer(HumanoidRootPart5)
        end)

        local LeftDetector = v788:FindFirstChild("LeftDetector")

        if LeftDetector then
            local LeftWeld = LeftDetector:FindFirstChild("LeftWeld")
            local BlobmanSeatAndOwnerScript = v788:FindFirstChild("BlobmanSeatAndOwnerScript")

            if BlobmanSeatAndOwnerScript and LeftWeld then
                pcall(function()
                    BlobmanSeatAndOwnerScript.CreatureGrab:FireServer(LeftDetector, HumanoidRootPart, LeftWeld)
                    task.wait(0.1)
                    BlobmanSeatAndOwnerScript.CreatureGrab:FireServer(LeftDetector, HumanoidRootPart5, LeftWeld)
                    task.wait(0.1)
                    BlobmanSeatAndOwnerScript.CreatureDrop:FireServer(LeftWeld)
                end)
            end
        end

        task.wait(0.6)
        HumanoidRootPart.CFrame = HumanoidRootPartCFrame

        if v788.PrimaryPart then
            v788:SetPrimaryPartCFrame(PrimaryPartCFrame)
        end
    end
	})
    Label = LoopTab:CreateLabel("Lock", "lock-keyhole")
    t2.value100 = nil
    t2.value101 = nil
    t2.value102 = LoopTab:CreateToggle({
		Name = "Basic Lock   <font face=\"GothamBlack\" color=\"rgb(255,251,0)\">BLOBMAN</font>   <font face=\"GothamBlack\" color=\"rgb(0,255,77)\">LOCK</font>",
		CurrentValue = false,
		Flag = "LockTarget1Toggle",
		Callback = function(p140)
        if p140 then
            if t2.value100 then
                t2.value100:Set(false)
            end

            if t2.value101 then
                t2.value101:Set(false)
            end

            LockTarget1Active = true
            task.spawn(function()
                while LockTarget1Active do
                    if not t2.value82 then
                        task.wait()

                        continue
                    end

                    local t2value82 = t2.value96:FindFirstChild(t2.value82)

                    if not t2value82 or not t2value82.Character then
                        task.wait()

                        continue
                    end

                    local HumanoidRootPart = t2value82.Character:FindFirstChild("HumanoidRootPart")

                    if not HumanoidRootPart then
                        task.wait()

                        continue
                    end

                    local Character = t1.value3.Character
                    local v1972 = Character and Character:FindFirstChildOfClass("Humanoid")
                    local v1973 = Character and Character:FindFirstChild("HumanoidRootPart")

                    if not v1972 or not v1973 then
                        task.wait()

                        continue
                    end

                    local v1974 = v1972.SeatPart and v1972.SeatPart.Parent

                    if not v1974 or v1974.Name ~= "CreatureBlobman" then
                        v1974 = v78() or t2.value89()

                        if not v1974 then
                            t2.value88()
                            task.wait(1.7)
                            v1974 = v78()
                        end

                        if not v1974 or not v1974.PrimaryPart then
                            task.wait()

                            continue
                        end

                        local VehicleSeat = v1974:FindFirstChild("VehicleSeat")

                        if VehicleSeat then
                            task.wait(0.4)
                            pcall(function()
                                VehicleSeat:Sit(v1972)
                            end)
                            task.wait(0.4)
                        end

                        if not v1972.SeatPart or v1974 ~= v1972.SeatPart.Parent then
                            task.wait()

                            continue
                        end
                    end

                    if not v1972.SeatPart or v1972.SeatPart.Parent.Name ~= "CreatureBlobman" then
                        task.wait()
                    elseif not v1974 or not v1974.PrimaryPart then
                        task.wait()
                    else
                        local CreatureRelease = v1974.BlobmanSeatAndOwnerScript.CreatureRelease
                        local CreatureDrop = v1974.BlobmanSeatAndOwnerScript.CreatureDrop
                        local CreatureGrab = v1974.BlobmanSeatAndOwnerScript.CreatureGrab

                        if (HumanoidRootPart.Position - v1973.Position).Magnitude > 30 then
                            local CFrame3 = v1973.CFrame

                            v1973.CFrame = HumanoidRootPart.CFrame

                            local n9 = 0

                            if HumanoidRootPart.ReceiveAge ~= 0 then
                                if not (n9 >= 15) then
                                end
                            end

                            repeat
                                CreatureGrab:FireServer(v1974.RightDetector, HumanoidRootPart, v1974.RightDetector.RightWeld)
                                CreatureRelease:FireServer(v1974.RightDetector.RightWeld)
                                task.wait()
                                n9 += 1
                            until HumanoidRootPart.ReceiveAge == 0 or n9 >= 15

                            v1973.CFrame = CFrame3
                            task.wait()

                            if HumanoidRootPart.ReceiveAge == 0 then
                                HumanoidRootPart.CFrame = v1974.RightDetector.CFrame
                            end
                        end

                        CreatureGrab:FireServer(v1974.RightDetector, HumanoidRootPart, v1974.RightDetector.RightWeld)
                        CreatureDrop:FireServer(v1974.RightDetector.RightWeld)
                        CreatureGrab:FireServer(v1974.RightDetector, HumanoidRootPart, v1974.RightDetector.RightWeld)
                        task.wait()
                    end
                end
            end)

            return
        end

        LockTarget1Active = false
    end
	})
    t2.value100 = LoopTab:CreateToggle({
		Name = "Mid Lock   <font face=\"GothamBlack\" color=\"rgb(255,251,0)\">BLOBMAN</font>   <font face=\"GothamBlack\" color=\"rgb(255,137,0)\">LOCK</font>",
		CurrentValue = false,
		Flag = "LockTarget2Toggle",
		Callback = function(p141)
        if p141 then
            if t2.value102 then
                t2.value102:Set(false)
            end

            if t2.value101 then
                t2.value101:Set(false)
            end

            LockTarget2Active = true
            task.spawn(function()
                while LockTarget2Active do
                    if not t2.value82 then
                        task.wait()

                        continue
                    end

                    local t2value82 = t2.value96:FindFirstChild(t2.value82)

                    if not t2value82 or not t2value82.Character then
                        task.wait()

                        continue
                    end

                    local HumanoidRootPart = t2value82.Character:FindFirstChild("HumanoidRootPart")

                    if not HumanoidRootPart then
                        task.wait()

                        continue
                    end

                    local Character = t1.value3.Character
                    local v1984 = Character and Character:FindFirstChildOfClass("Humanoid")
                    local v1985 = Character and Character:FindFirstChild("HumanoidRootPart")

                    if not v1984 or not v1985 then
                        task.wait()

                        continue
                    end

                    local v1986 = v1984.SeatPart and v1984.SeatPart.Parent

                    if not v1986 or v1986.Name ~= "CreatureBlobman" then
                        v1986 = v78() or t2.value89()

                        if not v1986 then
                            t2.value88()
                            task.wait(1.7)
                            v1986 = v78()
                        end

                        if not v1986 or not v1986.PrimaryPart then
                            task.wait()

                            continue
                        end

                        local VehicleSeat = v1986:FindFirstChild("VehicleSeat")

                        if VehicleSeat then
                            task.wait(0.4)
                            pcall(function()
                                VehicleSeat:Sit(v1984)
                            end)
                            task.wait(0.4)
                        end

                        if not v1984.SeatPart or v1986 ~= v1984.SeatPart.Parent then
                            task.wait()

                            continue
                        end
                    end

                    if not v1984.SeatPart or v1984.SeatPart.Parent.Name ~= "CreatureBlobman" then
                        task.wait()
                    elseif not v1986 or not v1986.PrimaryPart then
                        task.wait()
                    else
                        local CreatureRelease = v1986.BlobmanSeatAndOwnerScript.CreatureRelease
                        local CreatureDrop = v1986.BlobmanSeatAndOwnerScript.CreatureDrop
                        local CreatureGrab = v1986.BlobmanSeatAndOwnerScript.CreatureGrab

                        if (HumanoidRootPart.Position - v1985.Position).Magnitude > 30 then
                            local CFrame4 = v1985.CFrame

                            v1985.CFrame = HumanoidRootPart.CFrame

                            local n10 = 0

                            if HumanoidRootPart.ReceiveAge ~= 0 then
                                if not (n10 >= 15) then
                                end
                            end

                            repeat
                                CreatureGrab:FireServer(v1986.RightDetector, HumanoidRootPart, v1986.RightDetector.RightWeld)
                                CreatureRelease:FireServer(v1986.RightDetector.RightWeld)
                                task.wait()
                                n10 += 1
                            until HumanoidRootPart.ReceiveAge == 0 or n10 >= 15

                            v1985.CFrame = CFrame4
                            task.wait()

                            if HumanoidRootPart.ReceiveAge == 0 then
                                HumanoidRootPart.CFrame = v1986.RightDetector.CFrame
                            end
                        end

                        CreatureGrab:FireServer(v1986.RightDetector, HumanoidRootPart, v1986.RightDetector.RightWeld)
                        CreatureDrop:FireServer(v1986.RightDetector.RightWeld)
                        task.wait()
                    end
                end
            end)

            return
        end

        LockTarget2Active = false
    end
	})
    t2.value101 = LoopTab:CreateToggle({
		Name = "Ultimate Lock   <font face=\"GothamBlack\" color=\"rgb(255,251,0)\">BLOBMAN</font>   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">LOCK</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Flag = "SuperLockToggle",
		Callback = function(p142)
        if p142 then
            if t2.value102 then
                t2.value102:Set(false)
            end

            if t2.value100 then
                t2.value100:Set(false)
            end

            SuperLockActive = true
            task.spawn(function()
                while SuperLockActive do
                    if not t2.value82 then
                        task.wait()

                        continue
                    end

                    local t2value82 = t2.value96:FindFirstChild(t2.value82)

                    if not t2value82 or not t2value82.Character then
                        task.wait()

                        continue
                    end

                    local HumanoidRootPart = t2value82.Character:FindFirstChild("HumanoidRootPart")
                    local Humanoid18 = t2value82.Character:FindFirstChild("Humanoid")

                    if not HumanoidRootPart or not Humanoid18 then
                        task.wait()

                        continue
                    end

                    local Character = t1.value3.Character
                    local v1997 = Character and Character:FindFirstChildOfClass("Humanoid")
                    local v1998 = Character and Character:FindFirstChild("HumanoidRootPart")

                    if not v1997 or not v1998 then
                        task.wait()

                        continue
                    end

                    local v1999 = v1997.SeatPart and v1997.SeatPart.Parent

                    if not v1999 or v1999.Name ~= "CreatureBlobman" then
                        v1999 = v78() or t2.value89()

                        if not v1999 then
                            t2.value88()
                            task.wait(1.7)
                            v1999 = v78()
                        end

                        if not v1999 or not v1999.PrimaryPart then
                            task.wait()

                            continue
                        end

                        local VehicleSeat = v1999:FindFirstChild("VehicleSeat")

                        if VehicleSeat then
                            task.wait(0.4)
                            pcall(function()
                                VehicleSeat:Sit(v1997)
                            end)
                            task.wait(0.4)
                        end

                        if not v1997.SeatPart or v1999 ~= v1997.SeatPart.Parent then
                            task.wait()

                            continue
                        end
                    end

                    if not v1997.SeatPart or v1997.SeatPart.Parent.Name ~= "CreatureBlobman" then
                        task.wait()
                    elseif not v1999 or not v1999.PrimaryPart then
                        task.wait()
                    else
                        local CreatureRelease = v1999.BlobmanSeatAndOwnerScript.CreatureRelease
                        local _ = v1999.BlobmanSeatAndOwnerScript.CreatureDrop
                        local CreatureGrab = v1999.BlobmanSeatAndOwnerScript.CreatureGrab

                        if (HumanoidRootPart.Position - v1998.Position).Magnitude > 30 then
                            local CFrame5 = v1998.CFrame

                            v1998.CFrame = HumanoidRootPart.CFrame

                            local n11 = 0

                            if HumanoidRootPart.ReceiveAge ~= 0 then
                                if not (n11 >= 15) then
                                end
                            end

                            repeat
                                CreatureGrab:FireServer(v1999.RightDetector, HumanoidRootPart, v1999.RightDetector.RightWeld)
                                CreatureRelease:FireServer(v1999.RightDetector.RightWeld)
                                task.wait()
                                n11 += 1
                            until HumanoidRootPart.ReceiveAge == 0 or n11 >= 15

                            v1998.CFrame = CFrame5
                        end

                        CreatureGrab:FireServer(v1999.RightDetector, HumanoidRootPart, v1999.RightDetector.RightWeld)
                        CreatureRelease:FireServer(v1999.RightDetector.RightWeld)
                        Humanoid18:ChangeState(Enum.HumanoidStateType.Seated)

                        if HumanoidRootPart.ReceiveAge == 0 then
                            HumanoidRootPart.CFrame = v1999.RightDetector.CFrame

                            for _, child in pairs(t2value82.Character:GetChildren()) do
                                if child:IsA("BasePart") and child.Name ~= "HumanoidRootPart" then
                                    child.CanCollide = false
                                end
                            end
                        end

                        task.wait()
                    end
                end
            end)

            return
        end

        SuperLockActive = false
    end
	})
end
Label = LoopTab:CreateLabel("Fun", "ferris-wheel")
LoopTab:CreateToggle({
	Name = "Loop Fling   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">GRAB</font>   <font face=\"GothamBlack\" color=\"rgb(255,100,0)\">FLING</font>   <font face=\"GothamBlack\" color=\"rgb(0,255,255)\">PREMIUM</font>",
	CurrentValue = false,
	Flag = "LoopFlingToggle",
	Callback = function(p143)
    if p143 then
        StartLoopBounce(t2.value82)

        return
    end

    StopLoopBounce()
end
})
LoopTab:CreateLabel("Utility", "settings")
AutoFreezeBlobmanEnabled = false
FreezedBlobs = {}
trackedBlobs = {}
function freezeBlobman(p144)
    if not p144 or not p144.PrimaryPart then
        return
    end

    if FreezedBlobs[p144] then
        return
    end

    FreezedBlobs[p144] = true

    local BodyVelocity = Instance.new("BodyVelocity")

    BodyVelocity.Name = "AutoFreezeVelocity"
    BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
    BodyVelocity.Velocity = Vector3.zero
    BodyVelocity.P = 10000
    BodyVelocity.Parent = p144.PrimaryPart

    local BodyGyro = Instance.new("BodyGyro")

    BodyGyro.Name = "AutoFreezeGyro"
    BodyGyro.MaxTorque = Vector3.new(1e999, 1e999, 1e999)
    BodyGyro.P = 10000
    BodyGyro.D = 500
    BodyGyro.CFrame = p144.PrimaryPart.CFrame
    BodyGyro.Parent = p144.PrimaryPart
end
function unfreezeBlobman(p145)
    if not p145 or not p145.PrimaryPart then
        return
    end

    FreezedBlobs[p145] = nil
    pcall(function()
        p145.PrimaryPart:FindFirstChild("AutoFreezeVelocity"):Destroy()
        p145.PrimaryPart:FindFirstChild("AutoFreezeGyro"):Destroy()
    end)
end
function getPlayerSeatBlob()
    local Character = t1.value3.Character
    local v806 = Character and Character:FindFirstChildOfClass("Humanoid")

    return v806 and (v806.SeatPart and v806.SeatPart.Parent)
end
task.spawn(function()
    while true do
        task.wait(0.5)

        if AutoFreezeBlobmanEnabled then
            local v807 = getPlayerSeatBlob()

            for k, _ in pairs(trackedBlobs) do
                local v810 = k

                if v810 and v810.Parent then
                    if v810 == v807 then
                        freezeBlobman(v810)
                    else
                        unfreezeBlobman(v810)
                    end
                else
                    trackedBlobs[v810] = nil
                end
            end
        end
    end
end)
workspace.DescendantAdded:Connect(function(descendant)
    if descendant:IsA("Model") and descendant.Name == "CreatureBlobman" then
        trackedBlobs[descendant] = true
    end
end)
task.spawn(function()
    for _, child in ipairs(workspace:GetChildren()) do
        if child:IsA("Folder") and child.Name:match("SpawnedInToys") then
            for _, descendant in ipairs(child:GetDescendants()) do
                if descendant:IsA("Model") and descendant.Name == "CreatureBlobman" then
                    trackedBlobs[descendant] = true
                end
            end
        end
    end

    local PlotItems = workspace:FindFirstChild("PlotItems")

    if PlotItems then
        local GetChildren = PlotItems.GetChildren

        for _, v in ipairs(GetChildren(PlotItems)) do
            local GetDescendants = v.GetDescendants

            for _, v8 in ipairs(GetDescendants(v)) do
                if v8:IsA("Model") and v8.Name == "CreatureBlobman" then
                    trackedBlobs[v8] = true
                end
            end
        end
    end
end)
LoopTab:CreateToggle({
	Name = "Auto Freeze Blobman   <font face=\"GothamBlack\" color=\"rgb(255,251,0)\">BLOBMAN</font>   <font face=\"GothamBlack\" color=\"rgb(0,0,255)\">FREEZE</font>",
	CurrentValue = false,
	Flag = "AutoFreezeBlobmanToggle",
	Callback = function(p146)
    AutoFreezeBlobmanEnabled = p146

    if not p146 then
        for k, _ in pairs(trackedBlobs) do
            unfreezeBlobman(k)
        end

        FreezedBlobs = {}
    end
end
})
ServerTab:CreateLabel("Aggressive", "Skull")
t2.value103 = nil
t2.value104 = nil
t2.value105 = false
function attachCameraToSpawn()
    local CurrentCamera = Workspace.CurrentCamera

    CurrentCamera.CameraType = Enum.CameraType.Scriptable
    CurrentCamera.CFrame = CFrame.new(0, 50, 50) * CFrame.Angles(-0.7853981633974483, 0, 0)
end
function detachCamera()
    local CurrentCamera = Workspace.CurrentCamera
    local Character = t1.value3.Character

    if Character and Character:FindFirstChild("Humanoid") then
        CurrentCamera.CameraType = Enum.CameraType.Custom
        CurrentCamera.CameraSubject = Character.Humanoid

        return
    end

    CurrentCamera.CameraType = Enum.CameraType.Custom
end
function performKillAll()
    attachCameraToSpawn()

    for _, player12 in ipairs(t2.value96:GetPlayers()) do
        if player12 ~= t1.value3 and not t2.value12(player12) then
            local Character = player12.Character
            local v832 = Character and Character:FindFirstChild("HumanoidRootPart")
            local v833 = Character and Character:FindFirstChild("Humanoid")
            local v834 = Character and Character:FindFirstChild("Head")

            if v832 and (v833 and v834) and not isTooHigh(player12) and (not player12:FindFirstChild("InPlot") or not player12.InPlot.Value) and v833:GetState() ~= Enum.HumanoidStateType.Dead then
                local Character5 = t1.value3.Character
                local v836 = Character5 and Character5:FindFirstChild("HumanoidRootPart")

                if Character5 and v836 then
                    if not Character5:GetAttribute("SavingOriginalPos") then
                        saveOriginalPosAttr()
                    end

                    Character5:SetAttribute("SavingOriginalPos", true)
                    Workspace.FallenPartsDestroyHeight = (0/0)
                    v836:PivotTo((CFrame.new(v832.Position + t2.value86)))
                    setNoCollideChar(Character)
                    SetNetworkOwner:FireServer(v832, v832.CFrame)
                    task.wait(0.05)
                    DestroyGrabLine:FireServer(v832)
                    task.wait(0.05)

                    if v834:FindFirstChild("PartOwner") and v834.PartOwner.Value == t1.value3.Name then
                        task.wait(0.05)
                        modifyTarget(v832, v833)
                    end
                end
            end
        end
    end

    task.wait(0.05)
end
function StartLoopKillAll()
    if t2.value103 then
        t2.value103:Disconnect()
    end

    t2.value103 = t1.value2.Heartbeat:Connect(performKillAll)
end
function StopLoopKillAll()
    if t2.value103 then
        t2.value103:Disconnect()
    end

    detachCamera()
end
function executeKickAll()
    attachCameraToSpawn()

    for _, player13 in ipairs(t2.value96:GetPlayers()) do
        if player13 ~= t1.value3 and not t2.value12(player13) then
            local Character = player13.Character
            local v840 = Character and Character:FindFirstChild("HumanoidRootPart")
            local v841 = Character and Character:FindFirstChild("Head")
            local v842 = v840
            local v843 = Character and Character:FindFirstChild("Humanoid")

            if v840 then
                v842 = v841 and v843
            end

            if v842 and not (v843.Health <= 0) and not isTooHigh(player13) and (not player13:FindFirstChild("InPlot") or not player13.InPlot.Value) then
                local Character6 = t1.value3.Character

                if Character6 and Character6:FindFirstChild("HumanoidRootPart") then
                    local Pivot = Character6:GetPivot()

                    Character6:PivotTo(CFrame.new(v840.Position + Vector3.new(0, 0, -3)))
                    DisableCollisions(Character)
                    SetNetworkOwner:FireServer(v840, v840.CFrame)
                    task.wait()
                    Character6:PivotTo(Pivot)
                    task.wait(0.05)
                    DestroyGrabLine:FireServer(v840)
                    task.wait(0.05)

                    local PartOwner = v841:FindFirstChild("PartOwner")

                    if PartOwner and PartOwner.Value == t1.value3.Name then
                        sendToSky(v840, v843)
                    end
                end
            end
        end
    end

    task.wait(0.05)
end
function StartLoopKickAll()
    if t2.value104 then
        t2.value104:Disconnect()
    end

    t2.value105 = true
    t2.value104 = t1.value2.Heartbeat:Connect(function()
        if t2.value105 then
            executeKickAll()
        end
    end)
end
function StopLoopKickAll()
    if t2.value104 then
        t2.value104:Disconnect()
    end

    detachCamera()
end
ServerTab:CreateToggle({
	Name = "LoopKill All\t <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>    <font face=\"GothamBlack\" color=\"rgb(255,120,0)\">GLOBAL</font>\t<font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>\t <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
	CurrentValue = false,
	Flag = "LoopKillAllToggle",
	Callback = function(p147)
    if p147 then
        StartLoopKillAll()

        return
    end

    StopLoopKillAll()
end
})
ServerTab:CreateToggle({
	Name = "LoopKick All \t<font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>\t<font face=\"GothamBlack\" color=\"rgb(0,0,255)\">GLOBAL</font>\t <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font> \t  <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
	CurrentValue = false,
	Flag = "LoopKickAllToggle",
	Callback = function(p148)
    if p148 then
        StartLoopKickAll()

        return
    end

    StopLoopKickAll()
end
})
ServerTab:CreateLabel("Annoying", "Zap")
folder = workspace:WaitForChild(t1.value3.Name .. "SpawnedInToys")
ragdollToggleActive = false
ragdollCurrentFood = nil
ragdollLastSpawn = 0
ragdollSpawnCooldown = 0.5
ragdollActive = false
ragdollBananaPeel = nil
vomitToggleActive = false
vomitReverseOrder = false
campfireToggleActive = false
campfireCurrentToy = nil
campfireLastSpawn = 0
campfireSpawnCooldown = 0.5
campfireToyActive = false
DeleteToyRE = t2.value9:WaitForChild("MenuToys"):WaitForChild("DestroyToy")
ServerTab:CreateToggle({
	Name = "LoopRagdoll All    <font face=\"GothamBlack\" color=\"rgb(255,215,0)\">BANANA</font>    <font face=\"GothamBlack\" color=\"rgb(160,0,255)\">GLOBAL</font>    <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>",
	CurrentValue = false,
	Callback = function(p149)
    ragdollToggleActive = p149

    if p149 then
        spawnRagdollFood()

        return
    end

    if ragdollCurrentFood and ragdollCurrentFood.Parent then
        pcall(function()
            DeleteToyRE:FireServer(ragdollCurrentFood)
        end)
    end

    ragdollCurrentFood = nil
    ragdollActive = false
    ragdollBananaPeel = nil
end
})
function getRoot()
    return t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")
end
function getPlayerLegs(p150)
    if not p150 or not p150.Character then
        return {}
    end

    local t32 = {}

    for _, v in pairs({
		"Right Leg",
		"Left Leg"
	}) do
        local v9 = p150.Character:FindFirstChild(v)

        if v9 and v9:IsA("BasePart") then
            table.insert(t32, v9)
        end
    end

    return t32
end
function setRagdollOwner(p151)
    if p151 and p151.Parent then
        pcall(function()
            for _, descendant in pairs(p151:GetDescendants()) do
                local v2010 = descendant

                if v2010:IsA("BasePart") then
                    SetNetworkOwner:FireServer(v2010, v2010.CFrame)
                    pcall(function()
                        DestroyGrabLine:FireServer(v2010)
                    end)
                end
            end
        end)
    end
end
function spawnRagdollFood()
    if not ragdollToggleActive then
        return
    end

    if tick() - ragdollLastSpawn < ragdollSpawnCooldown then
        return
    end

    ragdollLastSpawn = tick()

    local v856 = getRoot()

    if not v856 then
        return
    end

    local t33 = {
		"FoodBanana",
		v856.CFrame * CFrame.new(0, 0, 10),
		Vector3.new(0, 97.69, 0)
	}

    pcall(function()
        t2.value9.MenuToys.SpawnToyRemoteFunction:InvokeServer(unpack(t33))
    end)
end
function t2.value106(p152)
    if not ragdollToggleActive then
        return
    end
    local HoldPart = p152:WaitForChild("HoldPart", 3)
    if not HoldPart then
        return
    end
    pcall(function()
        HoldPart.HoldItemRemoteFunction:InvokeServer(p152, t1.value3.Character)
    end)
    local RigidConstraint = HoldPart:FindFirstChild("RigidConstraint")
    if RigidConstraint then
        local RigidConstraintAttachment1 = RigidConstraint.Attachment1

        if RigidConstraintAttachment1 then
            RigidConstraintAttachment1 = RigidConstraint.Attachment1:IsDescendantOf(t1.value3.Character)
        end

        RigidConstraint = RigidConstraintAttachment1
    end
    if RigidConstraint and (not HoldPart:FindFirstChild("EatingSound") or not HoldPart.EatingSound.IsPlaying) then
        pcall(function()
            t2.value9.HoldEvents.Use:FireServer(p152)
        end)
        task.wait(2.5)
    end
    local t34 = {
		p152,
		getRoot().CFrame * CFrame.Angles(0, 0.7853981633974483, 0) * CFrame.new(0, -2, 3),
		Vector3.new(0, 97.69, 0)
	}
    local u863 = t34
    pcall(function()
        HoldPart.DropItemRemoteFunction:InvokeServer(unpack(u863))
    end)
    task.wait(0.5)
    setRagdollOwner(p152)
    local players = t2.value96:GetPlayers()
    local v865 = players[math.random(2, #players)]
    local v866 = getPlayerLegs(v865)
    local v867 = #v866 > 0
    if v867 then
        v867 = v866[math.random(1, #v866)].CFrame * CFrame.new(math.random(-2, 2), -3, math.random(-2, 2))
    end
    local v868 = v867 or getRoot().CFrame * CFrame.Angles(0, 0.7853981633974483, 0) * CFrame.new(0, -2, 3)
    pcall(function()
        for _, descendant in pairs(p152:GetDescendants()) do
            if descendant:IsA("BasePart") then
                descendant.CFrame = v868
            end
        end
    end)
    for _, child in pairs(p152:GetChildren()) do
        if child.Name == "BananaPeel" and child:FindFirstChildOfClass("TouchTransmitter") then
            child.Size = Vector3.new(10, 10, 10)
            child.Transparency = 1
            ragdollBananaPeel = child
            ragdollActive = true
            task.spawn(function()
                while ragdollActive and (ragdollBananaPeel and ragdollBananaPeel.Parent) do
                    local v2013 = getRoot()

                    if not v2013 then
                        waitTime(0.1)
                    else
                        local t35 = {}

                        for _, player14 in pairs(t2.value96:GetPlayers()) do
                            if not t2.value12(player14) and (player14 ~= t1.value3 and player14.Character) then
                                local HumanoidRootPart = player14.Character:FindFirstChild("HumanoidRootPart")

                                if HumanoidRootPart then
                                    local Magnitude = (v2013.Position - HumanoidRootPart.Position).Magnitude
                                    local AssemblyLinearVelocity = HumanoidRootPart.AssemblyLinearVelocity
                                    local insert = table.insert
                                    local v2021 = getPlayerLegs(player14)
                                    local Magnitude2 = AssemblyLinearVelocity.Magnitude

                                    insert(t35, {
										player = player14,
										distance = Magnitude,
										legs = v2021,
										velocity = AssemblyLinearVelocity,
										speed = Magnitude2
									})
                                end
                            end
                        end

                        table.sort(t35, function(p153, p154)
                            return p153.distance < p154.distance
                        end)

                        for _, v in ipairs(t35) do
                            if not ragdollActive or (not ragdollBananaPeel or not ragdollBananaPeel.Parent) then
                                break
                            end

                            if #v.legs > 0 then
                                local CFrame6 = v.legs[math.random(1, #v.legs)].CFrame
                                local v2026 = math.random(-5, 5) / 10
                                local v2027 = math.random(-20, -10) / 10
                                local v2028 = math.random(-5, 5) / 10
                                local v2029 = tick() % 360 * 50

                                ragdollBananaPeel.CFrame = CFrame6 * CFrame.new(v2026, v2027, v2028) * CFrame.Angles(math.rad(v2029), math.rad(v2029 * 0.5), 0)
                                ragdollBananaPeel.AssemblyLinearVelocity = v.velocity * 0.8 + Vector3.new(math.random(-10, 10), math.random(10, 30), math.random(-10, 10))
                                waitTime(0.16)
                            end
                        end
                    end
                end
            end)

            break
        end
    end
end
folder.ChildAdded:Connect(function(child)
    if child.Name == "FoodBanana" and ragdollToggleActive then
        ragdollCurrentFood = child
        task.spawn(function()
            t2.value106(ragdollCurrentFood)
        end)

        return
    end

    if child.Name == "Campfire" and campfireToggleActive then
        campfireCurrentToy = child
        task.spawn(function()
            waitTime(0.5)
            setCampfireOwner(campfireCurrentToy)
            campfireToyActive = true
            campfireLoop()
        end)
    end
end)
t1.value2.Heartbeat:Connect(function()
    if ragdollToggleActive and not ragdollCurrentFood or not ragdollCurrentFood.Parent then
        ragdollCurrentFood = nil
        spawnRagdollFood()

        return
    end

    if campfireToggleActive and not campfireCurrentToy or not campfireCurrentToy.Parent then
        campfireCurrentToy = nil
        spawnCampfireToy()
    end
end)
Camera = workspace.CurrentCamera
ServerTab:CreateToggle({
	Name = "LoopVomit All    <font face=\"GothamBlack\" color=\"rgb(150, 75, 0)\">POOP</font>    <font face=\"GothamBlack\" color=\"rgb(90,120,200)\">GLOBAL</font>",
	CurrentValue = false,
	Callback = function(p155)
    vomitToggleActive = p155

    if p155 then
        vomitReverseOrder = false
        spawnVomitPoop()
    end
end
})
function getRootVomit(p156)
    return p156 and p156:FindFirstChild("HumanoidRootPart")
end
function focusPlayerVomit(p157)
    if t2.value12(p157) then
        return
    end

    local Character = t1.value3.Character
    local v876 = getRootVomit(Character)

    if not v876 or not p157.Character then
        return
    end

    local v877 = getRootVomit(p157.Character)
    local Humanoid19 = p157.Character:FindFirstChildOfClass("Humanoid")

    if not v877 or Humanoid19 and Humanoid19.Health <= 0 then
        return
    end

    local timestamp = tick()

    if not (tick() - timestamp >= 0.142) then
    end

    repeat
        if not v877 or not v876 then
            return
        end

        local v880 = v877.CFrame * CFrame.new(0, 0.5, 3)

        v876.CFrame = CFrame.lookAt(v880.Position, v877.Position)
        Camera.CFrame = CFrame.lookAt(Camera.CFrame.Position, v877.Position)
        v876.AssemblyLinearVelocity = Vector3.zero
        v876.AssemblyAngularVelocity = Vector3.zero
        t1.value2.Heartbeat:Wait()
    until tick() - timestamp >= 0.142
end
function tpToEveryoneVomit()
    local players = t2.value96:GetPlayers()
    local t36 = {}
    for v885, v886 in ipairs(players) do

        if v886 ~= t1.value3 and (v886.Character and not t2.value12(v886)) then
            table.insert(t36, v886)
        end
    end
    if vomitReverseOrder then
        for i = #t36, 1, -1 do
            focusPlayerVomit(t36[i])
        end
    else
        for _, v in ipairs(t36) do
            focusPlayerVomit(v)
        end
    end
    vomitReverseOrder = not vomitReverseOrder
end
function spawnVomitPoop()
    local v890 = getRootVomit(t1.value3.Character)

    if not v890 then
        return
    end

    local t37 = {
		"PoopPile",
		v890.CFrame * CFrame.new(0, 0, 10),
		Vector3.new(0, 97.69, 0)
	}

    pcall(function()
        t2.value9.MenuToys.SpawnToyRemoteFunction:InvokeServer(unpack(t37))
    end)
end
function vomitProcessFood(p158)
    if not vomitToggleActive then
        return
    end

    local HoldPart = p158:WaitForChild("HoldPart", 5)

    if not HoldPart then
        return
    end

    pcall(function()
        HoldPart.HoldItemRemoteFunction:InvokeServer(p158, t1.value3.Character)
    end)
    waitTime(0.3)
    pcall(function()
        t2.value9.HoldEvents.Use:FireServer(p158)
    end)
    waitTime(2.9)

    if vomitToggleActive then
        tpToEveryoneVomit()
        spawnVomitPoop()
    end
end
folder.ChildAdded:Connect(function(child)
    if child.Name == "PoopPile" and vomitToggleActive then
        task.spawn(function()
            vomitProcessFood(child)
        end)
    end
end)
ServerTab:CreateToggle({
	Name = "Fire All    <font face=\"GothamBlack\" color=\"rgb(205,133,63)\">CAMPFIRE</font>    <font face=\"GothamBlack\" color=\"rgb(150,0,0)\">GLOBAL</font>    <font face=\"GothamBlack\" color=\"rgb(255,255,0)\">BETA</font>",
	CurrentValue = false,
	Callback = function(p159)
    campfireToggleActive = p159

    if p159 then
        spawnCampfireToy()

        return
    end

    campfireToyActive = false

    if campfireCurrentToy and campfireCurrentToy.Parent then
        pcall(function()
            DeleteToyRE:FireServer(campfireCurrentToy)
        end)
    end

    campfireCurrentToy = nil
end
})
function setCampfireOwner(p160)
    if p160 and p160.Parent then
        pcall(function()
            for _, descendant in pairs(p160:GetDescendants()) do
                if descendant:IsA("BasePart") then
                    SetNetworkOwner:FireServer(descendant, descendant.CFrame)
                end
            end
        end)
    end
end
function spawnCampfireToy()
    if not campfireToggleActive then
        return
    end

    if tick() - campfireLastSpawn < campfireSpawnCooldown then
        return
    end

    campfireLastSpawn = tick()

    local v897 = getRoot()

    if not v897 then
        return
    end

    local t38 = {
		"Campfire",
		v897.CFrame * CFrame.new(0, 0, 10),
		Vector3.new(0, 97.69, 0)
	}

    pcall(function()
        t2.value9.MenuToys.SpawnToyRemoteFunction:InvokeServer(unpack(t38))
    end)
end
function checkCampfireFireEnabled(p161)
    local FirePlayerPart = p161:FindFirstChild("FirePlayerPart")

    if not FirePlayerPart then
        return false
    end

    local Attachment = FirePlayerPart:FindFirstChild("Attachment")

    if not Attachment then
        return false
    end

    local FireParticleEmitter = Attachment:FindFirstChild("FireParticleEmitter")

    return FireParticleEmitter and FireParticleEmitter.Enabled
end
function playerHasFireInHRP(p162)
    if not p162 or not p162.Character then
        return false
    end

    local HumanoidRootPart = p162.Character:FindFirstChild("HumanoidRootPart")

    if not HumanoidRootPart then
        return false
    end

    local GetDescendants = HumanoidRootPart.GetDescendants

    for _, v in pairs(GetDescendants(HumanoidRootPart)) do
        if v:IsA("FireParticleEmitter") then
            return true
        end
    end

    return false
end
function campfireLoop()
    task.spawn(function()
        while campfireToyActive and (campfireCurrentToy and campfireCurrentToy.Parent) do
            if not checkCampfireFireEnabled(campfireCurrentToy) then
                pcall(function()
                    DeleteToyRE:FireServer(campfireCurrentToy)
                end)
                campfireCurrentToy = nil
                campfireToyActive = false
                spawnCampfireToy()
                waitTime(0.5)

                return
            end

            if not getRoot() then
                waitTime(0.1)
            else
                local t39 = {}
                local t40 = {}
                for v2036, v2037 in pairs(t2.value96:GetPlayers()) do

                    if not t2.value12(v2037) and (v2037 ~= t1.value3 and v2037.Character) and v2037.Character:FindFirstChild("HumanoidRootPart") then
                        if playerHasFireInHRP(v2037) then
                            table.insert(t39, v2037)
                        else
                            table.insert(t40, v2037)
                        end
                    end
                end
                local v2038, v2039, v2040 = pairs(t40)
                while true do
                    local v2041

                    v2040, v2041 = v2038(v2039, v2040)

                    if not v2040 or (not campfireToyActive or (not campfireCurrentToy or not campfireCurrentToy.Parent)) then
                        break
                    end

                    local HumanoidRootPart = v2041.Character:FindFirstChild("HumanoidRootPart")

                    if HumanoidRootPart then
                        pcall(function()
                            campfireCurrentToy:PivotTo(HumanoidRootPart.CFrame * CFrame.new(0, -2, 0))
                        end)
                        waitTime(0.2)
                    end
                end
                for _, v in pairs(t39) do
                    if not campfireToyActive or (not campfireCurrentToy or not campfireCurrentToy.Parent) then
                        break
                    end

                    local HumanoidRootPart = v.Character:FindFirstChild("HumanoidRootPart")

                    if HumanoidRootPart then
                        pcall(function()
                            campfireCurrentToy:PivotTo(HumanoidRootPart.CFrame * CFrame.new(0, -2, 0))
                        end)
                        waitTime(0.2)
                    end
                end
            end
        end
    end)
end
ServerTab:CreateLabel("Fun", "Cone")
bringAllToggleActive = false
freezecampart = nil
playerCFrame = nil
cameraCFrame = nil
bringAllActive = false
playerCFrame = nil
cameraCFrame = nil
freezecampart = nil
function GetPlayerCFrame()
    local Character = t1.value3.Character

    if Character then
        return Character.HumanoidRootPart.CFrame
    end
end
freezecampart = Instance.new("Part", Workspace)
freezecampart.Name = "BloodyCamera"
freezecampart.Anchored = true
freezecampart.CanCollide = false
freezecampart.Transparency = 1
freezecampart.CanQuery = false
freezecampart.Size = Vector3.new()
function FreezeCam(p163)
    freezecampart.CFrame = p163
    Workspace.CurrentCamera.CameraType = Enum.CameraType.Follow
    Workspace.CurrentCamera.CameraSubject = freezecampart
end
function unFreezeCam()
    Workspace.CurrentCamera.CameraSubject = t1.value3.Character:FindFirstChildOfClass("Humanoid")
    Workspace.CurrentCamera.CameraType = Enum.CameraType.Custom
end
function CheckPlayerBring(p164)
    if t2.value12(p164) then
        return false
    end

    if p164 and p164.Character then
        local HumanoidRootPart = p164.Character:FindFirstChild("HumanoidRootPart")
        local Humanoid20 = p164.Character:FindFirstChildOfClass("Humanoid")

        if HumanoidRootPart and Humanoid20 then
            return Humanoid20:FindFirstChild("Ragdolled") ~= nil
        end
    end

    return false
end
function CheckNetworkOwnerShipOnPlayer(p165)
    local Character = p165.Character

    if Character then
        Character = p165.Character:FindFirstChild("Head") and (p165.Character.Head:FindFirstChild("PartOwner") and p165.Character.Head.PartOwner.Value == t1.value3.Name)
    end

    if Character then
        return true
    end

    return false
end
function SNOWshipOnce(p166)
    local v916 = t1.value3:DistanceFromCharacter(p166.Position)

    if t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart") and v916 <= 30 then
        SetNetworkOwner:FireServer(p166, CFrame.lookAt(t1.value3.Character.HumanoidRootPart.Position, p166.Position))
    end
end
function CreateBringBody(p167, p168)
    if p167:FindFirstChild("BringBody") then
        p167.BringBody.Position = p168.Position

        return
    end

    local BodyPosition = Instance.new("BodyPosition", p167)

    BodyPosition.Name = "BringBody"
    BodyPosition.Position = p168.Position
    BodyPosition.MaxForce = Vector3.new(1e999, 1e999, 1e999)
    BodyPosition.D = 5000
    BodyPosition.P = 1500000
end
function TeleportPlayer(p169)
    local Character = t1.value3.Character

    if Character and typeof(p169) == "CFrame" then
        local HumanoidRootPart = Character.HumanoidRootPart
        local Humanoid21 = Character:FindFirstChildOfClass("Humanoid")

        HumanoidRootPart.CFrame = HumanoidRootPart.CFrame.Rotation + p169.Position

        if Humanoid21.SeatPart == nil or tostring(Humanoid21.SeatPart.Parent) ~= "CreatureBlobman" then
            Humanoid21.Sit = false
        end
    end
end
ServerTab:CreateToggle({
	Name = "Bring All   <font face=\"GothamBlack\" color=\"rgb(255,50,0)\">FAST</font>   <font face=\"GothamBlack\" color=\"rgb(0,255,0)\">GLOBAL</font>   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>\t <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
	CurrentValue = false,
	Callback = function(p170)
    bringAllActive = p170

    if p170 then
        playerCFrame = GetPlayerCFrame()

        if not playerCFrame then
            return
        end

        cameraCFrame = CFrame.lookAt(playerCFrame.Position + Vector3.new(0, 5, 15), playerCFrame.Position)
        Workspace.CurrentCamera.CFrame = cameraCFrame
        task.spawn(function()
            while bringAllActive do
                FreezeCam(cameraCFrame)

                for _, player15 in pairs(t2.value96:GetPlayers()) do
                    if player15 ~= t1.value3 and CheckPlayerBring(player15) then
                        local HumanoidRootPart = player15.Character:FindFirstChild("HumanoidRootPart")
                        local Humanoid22 = player15.Character:FindFirstChildOfClass("Humanoid")

                        if HumanoidRootPart and (Humanoid22 and Humanoid22:FindFirstChild("Ragdolled")) then
                            for _ = 0, 50 do
                                if not bringAllActive then
                                    break
                                end

                                SNOWshipOnce(HumanoidRootPart)

                                if CheckNetworkOwnerShipOnPlayer(player15) then
                                    HumanoidRootPart.CFrame = playerCFrame * CFrame.new(math.random(-3, 3) / 10, 0, math.random(-3, 3) / 10)
                                    HumanoidRootPart.AssemblyLinearVelocity = Vector3.new(0, 0, 0)
                                    HumanoidRootPart.AssemblyAngularVelocity = Vector3.new(0, 0, 0)

                                    local GetChildren = HumanoidRootPart.GetChildren

                                    for _, v in pairs(GetChildren(HumanoidRootPart)) do
                                        if v:IsA("BodyVelocity") or (v:IsA("BodyPosition") or v:IsA("BodyAngularVelocity")) then
                                            v:Destroy()
                                        end
                                    end

                                    local BodyPosition = Instance.new("BodyPosition", HumanoidRootPart)

                                    BodyPosition.Name = "AntiFloatBody"
                                    BodyPosition.Position = playerCFrame.Position + Vector3.new(math.random(-2, 2), -2, math.random(-2, 2))
                                    BodyPosition.MaxForce = Vector3.new(4000, 4000, 4000)
                                    BodyPosition.P = 10000
                                    BodyPosition.D = 2000
                                    task.spawn(function()
                                        task.wait(2)

                                        if BodyPosition and BodyPosition.Parent then
                                            BodyPosition:Destroy()
                                        end
                                    end)

                                    break
                                end

                                task.wait()

                                if HumanoidRootPart.Position.Y <= -12 then
                                    TeleportPlayer(CFrame.new(HumanoidRootPart.Position + Vector3.new(0, 5, -15)))
                                else
                                    TeleportPlayer(CFrame.new(HumanoidRootPart.Position + Vector3.new(0, -10, -10)))
                                end
                            end
                        end
                    end
                end

                TeleportPlayer(CFrame.new(527, 123, -376))
                task.wait()
            end

            unFreezeCam()
            TeleportPlayer(playerCFrame)
        end)
    end
end
})
AuraTab:CreateLabel("OP Auras", "crown")
t2.value107 = false
t2.value108 = nil
AuraTab:CreateToggle({
	Name = "Void Aura\t  <font face=\"GothamBlack\" color=\"rgb(128,0,255)\">VOID</font>\t <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>\t<font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>",
	CurrentValue = false,
	Flag = "DeathAura",
	Callback = function(p171)
    t2.value107 = p171

    if p171 then
        if t2.value108 then
            t2.value108:Disconnect()
        end

        t2.value108 = t1.value2.Heartbeat:Connect(function()
            if not t2.value107 then
                return
            end

            local Character = t1.value3.Character
            local v2056 = Character and Character:FindFirstChild("HumanoidRootPart")

            if not v2056 then
                return
            end

            local players = t2.value96:GetPlayers()

            for i = 1, #players do
                local v2059 = players[i]

                if v2059 ~= t1.value3 and v2059.Character and not t2.value12(v2059) then
                    local Character7 = v2059.Character
                    local HumanoidRootPart = Character7:FindFirstChild("HumanoidRootPart")
                    local Humanoid23 = Character7:FindFirstChild("Humanoid")

                    if HumanoidRootPart and (Humanoid23 and (v2056.Position - HumanoidRootPart.Position).Magnitude <= 30) then
                        pcall(function()
                            SetNetworkOwner:FireServer(HumanoidRootPart, HumanoidRootPart.CFrame)
                            DestroyGrabLine:FireServer(HumanoidRootPart)
                            for v2326, v2327 in pairs(Character7:GetChildren()) do

                                if v2327:IsA("BasePart") then
                                    v2327.CFrame = CFrame.new(-900000000000, 9000000000000, -900000000000)
                                end
                            end
                            task.wait()
                            for _, child in pairs(Character7:GetChildren()) do
                                if child:IsA("BasePart") then
                                    child.CFrame = CFrame.new(-900000000000, 9000000000000, -900000000000)
                                end
                            end
                            local BodyVelocity = Instance.new("BodyVelocity")
                            BodyVelocity.Velocity = Vector3.new(0, 90000000000, 0)
                            BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                            BodyVelocity.P = 100000075
                            BodyVelocity.Parent = HumanoidRootPart
                            Humanoid23.BreakJointsOnDeath = false
                            Humanoid23:ChangeState(Enum.HumanoidStateType.Dead)
                            task.delay(2, function()
                                if BodyVelocity and BodyVelocity.Parent then
                                    BodyVelocity:Destroy()
                                end
                            end)
                        end)
                    end
                end
            end
        end)

        return
    end

    if t2.value108 then
        t2.value108:Disconnect()
    end
end
})
t2.value109 = false
t2.value110 = nil
AuraTab:CreateToggle({
	Name = "Kick Aura\t  <font face=\"GothamBlack\" color=\"rgb(255,200,0)\">KICK</font>\t<font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>\t  <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
	CurrentValue = false,
	Flag = "KickAura",
	Callback = function(p172)
    t2.value109 = p172

    if p172 then
        if t2.value110 then
            t2.value110:Disconnect()
        end

        t2.value110 = t1.value2.Heartbeat:Connect(function()
            if not t2.value109 then
                return
            end

            local Character = t1.value3.Character
            local v2064 = Character and Character:FindFirstChild("HumanoidRootPart")

            if not v2064 then
                return
            end

            local players = t2.value96:GetPlayers()

            for i = 1, #players do
                local v2067 = players[i]

                if v2067 ~= t1.value3 and v2067.Character and not t2.value12(v2067) then
                    local HumanoidRootPart = v2067.Character:FindFirstChild("HumanoidRootPart")

                    if HumanoidRootPart and (v2064.Position - HumanoidRootPart.Position).Magnitude <= 30 then
                        pcall(function()
                            SetNetworkOwner:FireServer(HumanoidRootPart, HumanoidRootPart.CFrame)
                            DestroyGrabLine:FireServer(HumanoidRootPart)
                            HumanoidRootPart.CFrame = CFrame.new(0, 90000000000000, 0)
                            task.wait()
                            HumanoidRootPart.CFrame = CFrame.new(0, 900000000000, 0)

                            local BodyVelocity = Instance.new("BodyVelocity")

                            BodyVelocity.Velocity = Vector3.new(0, 9000000000000, 0)
                            BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                            BodyVelocity.P = 100000000075
                            BodyVelocity.Parent = HumanoidRootPart
                            task.delay(2, function()
                                if BodyVelocity and BodyVelocity.Parent then
                                    BodyVelocity:Destroy()
                                end
                            end)
                        end)
                    end
                end
            end
        end)

        return
    end

    if t2.value110 then
        t2.value110:Disconnect()
    end
end
})
t2.value111 = false
t2.value112 = nil
AuraTab:CreateToggle({
	Name = "Grab Aura   <font face=\"GothamBlack\" color=\"rgb(0,255,128)\">SPAM</font>    <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>",
	CurrentValue = false,
	Flag = "GrabAura",
	Callback = function(p173)
    t2.value111 = p173

    if p173 then
        if t2.value112 then
            t2.value112:Disconnect()
        end

        t2.value112 = t1.value2.Heartbeat:Connect(function(_)
            if not t2.value111 then
                return
            end

            local Character = t1.value3.Character

            if not Character or not Character:FindFirstChild("HumanoidRootPart") then
                return
            end

            local HumanoidRootPart = Character.HumanoidRootPart
            local players = t2.value96:GetPlayers()

            for i = 1, #players do
                local v2074 = players[i]

                if v2074 ~= t1.value3 and v2074.Character and not t2.value12(v2074) then
                    local HumanoidRootPart6 = v2074.Character:FindFirstChild("HumanoidRootPart")

                    if HumanoidRootPart6 and (HumanoidRootPart.Position - HumanoidRootPart6.Position).Magnitude <= 30 then
                        pcall(function()
                            t2.value9.GrabEvents.SetNetworkOwner:FireServer(HumanoidRootPart6, HumanoidRootPart6.CFrame)
                        end)
                    end
                end
            end
        end)

        return
    end

    if t2.value112 then
        t2.value112:Disconnect()
    end
end
})
t2.value113 = 100
t2.value114 = 30
t2.value115 = {}
t2.value116 = nil
AuraTab:CreateToggle({
	Name = "Throw Aura\t   <font face=\"GothamBlack\" color=\"rgb(255,128,0)\">THROW</font>\t  <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>",
	CurrentValue = false,
	Flag = "ThrowAura",
	Callback = function(p175)
    if p175 then
        if t2.value116 then
            t2.value116:Disconnect()
        end

        t2.value116 = t1.value2.Heartbeat:Connect(function()
            local v2076 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")

            if not v2076 then
                return
            end

            local Position = v2076.Position

            for _, player16 in pairs(t2.value96:GetPlayers()) do
                if player16 ~= t1.value3 and player16.Character and not t2.value12(player16) then
                    local HumanoidRootPart = player16.Character:FindFirstChild("HumanoidRootPart")

                    if HumanoidRootPart and (HumanoidRootPart.Position - Position).Magnitude <= t2.value114 then
                        pcall(function()
                            SetNetworkOwner:FireServer(HumanoidRootPart, HumanoidRootPart.CFrame)
                        end)

                        local ThrowBV = HumanoidRootPart:FindFirstChild("ThrowBV")

                        if not ThrowBV then
                            ThrowBV = Instance.new("BodyVelocity")
                            ThrowBV.Name = "ThrowBV"
                            ThrowBV.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                            ThrowBV.Parent = HumanoidRootPart
                            t2.value115[HumanoidRootPart] = ThrowBV
                        end

                        ThrowBV.Velocity = Vector3.new(math.random(-t2.value113, t2.value113), math.random(5, t2.value113), math.random(-t2.value113, t2.value113))
                    elseif t2.value115[HumanoidRootPart] then
                        t2.value115[HumanoidRootPart]:Destroy()
                        t2.value115[HumanoidRootPart] = nil
                    end
                end
            end
        end)

        return
    end

    if t2.value116 then
        t2.value116:Disconnect()
    end

    for _, v in pairs(t2.value115) do
        if v and v.Parent then
            v:Destroy()
        end
    end
end
})
do
    local _AuraTab = AuraTab
    local value113 = t2.value113

    _AuraTab:CreateSlider({
		Name = "Throw Speed",
		Range = {
			10,
			1000
		},
		Increment = 1,
		Suffix = "Velocity",
		CurrentValue = value113,
		Flag = "ThrowSpeed",
		Callback = function(p176)
        t2.value113 = p176
    end
	})
    AuraTab:CreateLabel("Objects & Players Auras", "user-circle")
    Bodies = {}
    GrabbedObjects = {}
    Active = false
    TornadoOffset = 10
    TornadoHeight = 5
    TornadoSpeed = 0.1
    TornadoImpact = "Players"

    function t2.value117()
        for _, v in pairs(Bodies) do
            if v and v.Parent then
                v:Destroy()
            end
        end

        Bodies = {}
        GrabbedObjects = {}
    end
    function ApplyMotion(p177, p178, p179, p180, p181)
        if not p177 or p177.Anchored then
            return
        end

        local TornadoAuraVelocity = p177:FindFirstChild("TornadoAuraVelocity")

        if not TornadoAuraVelocity then
            TornadoAuraVelocity = Instance.new("BodyPosition")
            TornadoAuraVelocity.Name = "TornadoAuraVelocity"
            TornadoAuraVelocity.MaxForce = Vector3.new(1000000, 1000000, 1000000)
            TornadoAuraVelocity.P = 50000
            TornadoAuraVelocity.D = 1250
            TornadoAuraVelocity.Parent = p177
            table.insert(Bodies, TornadoAuraVelocity)
        end

        local vector3 = Vector3.new(math.cos(p179) * p180, p181, math.sin(p179) * p180)

        TornadoAuraVelocity.Position = p178.Position + vector3
    end
    function GetPlayerRoot(p182)
        local Character = p182.Character

        if Character then
            return Character:FindFirstChild("HumanoidRootPart")
        end
    end
    function isPlayerPart(p183)
        for _, player17 in ipairs(t2.value96:GetPlayers()) do
            if player17.Character and p183:IsDescendantOf(player17.Character) then
                return true
            end
        end

        return false
    end

    t1.value2.Heartbeat:Connect(function()
        if not Active then
            t2.value117()

            return
        end

        local v946 = GetPlayerRoot(t1.value3)

        if not v946 then
            return
        end

        local CFrame7 = v946.CFrame
        local v948 = tick() * TornadoSpeed * 2 * 3.141592653589793 % 6.283185307179586

        for _, v in pairs(GrabbedObjects) do
            if v and v.Parent then
                ApplyMotion(v, CFrame7, v948, TornadoOffset, TornadoHeight)
            end
        end
    end)
    task.spawn(function()
        while task.wait(0.3) do
            if Active then
                local v951 = GetPlayerRoot(t1.value3)

                if v951 then
                    if TornadoImpact == "Objects" or TornadoImpact == "Player & Object" then
                        local PartBoundsInRadius = workspace:GetPartBoundsInRadius(v951.Position, 30)

                        for _, v in pairs(PartBoundsInRadius) do
                            local v955 = v

                            if v955:IsA("BasePart") and (not v955.Anchored and not isPlayerPart(v955)) then
                                pcall(function()
                                    SetNetworkOwner:FireServer(v955, v955.CFrame)
                                end)

                                if not table.find(GrabbedObjects, v955) then
                                    table.insert(GrabbedObjects, v955)
                                end
                            end
                        end
                    end

                    if TornadoImpact == "Players" or TornadoImpact == "Player & Object" then
                        for _, player18 in pairs(t2.value96:GetPlayers()) do
                            if player18 ~= t1.value3 and player18.Character and not t2.value12(player18) then
                                local v958 = player18.Character:FindFirstChild("Torso") or player18.Character:FindFirstChild("HumanoidRootPart")

                                if v958 and (v951.Position - v958.Position).Magnitude <= 30 then
                                    pcall(function()
                                        SetNetworkOwner:FireServer(v958, v958.CFrame)
                                    end)

                                    if not table.find(GrabbedObjects, v958) then
                                        table.insert(GrabbedObjects, v958)
                                    end
                                end
                            end
                        end
                    end
                end
            end
        end
    end)
    AuraTab:CreateToggle({
		Name = "Telekinesis Aura    <font face=\"GothamBlack\" color=\"rgb(0,200,255)\">ORBIT</font>   <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>\t <font face=\"GothamBlack\" color=\"rgb(255, 255, 255)\">(PLAYER & OBJECT)</font>",
		CurrentValue = false,
		Flag = "TelekinesisAura",
		Callback = function(p184)
        Active = p184

        if not p184 then
            t2.value117()
        end
    end
	})
    AuraTab:CreateDropdown({
		Name = "Impact\t  <font face=\"GothamBlack\" color=\"rgb(255,40,0)\">SELECT</font>",
		Options = {
			"Players",
			"Objects",
			"Player & Object"
		},
		CurrentOption = { "Players" },
		MultipleOptions = false,
		Flag = "TornadoImpact",
		Callback = function(p185)
        local v961 = p185[1]

        t2.value117()
        TornadoImpact = v961
    end
	})

    local _AuraTab2 = AuraTab
    local _TornadoOffset = TornadoOffset

    _AuraTab2:CreateSlider({
		Name = "Distance",
		Range = {
			1,
			500
		},
		Increment = 1,
		Suffix = "Offset",
		CurrentValue = _TornadoOffset,
		Flag = "AuraDistance",
		Callback = function(p186)
        TornadoOffset = p186
    end
	})

    local _AuraTab3 = AuraTab
    local _TornadoHeight = TornadoHeight

    _AuraTab3:CreateSlider({
		Name = "Height",
		Range = {
			1,
			500
		},
		Increment = 1,
		Suffix = "Height",
		CurrentValue = _TornadoHeight,
		Flag = "AuraHeight",
		Callback = function(p187)
        TornadoHeight = p187
    end
	})

    local _AuraTab4 = AuraTab
    local _TornadoSpeed = TornadoSpeed

    _AuraTab4:CreateSlider({
		Name = "Rotation Speed",
		Range = {
			0.01,
			1
		},
		Increment = 0.001,
		Suffix = "Speed",
		CurrentValue = _TornadoSpeed,
		Flag = "AuraSpeed",
		Callback = function(p188)
        TornadoSpeed = p188
    end
	})
    AuraTab:CreateSection("Air Aura")
    t2.value118 = 50
    t2.value119 = {}
    t2.value120 = nil
    t2.value121 = "Players"
    CONFIG = {
		AURA_RADIUS = 30,
		SCAN_DELAY = 0.1,
		MAX_DISTANCE = 30
	}

    function isPlayerPart(p189)
        for _, player19 in ipairs(t2.value96:GetPlayers()) do
            local Character = player19.Character

            if Character then
                Character = p189:IsDescendantOf(player19.Character)
            end

            if Character then
                return true
            end
        end

        return false
    end
    function cleanUpObjects()
        for _, v in pairs(t2.value119) do
            if v and v.Parent then
                v:Destroy()
            end
        end

        t2.value119 = {}
    end

    AuraTab:CreateToggle({
		Name = "Air Suspend Aura   <font face=\"GothamBlack\" color=\"rgb(120,0,255)\">FLY</font>    <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>\t <font face=\"GothamBlack\" color=\"rgb(255, 255, 255)\">(PLAYER & OBJECT)</font>",
		CurrentValue = false,
		Flag = "AirSuspendAura",
		Callback = function(p190)
        if p190 then
            task.spawn(function()
                while task.wait(0.3) and t2.value120 do
                    local v2082 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")

                    if v2082 then
                        local PartBoundsInRadius = workspace:GetPartBoundsInRadius(v2082.Position, CONFIG.AURA_RADIUS)
                        for v2086, v2087 in pairs(PartBoundsInRadius) do

                            local v2088 = v2087

                            if v2088:IsA("BasePart") and (not v2088.Anchored and not isPlayerPart(v2088)) and (t2.value121 == "Objects" or t2.value121 == "Player & Object") then
                                pcall(function()
                                    SetNetworkOwner:FireServer(v2088, v2088.CFrame)
                                end)
                            end
                        end
                        if t2.value121 == "Players" or t2.value121 == "Player & Object" then
                            for _, player20 in pairs(t2.value96:GetPlayers()) do
                                if player20 ~= t1.value3 and player20.Character and not t2.value12(player20) then
                                    local v2091 = player20.Character:FindFirstChild("Torso") or player20.Character:FindFirstChild("HumanoidRootPart")

                                    if v2091 and (v2082.Position - v2091.Position).Magnitude <= CONFIG.MAX_DISTANCE then
                                        pcall(function()
                                            SetNetworkOwner:FireServer(v2091, v2091.CFrame)
                                        end)
                                    end
                                end
                            end
                        end
                    end
                end
            end)
            t2.value120 = coroutine.create(function()
                while task.wait(CONFIG.SCAN_DELAY) do
                    local v2092 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")
                    if not v2092 then
                        return
                    end
                    local PartBoundsInRadius = workspace:GetPartBoundsInRadius(v2092.Position, CONFIG.AURA_RADIUS)
                    for v2096, v2097 in pairs(PartBoundsInRadius) do

                        if v2097:IsA("BasePart") and (not v2097.Anchored and not isPlayerPart(v2097)) and (t2.value121 == "Objects" or t2.value121 == "Player & Object") and not t2.value119[v2097] then
                            local BodyVelocity = Instance.new("BodyVelocity")

                            BodyVelocity.Name = "AirSuspendBV"
                            BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                            BodyVelocity.Velocity = Vector3.new(0, t2.value118, 0)
                            BodyVelocity.Parent = v2097
                            t2.value119[v2097] = BodyVelocity
                        end
                    end
                    if t2.value121 == "Players" or t2.value121 == "Player & Object" then
                        for _, player21 in pairs(t2.value96:GetPlayers()) do
                            if player21 ~= t1.value3 and player21.Character and not t2.value12(player21) then
                                local v2101 = player21.Character:FindFirstChild("Torso") or player21.Character:FindFirstChild("HumanoidRootPart")
                                local v2102 = v2101

                                if v2102 then
                                    v2101 = (v2092.Position - v2102.Position).Magnitude <= CONFIG.MAX_DISTANCE
                                end

                                if v2101 and not t2.value119[player21] then
                                    local BodyVelocity = Instance.new("BodyVelocity")

                                    BodyVelocity.Name = "AirSuspendBV"
                                    BodyVelocity.MaxForce = Vector3.new(1e999, 1e999, 1e999)
                                    BodyVelocity.Velocity = Vector3.new(0, t2.value118, 0)
                                    BodyVelocity.Parent = v2102
                                    t2.value119[player21] = BodyVelocity
                                end
                            end
                        end
                    end
                end
            end)
            coroutine.resume(t2.value120)

            return
        end

        if t2.value120 then
            coroutine.close(t2.value120)
        end

        cleanUpObjects()
    end
	})
    dropdown = AuraTab:CreateDropdown({
		Name = "Impact\t  <font face=\"GothamBlack\" color=\"rgb(255,40,0)\">SELECT</font>",
		Options = {
			"Players",
			"Objects",
			"Player & Object"
		},
		CurrentOption = { "Players" },
		MultipleOptions = false,
		Flag = "AirSuspendImpact",
		Callback = function(p191)
        local _ = p191[1]

        cleanUpObjects()
    end
	})

    local _AuraTab5 = AuraTab
    local str = tostring(t2.value118)

    _AuraTab5:CreateInput({
		Name = "Speed",
		CurrentValue = str,
		PlaceholderText = "Enter speed",
		RemoveTextAfterFocusLost = false,
		Flag = "AirSuspendSpeed",
		Callback = function(p192)
        if not tonumber(p192) then
        end
    end
	})
    AuraTab:CreateSection("Teleport")
    t2.value122 = false
    t2.value123 = "Cursed Cloud"
    t2.value124 = nil
    AuraTab:CreateToggle({
		Name = "Teleport Aura\t  <font face=\"GothamBlack\" color=\"rgb(0,255,128)\">TP</font>    <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>\t<font face=\"GothamBlack\" color=\"rgb(255, 255, 255)\">(PLAYER)</font>",
		CurrentValue = false,
		Flag = "TeleportAura",
		Callback = function(p193)
        t2.value122 = p193

        if p193 then
            if t2.value124 then
                t2.value124:Disconnect()
            end

            t2.value124 = t1.value2.Heartbeat:Connect(function()
                local v2104 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")

                if not v2104 then
                    return
                end

                for _, player22 in pairs(t2.value96:GetPlayers()) do
                    if player22 ~= t1.value3 and player22.Character and not t2.value12(player22) then
                        local HumanoidRootPart = player22.Character:FindFirstChild("HumanoidRootPart")

                        if HumanoidRootPart and (v2104.Position - HumanoidRootPart.Position).Magnitude <= 30 then
                            pcall(function()
                                SetNetworkOwner:FireServer(HumanoidRootPart, HumanoidRootPart.CFrame)
                            end)

                            local vector3 = Vector3.new(0, 0, 0)

                            if t2.value123 == "Cursed Cloud" then
                                vector3 = Vector3.new(900000, 100, 3000)
                            elseif t2.value123 == "Spawn" then
                                vector3 = Vector3.new(0, 0, 0)
                            elseif t2.value123 == "Void" then
                                vector3 = Vector3.new(0, 1000000000000, 0)
                            elseif t2.value123 == "Cozy Place" then
                                vector3 = Vector3.new(592, 153, -101)
                            elseif t2.value123 == "Big Cave" then
                                vector3 = Vector3.new(-97.15, -7.35, 549.19)
                            elseif t2.value123 == "Small Cave" then
                                vector3 = Vector3.new(-35.08, -7.35, -275.37)
                            elseif t2.value123 == "Small Cave 2" then
                                vector3 = Vector3.new(137.87, -7.35, -389.94)
                            elseif t2.value123 == "Very Very Small Cave" then
                                vector3 = Vector3.new(191.09, -7.35, -564.27)
                            elseif t2.value123 == "Island Cave" then
                                vector3 = Vector3.new(90.77, 282.19, 333.66)
                            elseif t2.value123 == "Poison" then
                                vector3 = Vector3.new(71.25, -68.07, 269.03)
                            end

                            HumanoidRootPart.CFrame = CFrame.new(vector3)
                        end
                    end
                end
            end)

            return
        end

        if t2.value124 then
            t2.value124:Disconnect()
        end
    end
	})
    AuraTab:CreateDropdown({
		Name = "Teleport Location",
		Options = {
			"Cursed Cloud",
			"Spawn",
			"Void",
			"Cozy Place",
			"Big Cave",
			"Small Cave",
			"Small Cave 2",
			"Very Very Small Cave",
			"Island Cave",
			"Poison"
		},
		CurrentOption = { "Cursed Cloud" },
		Flag = "TeleportAuraLocation",
		Callback = function(p194)
        t2.value123 = p194[1]
    end
	})
    VisualTab:CreateLabel("Shaders", "cloudy")
    Lighting = game.Lighting
    InnerUFO = Workspace.Map.AlwaysHereTweenedObjects.InnerUFO.Object.ObjectModel
    OuterUFO = Workspace.Map.AlwaysHereTweenedObjects.OuterUFO.Object.ObjectModel

    local ClockTime = Lighting.ClockTime
    local LightingBrightness = Lighting.Brightness
    local OutdoorAmbient = Lighting.OutdoorAmbient
    local EnvironmentDiffuseScale = Lighting.EnvironmentDiffuseScale
    local EnvironmentSpecularScale = Lighting.EnvironmentSpecularScale
    local ExposureCompensation = Lighting.ExposureCompensation
    local FogColor = Lighting.FogColor
    local FogEnd = Lighting.FogEnd
    local FogStart = Lighting.FogStart
    local MoonAngularSize = Lighting.Sky.MoonAngularSize
    local StarCount = Lighting.Sky.StarCount

    DefaultLighting = {
		ClockTime = ClockTime,
		Brightness = LightingBrightness,
		OutdoorAmbient = OutdoorAmbient,
		EnvironmentDiffuseScale = EnvironmentDiffuseScale,
		EnvironmentSpecularScale = EnvironmentSpecularScale,
		ExposureCompensation = ExposureCompensation,
		FogColor = FogColor,
		FogEnd = FogEnd,
		FogStart = FogStart,
		MoonAngularSize = MoonAngularSize,
		StarCount = StarCount
	}
    States = {
		BeamLights = false,
		DayNight = false,
		Textures = false
	}
    VisualTab:CreateToggle({
		Name = "Beam Lights\t  <font face=\"GothamBlack\" color=\"rgb(0,255,0)\">NEON</font>",
		CurrentValue = false,
		Flag = "BeamLights",
		Callback = function(p195)
        States.BeamLights = p195

        if p195 then
            for k, v in pairs({
					Brightness = 10,
					LightInfluence = 0
				}) do
                OuterUFO.Laser.Beam[k] = v
                InnerUFO.Laser.Beam[k] = v
            end
            OuterUFO.Laser.Beam.Color = ColorSequence.new({
					ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 255, 0)),
					ColorSequenceKeypoint.new(0.5, Color3.fromRGB(0, 75, 0)),
					ColorSequenceKeypoint.new(0.9, Color3.fromRGB(84, 230, 96)),
					ColorSequenceKeypoint.new(1, Color3.fromRGB(193, 230, 187))
				})
            local Beam = OuterUFO.Laser.Beam
            local Beam2 = OuterUFO.Laser.Beam
            Beam.Width0 = 2
            Beam2.Width1 = 10
            InnerUFO.Laser.Beam.Color = OuterUFO.Laser.Beam.Color
            local Beam3 = InnerUFO.Laser.Beam
            local Beam4 = InnerUFO.Laser.Beam
            Beam3.Width0 = 2
            Beam4.Width1 = 13
            for v986, v987 in Workspace:GetDescendants() do

                if v987.Name == "GrabParts" then
                    local GrabBeam = v987:WaitForChild("BeamPart"):WaitForChild("GrabBeam")

                    GrabBeam.Brightness = 10
                    GrabBeam.LightEmission = 1
                    GrabBeam.LightInfluence = 0
                end
            end
            for _, descendant in Workspace:GetDescendants() do
                if descendant.Name == "Campfire" then
                    local FireLight = descendant:WaitForChild("FirePlayerPart"):WaitForChild("FireLight")

                    FireLight.Brightness = 5
                    FireLight.Shadows = false
                elseif descendant.Name == "FireworkSparkler" then
                    local PointLight = descendant:WaitForChild("Stick"):WaitForChild("Attachment"):WaitForChild("PointLight")

                    PointLight.Brightness = 5
                    PointLight.Range = 15
                    PointLight.Shadows = true
                end
            end

            return
        end

        OuterUFO.Laser.Beam.Brightness = 1
        InnerUFO.Laser.Beam.Brightness = 1
    end
	})
    VisualTab:CreateToggle({
		Name = "Day/Night Mode\t <font face=\"GothamBlack\" color=\"rgb(0,0,120)\">ATMOSPHERE</font>",
		CurrentValue = false,
		Flag = "DayNight",
		Callback = function(p196)
        States.DayNight = p196

        if p196 then
            Lighting.ClockTime = 4
            Lighting.Brightness = 3
            Lighting.OutdoorAmbient = Color3.fromRGB(0, 0, 0)
            Lighting.EnvironmentDiffuseScale = 0
            Lighting.EnvironmentSpecularScale = 1
            Lighting.ExposureCompensation = -1
            Lighting.Sky.MoonAngularSize = 20
            Lighting.Sky.StarCount = 5000
            Lighting.FogColor = Color3.fromRGB(52, 52, 52)

            local _Lighting = Lighting
            local _Lighting2 = Lighting

            _Lighting.FogEnd = 1000
            _Lighting2.FogStart = 0

            return
        end

        Lighting.ClockTime = DefaultLighting.ClockTime
        Lighting.Brightness = DefaultLighting.Brightness
        Lighting.OutdoorAmbient = DefaultLighting.OutdoorAmbient
        Lighting.EnvironmentDiffuseScale = DefaultLighting.EnvironmentDiffuseScale
        Lighting.EnvironmentSpecularScale = DefaultLighting.EnvironmentSpecularScale
        Lighting.ExposureCompensation = DefaultLighting.ExposureCompensation
        Lighting.Sky.MoonAngularSize = DefaultLighting.MoonAngularSize
        Lighting.Sky.StarCount = DefaultLighting.StarCount
        Lighting.FogColor = DefaultLighting.FogColor
        Lighting.FogEnd = DefaultLighting.FogEnd
        Lighting.FogStart = DefaultLighting.FogStart
    end
	})
    VisualTab:CreateToggle({
		Name = "Better Textures & Materials   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OPTIMIZATION</font>",
		CurrentValue = false,
		Flag = "Textures",
		Callback = function(p197)
        States.Textures = p197

        if p197 then
            OuterUFO.Laser.Beam.Texture = "rbxassetid://8933355899"
            InnerUFO.Laser.Beam.Texture = "rbxassetid://8933355899"

            for _, descendant in Workspace:GetDescendants() do
                if descendant.Name == "Button" then
                    descendant.Material = Enum.Material.Neon

                    if descendant.Parent.Name == "BombMissile" then
                        descendant.BrickColor = BrickColor.new(210, 0, 0)
                    end
                end
            end

            return
        end

        OuterUFO.Laser.Beam.Texture = ""
        InnerUFO.Laser.Beam.Texture = ""
    end
	})
    Lighting.GlobalShadows = true
    Lighting.Technology = Enum.Technology.Future
    Lighting.GeographicLatitude = 20
    Workspace.DescendantAdded:Connect(function(descendant)
        if States.BeamLights then
            if descendant.Name == "Campfire" then
                local FireLight = descendant:WaitForChild("FirePlayerPart"):WaitForChild("FireLight")

                FireLight.Brightness = 5
                FireLight.Shadows = false
            elseif descendant.Name == "FireworkSparkler" then
                local PointLight = descendant:WaitForChild("Stick"):WaitForChild("Attachment"):WaitForChild("PointLight")

                PointLight.Brightness = 5
                PointLight.Range = 15
                PointLight.Shadows = true
            elseif descendant.Name == "GrabParts" then
                local GrabBeam = descendant:WaitForChild("BeamPart"):WaitForChild("GrabBeam")

                GrabBeam.Brightness = 10
                GrabBeam.LightEmission = 1
                GrabBeam.LightInfluence = 0
            end
        end

        if States.Textures and descendant.Name == "Button" then
            descendant.Material = Enum.Material.Neon

            if descendant.Parent.Name == "BombMissile" then
                descendant.BrickColor = BrickColor.new(210, 0, 0)
            end
        end
    end)
    VisualTab:CreateLabel("Player ESP", "user")
    _G.PlayerHighlightColor = _G.PlayerHighlightColor or Color3.fromRGB(255, 0, 0)
    _G.ObjectHighlightColor = _G.ObjectHighlightColor or Color3.fromRGB(255, 0, 0)
    t2.value125 = {
		ph = false,
		pi = false,
		oh = false,
		own = false,
		conns = {}
	}
    t2.value126 = {}
    t2.value127 = {}
    t2.value128 = {}

    function discAll()
        for _, v in ipairs(t2.value125.conns) do
            local v1005 = v

            pcall(function()
                v1005:Disconnect()
            end)
        end

        table.clear(t2.value125.conns)
    end
    function rmHighlight(p198)
        if t2.value126[p198] then
            t2.value126[p198]:Destroy()
            t2.value126[p198] = nil
        end
    end
    function rmIcon(p199)
        if t2.value127[p199] then
            t2.value127[p199]:Destroy()
            t2.value127[p199] = nil
        end
    end
    function mkHighlight(p200, p201)
        rmHighlight(p201)

        local Highlight = Instance.new("Highlight")

        Highlight.FillColor = _G.PlayerHighlightColor
        Highlight.OutlineColor = Color3.new(0, 0, 0)
        Highlight.FillTransparency = 0
        Highlight.OutlineTransparency = 0
        Highlight.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
        Highlight.Adornee = p200
        Highlight.Parent = game:GetService("CoreGui")
        t2.value126[p201] = Highlight
    end
    function mkIcon(p202, p203)
        if not p202 then
            return
        end

        local HumanoidRootPart = p202:FindFirstChild("HumanoidRootPart")

        if not HumanoidRootPart then
            return
        end

        rmIcon(p203)

        local BillboardGui = Instance.new("BillboardGui")

        BillboardGui.Adornee = HumanoidRootPart
        BillboardGui.Size = UDim2.new(0, 100, 0, 100)
        BillboardGui.AlwaysOnTop = true
        BillboardGui.StudsOffset = Vector3.new(0, 3, 0)

        local ImageLabel = Instance.new("ImageLabel")

        ImageLabel.BackgroundTransparency = 1
        ImageLabel.Size = UDim2.new(0, 64, 0, 64)
        ImageLabel.Position = UDim2.new(0.5, -32, 0, 0)
        ImageLabel.Image = "https://www.roblox.com/headshot-thumbnail/image?userId=" .. p203.UserId .. "&width=420&height=420&format=png"
        ImageLabel.Parent = BillboardGui

        local TextLabel = Instance.new("TextLabel")

        TextLabel.BackgroundTransparency = 1
        TextLabel.Size = UDim2.new(1, 0, 0, 20)
        TextLabel.Position = UDim2.new(0, 0, 1, -20)
        TextLabel.Text = p203.DisplayName .. " (@" .. p203.Name .. ")"
        TextLabel.TextColor3 = Color3.new(1, 1, 1)
        TextLabel.TextStrokeTransparency = 0
        TextLabel.Font = Enum.Font.GothamBold
        TextLabel.TextScaled = true
        TextLabel.Parent = BillboardGui
        BillboardGui.Parent = game:GetService("CoreGui")
        t2.value127[p203] = BillboardGui
    end
    function attachPlayer(p204)
        table.insert(t2.value125.conns, p204.CharacterAdded:Connect(function(character)
            task.wait(0.2)
            if t2.value125.ph and character then
                mkHighlight(character, p204)
            end
            if t2.value125.pi and character then
                mkIcon(character, p204)
            end
            local connection
            connection = character:WaitForChild("Humanoid").Died:Connect(function()
                rmHighlight(p204)
                rmIcon(p204)

                if connection then
                    connection:Disconnect()
                end
            end)
            table.insert(t2.value125.conns, connection)
        end))
    end

    discAll()

    for _, player23 in ipairs(t2.value96:GetPlayers()) do
        if player23 ~= t1.value3 then
            attachPlayer(player23)
        end
    end

    table.insert(t2.value125.conns, t2.value96.PlayerAdded:Connect(attachPlayer))
    table.insert(t2.value125.conns, t2.value96.PlayerRemoving:Connect(function(player24)
        rmHighlight(player24)
        rmIcon(player24)
    end))
    VisualTab:CreateToggle({
		Name = "Player ESP    <font face=\"GothamBlack\" color=\"rgb(0,255,29)\">HIGHLIGHT</font>",
		CurrentValue = false,
		Callback = function(p205)
        t2.value125.ph = p205

        for _, player25 in ipairs(t2.value96:GetPlayers()) do
            if player25 ~= t1.value3 then
                local Character = player25.Character

                if p205 and Character then
                    mkHighlight(Character, player25)
                else
                    rmHighlight(player25)
                end
            end
        end
    end
	})
    VisualTab:CreateToggle({
		Name = "Player ESP    <font face=\"GothamBlack\" color=\"rgb(255,255,0)\">ICON</font>",
		CurrentValue = false,
		Callback = function(p206)
        t2.value125.pi = p206

        for _, player26 in ipairs(t2.value96:GetPlayers()) do
            if player26 ~= t1.value3 then
                local Character = player26.Character

                if p206 and Character then
                    mkIcon(Character, player26)
                else
                    rmIcon(player26)
                end
            end
        end
    end
	})
    VisualTab:CreateLabel("Object ESP", "box")

    function isToysFolder(p207)
        return p207:IsA("Folder") and p207.Name:match("SpawnedInToys$")
    end
    function clearMissingOH()
        for k, v in pairs(t2.value128) do
            local v1030 = k

            if not v1030 or not v1030.Parent then
                if v then
                    v:Destroy()
                end

                t2.value128[v1030] = nil
            end
        end
    end
    function addObjHighlight(p208)
        if t2.value128[p208] then
            return
        end

        local Highlight = Instance.new("Highlight")

        Highlight.FillColor = _G.ObjectHighlightColor
        Highlight.OutlineColor = Color3.new(0, 0, 0)
        Highlight.FillTransparency = 0
        Highlight.OutlineTransparency = 0
        Highlight.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
        Highlight.Adornee = p208
        Highlight.Parent = game:GetService("CoreGui")
        t2.value128[p208] = Highlight
    end
    function refreshObjects()
        clearMissingOH()

        for _, child in ipairs(workspace:GetChildren()) do
            if isToysFolder(child) then
                for _, descendant in ipairs(child:GetDescendants()) do
                    if descendant:IsA("Model") and descendant.PrimaryPart or descendant:FindFirstChildWhichIsA("BasePart") then
                        if t2.value125.oh then
                            addObjHighlight(descendant)
                        elseif t2.value128[descendant] then
                            t2.value128[descendant]:Destroy()
                            t2.value128[descendant] = nil
                        end
                    end
                end
            end
        end
    end

    t2.value129 = nil
    t2.value130 = nil

    function toggleObjects(p209)
        t2.value125.oh = p209

        if not p209 then
            if t2.value129 then
                t2.value129:Disconnect()
            end

            if t2.value130 then
                t2.value130:Disconnect()
            end

            for k, v in pairs(t2.value128) do
                if v then
                    v:Destroy()
                end

                t2.value128[k] = nil
            end

            return
        end

        refreshObjects()
        workspace.DescendantAdded:Connect(function(descendant)
            if not t2.value125.oh then
                return
            end

            if descendant:IsA("Model") then
                local descendantParent = descendant.Parent

                while descendantParent and (descendantParent ~= workspace and not isToysFolder(descendantParent)) do
                    descendantParent = descendantParent.Parent
                end

                if descendantParent and isToysFolder(descendantParent) then
                    addObjHighlight(descendant)
                end
            end
        end)
        workspace.DescendantRemoving:Connect(function(descendant)
            if t2.value128[descendant] then
                t2.value128[descendant]:Destroy()
                t2.value128[descendant] = nil
            end
        end)
    end

    VisualTab:CreateToggle({
		Name = "Player Object ESP   <font face=\"GothamBlack\" color=\"rgb(120,0,120)\">HIGHLIGHT</font>",
		CurrentValue = false,
		Callback = function(p210)
        toggleObjects(p210)
    end
	})
    t2.value131 = {}
    t2.value132 = nil
    t2.value133 = nil

    function isOwnToysFolder(p211)
        local v1042 = p211:IsA("Folder")

        if v1042 then
            v1042 = p211.Name:match("SpawnedInToys$")

            if v1042 then
                v1042 = p211.Parent == workspace

                if not v1042 then
                    v1042 = p211.Parent == workspace:FindFirstChild(t1.value3.Name)

                    if not v1042 then
                        v1042 = tostring(p211):lower():find(t1.value3.Name:lower(), 1, true)
                    end
                end
            end
        end

        return v1042
    end
    function clearOwn()
        for k, v in pairs(t2.value131) do
            if v then
                v:Destroy()
            end

            t2.value131[k] = nil
        end

        if t2.value132 then
            t2.value132:Disconnect()
        end

        if t2.value133 then
            t2.value133:Disconnect()
        end
    end
    function addOwn(p212)
        if t2.value131[p212] then
            return
        end

        local Highlight = Instance.new("Highlight")

        Highlight.FillColor = _G.ObjectHighlightColor
        Highlight.OutlineColor = Color3.new(0, 0, 0)
        Highlight.FillTransparency = 0
        Highlight.OutlineTransparency = 0
        Highlight.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
        Highlight.Adornee = p212
        Highlight.Parent = game:GetService("CoreGui")
        t2.value131[p212] = Highlight
    end
    function refreshOwn()

        for v1049, v1050 in pairs(t2.value131) do

            if not v1049 or not v1049.Parent then
                if v1050 then
                    v1050:Destroy()
                end

                t2.value131[v1049] = nil
            end
        end
        for _, child in ipairs(workspace:GetChildren()) do
            if isOwnToysFolder(child) then
                for _, descendant in ipairs(child:GetDescendants()) do
                    if descendant:IsA("Model") and descendant.PrimaryPart or descendant:FindFirstChildWhichIsA("BasePart") then
                        addOwn(descendant)
                    end
                end
            end
        end
    end

    VisualTab:CreateLabel("Settings", "Settings")

    local _VisualTab = VisualTab
    local __G = _G
    local CreateColorPicker = _VisualTab.CreateColorPicker
    local PlayerHighlightColor = __G.PlayerHighlightColor

    CreateColorPicker(_VisualTab, {
		Name = "Player Highlight Color",
		Color = PlayerHighlightColor,
		Callback = function(p213)
        _G.PlayerHighlightColor = p213

        for _, v in pairs(t2.value126) do
            if v then
                v.FillColor = p213
            end
        end
    end
	})

    local _VisualTab2 = VisualTab
    local __G2 = _G
    local CreateColorPicker2 = _VisualTab2.CreateColorPicker
    local ObjectHighlightColor = __G2.ObjectHighlightColor

    CreateColorPicker2(_VisualTab2, {
		Name = "Object Highlight Color",
		Color = ObjectHighlightColor,
		Callback = function(p214)
        _G.ObjectHighlightColor = p214
        for v1061, v1062 in pairs(t2.value128) do

            if v1062 then
                v1062.FillColor = p214
            end
        end
        for _, v in pairs(t2.value131) do
            if v then
                v.FillColor = p214
            end
        end
    end
	})
    KeybindTab:CreateSection("Keybinds")
    KeybindTab:CreateButton({
		Name = "MobileKeyboard  <font face=\"GothamBlack\" color=\"rgb(240,25,56)\">MOBILE</font>",
		Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/Delta-Scripts/main/MobileKeyboard.txt"))()
    end
	})
    t2.value134 = t1.value3:GetMouse()

    function teleportToMouse()
        local Character = t1.value3.Character
        local v1066 = Character and Character:FindFirstChild("HumanoidRootPart")

        if not v1066 or (not t2.value134.Target or not t2.value134.Target:IsA("BasePart")) then
            return
        end

        local HitPosition = t2.value134.Hit.Position

        v1066.CFrame = CFrame.new(HitPosition + Vector3.new(0, 5, 0))
    end

    KeybindTab:CreateKeybind({
		Name = "Teleport to Mouse\t<font face=\"GothamBlack\" color=\"rgb(180,0,255)\">TELEPORT</font>",
		CurrentKeybind = "Z",
		HoldToInteract = false,
		Callback = teleportToMouse
	})
    KeybindTab:CreateKeybind({
		Name = "Spawn Pallet  <font face=\"GothamBlack\" color=\"rgb(240,184,111)\">PALLET</font>",
		CurrentKeybind = "P",
		HoldToInteract = false,
		Callback = function()
        local HumanoidRootPart = (t1.value3.Character or t1.value3.CharacterAdded:Wait()):WaitForChild("HumanoidRootPart")
        local LookVector = workspace.CurrentCamera.CFrame.LookVector
        local v1070 = HumanoidRootPart.Position + LookVector * 3
        local cFrame = CFrame.new(v1070, v1070 + LookVector)

        SpawnToyRF:InvokeServer("PalletLightBrown", cFrame, Vector3.new(0, 5, 0))
    end
	})
    KeybindTab:CreateSection("Limb OP ")

    function deleteLimbs(p215)
        if not p215 then
            return
        end

        for _, v in ipairs({
			"Right Arm",
			"Left Arm",
			"Right Leg",
			"Left Leg"
		}) do
            local v10 = p215:FindFirstChild(v)

            if v10 then
                for _, child in ipairs(v10:GetChildren()) do
                    if child:IsA("Motor6D") or (child:IsA("Weld") or child:IsA("WeldConstraint")) then
                        child:Destroy()
                    end
                end

                v10.CFrame = CFrame.new(0, -10000, 0)
            end
        end
    end

    KeybindTab:CreateKeybind({
		Name = "Delete Limbs  <font face=\"GothamBlack\" color=\"rgb(7,255,0)\">GRAB</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentKeybind = "U",
		HoldToInteract = false,
		Callback = function()
        local GrabParts = workspace:FindFirstChild("GrabParts")
        local v1079 = GrabParts and GrabParts:FindFirstChild("GrabPart")

        if not v1079 then
            return
        end

        local WeldConstraint = v1079:FindFirstChild("WeldConstraint")

        if not WeldConstraint or not WeldConstraint.Part1 then
            return
        end

        local Model = WeldConstraint.Part1:FindFirstAncestorOfClass("Model")

        if not Model then
            return
        end

        local CFrame8 = v1079.CFrame

        deleteLimbs(Model)

        if SpawnToyRF then
            SpawnToyRF:InvokeServer("PalletLightBrown", CFrame8, Vector3.new(0, 0, 0))
        end
    end
	})
    KeybindTab:CreateParagraph({
		Title = "How to use it :",
		Content = "Grab a part of a player <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">TORSO</font> or <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">HEAD</font> and <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">RAGDOLL</font> him, then press the Keybind to remove all limbs. A pallet will spawn exactly where the grabbed part is."
	})
    t2.value135 = false
    t2.value136 = nil
    KeybindTab:CreateKeybind({
		Name = "Aimbot player  <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">CLOSEST</font>",
		CurrentKeybind = "T",
		HoldToInteract = false,
		Callback = function()
        t2.value135 = not t2.value135

        if t2.value135 then
            t2.value136 = game:GetService("RunService").RenderStepped:Connect(function()
                local CurrentCamera = workspace.CurrentCamera
                local v2115 = t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart")
                if not v2115 then
                    return
                end
                local v2116
                local n12 = 1e999
                for v2120, v2121 in pairs(game.Players:GetPlayers()) do

                    if v2121 ~= t1.value3 and v2121.Character then
                        local HumanoidRootPart = v2121.Character:FindFirstChild("HumanoidRootPart")

                        if HumanoidRootPart then
                            local Magnitude = (v2115.Position - HumanoidRootPart.Position).Magnitude

                            if Magnitude < n12 then
                                n12 = Magnitude
                                v2116 = v2121
                            end
                        end
                    end
                end
                if v2116 and v2116.Character then
                    local Head = v2116.Character:FindFirstChild("Head")

                    if Head then
                        CurrentCamera.CFrame = CFrame.new(CurrentCamera.CFrame.Position, Head.Position)
                    end
                end
            end)

            return
        end

        if t2.value136 then
            t2.value136:Disconnect()
        end
    end
	})
    t2.value137 = t2.value9:WaitForChild("MenuToys"):WaitForChild("SpawnToyRemoteFunction")
    t2.value138 = t2.value9:WaitForChild("CharacterEvents"):WaitForChild("RagdollRemote")
    KeybindTab:CreateSection("Lobotomy OP")
    Button = KeybindTab:CreateButton({
		Name = "Lobotomy    <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">OP</font>   <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		Callback = function()
        t2.value137:InvokeServer("CreatureBlobman", humanoidRootPart.CFrame * CFrame.new(0, 0, -5), Vector3.new(0, -16.157, 0))
        task.spawn(function()
            while true do
                local v2125 = workspace:FindFirstChild(t1.value3.Name .. "SpawnedInToys")

                if v2125 and v2125:FindFirstChild("CreatureBlobman") then
                    local VehicleSeat = v2125.CreatureBlobman:FindFirstChild("VehicleSeat")

                    if VehicleSeat and VehicleSeat.Occupant ~= Humanoid then
                        VehicleSeat:Sit(Humanoid)
                    end
                end

                task.wait(0.1)
            end
        end)
        task.spawn(function()
            while true do
                pcall(function()
                    t1.value3.IsHeld.Value = true
                end)
                task.wait()
            end
        end)
        task.spawn(function()
            while true do
                for _ = 1, 12 do
                    t2.value138:FireServer(humanoidRootPart, 0)
                end

                task.wait()
            end
        end)
    end
	})
    KeybindTab:CreateParagraph({
		Title = "How it work : ",
		Content = "Basically, it breaks grabbing, destroys the house barrier, and prevents us from spawning items."
	})
    InfoTab:CreateSection("Premium Info")
    InfoTab:CreateParagraph({
		Title = "<font face=\"GothamBlack\" color=\"rgb(255,0,0)\">How to get premium ?</font>",
		Content = "Join the <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">discord</font>, the price for premium is <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">200 ROBUX</font> To have it permanently."
	})
    Button = InfoTab:CreateButton({
		Name = "Copy Discord link",
		Callback = function()
        if setclipboard then
            setclipboard("https://discord.gg/PMk4T9F8ZC")
        end
    end
	})
    t2.value139 = nil
    t2.value140 = nil
    t2.value141 = nil
    t2.value142 = t2.value9:WaitForChild("MenuToys"):WaitForChild("SpawnToyRemoteFunction")
    t2.value143 = t2.value9:WaitForChild("BombEvents"):WaitForChild("BombExplode")
    _G.ToyToLoad = _G.ToyToLoad or "BombMissile"
    _G.MaxMissiles = _G.MaxMissiles or 5
    _G.ExplosionMode = _G.ExplosionMode or "Instant"
    _G.ExplosionDelay = _G.ExplosionDelay or 0.05
    _G.PredictionTime = 0.4
    t2.value144 = {}
    t2.value145 = {}
    t2.value146 = false
    t2.value147 = nil
    t2.value148 = false
    t2.value149 = false
    t2.value150 = 0
    t2.value151 = 0.3

    function cleanupBomb(p216, p217)
        for i = #p217, 1, -1 do
            local v1086 = i

            if p216 == p217[v1086] then
                table.remove(p217, v1086)
            end
        end
    end
    function isValidBomb(p218)
        return p218 and (p218.Parent and (p218.PrimaryPart and p218:FindFirstChild("PartHitDetector")))
    end
    function getPredictedCFrame(p219)
        local p219CFrame = p219.CFrame

        if _G.PredictionTime <= 0 then
            return p219CFrame
        end

        local p219Velocity = p219.Velocity
        local Magnitude = p219Velocity.Magnitude

        if Magnitude < 1 then
            return p219CFrame
        end

        local Unit = p219Velocity.Unit
        local v1093 = p219.Position + Unit * (Magnitude * _G.PredictionTime)

        return CFrame.new(v1093, v1093 + p219CFrame.LookVector)
    end
    function teleportBombToTarget(p220, p221)
        if not p220 or (not p220.PrimaryPart or not p221) then
            return false
        end

        return (pcall(function()
            local v2128 = getPredictedCFrame(p221)

            p220:SetPrimaryPartCFrame(v2128)
        end))
    end
    function setupBomb(p222)
        if not p222 or not p222.Parent then
            return false
        end

        if not t2.value146 then
            return false
        end

        if not p222:WaitForChild("ThisToysNumber", 2) then
            cleanupBomb(p222, t2.value145)

            return false
        end

        local n13 = 0

        while not p222.PrimaryPart and n13 < 4 do
            task.wait(0.05)
            n13 += 0.05
        end

        if not p222.PrimaryPart or not p222.Parent then
            cleanupBomb(p222, t2.value145)

            return false
        end

        local Body = p222:WaitForChild("Body", 1)

        if not Body then
            cleanupBomb(p222, t2.value145)

            return false
        end

        if not pcall(function()
            SetNetworkOwner:FireServer(Body, Body.CFrame)

            local PartOwner = Body:WaitForChild("PartOwner", 0.5)

            if not PartOwner or PartOwner.Value ~= t1.value3.Name then
                return false
            end

            if t2.value10 and t2.value10:FindFirstChild("Head") then
                local v2130 = t2.value10.Head.Position + Vector3.new(0, 1000, 0)
                local v2131 = #t2.value144
                local v2132 = v2130 + Vector3.new(v2131 % 8 * 6, -math.floor(v2131 / 8) * 6, 0)

                for _, child in ipairs(p222:GetChildren()) do
                    if child:IsA("BasePart") then
                        child.CanCollide = false
                    end
                end

                p222:SetPrimaryPartCFrame(CFrame.new(v2132))
                task.wait(0.2)

                for _, child in ipairs(p222:GetChildren()) do
                    if child:IsA("BasePart") then
                        child.Anchored = true
                    end
                end
            end
        end) or not p222.Parent then
            cleanupBomb(p222, t2.value145)

            return false
        end

        table.insert(t2.value144, p222)
        cleanupBomb(p222, t2.value145)
        p222.AncestryChanged:Connect(function()
            if not p222.Parent then
                cleanupBomb(p222, t2.value144)
            end
        end)

        return true
    end
    function setupExplosionCharacter()
        t2.value10 = t1.value3.Character or t1.value3.CharacterAdded:Wait()
        t2.value139 = t1.value3.Name .. "SpawnedInToys"

        local t2value139 = workspace:FindFirstChild(t2.value139)

        if not t2value139 then
            t2value139 = workspace:WaitForChild(t2.value139)
        end

        t2.value140 = t2value139
        t2.value144 = {}
        t2.value145 = {}

        if t2.value141 then
            t2.value141:Disconnect()
        end

        t2.value140.ChildAdded:Connect(function(child)
            if not t2.value146 then
                return
            end

            if child.Name == _G.ToyToLoad then
                table.insert(t2.value145, child)
                task.spawn(function()
                    task.wait(0.15)
                    setupBomb(child)
                end)
            end
        end)

        for _, child in ipairs(t2.value140:GetChildren()) do
            local v1102 = child

            if t2.value146 and v1102.Name == _G.ToyToLoad then
                table.insert(t2.value145, v1102)
                task.spawn(function()
                    setupBomb(v1102)
                end)
            end
        end
    end

    setupExplosionCharacter()
    t1.value3.CharacterAdded:Connect(function()
        task.wait(0.5)
        setupExplosionCharacter()
    end)

    function spawnBombs()
        if t2.value148 then
            return
        end

        if not t2.value10 or not t2.value10:FindFirstChild("Head") then
            return
        end

        if tick() - t2.value150 < t2.value151 then
            return
        end

        local __G3 = _G
        local v1104 = #t2.value144 + #t2.value145
        local v1105 = __G3.MaxMissiles - v1104

        if v1105 <= 0 then
            return
        end

        local HeadPosition = t2.value10.Head.Position
        local cFrame = CFrame.new(HeadPosition)
        local vector3 = Vector3.new(0, 90, 0)
        local v1109 = false
        local n14 = 0

        while true do
            n14 += 1

            if (not v1109 or not (v1105 <= n14)) and (v1109 or not (n14 <= v1105)) then
                break
            end

            if t1.value3:FindFirstChild("CanSpawnToy") and t1.value3.CanSpawnToy.Value then
                task.spawn(function()
                    pcall(function()
                        t2.value142:InvokeServer(_G.ToyToLoad, cFrame, vector3)
                    end)
                end)
                task.wait(0.05)
            end
        end

        task.wait(0.2)
        t2.value148 = false
    end
    function explodeOnTarget(p223)
        if t2.value149 then
            return false
        end
        if not p223 or not p223.Character then
            return false
        end
        if not p223.Character:FindFirstChild("HumanoidRootPart") then
            return false
        end
        local t41 = {}
        for v1115, v1116 in ipairs(t2.value144) do

            if isValidBomb(v1116) then
                table.insert(t41, v1116)
            end
        end
        if #t41 < _G.MaxMissiles then
            return false
        end
        local t42 = {}
        for i = 1, _G.MaxMissiles do
            t42[i] = t41[i]
        end
        local n15 = 0
        t2.value144 = {}
        for _, v in ipairs(t42) do
            if not p223.Character then
                break
            end

            local HumanoidRootPart = p223.Character:FindFirstChild("HumanoidRootPart")

            if not HumanoidRootPart or not HumanoidRootPart.Parent then
                break
            end

            if isValidBomb(v) then
                teleportBombToTarget(v, HumanoidRootPart)
                local PartHitDetector = v:FindFirstChild("PartHitDetector")
                local t43 = {
					Radius = 17.5,
					TimeLength = 2,
					Hitbox = PartHitDetector,
					ExplodesByFire = false,
					MaxForcePerStudSquared = 225,
					Model = v,
					ImpactSpeed = 100,
					ExplodesByPointy = false,
					DestroysModel = false,
					PositionPart = HumanoidRootPart
				}
                local HumanoidRootPartPosition = HumanoidRootPart.Position
                local t44 = {
					t43,
					HumanoidRootPartPosition
				}
                if pcall(function()
                    t2.value143:FireServer(unpack(t44))
                end) then
                    n15 += 1
                end
            end

            if _G.ExplosionMode == "Sequential" then
                task.wait(_G.ExplosionDelay)
            else
                task.wait(0.01)
            end
        end
        task.wait(0.1)
        t2.value149 = false

        return n15 > 0
    end
    function autoSpamLoop()
        while t2.value146 do
            local value147 = t2.value147

            if value147 then
                value147 = t2.value96:FindFirstChild(t2.value147)
            end

            if value147 and value147.Character then
                if _G.MaxMissiles == 1 then
                    if not t2.value148 and not t2.value149 then
                        spawnBombs()
                        task.wait(0.3)

                        if #t2.value144 >= 1 then
                            explodeOnTarget(value147)
                        end
                    end
                else
                    if #t2.value144 < _G.MaxMissiles and not t2.value148 then
                        spawnBombs()
                    end

                    if #t2.value144 >= _G.MaxMissiles and not t2.value149 and explodeOnTarget(value147) then
                        task.wait(0.4)
                    end
                end
            end

            task.wait(0.1)
        end
    end

    task.spawn(function()
        while true do
            task.wait(3)

            for i = #t2.value145, 1, -1 do
                local v1129 = i

                if not t2.value145[v1129] or not t2.value145[v1129].Parent then
                    table.remove(t2.value145, v1129)
                end
            end

            for i = #t2.value144, 1, -1 do
                local v1131 = i

                if not isValidBomb(t2.value144[v1131]) then
                    table.remove(t2.value144, v1131)
                end
            end
        end
    end)
    Label = ExplosionTab:CreateLabel("Missile", "Rocket")

    function ExplosionOptionText(p224)
        return string.format("👤 @%s (%s)", p224.Name, p224.DisplayName or "")
    end

    ExplosionDropdown = ExplosionTab:CreateDropdown({
		Name = "Select Target   <font face=\"GothamBlack\" color=\"rgb(255,128,0)\">TRACK</font>",
		Options = {},
		CurrentOption = {},
		MultipleOptions = false,
		Flag = "ExplosionTargetDropdown",
		Callback = function(p225)
        p225[1]:match("@([%w_]+)")
    end
	})

    function refreshExplosionDropdown()
        local t45 = {}

        for _, player27 in ipairs(t2.value96:GetPlayers()) do
            if player27 ~= t1.value3 then
                table.insert(t45, ExplosionOptionText(player27))
            end
        end

        ExplosionDropdown:Refresh(t45)
    end

    t2.value96.PlayerAdded:Connect(function()
        task.wait(0.5)
        refreshExplosionDropdown()
    end)
    t2.value96.PlayerRemoving:Connect(function()
        task.wait(0.5)
        refreshExplosionDropdown()
    end)
    refreshExplosionDropdown()
    ExplosionTab:CreateSection("Settings")

    local _ExplosionTab = ExplosionTab
    local MaxMissiles = _G.MaxMissiles

    _ExplosionTab:CreateSlider({
		Name = "Missiles per Wave\t<font face=\"GothamBlack\" color=\"rgb(128,0,255)\">SALVO</font>",
		Range = {
			1,
			10
		},
		Increment = 1,
		CurrentValue = MaxMissiles,
		Suffix = " missiles",
		Flag = "ExplosionMissileSlider",
		Callback = function(p226)
        _G.MaxMissiles = p226
    end
	})

    local _ExplosionTab2 = ExplosionTab
    local CreateDropdown = _ExplosionTab2.CreateDropdown
    local t46 = { _G.ExplosionMode }

    CreateDropdown(_ExplosionTab2, {
		Name = "Explosion Mode\t<font face=\"GothamBlack\" color=\"rgb(255,64,64)\">BLAST</font>",
		Options = {
			"Instant",
			"Sequential"
		},
		CurrentOption = t46,
		MultipleOptions = false,
		Flag = "ExplosionModeDropdown",
		Callback = function(p227)
        _G.ExplosionMode = p227[1]
    end
	})
end
local t68
do
    local _ExplosionTab = ExplosionTab
    local ExplosionDelay = _G.ExplosionDelay

    _ExplosionTab:CreateSlider({
		Name = "Delay (Sequential)\t<font face=\"GothamBlack\" color=\"rgb(255,200,0)\">INTERVAL</font>",
		Range = {
			0,
			0.3
		},
		Increment = 0.01,
		CurrentValue = ExplosionDelay,
		Suffix = " s",
		Flag = "ExplosionDelaySlider",
		Callback = function(p228)
        _G.ExplosionDelay = p228
    end
	})
    ExplosionTab:CreateToggle({
		Name = "Auto Spam   <font face=\"GothamBlack\" color=\"rgb(0,255,0)\">RAPID</font>",
		CurrentValue = false,
		Flag = "ExplosionAutoSpamToggle",
		Callback = function(p229)
        t2.value146 = p229

        if t2.value146 then
            task.spawn(autoSpamLoop)
        end
    end
	})
    ExplosionTab:CreateParagraph({
		Title = "<b>Missile Explosion</b>",
		Content = "When auto-spam is enabled, it is recommended to avoid sudden or fast movements."
	})
    MiscTab:CreateLabel("Silent Aim", "Target")
    extendGrabLineRemoteEvent = GrabEvents:WaitForChild("ExtendGrabLine")
    GrabPartsModel = game:GetService("ReplicatedFirst").GrabParts
    maxDistance = 30
    pcDistance = 19
    _G.ActualFakeGrabParts = nil
    currentGrabbedPart = nil
    t2.value152 = nil
    t2.value153 = nil
    t2.value154 = nil

    function CheckNetworkOwnerShipOnPart(p230, p231)
        if typeof(p230) == "Instance" and (p230:FindFirstChild("PartOwner") and p230.PartOwner.Value == t1.value3.Name) then
            return not p231 or p230.PartOwner
        end

        return false
    end
    function isPlayerCharacter(p232)
        if not p232 or not p232.Parent then
            return false
        end

        return p232.Parent:FindFirstChildOfClass("Humanoid") ~= nil
    end
    function isPlayerInPlot(p233)
        if p233 and p233:FindFirstChild("InPlot") then
            return p233.InPlot.Value == true
        end

        return false
    end
    function checkObjectInRaycast()
        local CurrentCamera = Workspace.CurrentCamera
        local CFramePosition = CurrentCamera.CFrame.Position
        local v1147 = CurrentCamera.CFrame.LookVector * 30
        local raycastParams = RaycastParams.new()

        raycastParams.FilterType = Enum.RaycastFilterType.Blacklist
        raycastParams.FilterDescendantsInstances = { t1.value3.Character }

        local raycastResult = Workspace:Raycast(CFramePosition, v1147, raycastParams)

        if raycastResult then
            local Instance2 = raycastResult.Instance

            if Instance2:IsA("BasePart") and not isPlayerCharacter(Instance2) then
                return true, (CFramePosition - raycastResult.Position).Magnitude
            end
        end

        return false, 1e999
    end
    function CleanupGrab()
        if _G.ActualFakeGrabParts then
            local _currentGrabbedPart = currentGrabbedPart

            DestroyGrabLine:FireServer(_currentGrabbedPart)
            _G.ActualFakeGrabParts:Destroy()
            _G.ActualFakeGrabParts = nil
            currentGrabbedPart = nil
        end

        if t2.value152 then
            t2.value152:Disconnect()
        end

        if t2.value153 then
            t2.value153:Disconnect()
        end

        Workspace.CurrentCamera.CameraType = Enum.CameraType.Custom
        t2.value7.MouseBehavior = Enum.MouseBehavior.Default
        pcall(function()
            t1.value3.PlayerScripts.CharacterAndBeamMove.GrabNotifyEvent:Fire(false)
        end)
    end
    function t2.value155(p234)
        local Character = t1.value3.Character

        if _G.ActualFakeGrabParts then
            if p234 == currentGrabbedPart then
                return
            end

            CleanupGrab()
        end

        local v1154 = Character

        if Character then
            v1154 = p234

            if v1154 then
                v1154 = p234:IsA("BasePart") and (Character:FindFirstChildOfClass("Humanoid") and Character:FindFirstChildOfClass("Humanoid").Health > 0)
            end
        end

        if v1154 then
            if _G.RealGrabParts then
                return
            end

            local Head = p234.Parent:FindFirstChild("Head")
            local Humanoid24 = p234.Parent:FindFirstChildOfClass("Humanoid")
            local v1157 = Head or p234

            if Humanoid24 and Humanoid24.Health < 1 then
                return
            end

            SetNetworkOwner:FireServer(v1157, Workspace.CurrentCamera.CFrame)
            CreateGrabLine:FireServer(v1157)
            pcDistance = (p234.Position - Workspace.CurrentCamera.CFrame.Position).Magnitude

            local clone = GrabPartsModel:Clone()

            clone:SetAttribute("Fake", true)
            clone.Name = "GrabParts"
            clone.GrabPart.Color = t1.value3:FindFirstChild("BeamColor") and t1.value3.BeamColor.BallColorHolder.Value or Color3.new(1, 1, 1)
            clone.BeamPart.GrabBeam.Color = t1.value3:FindFirstChild("BeamColor") and t1.value3.BeamColor.ColorSequenceHolder.Color or ColorSequence.new(Color3.new(1, 1, 1))
            clone.DragPart.Anchored = true
            clone.GrabPart.WeldConstraint.Part1 = p234
            clone.GrabPart.Position = p234.Position
            clone.GrabPart.Anchored = false
            clone.BeamPart.Anchored = true
            clone.BeamPart.GrabBeam.Attachment0 = Character:FindFirstChild("CamPart") and Character.CamPart:FindFirstChild("Attachment") or nil
            clone.Parent = Workspace
            _G.ActualFakeGrabParts = clone
            currentGrabbedPart = p234
            task.spawn(function()
                task.wait(0.2)

                if CheckNetworkOwnerShipOnPart(v1157, true) == false then
                    CleanupGrab()
                end
            end)
            t2.value7.InputChanged:Connect(function(input, gameProcessed)
                if not gameProcessed and input.UserInputType == Enum.UserInputType.MouseWheel then
                    if input.Position.Z < 0 then
                        pcDistance = math.clamp(pcDistance - 1, 3, 30)
                    elseif input.Position.Z > 0 then
                        pcDistance = math.clamp(pcDistance + 1, 3, 30)
                    end

                    extendGrabLineRemoteEvent:FireServer(pcDistance)
                end
            end)
            t2.value7.InputBegan:Connect(function(input, gameProcessed)
                if not (not gameProcessed and input.KeyCode == Enum.KeyCode.R) then
                end
            end)
            task.spawn(function()
                pcall(function()
                    t1.value3.PlayerScripts.CharacterAndBeamMove.GrabNotifyEvent:Fire(true)
                end)

                while true do
                    local cloneParent = clone.Parent

                    if cloneParent then
                        cloneParent = p234:IsDescendantOf(Workspace)
                    end

                    if not cloneParent or _G.SilentAimV2 and not isPlayerCharacter(p234) then
                        break
                    end

                    clone.DragPart.Position = Workspace.CurrentCamera.CFrame.Position + Workspace.CurrentCamera.CFrame.LookVector * pcDistance

                    if Workspace:FindFirstChild("RotateOrientPart") then
                        clone.DragPart.DragAttach.WorldOrientation = Workspace.RotateOrientPart.PartOrient.WorldOrientation
                    end

                    clone.BeamPart.CFrame = CFrame.lookAt(clone.GrabPart.Position, clone.DragPart.Position, Vector3.new(0, 0, 1))
                    clone.BeamPart.GrabBeam.CurveSize1 = (clone.GrabPart.Position - clone.DragPart.Position).Magnitude * 1.5
                    clone.GrabPart.BeamSound.PlaybackSpeed = (clone.GrabPart.Position - clone.DragPart.Position).Magnitude * 1.5 * 1.5 / 2 + 2.5
                    task.wait()
                end

                CleanupGrab()
            end)
        end
    end
    function getNearestPlayer()
        local v1159
        local v1160 = maxDistance + 1
        for _, player28 in pairs(t2.value96:GetPlayers()) do
            local v1163 = player28 ~= t1.value3

            if v1163 then
                v1163 = player28.Character

                if v1163 then
                    v1163 = player28.Character:FindFirstChild("HumanoidRootPart") and (t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart"))
                end
            end

            if v1163 and not isPlayerInPlot(player28) then
                local Magnitude = (t1.value3.Character.HumanoidRootPart.Position - player28.Character.HumanoidRootPart.Position).Magnitude

                if Magnitude < v1160 then
                    v1159 = player28
                    v1160 = Magnitude
                end
            end
        end

        return v1159
    end
    function handleMouseButton1()
        if _G.ActualFakeGrabParts then
            CleanupGrab()

            return
        end

        local v1165, v1166 = checkObjectInRaycast()

        if _G.SilentAimV2 then
            if v1165 then
                v1165 = v1166 <= 30
            end

            if v1165 then
                return
            end

            local v1167 = getNearestPlayer()

            if v1167 and (v1167.Character and v1167.Character:FindFirstChild("HumanoidRootPart")) and (t1.value3.Character.HumanoidRootPart.Position - v1167.Character.HumanoidRootPart.Position).Magnitude <= maxDistance then
                local Head = v1167.Character:FindFirstChild("Head")

                if Head then
                    t2.value155(Head)
                end
            end
        end
    end

    MiscTab:CreateToggle({
		Name = "Silent Aim    <font face=\"GothamBlack\" color=\"rgb(47,245,89)\">[PC ONLY]</font>    <font face=\"GothamBlack\" color=\"rgb(123,67,89)\">BETA</font>",
		CurrentValue = false,
		Flag = "SilentAimToggle",
		Callback = function(p235)
        _G.SilentAimV2 = p235

        if p235 then
            if not t2.value154 then
                t2.value154 = t2.value7.InputBegan:Connect(function(input)
                    if input.UserInputType == Enum.UserInputType.MouseButton1 then
                        handleMouseButton1()
                    end
                end)

                return
            end
        else
            if t2.value154 then
                t2.value154:Disconnect()
            end

            CleanupGrab()
        end
    end
	})
    MiscTab:CreateParagraph({
		Title = "On which executor it work ?",
		Content = "It work on  <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">EVERY PC executor</font> like <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">XENO</font>, <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">HYDROGEN</font>, <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">POTASSIUM</font> etc.."
	})
    Hitbox = {
		"Head",
		"Torso",
		"Left Leg",
		"Right Leg"
	}
    t2.value156 = false
    Distance = 30
    hookSupported = hookmetamethod and getrawmetatable
    t2.value157 = nil

    if hookSupported then
    end

    function SilentAimFunction(p236, p237)
        if not t2.value156 or (not hookSupported or not t2.value157) then
            return t2.value157(p236, p237)
        end
        local v1172
        local n16 = 1e999
        for v1176, v1177 in pairs(t2.value96:GetPlayers()) do

            if v1177 ~= t1.value3 and (v1177.Character and v1177.Character:FindFirstChild("HumanoidRootPart")) then
                local Humanoid25 = v1177.Character:FindFirstChildOfClass("Humanoid")

                if Humanoid25 and Humanoid25.Health > 0 then
                    local HumanoidRootPart = v1177.Character.HumanoidRootPart
                    local _, v1181 = camera:WorldToScreenPoint(HumanoidRootPart.Position)

                    if v1181 then
                        local Magnitude = (t1.value3.Character.HumanoidRootPart.Position - HumanoidRootPart.Position).Magnitude

                        if Magnitude < n16 then
                            v1172 = v1177
                            n16 = Magnitude
                        end
                    end
                end
            end
        end
        if v1172 and (n16 <= Distance and v1172.Character) then
            local v1183 = Hitbox[math.random(1, #Hitbox)]
            local v1184 = v1172.Character:FindFirstChild(v1183)

            if v1184 then
                local CFramePosition = camera.CFrame.Position
                local _ = (v1184.Position - CFramePosition).Unit * p237
                local Position = v1184.Position
                local vector3 = Vector3.new(0, 1, 0)
                local Plastic = Enum.Material.Plastic
                local t47 = {
					Instance = v1184,
					Position = Position,
					Normal = vector3,
					Material = Plastic
				}
                local CFrame9 = v1184.CFrame
                local t48 = { CFrame.new(t47.Position) }

                return t47, CFrame9:ToObjectSpace(v1(t48))
            end
        end

        return t2.value157(p236, p237)
    end

    PlayerScripts = t1.value3:WaitForChild("PlayerScripts", 5)
    raycastModule = PlayerScripts and PlayerScripts:FindFirstChild("RaycastModule")

    if hookSupported and raycastModule then
        module = require(raycastModule)

        if module and module.RaycastFromCam then
            local _ = module.RaycastFromCam

            function module.RaycastFromCam(p238, p239)
                return SilentAimFunction(p238, p239)
            end
        end
    end

    MiscTab:CreateToggle({
		Name = "Silent Aim <font face=\"GothamBlack\" color=\"rgb(47,34,89)\">HOOK</font>",
		CurrentValue = false,
		Flag = "SilentAimToggle",
		Callback = function(p240)
        t2.value156 = p240

        if p240 then
            p240 = not hookSupported
        end

        if p240 then
            t2.value6:Notify({
					Title = "disabled",
					Content = "Function disabled (hook not supported)",
					Duration = 4,
					Image = "x"
				})
        end
    end
	})
    MiscTab:CreateParagraph({
		Title = "On which executor it work ?",
		Content = "It work on <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">good executor</font> like <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">DELTA</font>, <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">POTASSIUM</font> etc.."
	})
    MiscTab:CreateLabel("Script", "notebook-text")
    MiscTab:CreateButton({
		Name = "Open  <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">Infinite Yield</font>",
		Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
    end
	})
    MiscTab:CreateLabel("Pleasant", "thumbs-up")
    t2.value158 = 0.5
    boomboxList = {}
    MiscTab:CreateSlider({
		Name = "Boombox <font face=\"GothamBlack\" color=\"rgb(244,34,56)\">Volume</font>",
		Range = {
			0,
			1
		},
		Increment = 0.1,
		Suffix = "Volume",
		CurrentValue = 0.5,
		Flag = "BoomboxVolume",
		Callback = function(p241)
        t2.value158 = p241

        for _, v in pairs(boomboxList) do
            if v.sound and v.sound.Parent then
                v.sound.Volume = p241
            end
        end
    end
	})
    task.spawn(function()
        for _, descendant in pairs(workspace:GetDescendants()) do
            if descendant.Name == "Boombox" and descendant:FindFirstChild("Speaker") then
                local Speaker = descendant.Speaker

                for _, child in pairs(Speaker:GetChildren()) do
                    local v1204 = child:IsA("Sound")

                    if v1204 then
                        v1204 = child.Name:find("01_Green") or (child.Name:find("02_Street") or child.Name:find("03_Ukrainian"))
                    end

                    if v1204 then
                        table.insert(boomboxList, {
							sound = child
						})
                        child.Volume = t2.value158
                    end
                end
            end
        end
    end)
    workspace.DescendantAdded:Connect(function(descendant)
        task.wait(0.1)

        if descendant.Name == "Boombox" and descendant:FindFirstChild("Speaker") then
            local Speaker = descendant.Speaker

            for _, child in pairs(Speaker:GetChildren()) do
                local v1209 = child:IsA("Sound")

                if v1209 then
                    v1209 = child.Name:find("01_Green") or (child.Name:find("02_Street") or child.Name:find("03_Ukrainian"))
                end

                if v1209 then
                    table.insert(boomboxList, {
						sound = child
					})
                    child.Volume = t2.value158
                end
            end
        end
    end)
    MiscTab:CreateLabel("Auto", "Repeat")

    function GetPlayerCharacter()
        if t1.value3.Character and t1.value3.Character:FindFirstChild("HumanoidRootPart") then
            return t1.value3.Character
        end
    end
    function TeleportPlayer(p242)
        local v1211 = GetPlayerCharacter()

        if v1211 then
            v1211.HumanoidRootPart.CFrame = p242
        end
    end
    function lookAt(p243, p244)
        local Unit = (p244 - p243).Unit
        local v1215 = Unit:Cross(Vector3.new(0, 1, 0))
        local v1216 = v1215:Cross(Unit)

        return CFrame.fromMatrix(p243, v1215, v1216)
    end
    function SNOWship(p245)
        if p245 then
            SetNetworkOwner:FireServer(p245, lookAt(t1.value3.Character.HumanoidRootPart.Position, p245.Position))
        end
    end
    function areAllSlotsNeon()
        for _, child in pairs(Workspace.Slots:GetChildren()) do
            if child.SlotHandle.LightBall.Material ~= Enum.Material.Neon then
                return false
            end
        end

        return true
    end

    timeleft = Workspace.Slots.Slots.Screen.SlotGui.TimeLeftFrame.TimeText
    MiscTab:CreateToggle({
		Name = "Enable Auto‑Spin\t<font face=\"GothamBlack\" color=\"rgb(0,26,255)\">CASINO</font>",
		CurrentValue = false,
		Flag = "spin_toggle",
		Callback = function(p246)
        _G.AutoSpin = p246

        if p246 then
            while _G.AutoSpin do
                if areAllSlotsNeon() then
                    local HumanoidRootPartCFrame = t1.value3.Character.HumanoidRootPart.CFrame

                    for _, child in pairs(Workspace.Slots:GetChildren()) do
                        local Handle = child.SlotHandle.Handle

                        Handle.CanCollide = false

                        for _ = 1, 10 do
                            TeleportPlayer(Handle.CFrame + Vector3.new(0, 5, 0))
                            SNOWship(Handle)
                            task.wait(0.15)
                        end

                        Handle.CanCollide = true
                        task.wait(0.4)

                        if not areAllSlotsNeon() then
                            break
                        end
                    end

                    TeleportPlayer(HumanoidRootPartCFrame)
                end

                task.wait(3)
            end
        end
    end
	})
    TimeDisplay = MiscTab:CreateLabel("Time Remaining: 0:00")
    timeleft.Changed:Connect(function(property)
        if property == "Text" then
            TimeDisplay:Set("Time Remaining: " .. timeleft.Text)
        end
    end)
    FunTab:CreateLabel("Chat", "message-circle-more")
    keywords = {
		"kick",
		"dead",
		"yo",
		"ree",
		"mad",
		"uwu",
		"yay",
		"banana",
		"spook",
		"grr",
		"ew",
		"lol",
		"hehe",
		"hmm",
		"dad",
		"hold",
		"pew",
		"drink",
		"soda",
		"yeehaw",
		"fly",
		"ahem",
		"cough",
		"one",
		"two",
		"three",
		"four",
		"five",
		"mom",
		"yum",
		"sh",
		"aaa",
		"cry",
		"sing",
		"xd",
		"?"
	}
    spamEnabled = false
    currentKeyword = keywords[1]
    t1.value2.Heartbeat:Connect(function()
        if spamEnabled and currentKeyword ~= nil then
            pcall(function()
                t2.value2:SendAsync("/clear " .. tostring(currentKeyword))
            end)
        end
    end)
    FunTab:CreateToggle({
		Name = "Enable Spam    <font face=\"GothamBlack\" color=\"rgb(0,26,255)\">LOUD</font>",
		CurrentValue = false,
		Flag = "SpamToggle",
		Callback = function(p247)
        spamEnabled = p247
    end
	})

    local _FunTab = FunTab
    local _keywords = keywords
    local v120 = keywords[1]

    _FunTab:CreateDropdown({
		Name = "Select Keyword",
		Options = _keywords,
		CurrentOption = v120,
		Flag = "KeywordDropdown",
		Callback = function(p248)
        if typeof(p248) == "table" then
            currentKeyword = p248[1]

            return
        end

        currentKeyword = p248
    end
	})
    FunTab:CreateLabel("Animation", "party-popper")
    player = t2.value96.LocalPlayer
    humanoid = nil
    animator = nil
    animationTrack = nil
    animations = {
		Crouch = "rbxassetid://6980229055",
		FireFlail = "rbxassetid://11227676639",
		Flail = "rbxassetid://7047322890",
		Typing = "rbxassetid://7004578012"
	}
    currentAnimation = "Crouch"
    animEnabled = false

    function setupCharacter(p249)
        humanoid = p249:WaitForChild("Humanoid")
        animator = humanoid:FindFirstChildOfClass("Animator")

        if not animator then
            animator = Instance.new("Animator")
            animator.Parent = humanoid
        end
    end

    if player.Character then
        setupCharacter(player.Character)
    end

    player.CharacterAdded:Connect(setupCharacter)
    t1.value2.Heartbeat:Connect(function()
        if animEnabled and (humanoid and animator) then
            if not animationTrack or not animationTrack.IsPlaying then
                local Animation = Instance.new("Animation")

                Animation.AnimationId = animations[currentAnimation]
                animationTrack = animator:LoadAnimation(Animation)
                animationTrack:Play()

                return
            end
        elseif animationTrack then
            animationTrack:Stop()
            animationTrack = nil
        end
    end)
    FunTab:CreateToggle({
		Name = "Play Animation\t <font face=\"GothamBlack\" color=\"rgb(0,255,0)\">ANIM</font>",
		CurrentValue = false,
		Flag = "AnimToggle",
		Callback = function(p250)
        animEnabled = p250
    end
	})
    FunTab:CreateDropdown({
		Name = "Select Animation",
		Options = {
			"Crouch",
			"FireFlail",
			"Flail",
			"Typing"
		},
		CurrentOption = "Crouch",
		Flag = "AnimDropdown",
		Callback = function(p251)
        if typeof(p251) == "table" then
            currentAnimation = p251[1]
        else
            currentAnimation = p251
        end

        if animationTrack then
            animationTrack:Stop()
            animationTrack = nil
        end
    end
	})
    FunTab:CreateLabel("Wings", "bird")
    t2.value159 = false
    WingsSpeed = 2.5
    WingsAngle = 35
    AutoRegrab = false
    t2.value160 = "PalletLightBrown"
    t2.value161 = "WingPallet"
    PalletAmount = 12
    WingDistance = 23
    t2.value162 = {}
    t2.value163 = {}
    spawnCooldown = false
    t2.value164 = 0
    t2.value165 = 0
    t2.value166 = {}
    offsets = {
		CFrame.new(-WingDistance / 2, 0, 1),
		CFrame.new(WingDistance / 2, 0, 1)
	}

    function getCurrentSpawnFolder()
        if t2.value11.Value then
            local v1233 = GetOwnedPlot()

            if not v1233 then
                return nil
            end

            local PlotItems = workspace:FindFirstChild("PlotItems")

            if PlotItems then
                return (PlotItems:FindFirstChild("Plot" .. v1233))
            end

            return nil
        end

        return workspace:FindFirstChild(t1.value3.Name .. "SpawnedInToys") or workspace:WaitForChild(t1.value3.Name .. "SpawnedInToys", 15)
    end
    function watchFolder(p252)
        if not p252 or t2.value166[p252] then
            return
        end

        local GetChildren = p252.GetChildren

        t2.value166[p252] = true

        for _, v in ipairs(GetChildren(p252)) do
            if v and v.Name == t2.value160 then
                task.wait(0.2)
                v.Name = t2.value161
                forceNetworkOwnership(v)
                setupAntiGrab(v)
            end
        end

        p252.ChildAdded:Connect(function(child)
            if not t2.value159 then
                return
            end

            if child and child.Name == t2.value160 then
                task.wait(0.2)
                child.Name = t2.value161
                forceNetworkOwnership(child)
                setupAntiGrab(child)
            end
        end)
    end

    local _FunTab2 = FunTab
    local value159 = t2.value159

    _FunTab2:CreateToggle({
		Name = "Enable Wings    <font face=\"GothamBlack\" color=\"rgb(15,255,130)\">FLY</font>   <font face=\"GothamBlack\" color=\"rgb(255,255,255)\">WING</font>",
		CurrentValue = value159,
		Callback = function(p253)
        local u1240 = p253
        pcall(function()
            if t2.value159 == u1240 then
                return
            end

            t2.value159 = u1240

            if not t2.value159 then
                spawnCooldown = false
                local v2145 = getAllPalletFolders()
                for v2148, v2149 in ipairs(v2145) do

                    for i = #v2149:GetChildren(), 1, -1 do
                        local v2151 = v2149:GetChildren()[i]

                        if v2151 and v2151.Name == t2.value161 then
                            pcall(function()
                                DeleteToyRE:FireServer(v2151)
                            end)
                            t2.value163[v2151] = nil
                        end
                    end
                end
                for _, v in ipairs(t2.value162) do
                    if v and v.Handle then
                        v.Handle:Destroy()
                    end

                    if v and v.Segments then
                        for _, v11 in ipairs(v.Segments) do
                            if v11 then
                                v11:Destroy()
                            end
                        end
                    end
                end
                t2.value162 = {}

                return
            end

            rebuildWings()

            local v2156 = getAllPalletFolders()

            for _, v in ipairs(v2156) do
                watchFolder(v)
            end
        end)
    end
	})

    local _FunTab3 = FunTab
    local _PalletAmount = PalletAmount

    _FunTab3:CreateSlider({
		Name = "Pallet Amount    <font face=\"GothamBlack\" color=\"rgb(255,255,0)\">SIZE</font>",
		Range = {
			2,
			20
		},
		Increment = 2,
		CurrentValue = _PalletAmount,
		Callback = function(p254)
        local u1242 = p254
        pcall(function()
            local _PalletAmount2 = PalletAmount

            PalletAmount = u1242

            if _PalletAmount2 > u1242 then
                cleanupExcess()
            end

            rebuildWings()

            if t2.value159 and t1.value3.Character then
                local HumanoidRootPart = t1.value3.Character:FindFirstChild("HumanoidRootPart")

                if HumanoidRootPart then
                    local v2161 = countAllWingPallets()
                    local v2162 = PalletAmount - v2161

                    if v2162 > 0 then
                        spawnCooldown = true

                        for i = 1, v2162 do
                            task.spawn(function()
                                task.wait((i - 1) * 0.1)
                                spawnPalletsSingle(HumanoidRootPart)
                            end)
                        end

                        task.delay(2, function()
                            spawnCooldown = false
                        end)
                    end
                end
            end
        end)
    end
	})
    FunTab:CreateToggle({
		Name = "Auto Regrab   <font face=\"GothamBlack\" color=\"rgb(255, 150, 51)\">ANTIS</font>",
		CurrentValue = false,
		Callback = function(p255)
        AutoRegrab = p255
    end
	})

    local _FunTab4 = FunTab
    local _WingsSpeed = WingsSpeed

    _FunTab4:CreateSlider({
		Name = "Wings Speed     <font face=\"GothamBlack\" color=\"rgb(255,80,0)\">VELOCITY</font>",
		Range = {
			1,
			10
		},
		Increment = 0.1,
		CurrentValue = _WingsSpeed,
		Callback = function(p256)
        WingsSpeed = p256
    end
	})

    local _FunTab5 = FunTab
    local _WingsAngle = WingsAngle

    _FunTab5:CreateSlider({
		Name = "Wings Angle   <font face=\"GothamBlack\" color=\"rgb(0,200,255)\">TILT</font>",
		Range = {
			10,
			60
		},
		Increment = 1,
		CurrentValue = _WingsAngle,
		Callback = function(p257)
        WingsAngle = p257
    end
	})

    function CP()
        local Part = Instance.new("Part")

        Part.Anchored = true
        Part.CanCollide = false
        Part.Transparency = 1
        Part.Size = Vector3.new(1, 1, 1)
        Part.Parent = workspace

        return Part
    end
    function rebuildWings()
        for _, v in ipairs(t2.value162) do
            if v and v.Handle then
                v.Handle:Destroy()
            end

            if v and v.Segments then
                for _, v12 in ipairs(v.Segments) do
                    if v12 then
                        v12:Destroy()
                    end
                end
            end
        end

        t2.value162 = {}

        local v1251 = PalletAmount / 2

        for i = 1, 2 do
            local t49 = {}

            for _ = 1, v1251 do
                table.insert(t49, CP())
            end

            t2.value162[i] = {
				Handle = CP(),
				Segments = t49
			}
        end
    end
    function countAllWingPallets()
        local n17 = 0
        local v1256 = getAllPalletFolders()

        for _, v in ipairs(v1256) do
            for _, child in ipairs(v:GetChildren()) do
                if child and child.Name == t2.value161 or child:IsA("Model") and child.Name == t2.value161 then
                    n17 += 1
                end
            end
        end

        return n17
    end
    function cleanupALL()
        local v1261 = getAllPalletFolders()

        for _, v in ipairs(v1261) do
            for i = #v:GetChildren(), 1, -1 do
                local v1265 = v:GetChildren()[i]

                if v1265 and v1265.Name == t2.value161 then
                    pcall(function()
                        DeleteToyRE:FireServer(v1265)
                    end)
                    t2.value163[v1265] = nil
                end
            end
        end
    end
    function cleanupExcess()
        local v1266
        local v1267 = getAllPalletFolders()
        for _, v in ipairs(v1267) do
            local GetChildren = v.GetChildren

            for _, v13 in ipairs(GetChildren(v)) do
                local v1273 = v13

                if v1273 and v1273.Name == t2.value161 then
                    local _PalletAmount3 = PalletAmount

                    v1266 += 1

                    if _PalletAmount3 < v1266 then
                        pcall(function()
                            DeleteToyRE:FireServer(v1273)
                        end)
                        t2.value163[v1273] = nil
                    end
                end
            end
        end
    end
    function CBM(p258)
        local v1276 = p258:FindFirstChild("WingGyro") or Instance.new("BodyGyro")
        local v1277 = p258:FindFirstChild("WingPos") or Instance.new("BodyPosition")

        v1276.Name = "WingGyro"
        v1277.Name = "WingPos"
        v1276.P = 15000
        v1276.D = 200
        v1276.MaxTorque = Vector3.new(1, 1, 1) * 10000000000
        v1277.P = 15000
        v1277.D = 200
        v1277.MaxForce = Vector3.new(1, 1, 1) * 10000000000
        v1276.Parent = p258
        v1277.Parent = p258

        return v1276, v1277
    end
    function forceNetworkOwnership(p259)
        if t2.value163[p259] then
            return
        end

        t2.value163[p259] = true
        task.spawn(function()
            local v2164 = p259:WaitForChild("SoundPart", 3) or (p259.PrimaryPart or p259:FindFirstChildOfClass("BasePart"))

            if not v2164 then
                return
            end

            for _, descendant in ipairs(p259:GetDescendants()) do
                if descendant:IsA("BasePart") then
                    descendant.CanCollide = false
                end
            end

            for _ = 1, 5 do
                SetNetworkOwner:FireServer(v2164, v2164.CFrame)
                task.wait(0.1)
            end
        end)
    end
    function setupAntiGrab(p260)
        local timestamp = tick()

        task.spawn(function()
            local v2168 = p260:WaitForChild("SoundPart", 3) or (p260.PrimaryPart or p260:FindFirstChildOfClass("BasePart"))

            if not v2168 then
                return
            end

            task.wait(1.5)

            while p260.Parent do
                local PartOwner = v2168:FindFirstChild("PartOwner")
                local _AutoRegrab = AutoRegrab

                if _AutoRegrab then
                    _AutoRegrab = tick() - timestamp > 2 and (not not PartOwner and PartOwner.Value ~= t1.value3.Name) or not PartOwner
                end

                if _AutoRegrab then
                    local Character = t1.value3.Character
                    local v2172 = Character and Character:FindFirstChild("HumanoidRootPart")

                    if v2172 and v2172.Parent then
                        local CFrame10 = v2172.CFrame

                        v2172.CFrame = v2168.CFrame * CFrame.new(0, 5, 0)

                        for _ = 1, 8 do
                            SetNetworkOwner:FireServer(v2168, v2168.CFrame)
                        end

                        task.wait(0.05)
                        v2172.CFrame = CFrame10
                    end
                end

                task.wait(0.01)
            end
        end)
    end
    function spawnPalletsSingle(p261)
        if not canSpawn() or not t2.value159 then
            return
        end

        if not getCurrentSpawnFolder() then
            return
        end

        local LookVector = workspace.CurrentCamera.CFrame.LookVector
        local v1283 = p261.Position + LookVector * -3
        local cFrame = CFrame.new(v1283, v1283 + LookVector)
        local _SpawnToyRF = SpawnToyRF
        local value160 = t2.value160
        local t50 = { Vector3.new(0, 90, 0) }

        _SpawnToyRF:InvokeServer(value160, cFrame, v1(t50))
    end
    function spawnPallets(p262)
        if not canSpawn() or (spawnCooldown or not t2.value159) then
            return
        end

        if not getCurrentSpawnFolder() then
            return
        end

        local v1289 = countAllWingPallets()
        local v1290 = PalletAmount - v1289

        if v1290 <= 0 then
            return
        end

        spawnCooldown = true

        for i = 1, v1290 do
            task.spawn(function()
                task.wait((i - 1) * 0.05)

                local LookVector = workspace.CurrentCamera.CFrame.LookVector
                local v2176 = p262.Position + LookVector * -1
                local cFrame = CFrame.new(v2176, v2176 + LookVector)

                SpawnToyRF:InvokeServer(t2.value160, cFrame, Vector3.new(0, 90, 0))
            end)
        end

        task.delay(1, function()
            spawnCooldown = false
        end)
    end

    task.spawn(function()
        while true do
            task.wait(2)

            if t2.value159 then
                local v1292 = getAllPalletFolders()

                for _, v in ipairs(v1292) do
                    watchFolder(v)
                end
            end
        end
    end)
    rebuildWings()

    local v129 = getAllPalletFolders()

    for _, v in ipairs(v129) do
        watchFolder(v)
    end

    t1.value2.RenderStepped:Connect(function(dt)
        if not t2.value159 then
            return
        end
        local Character = t1.value3.Character
        local v1297 = Character and Character:FindFirstChild("HumanoidRootPart")
        if not v1297 then
            return
        end
        local v1298 = dt * (WingsSpeed + v1297.Velocity.Magnitude / 40)
        local v1299 = t2
        v1299.value164 = v1299.value164 + v1298
        local v1300 = t2
        v1300.value165 = v1300.value165 + dt
        if t2.value165 >= 0.5 then
            spawnPallets(v1297)
        end
        local t51 = {}
        local v1302 = getAllPalletFolders()
        for v1305, v1306 in ipairs(v1302) do

            for _, child in ipairs(v1306:GetChildren()) do
                if child and child.Name == t2.value161 or child:IsA("Model") and child.Name == t2.value161 then
                    table.insert(t51, child)
                end
            end
        end
        local v1309 = PalletAmount / 2
        for i, v in ipairs(t2.value162) do
            local v1312 = i
            local _math = math
            local v1314 = v1312 ~= 1 and -1 or 1
            local v1315 = _math.sin(t2.value164) * math.rad(WingsAngle) * v1314

            if v and v.Handle then
                v.Handle.CFrame = v1297.CFrame * offsets[v1312] * CFrame.Angles(0, 0, v1315)
            end

            if v and v.Segments then
                for i2, v14 in ipairs(v.Segments) do
                    local v1318 = i2

                    if v14 then
                        local v1319 = v1318 == 1 and v.Handle.CFrame or v.Segments[v1318 - 1].CFrame

                        v14.CFrame = v14.CFrame:Lerp(v1319 * offsets[v1312], 0.45)

                        local v1320 = t51[(v1312 - 1) * v1309 + v1318]

                        if v1320 then
                            local v1321 = v1320.PrimaryPart or (v1320:FindFirstChild("SoundPart") or v1320:FindFirstChildOfClass("BasePart"))

                            if v1321 then
                                local v1322, v1323 = CBM(v1321)

                                v1323.Position = v14.Position
                                v1322.CFrame = v14.CFrame * CFrame.Angles(0, 3.141592653589793, 0)
                                v1321.CanCollide = false
                            end
                        end
                    end
                end
            end
        end
    end)
    FunTab:CreateLabel("Control", "footprints")
    _G.ControlEnabled = false
    _G.ControllingCreature = nil

    function lookAt(p263, p264)
        local Unit = (p264 - p263).Unit
        local v1327 = Unit:Cross(Vector3.new(0, 1, 0))
        local v1328 = v1327:Cross(Unit)

        return CFrame.fromMatrix(p263, v1327, v1328)
    end
    function CheckOwnership(p265)
        local PartOwner = p265:FindFirstChild("PartOwner")

        return PartOwner and PartOwner.Value == t1.value3.Name
    end
    function SNOWshipOnce(p266)
        if not p266 or not t1.value3.Character then
            return false
        end

        if CheckOwnership(p266) then
            return true
        end

        local HumanoidRootPart = t1.value3.Character:FindFirstChild("HumanoidRootPart")

        if HumanoidRootPart and (HumanoidRootPart.Position - p266.Position).Magnitude <= 60 then
            local _SetNetworkOwner = SetNetworkOwner
            local t52 = { lookAt(HumanoidRootPart.Position, p266.Position) }

            _SetNetworkOwner:FireServer(p266, v1(t52))

            return true
        end

        return false
    end
    function handleDestroyGrabLine(p267)
        local HumanoidRootPart = p267:FindFirstChild("HumanoidRootPart")

        if HumanoidRootPart then
            DestroyGrabLine:FireServer(HumanoidRootPart)
        end
    end
    function getTarget()
        local Character = t1.value3.Character

        if not Character then
            return nil
        end

        local CurrentCamera = Workspace.CurrentCamera
        local raycastParams = RaycastParams.new()

        raycastParams.FilterDescendantsInstances = { Character }
        raycastParams.FilterType = Enum.RaycastFilterType.Exclude

        local raycastResult = Workspace:Raycast(CurrentCamera.CFrame.Position, CurrentCamera.CFrame.LookVector * 150, raycastParams)

        if raycastResult then
            local Model = raycastResult.Instance:FindFirstAncestorOfClass("Model")

            if Model and (Model:FindFirstChildOfClass("Humanoid") and Model ~= Character) then
                if Model.Parent.Name == "CreatureBlobman" then
                    return nil
                end

                return Model
            end
        end

        return nil
    end

    t2.value167 = {}

    function forceNoCollision(p268)
        for _, descendant in pairs(p268:GetDescendants()) do
            local v1345 = descendant

            if v1345:IsA("BasePart") then
                v1345.CanCollide = false

                if not t2.value167[v1345] then
                    t2.value167[v1345] = v1345:GetPropertyChangedSignal("CanCollide"):Connect(function()
                        if _G.ControllingCreature and _G.ControlEnabled then
                            v1345.CanCollide = false
                        end
                    end)
                end
            end
        end
    end
    function clearCollisionConnections()
        for _, v in pairs(t2.value167) do
            if v then
                v:Disconnect()
            end
        end

        t2.value167 = {}
    end
    function t2.value168(p269)
        if p269.Parent.Name == "CreatureBlobman" then
            return
        end

        if _G.ControllingCreature then
            handleDestroyGrabLine(_G.ControllingCreature)
            _G.ControllingCreature = nil
            task.wait(0.1)
        end

        local Humanoid26 = p269:FindFirstChildOfClass("Humanoid")
        local v1350 = p269:FindFirstChild("HumanoidRootPart") or p269.PrimaryPart
        local Head = p269:FindFirstChild("Head")
        local Character = t1.value3.Character
        local Humanoid27 = Character:FindFirstChildOfClass("Humanoid")
        local HumanoidRootPart = Character:FindFirstChild("HumanoidRootPart")

        if not v1350 or (not Humanoid26 or not HumanoidRootPart) then
            return
        end

        _G.ControllingCreature = p269
        Humanoid27.AutoRotate = false

        local BodyVelocity = Instance.new("BodyVelocity", v1350)

        BodyVelocity.MaxForce = Vector3.new(1e999, 0, 1e999)
        BodyVelocity.Velocity = Vector3.new(0, 0, 0)

        local BodyGyro = Instance.new("BodyGyro", v1350)

        BodyGyro.MaxTorque = Vector3.new(0, 1e999, 0)
        BodyGyro.P = 40000
        BodyGyro.D = 500
        Humanoid26:SetStateEnabled(Enum.HumanoidStateType.Seated, false)
        Humanoid26.Sit = false
        forceNoCollision(Character)

        local connection = Character.DescendantAdded:Connect(function(descendant)
            if descendant:IsA("BasePart") and _G.ControllingCreature then
                descendant.CanCollide = false
                t2.value167[descendant] = descendant:GetPropertyChangedSignal("CanCollide"):Connect(function()
                    if _G.ControllingCreature and _G.ControlEnabled then
                        descendant.CanCollide = false
                    end
                end)
            end
        end)

        task.spawn(function()
            while true do
                local v2179 = _G.ControllingCreature == p269

                if v2179 then
                    v2179 = p269.Parent and (_G.ControlEnabled and Character.Parent)
                end

                if not v2179 then
                    break
                end

                local CurrentCamera = Workspace.CurrentCamera
                local MoveDirection = Humanoid27.MoveDirection

                HumanoidRootPart.CFrame = v1350.CFrame * CFrame.new(0, -10, 0)
                HumanoidRootPart.Velocity = Vector3.new(0, 0, 0)
                forceNoCollision(Character)
                SNOWshipOnce(Head or v1350)

                if MoveDirection.Magnitude > 0 then
                    Humanoid26:ChangeState(Enum.HumanoidStateType.Running)
                    Humanoid26:Move(MoveDirection, false)
                    BodyVelocity.Velocity = Vector3.new(MoveDirection.X, 0, MoveDirection.Z) * 26
                else
                    BodyVelocity.Velocity = Vector3.new(0, 0, 0)
                end

                BodyGyro.CFrame = CFrame.lookAt(v1350.Position, v1350.Position + Vector3.new(CurrentCamera.CFrame.LookVector.X, 0, CurrentCamera.CFrame.LookVector.Z))
                CurrentCamera.CameraSubject = Humanoid26
                t1.value2.Heartbeat:Wait()
            end

            handleDestroyGrabLine(p269)

            if connection then
                connection:Disconnect()
            end

            clearCollisionConnections()

            if BodyVelocity then
                BodyVelocity:Destroy()
            end

            if BodyGyro then
                BodyGyro:Destroy()
            end

            Humanoid27.AutoRotate = true
            Workspace.CurrentCamera.CameraSubject = Humanoid27
            HumanoidRootPart.Anchored = true
            HumanoidRootPart.AssemblyLinearVelocity = Vector3.new(0, 0, 0)
            HumanoidRootPart.CFrame = v1350.CFrame * CFrame.new(10, 4, 0)
            task.wait(0.2)
            HumanoidRootPart.Anchored = false

            for _, descendant in pairs(Character:GetDescendants()) do
                if descendant:IsA("BasePart") and (descendant.Name ~= "CamPart" and descendant.Name ~= "HumanoidRootPart") then
                    descendant.CanCollide = true
                end
            end
        end)
    end

    FunTab:CreateToggle({
		Name = "Control <b>X</b>  <font face=\"GothamBlack\" color=\"rgb(0,67,47)\">PLAYER</font>  &  <font face=\"GothamBlack\" color=\"rgb(255,34,0)\">NPC</font>\t <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Flag = "PossessToggle",
		Callback = function(p270)
        _G.ControlEnabled = p270

        if p270 then
            t2.value6:Notify({
					Title = "Info",
					Content = "Look at target + Press 'X'",
					Duration = 3
				})

            return
        end

        if _G.ControllingCreature then
            handleDestroyGrabLine(_G.ControllingCreature)
        end

        _G.ControllingCreature = nil
        clearCollisionConnections()
    end
	})
    FunTab:CreateParagraph({
		Title = "<font face=\"GothamBlack\" color=\"rgb(150,60,0)\">CONTROL SYSTEM</font>",
		Content = "Press <b>X</b> and <b>AIM YOUR MOUSE</b> at a target. It can be a <b>SNOWMAN</b>, a <b>KID</b>, a <b>TURKEY</b>, or a <b>PLAYER</b>."
	})
    t2.value7.InputBegan:Connect(function(input, gameProcessed)
        if not gameProcessed then
            gameProcessed = not _G.ControlEnabled
        end

        if gameProcessed then
            return
        end

        if input.KeyCode == Enum.KeyCode.X then
            if _G.ControllingCreature then
                handleDestroyGrabLine(_G.ControllingCreature)
                _G.ControllingCreature = nil
                clearCollisionConnections()

                return
            end

            local v1361 = getTarget()

            if v1361 then
                t2.value168(v1361)

                return
            end

            t2.value6:Notify({
				Title = "Error",
				Content = "No target found or blocked.",
				Duration = 2
			})
        end
    end)
    t2.value7.JumpRequest:Connect(function()
        if _G.ControllingCreature then
            local Humanoid28 = _G.ControllingCreature:FindFirstChildOfClass("Humanoid")

            if Humanoid28 then
                Humanoid28.Jump = true
            end
        end
    end)
    FunTab:CreateLabel("Sparkles", "wand-sparkles")
    t2.value169 = false
    t2.value170 = 3
    t2.value171 = false
    t2.value172 = "FireworkSparkler"
    t2.value173 = "HeartSparkler"
    t2.value174 = 4
    t2.value175 = nil
    t2.value176 = "Heart"
    t2.value177 = 1.5
    t2.value178 = {}
    t2.value179 = {}
    t2.value180 = false
    t2.value181 = 0
    t2.value182 = 0
    t2.value183 = {}
    t2.value184 = false
    t2.value185 = {}
    PlayerDropdown = FunTab:CreateDropdown({
		Name = "Target Player   <font face=\"GothamBlack\" color=\"rgb(0,255,255)\">SELECT</font>",
		Options = {},
		CurrentOption = {},
		MultipleOptions = false,
		Flag = "PlayerDropdown",
		Callback = function(p271)
        if not p271 or (not p271[1] or p271[1] == "None") then
            t2.value175 = nil

            return
        end

        username = p271[1]:match("@([%w_]+)")

        if username then
            t2.value175 = username

            if t2.value169 then
                SE_rebuildHearts()
            end
        end
    end
	})
    FunTab:CreateToggle({
		Name = "Enable Sparkle Shape   <font face=\"GothamBlack\" color=\"rgb(240,184,111)\">SPARKLER</font>   <font face=\"GothamBlack\" color=\"rgb(50,20,147)\">SHAPE</font>",
		CurrentValue = false,
		Flag = "SparkleHeartToggle",
		Callback = function(p272)
        if p272 and not t2.value175 then
            t2.value6:Notify({
					Title = "Error",
					Content = "Please select a target player first!",
					Duration = 3,
					Image = "x"
				})
        end

        t2.value169 = p272

        if p272 then
            SE_rebuildHearts()

            local v1365 = getAllPalletFolders()

            for _, v in ipairs(v1365) do
                SE_watchFolder(v)
            end

            return
        end

        SE_cleanupALL()
    end
	})
    FunTab:CreateSlider({
		Name = "Sparkler Amount   <font face=\"GothamBlack\" color=\"rgb(255,215,0)\">1-5</font>",
		Range = {
			1,
			5
		},
		Increment = 1,
		CurrentValue = 5,
		Flag = "SparklerAmount",
		Callback = function(p273)
        old = t2.value174
        t2.value174 = p273

        if p273 < old then
            SE_cleanupExcess()
        end

        SE_rebuildHearts()
    end
	})
    t2.value174 = 5
    FunTab:CreateDropdown({
		Name = "Shape   <font face=\"GothamBlack\" color=\"rgb(130,50,0)\">PATTERN</font>",
		Options = {
			"Heart",
			"Dick",
			"L",
			"MiddleFinger",
			"nazi cross",
			"Square",
			"Triangle"
		},
		CurrentOption = { "Heart" },
		Flag = "ShapeDropdown",
		Callback = function(p274)
        t2.value176 = p274[1]
        t2.value184 = false
        generateShapePath()
    end
	})
    FunTab:CreateToggle({
		Name = "Auto Regrab   <font face=\"GothamBlack\" color=\"rgb(240,140,0)\">PROTECT</font>",
		CurrentValue = false,
		Flag = "AutoRegrab",
		Callback = function(p275)
        t2.value171 = p275
    end
	})
    FunTab:CreateSlider({
		Name = "Size   <font face=\"GothamBlack\" color=\"rgb(0,255,127)\">Scale</font>\t <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		Range = {
			0,
			10
		},
		Increment = 1,
		CurrentValue = 2,
		Flag = "SizeScale",
		Callback = function(p276)
        t2.value177 = p276
        t2.value184 = false
        generateShapePath()
    end
	})
    FunTab:CreateSlider({
		Name = "Height   <font face=\"GothamBlack\" color=\"rgb(255,0,30)\">OFFSET</font>",
		Range = {
			0,
			100
		},
		Increment = 5,
		CurrentValue = 20,
		Flag = "HeightOffset",
		Callback = function(p277)
        SE_HeightOffset = p277
    end
	})
    SE_RotationOffset = 0
    FunTab:CreateSlider({
		Name = "Rotation <font face=\"GothamBlack\" color=\"rgb(0,255,0)\">TURN</font>",
		Range = {
			-360,
			360
		},
		Increment = 5,
		CurrentValue = 0,
		Flag = "RotationOffset",
		Callback = function(p278)
        SE_RotationOffset = p278
    end
	})

    function optionText(p279)
        return string.format("👤 @%s (%s)", p279.Name, p279.DisplayName or "")
    end
    function refreshDropdown()
        local t53 = { optionText(t1.value3) }
        local t54 = { v1(t53) }

        for _, player29 in ipairs(t2.value96:GetPlayers()) do
            if player29 ~= t1.value3 then
                table.insert(t54, optionText(player29))
            end
        end

        PlayerDropdown:Refresh(t54)
    end

    t2.value96.PlayerAdded:Connect(function()
        task.wait(0.5)
        refreshDropdown()
    end)
    t2.value96.PlayerRemoving:Connect(function()
        task.wait(0.5)
        refreshDropdown()
    end)
    refreshDropdown()

    function generateShapePath()
        if t2.value184 then
            return
        end

        t2.value183 = {}

        local n18 = 3000
        local value177 = t2.value177

        if t2.value176 == "Heart" then
            for i = 0, n18 do
                local v1382 = i / n18 * 3.141592653589793 * 2
                local v1383 = math.sin(v1382)
                local v1384 = 16 * v1383 * v1383 * v1383 * value177
                local v1385 = (math.cos(v1382) * 13 - math.cos(2 * v1382) * 5 - math.cos(3 * v1382) * 2 - math.cos(4 * v1382)) * value177

                t2.value183[i] = Vector3.new(v1384, v1385 + 2, 0)
            end

            return
        end

        if t2.value176 == "Dick" then
            for i = 0, n18 do
                local v1387 = i
                local v1388 = v1387 / n18 * 3.141592653589793 * 2
                local v1389, v1390

                if v1388 < math.pi then
                    v1389 = 4 * value177 * math.cos(v1388)
                    v1390 = 8 * value177 + 16 * value177 * math.sin(v1388)
                elseif v1388 < math.pi * 1.5 then
                    local v1391 = (v1388 - 3.141592653589793) * 4

                    v1389 = -5 * value177 + 4 * value177 * math.cos(v1391)
                    v1390 = -2 * value177 + 4 * value177 * math.sin(v1391)
                else
                    local v1392 = (v1388 - 4.71238898038469) * 4 + 3.141592653589793

                    v1389 = 5 * value177 + 4 * value177 * math.cos(v1392)
                    v1390 = -2 * value177 + 4 * value177 * math.sin(v1392)
                end

                t2.value183[v1387] = Vector3.new(v1389, v1390 + 2, 0)
            end

            return
        end

        if t2.value176 == "L" then
            local v1393 = 8 * value177
            local v1394 = 10 * value177

            for i = 0, n18 do
                local v1396 = i
                local v1397 = math.abs((math.sin(v1396 / n18 * 2 * 3.141592653589793)))
                local v1398, n19

                if v1397 < 0.6 then
                    v1398 = v1397 / 0.6 * v1393 * 2
                    n19 = 0
                else
                    v1398 = v1393 * 2
                    n19 = (v1397 - 0.6) / 0.4 * v1394 * 2
                end

                t2.value183[v1396] = Vector3.new(v1398 - v1393, n19 + 2, 0)
            end

            return
        end

        if t2.value176 == "MiddleFinger" then
            local v1400 = 22 * value177
            local v1401 = 35 * value177
            local v1402 = 14 * value177

            for i = 0, n18 do
                local v1404 = i
                local v1405 = v1404 / n18
                local v1406, v1407

                if v1405 < 0.05 then
                    v1406 = -v1400 * 0.5
                    v1407 = v1405 / 0.05 * v1402
                elseif v1405 < 0.15 then
                    local _ = (v1405 - 0.05) / 0.1
                    local v1409 = (v1405 - 0.05) / 0.1 * 3.141592653589793

                    v1406 = -v1400 * 0.4 + math.cos(3.141592653589793 - v1409) * v1400 * 0.1
                    v1407 = v1402 + math.sin(v1409) * v1402 * 0.2
                elseif v1405 < 0.25 then
                    local _ = (v1405 - 0.15) / 0.1
                    local v1411 = (v1405 - 0.15) / 0.1 * 3.141592653589793

                    v1406 = -v1400 * 0.2 + math.cos(3.141592653589793 - v1411) * v1400 * 0.1
                    v1407 = v1402 + math.sin(v1411) * v1402 * 0.2
                elseif v1405 < 0.55 then
                    local v1412 = (v1405 - 0.25) / 0.3

                    if v1412 < 0.3 then
                        v1406 = -v1400 * 0.1
                        v1407 = v1402 + v1412 / 0.3 * (v1401 - v1402)
                    elseif v1412 < 0.7 then
                        local _ = (v1412 - 0.3) / 0.4
                        local v1414 = (v1412 - 0.3) / 0.4 * 3.141592653589793

                        v1406 = math.cos(3.141592653589793 - v1414) * v1400 * 0.1
                        v1407 = v1401 + math.sin(v1414) * v1400 * 0.1
                    else
                        v1406 = v1400 * 0.1
                        v1407 = v1401 - (v1412 - 0.7) / 0.3 * (v1401 - v1402)
                    end
                elseif v1405 < 0.65 then
                    local _ = (v1405 - 0.55) / 0.1
                    local v1416 = (v1405 - 0.55) / 0.1 * 3.141592653589793

                    v1406 = v1400 * 0.2 + math.cos(3.141592653589793 - v1416) * v1400 * 0.1
                    v1407 = v1402 + math.sin(v1416) * v1402 * 0.2
                elseif v1405 < 0.75 then
                    local _ = (v1405 - 0.65) / 0.1
                    local v1418 = (v1405 - 0.65) / 0.1 * 3.141592653589793

                    v1406 = v1400 * 0.4 + math.cos(3.141592653589793 - v1418) * v1400 * 0.1
                    v1407 = v1402 + math.sin(v1418) * v1402 * 0.2
                elseif v1405 < 0.8 then
                    v1406 = v1400 * 0.5
                    v1407 = v1402 - (v1405 - 0.75) / 0.05 * v1402
                else
                    v1406 = v1400 * 0.5 - (v1405 - 0.8) / 0.2 * v1400
                    v1407 = 0
                end

                t2.value183[v1404] = Vector3.new(v1406, v1407, 0)
            end

            return
        end

        if t2.value176 == "Square" then
            local v1419 = 14 * value177

            for i = 0, n18 do
                local v1421 = i
                local v1422 = v1421 / n18 * 3.141592653589793 * 2
                local v1423 = math.floor(v1422 / 1.5707963267948966) % 4
                local v1424 = v1422 % 1.5707963267948966 / 1.5707963267948966 * 2 - 1
                local v1425, v1426

                if v1423 == 0 then
                    v1425 = v1424 * v1419
                    v1426 = v1419
                elseif v1423 == 1 then
                    v1425 = v1419
                    v1426 = v1424 * -v1419
                elseif v1423 == 2 then
                    v1425 = v1424 * -v1419
                    v1426 = -v1419
                else
                    v1425 = -v1419
                    v1426 = v1424 * v1419
                end

                t2.value183[v1421] = Vector3.new(v1425, v1426 + 2, 0)
            end

            return
        end

        if t2.value176 == "nazi cross" then
            local v1427 = 12 * value177
            local v1428 = v1427 * 0.4
            local v1429 = false
            local t55 = {}
            local n20 = -1

            while true do
                n20 += 1

                if (not v1429 or not (n18 <= n20)) and (v1429 or not (n20 <= n18)) then
                    break
                end

                local v1432 = n20 / n18 * 3.141592653589793 * 2
                local v1433 = math.floor(v1432 / 0.5235987755982988) % 12
                local v1434 = v1432 % 0.5235987755982988 / 0.5235987755982988
                local n21, v1436

                if v1433 == 0 then
                    n21 = 0
                    v1436 = v1434 * v1427 * 0.5
                elseif v1433 == 1 then
                    v1436 = v1427 * 0.5
                    n21 = v1434 * v1428
                elseif v1433 == 2 then
                    v1436 = v1427 * 0.5 - v1434 * v1427 * 0.5
                    n21 = 0
                elseif v1433 == 3 then
                    v1436 = 0
                    n21 = -v1434 * v1427 * 0.5
                elseif v1433 == 4 then
                    v1436 = v1434 * v1428
                    n21 = -v1427 * 0.5
                elseif v1433 == 5 then
                    v1436 = 0
                    n21 = -v1427 * 0.5 + v1434 * v1427 * 0.5
                elseif v1433 == 6 then
                    v1436 = -v1434 * v1427 * 0.5
                    n21 = 0
                elseif v1433 == 7 then
                    v1436 = -v1427 * 0.5
                    n21 = -v1434 * v1428
                elseif v1433 == 8 then
                    local v1437 = v1434 * v1427

                    v1436 = -v1427 * 0.5 + v1437 * 0.5
                    n21 = 0
                elseif v1433 == 9 then
                    v1436 = 0
                    n21 = v1434 * v1427 * 0.5
                elseif v1433 == 10 then
                    v1436 = -v1434 * v1428
                    n21 = v1427 * 0.5
                else
                    v1436 = 0
                    n21 = v1427 * 0.5 - v1434 * v1427 * 0.5
                end

                t55[#t55 + 1] = Vector3.new(v1436, n21, 0)
            end

            local t56 = { 0 }
            local n22 = 0

            for i = 2, #t55 do
                n22 += (t55[i] - t55[i - 1]).Magnitude
                t56[i] = n22
            end

            local n23 = 2
            local v1442 = false
            local n24 = -1

            while true do
                n24 += 1

                if (not v1442 or not (n18 <= n24)) and (v1442 or not (n24 <= n18)) then
                    break
                end

                local v1444 = n24 / n18 * n22

                while n23 < #t56 and v1444 > t56[n23] do
                    n23 += 1
                end

                local v1445 = t56[n23 - 1]
                local v1446 = t56[n23]
                local v1447 = if v1446 ~= v1445 then (v1444 - v1445) / (v1446 - v1445) else 0
                local v1448 = t55[n23 - 1]:Lerp(t55[n23], v1447)

                t2.value183[n24] = v1448 + Vector3.new(0, 2, 0)
            end
        elseif t2.value176 == "Triangle" then
            for i = 0, n18 do
                local v1450 = i
                local v1451 = v1450 / n18 * 3.141592653589793 * 2
                local v1452 = math.floor(v1451 / 2.0943951023931953) % 3
                local v1453, n25

                if v1452 == 0 then
                    v1453 = 10 * value177
                    n25 = 0
                elseif v1452 == 1 then
                    n25 = 8 * value177
                    v1453 = -6 * value177
                else
                    n25 = -8 * value177
                    v1453 = -6 * value177
                end

                local v1455 = value177 * math.sin(v1451 * 0.5)

                t2.value183[v1450] = Vector3.new(n25 + v1455 * 0.3, v1453 + v1455 * 0.3 + 2, 0)
            end
        end
    end
    function getSmoothedShapePos(p280)
        if #t2.value183 == 0 then
            return Vector3.new(0, 0, 0)
        end

        local v1457 = p280 * #t2.value183
        local v1458 = math.floor(v1457) % #t2.value183
        local v1459 = (v1458 + 1) % #t2.value183
        local v1460 = v1457 - math.floor(v1457)

        return t2.value183[v1458]:Lerp(t2.value183[v1459], v1460)
    end
    function SE_CP()
        local Part = Instance.new("Part")

        Part.Anchored = true
        Part.CanCollide = false
        Part.Transparency = 1
        Part.Size = Vector3.new(1, 1, 1)
        Part.Parent = workspace

        return Part
    end
    function SE_rebuildHearts()
        for _, v in ipairs(t2.value178) do
            if v.Handle then
                v.Handle:Destroy()
            end
        end

        t2.value178 = {}

        for i = 1, t2.value174 do
            t2.value178[i] = {
				Handle = SE_CP()
			}
        end
    end
    function SE_countAllHeartSparkler()
        local n26 = 0
        local v1466 = getAllPalletFolders()

        for _, v in ipairs(v1466) do
            local GetChildren = v.GetChildren

            for _, v15 in ipairs(GetChildren(v)) do
                if v15.Name == t2.value173 then
                    n26 += 1
                end
            end
        end

        return n26
    end
    function SE_cleanupALL()
        local v1472 = getAllPalletFolders()

        for _, v in ipairs(v1472) do
            for _, child in ipairs(v:GetChildren()) do
                local v1477 = child

                if v1477.Name == t2.value173 then
                    pcall(function()
                        DeleteToyRE:FireServer(v1477)
                    end)
                    t2.value179[v1477] = nil
                end
            end
        end
    end
    function SE_cleanupExcess()
        local v1478
        local v1479 = getAllPalletFolders()
        for _, v in ipairs(v1479) do
            for _, child in ipairs(v:GetChildren()) do
                local v1484 = child

                if v1484.Name == t2.value173 then
                    v1478 += 1

                    if v1478 > t2.value174 then
                        pcall(function()
                            DeleteToyRE:FireServer(v1484)
                        end)
                        t2.value179[v1484] = nil
                    end
                end
            end
        end
    end
    function SE_CBM(p281)
        local v1486 = p281:FindFirstChild("HeartGyro") or Instance.new("BodyGyro")
        local v1487 = p281:FindFirstChild("HeartPos") or Instance.new("BodyPosition")

        v1486.Name = "HeartGyro"
        v1487.Name = "HeartPos"
        v1486.P = 15000
        v1486.D = 200
        v1487.P = 15000
        v1487.D = 200
        v1486.MaxTorque = Vector3.new(1, 1, 1) * 10000000000
        v1487.MaxForce = Vector3.new(1, 1, 1) * 10000000000
        v1486.Parent = p281
        v1487.Parent = p281

        return v1486, v1487
    end
    function SE_forceNetworkOwnership(p282)
        if t2.value179[p282] then
            return
        end

        t2.value179[p282] = true
        task.spawn(function()
            local Base = p282:FindFirstChild("Base")

            if not Base then
                Base = p282:WaitForChild("SoundPart", 3) or (p282.PrimaryPart or p282:FindFirstChildOfClass("BasePart"))
            end

            if not Base then
                return
            end

            for _, descendant in ipairs(p282:GetDescendants()) do
                if descendant:IsA("BasePart") then
                    descendant.CanCollide = false
                end
            end

            for _ = 1, 5 do
                SetNetworkOwner:FireServer(Base, Base.CFrame)
                task.wait(0.1)
            end
        end)
    end
    function SE_setupAntiGrab(p283)
        local timestamp = tick()

        task.spawn(function()
            local Base = p283:FindFirstChild("Base")

            if not Base then
                Base = p283:WaitForChild("SoundPart", 3) or (p283.PrimaryPart or p283:FindFirstChildOfClass("BasePart"))
            end

            if not Base then
                return
            end

            task.wait(1.5)

            while p283.Parent do
                local PartOwner = Base:FindFirstChild("PartOwner")
                local value171 = t2.value171

                if value171 then
                    value171 = tick() - timestamp > 2 and (not not PartOwner and PartOwner.Value ~= t1.value3.Name) or not PartOwner
                end

                if value171 then
                    local Character = t1.value3.Character
                    local v2192 = Character and Character:FindFirstChild("HumanoidRootPart")

                    if v2192 and v2192.Parent then
                        local CFrame11 = v2192.CFrame

                        v2192.CFrame = Base.CFrame * CFrame.new(0, 5, 0)

                        for _ = 1, 8 do
                            SetNetworkOwner:FireServer(Base, Base.CFrame)
                        end

                        task.wait(0.05)
                        v2192.CFrame = CFrame11
                    end
                end

                task.wait(0.01)
            end
        end)
    end
    function SE_watchFolder(p284)
        if not p284 or t2.value185[p284] then
            return
        end

        local GetChildren = p284.GetChildren

        t2.value185[p284] = true

        for _, v in ipairs(GetChildren(p284)) do
            if v.Name == t2.value172 then
                task.wait(0.2)
                v.Name = t2.value173
                SE_forceNetworkOwnership(v)
                SE_setupAntiGrab(v)
            end
        end

        p284.ChildAdded:Connect(function(child)
            if not t2.value169 then
                return
            end

            if child.Name == t2.value172 then
                task.wait(0.2)
                child.Name = t2.value173
                SE_forceNetworkOwnership(child)
                SE_setupAntiGrab(child)
            end
        end)
    end
    function SE_spawnSparkler(p285)
        if not canSpawn() or (t2.value180 or not t2.value169) then
            return
        end

        if not getCurrentSpawnFolder() then
            return
        end

        local v1496 = SE_countAllHeartSparkler()
        local v1497 = t2.value174 - v1496

        if v1497 <= 0 then
            return
        end

        for i = 1, v1497 do
            task.spawn(function()
                task.wait((i - 1) * 0.05)

                local LookVector = workspace.CurrentCamera.CFrame.LookVector
                local v2197 = p285.Position + LookVector * -1

                SpawnToyRF:InvokeServer(t2.value172, CFrame.new(v2197, v2197 + LookVector), Vector3.new(0, 90, 0))
            end)
        end

        task.delay(1, function()
        end)
    end

    task.spawn(function()
        while true do
            task.wait(2)

            if t2.value169 then
                local v1499 = getAllPalletFolders()

                for _, v in ipairs(v1499) do
                    SE_watchFolder(v)
                end
            end
        end
    end)
    SE_rebuildHearts()

    local v132 = getAllPalletFolders()

    for _, v in ipairs(v132) do
        SE_watchFolder(v)
    end

    generateShapePath()
    t1.value2.Heartbeat:Connect(function(dt)
        if not t2.value169 then
            return
        end
        if not t2.value175 then
            return
        end
        local Character = t1.value3.Character
        local v1504 = Character and Character:FindFirstChild("HumanoidRootPart")
        if not v1504 then
            return
        end
        local v1505 = dt * t2.value170
        local v1506 = t2
        v1506.value181 = v1506.value181 + v1505
        local v1507 = t2
        v1507.value182 = v1507.value182 + dt
        if t2.value182 >= 0.5 then
            SE_spawnSparkler(v1504)
        end
        local t57 = {}
        local v1509 = getAllPalletFolders()
        for v1512, v1513 in ipairs(v1509) do

            for _, child in ipairs(v1513:GetChildren()) do
                if child.Name == t2.value173 then
                    table.insert(t57, child)
                end
            end
        end
        local t2value175 = t2.value96:FindFirstChild(t2.value175)
        if t2value175 and t2value175.Character then
            local HumanoidRootPart = t2value175.Character:FindFirstChild("HumanoidRootPart")

            if HumanoidRootPart then
                local v1518 = HumanoidRootPart.Position + Vector3.new(0, SE_HeightOffset, 0)

                for i, v in ipairs(t2.value178) do
                    local v1521 = (i - 1) * (6.283185307179586 / t2.value174)
                    local v1522 = (t2.value181 + v1521) % 6.283185307179586 / 6.283185307179586
                    local v1523 = getSmoothedShapePos(v1522)
                    local v1524 = v1518 + CFrame.Angles(0, math.rad(SE_RotationOffset), 0) * v1523 + Vector3.new(6, 0, 0)

                    v.Handle.CFrame = CFrame.new(v1524)

                    local v1525 = t57[i]

                    if v1525 then
                        local v1526 = v1525:FindFirstChild("Base") or (v1525.PrimaryPart or (v1525:FindFirstChild("SoundPart") or v1525:FindFirstChildOfClass("BasePart")))

                        if v1526 then
                            local v1527, v1528 = SE_CBM(v1526)

                            v1528.Position = v1524
                            v1527.CFrame = CFrame.new(v1524)
                            v1526.CanCollide = false
                        end
                    end
                end
            end
        end
    end)
    FunTab:CreateLabel("PlotBreaker", "tower-control")
    autoBreakActive = false
    lastBreakTick = 0
    FunTab:CreateToggle({
		Name = "Auto   <font face=\"GothamBlack\" color=\"rgb(120,34,0)\">BREAK</font>    <font face=\"GothamBlack\" color=\"rgb(255,255,0)\">PLOT</font>",
		CurrentValue = false,
		Callback = function(p286)
        autoBreakActive = p286

        if p286 then
            task.spawn(function()
                while autoBreakActive do
                    if not (tick() - lastBreakTick < 0.6) then
                        lastBreakTick = tick()

                        local Character = t1.value3.Character
                        local v2199 = Character and Character:FindFirstChild("HumanoidRootPart")

                        if not v2199 then
                            continue
                        end

                        local CFrame12 = v2199.CFrame
                        local FoodHamburger = BackPack:FindFirstChild("FoodHamburger")

                        if not FoodHamburger then
                            task.spawn(function()
                                SpawnToyRF:InvokeServer("FoodHamburger", v2199.CFrame * CFrame.new(4, 4, 15), Vector3.zero)
                            end)
                            task.wait(0.25)
                            FoodHamburger = BackPack:FindFirstChild("FoodHamburger")
                        end

                        if FoodHamburger and FoodHamburger:FindFirstChild("HoldPart") then
                            local HoldItemRemoteFunction = FoodHamburger.HoldPart:FindFirstChild("HoldItemRemoteFunction")

                            if HoldItemRemoteFunction then
                                task.spawn(function()
                                    pcall(function()
                                        HoldItemRemoteFunction:InvokeServer(FoodHamburger, Character)
                                    end)
                                end)
                            end
                        end

                        local v2203 = workspace:FindFirstChild(t1.value3.Name .. "SpawnedInToys")
                        local n27 = 0

                        if v2203 then
                            local GetChildren = v2203.GetChildren

                            for _, v in ipairs(GetChildren(v2203)) do
                                if v.Name == "Boombox" then
                                    n27 += 1
                                end
                            end
                        end

                        v2199.CFrame = CFrame.new(-541, -7, 68)
                        task.wait(0.1)

                        if FoodHamburger then
                            DestroyToyRF:FireServer(FoodHamburger)
                        end

                        v2199.CFrame = CFrame12
                        task.wait(0.6)

                        local n28 = 0

                        if v2203 then
                            for _, child in ipairs(v2203:GetChildren()) do
                                if child.Name == "Boombox" then
                                    n28 += 1
                                end
                            end
                        end

                        if n27 <= n28 and n28 > 0 then
                            autoBreakActive = false
                            t2.value6:Notify({
									Title = "PlotBreaker",
									Content = "Server broken",
									Duration = 4,
									Image = "check"
								})

                            return
                        end

                        task.spawn(function()
                            SpawnToyRF:InvokeServer("Boombox", CFrame.new(-541, -2, 68), Vector3.zero)
                        end)
                        task.wait(0.8)

                        continue
                    end

                    t1.value2.Heartbeat:Wait()
                end
            end)
        end

        lastBreakTick = 0
    end
	})
    FunTab:CreateButton({
		Name = "Desync   <font face=\"GothamBlack\" color=\"rgb(0,120,0)\">TRACTOR</font>",
		Callback = function()
        local LocalPlayer = game.Players.LocalPlayer
        local ReplicatedStorage = game:GetService("ReplicatedStorage")
        local v1532 = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
        local HumanoidRootPart = v1532:WaitForChild("HumanoidRootPart")
        local Humanoid29 = v1532:WaitForChild("Humanoid")

        task.spawn(function()
            ReplicatedStorage.MenuToys.SpawnToyRemoteFunction:InvokeServer("TractorGreen", HumanoidRootPart.CFrame, Vector3.new(0, 97.69, 0))
        end)

        local TractorGreen = workspace:WaitForChild("fartitutatu11SpawnedInToys", 10):WaitForChild("TractorGreen", 5)

        TractorGreen:WaitForChild("VehicleSeat"):Sit(Humanoid29)
        ReplicatedStorage.MenuToys.DestroyToy:FireServer(TractorGreen)
    end
	})
    FunTab:CreateLabel("Hold", "ham")
    auraActive = false
    heldObjects = {}
    failedObjects = {}
    foodModels = {
		"FoodDonut",
		"FoodBread",
		"FoodBanana",
		"FoodBroccoli",
		"FoodCakePink",
		"FoodCoconut",
		"FoodDippyEgg",
		"FoodFrenchFries",
		"FoodHamburger",
		"FoodHotdog",
		"FoodMayonnaise",
		"FoodMeatStick",
		"FoodMushroomPoison",
		"FoodPizzaCheese",
		"FoodPizzaPepperoni",
		"FoodSodaCan",
		"PoopPile",
		"PoopPileSparkle",
		"CupMugWhite",
		"CupMugBrown"
	}
    cachedHoldables = {}
    cacheCount = 0

    function isFoodModel(p287)
        for _, v in ipairs(foodModels) do
            if p287 == v then
                return true
            end
        end

        return false
    end
    function smartFindHoldables()
        local t58 = {}
        local n29 = 0

        for _, child in ipairs(workspace:GetChildren()) do
            if n29 >= 50 then
                return t58
            end

            local v1543 = child:IsA("Model")

            if v1543 then
                v1543 = isFoodModel(child.Name) and child:FindFirstChild("HoldPart")
            end

            if v1543 then
                table.insert(t58, child)
                n29 += 1
            end

            for _, child3 in ipairs(child:GetChildren()) do
                if n29 >= 50 then
                    break
                end

                if child3:IsA("Model") and (isFoodModel(child3.Name) and child3:FindFirstChild("HoldPart")) then
                    table.insert(t58, child3)
                    n29 += 1
                end
            end
        end

        return t58
    end

    local function v135(p288)
        if not p288 or not p288.Parent then
            return false
        end

        if failedObjects[p288] and tick() - failedObjects[p288] < 5 then
            return false
        end

        local HoldPart = p288:FindFirstChild("HoldPart")

        if not HoldPart then
            return false
        end

        local HoldItemRemoteFunction = HoldPart:FindFirstChild("HoldItemRemoteFunction")

        if HoldItemRemoteFunction then
            local success = pcall(function()
                HoldItemRemoteFunction:InvokeServer(p288, t1.value3.Character)
            end)
            if not success then
                failedObjects[p288] = tick()

                return false
            end
            task.wait(0.03)
            local HoldEvents = t2.value9:FindFirstChild("HoldEvents")
            if HoldEvents then
                local Use = HoldEvents:FindFirstChild("Use")

                if Use then
                    pcall(function()
                        Use:FireServer(p288)
                    end)
                end
            end
            heldObjects[p288] = tick()
            failedObjects[p288] = nil

            return true
        end

        return false
    end

    function dropToVoid(p289)
        if not p289 or not p289.Parent then
            heldObjects[p289] = nil

            return
        end

        local HoldPart = p289:FindFirstChild("HoldPart")

        if not HoldPart then
            heldObjects[p289] = nil

            return
        end

        local cFrame = CFrame.new(0, -500, 0)
        local DropItemRemoteFunction = HoldPart:FindFirstChild("DropItemRemoteFunction")

        if DropItemRemoteFunction then
            pcall(function()
                local v2211 = DropItemRemoteFunction
                local v2212 = p289
                local v2213 = cFrame
                local t60 = { Vector3.new(0, 97.69, 0) }

                v2211:InvokeServer(v2212, v2213, v1(t60))
            end)
        end

        heldObjects[p289] = nil
    end

    lastTick = 0
    lastCleanup = 0

    function auraLoop()
        while auraActive do
            local timestamp = tick()

            if timestamp - lastTick < 0.4 then
                t1.value2.Heartbeat:Wait()
            else
                lastTick = timestamp

                if timestamp - lastCleanup > 3 then

                    for v1560, v1561 in pairs(heldObjects) do

                        if not v1560 or not v1560.Parent then
                            heldObjects[v1560] = nil
                        end
                    end
                    for k, v in pairs(failedObjects) do
                        local v1564 = k

                        if not v1564 or (not v1564.Parent or timestamp - v > 10) then
                            failedObjects[v1564] = nil
                        end
                    end
                    lastCleanup = timestamp
                end

                local v1565 = smartFindHoldables()
                local n30 = 0
                local n31 = 0
                local v1568, v1569, v1570 = ipairs(v1565)

                while true do
                    local v1571

                    v1570, v1571 = v1568(v1569, v1570)

                    if not v1570 or (n30 >= 10 or n31 >= 20) then
                        break
                    end

                    n31 += 1

                    if v1571.Parent and not heldObjects[v1571] and v135(v1571) then
                        n30 += 1
                    end
                end

                local n32 = 0

                for k, v in pairs(heldObjects) do
                    local v1575 = k

                    if n32 >= 5 then
                        break
                    end

                    if v1575.Parent and timestamp - v >= 2.7 then
                        dropToVoid(v1575)
                        n32 += 1
                    elseif not v1575.Parent then
                        heldObjects[v1575] = nil
                    end
                end

                t1.value2.Heartbeat:Wait()
            end
        end
    end

    FunTab:CreateToggle({
		Name = "Eat all Food   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">FAST</font>    <font face=\"GothamBlack\" color=\"rgb(0,0,255)\">FOOD</font>    <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Callback = function(p290)
        auraActive = p290

        if not p290 then
            heldObjects = {}
            failedObjects = {}

            return
        end

        heldObjects = {}
        failedObjects = {}
        lastTick = 0
        lastCleanup = 0
        task.spawn(auraLoop)
    end
	})
    instrumentModels = {
		"InstrumentBrassBugle",
		"InstrumentBrassTrumpet",
		"InstrumentBrassVuvuzela",
		"InstrumentDrumBongos",
		"InstrumentDrumSnare",
		"InstrumentGuitarAcoustic",
		"InstrumentGuitarBanjo",
		"InstrumentGuitarLyre",
		"InstrumentGuitarUkulele",
		"InstrumentGuitarViolin",
		"InstrumentPianoKeyboard",
		"InstrumentPianoMelodica",
		"InstrumentVoiceMicrophone",
		"InstrumentWoodwindOcarina",
		"InstrumentWoodwindSaxophone"
	}
    instrumentAuraActive = false
    instrumentHeldObjects = {}
    instrumentFailedObjects = {}

    function isInstrumentModel(p291)
        for _, v in ipairs(instrumentModels) do
            if p291 == v then
                return true
            end
        end

        return false
    end
    function smartFindInstruments()
        local t61 = {}
        local n33 = 0

        for _, child in ipairs(workspace:GetChildren()) do
            if n33 >= 50 then
                return t61
            end

            local v1584 = child:IsA("Model")

            if v1584 then
                v1584 = isInstrumentModel(child.Name) and child:FindFirstChild("HoldPart")
            end

            if v1584 then
                table.insert(t61, child)
                n33 += 1
            end

            local GetChildren = child.GetChildren

            for _, v in ipairs(GetChildren(child)) do
                if n33 >= 50 then
                    break
                end

                if v:IsA("Model") and (isInstrumentModel(v.Name) and v:FindFirstChild("HoldPart")) then
                    table.insert(t61, v)
                    n33 += 1
                end
            end
        end

        return t61
    end

    local function v136(p292)
        if not p292 or not p292.Parent then
            return false
        end

        if instrumentFailedObjects[p292] and tick() - instrumentFailedObjects[p292] < 5 then
            return false
        end

        local HoldPart = p292:FindFirstChild("HoldPart")

        if not HoldPart then
            return false
        end

        local HoldItemRemoteFunction = HoldPart:FindFirstChild("HoldItemRemoteFunction")

        if HoldItemRemoteFunction then
            local success = pcall(function()
                HoldItemRemoteFunction:InvokeServer(p292, t1.value3.Character)
            end)
            if not success then
                instrumentFailedObjects[p292] = tick()

                return false
            end
            task.wait(0.03)
            local HoldEvents = t2.value9:FindFirstChild("HoldEvents")
            if HoldEvents then
                local Use = HoldEvents:FindFirstChild("Use")

                if Use then
                    pcall(function()
                        Use:FireServer(p292)
                    end)
                end
            end
            instrumentHeldObjects[p292] = tick()
            instrumentFailedObjects[p292] = nil

            return true
        end

        return false
    end

    function dropInstrumentToVoid(p293)
        if not p293 or not p293.Parent then
            instrumentHeldObjects[p293] = nil

            return
        end

        local HoldPart = p293:FindFirstChild("HoldPart")

        if not HoldPart then
            instrumentHeldObjects[p293] = nil

            return
        end

        local cFrame = CFrame.new(0, -500, 0)
        local DropItemRemoteFunction = HoldPart:FindFirstChild("DropItemRemoteFunction")

        if DropItemRemoteFunction then
            pcall(function()
                DropItemRemoteFunction:InvokeServer(p293, cFrame, Vector3.new(0, 97.69, 0))
            end)
        end

        instrumentHeldObjects[p293] = nil
    end

    instrumentLastTick = 0
    instrumentLastCleanup = 0

    function instrumentAuraLoop()
        while instrumentAuraActive do
            local timestamp = tick()

            if timestamp - instrumentLastTick < 0.4 then
                t1.value2.Heartbeat:Wait()
            else
                instrumentLastTick = timestamp

                if timestamp - instrumentLastCleanup > 3 then

                    for v1602, v1603 in pairs(instrumentHeldObjects) do

                        if not v1602 or not v1602.Parent then
                            instrumentHeldObjects[v1602] = nil
                        end
                    end
                    for k, v in pairs(instrumentFailedObjects) do
                        local v1606 = k

                        if not v1606 or (not v1606.Parent or timestamp - v > 10) then
                            instrumentFailedObjects[v1606] = nil
                        end
                    end
                    instrumentLastCleanup = timestamp
                end

                local v1607 = smartFindInstruments()
                local n34 = 0
                local n35 = 0
                local v1610, v1611, v1612 = ipairs(v1607)

                while true do
                    local v1613

                    v1612, v1613 = v1610(v1611, v1612)

                    if not v1612 or (n34 >= 10 or n35 >= 20) then
                        break
                    end

                    n35 += 1

                    if v1613.Parent and not instrumentHeldObjects[v1613] and v136(v1613) then
                        n34 += 1
                    end
                end

                local n36 = 0

                for k, v in pairs(instrumentHeldObjects) do
                    local v1617 = k

                    if n36 >= 5 then
                        break
                    end

                    if v1617.Parent and timestamp - v >= 2.7 then
                        dropInstrumentToVoid(v1617)
                        n36 += 1
                    elseif not v1617.Parent then
                        instrumentHeldObjects[v1617] = nil
                    end
                end

                t1.value2.Heartbeat:Wait()
            end
        end
    end

    FunTab:CreateToggle({
		Name = "Use all Instruments    <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">FAST</font>    <font face=\"GothamBlack\" color=\"rgb(0,255,0)\">INSTRUMENT</font>  <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
		CurrentValue = false,
		Callback = function(p294)
        instrumentAuraActive = p294

        if not p294 then
            instrumentHeldObjects = {}
            instrumentFailedObjects = {}

            return
        end

        instrumentHeldObjects = {}
        instrumentFailedObjects = {}
        instrumentLastTick = 0
        instrumentLastCleanup = 0
        task.spawn(instrumentAuraLoop)
    end
	})
    player = t2.value96.LocalPlayer
    activeForm = nil
    formEnabled = false
    copyMovementEnabled = false
    currentPreset = "Penis Head"
    scriptRagdollToy = nil
    ragdollMonitor = nil
    RAGDOLL_UNIQUE_ID = nil
    isRespawning = false
    formDistance = 10
    formOrientation = 0

    local vector3 = Vector3.new(0, -10, 0)
    local cFrame = CFrame.Angles(0, 0, 0)
    local t63 = {
		pos = vector3,
		rot = cFrame
	}
    local vector3_10 = Vector3.new(0, 3, 0)
    local cFrame2 = CFrame.Angles(0, 0, 1.5707963267948966)
    local t64 = {
		pos = vector3_10,
		rot = cFrame2
	}
    local vector3_11 = Vector3.new(0, 0, 0)
    local cFrame3 = CFrame.Angles(0, 0, -1.5707963267948966)
    local t65 = {
		pos = vector3_11,
		rot = cFrame3
	}
    local vector3_12 = Vector3.new(1.75, 0, 0)
    local cFrame4 = CFrame.Angles(0, 0, 0)
    local t66 = {
		pos = vector3_12,
		rot = cFrame4
	}
    local vector3_13 = Vector3.new(-1, 0, 0)
    local cFrame5 = CFrame.Angles(0, 0, 0)
    local t67 = {
		pos = vector3_13,
		rot = cFrame5
	}
    local vector3_14 = Vector3.new(0, 4, 0)
    local cFrame6 = CFrame.Angles(0, 3.141592653589793, 0)

    t68 = {
		Torso = t63,
		["Right Arm"] = t64,
		["Left Arm"] = t65,
		["Right Leg"] = t66,
		["Left Leg"] = t67,
		Head = {
			pos = vector3_14,
			rot = cFrame6
		}
	}
end
local t74, t80
do
    local vector3 = Vector3.new(0, -10, 0)
    local cFrame = CFrame.Angles(0, 0, 0)
    local t69 = {
		pos = vector3,
		rot = cFrame
	}
    local vector3_15 = Vector3.new(0, 3, 0)
    local cFrame7 = CFrame.Angles(0, 0, 1.5707963267948966)
    local t70 = {
		pos = vector3_15,
		rot = cFrame7
	}
    local vector3_16 = Vector3.new(0, 0, 0)
    local cFrame8 = CFrame.Angles(0, 0, -1.5707963267948966)
    local t71 = {
		pos = vector3_16,
		rot = cFrame8
	}
    local vector3_17 = Vector3.new(0, -10, 0)
    local cFrame9 = CFrame.Angles(0, 0, 0)
    local t72 = {
		pos = vector3_17,
		rot = cFrame9
	}
    local vector3_18 = Vector3.new(-1, 0, 0)
    local cFrame10 = CFrame.Angles(0, 0, 0)
    local t73 = {
		pos = vector3_18,
		rot = cFrame10
	}
    local vector3_19 = Vector3.new(0, -10, 0)
    local cFrame11 = CFrame.Angles(0, 0, 0)

    t74 = {
		Torso = t69,
		["Right Arm"] = t70,
		["Left Arm"] = t71,
		["Right Leg"] = t72,
		["Left Leg"] = t73,
		Head = {
			pos = vector3_19,
			rot = cFrame11
		}
	}

    local vector3_20 = Vector3.new(0, 0, 0)
    local cFrame12 = CFrame.Angles(0, 0, 0)
    local t75 = {
		pos = vector3_20,
		rot = cFrame12
	}
    local vector3_21 = Vector3.new(0, -1, 0)
    local cFrame13 = CFrame.Angles(0, 0, v1({ math.rad(90) }))
    local t76 = {
		pos = vector3_21,
		rot = cFrame13
	}
    local vector3_22 = Vector3.new(0, -1, 0)
    local cFrame14 = CFrame.Angles(0, 0, v1({ math.rad(90) }))
    local t77 = {
		pos = vector3_22,
		rot = cFrame14
	}
    local vector3_23 = Vector3.new(0, -1, 0)
    local cFrame15 = CFrame.Angles(0, 0, 1.5707963267948966)
    local t78 = {
		pos = vector3_23,
		rot = cFrame15
	}
    local vector3_24 = Vector3.new(0, -1, 0)
    local cFrame16 = CFrame.Angles(0, 0, 1.5707963267948966)
    local t79 = {
		pos = vector3_24,
		rot = cFrame16
	}
    local vector3_25 = Vector3.new(0, 1.5, 0)
    local cFrame17 = CFrame.Angles(0, 0, 0)

    t80 = {
		Torso = t75,
		["Right Arm"] = t76,
		["Left Arm"] = t77,
		["Right Leg"] = t78,
		["Left Leg"] = t79,
		Head = {
			pos = vector3_25,
			rot = cFrame17
		}
	}
end
local vector3 = Vector3.new(0, -1, 0)
local cFrame = CFrame.Angles(4.71238898038469, 0, 0)
local t81 = {
	pos = vector3,
	rot = cFrame
}
local vector3_26 = Vector3.new(-1, -2.5, 1)
local cFrame18 = CFrame.Angles(3.141592653589793, 0, 1.5707963267948966)
local t82 = {
	pos = vector3_26,
	rot = cFrame18
}
local vector3_27 = Vector3.new(1, -2.5, 1)
local cFrame19 = CFrame.Angles(3.141592653589793, 0, 1.5707963267948966)
local t83 = {
	pos = vector3_27,
	rot = cFrame19
}
local vector3_28 = Vector3.new(1, -2, -1)
local cFrame20 = CFrame.Angles(0, 0, 1.5707963267948966)
local t84 = {
	pos = vector3_28,
	rot = cFrame20
}
local vector3_29 = Vector3.new(-1, -2, -1)
local cFrame21 = CFrame.Angles(0, 0, 1.5707963267948966)
local t85 = {
	pos = vector3_29,
	rot = cFrame21
}
local vector3_30 = Vector3.new(0, 0, -1)
local cFrame22 = CFrame.Angles(0, 0, 0)
local t86 = {
	Torso = t81,
	["Right Arm"] = t82,
	["Left Arm"] = t83,
	["Right Leg"] = t84,
	["Left Leg"] = t85,
	Head = {
		pos = vector3_30,
		rot = cFrame22
	}
}
local vector3_31 = Vector3.new(0, 0, 0)
local cFrame23 = CFrame.Angles(0, 0, 0 )
local t87 = {
	pos = vector3_31,
	rot = cFrame23
}
local vector3_32 = Vector3.new(0.5, 0, 0)
local cFrame24 = CFrame.Angles(0, 0, 0)
local t88 = {
	pos = vector3_32,
	rot = cFrame24
}
local vector3_33 = Vector3.new(0.5, 0, 0)
local cFrame25 = CFrame.Angles(0, 0, 0)
local t89 = {
	pos = vector3_33,
	rot = cFrame25
}
local vector3_34 = Vector3.new(0.5, 0, 0)
local cFrame26 = CFrame.Angles(0, 0, 0)
local t90 = {
	pos = vector3_34,
	rot = cFrame26
}
local vector3_35 = Vector3.new(0.5, 0, 0)
local cFrame27 = CFrame.Angles(0, 0, 0)
local t91 = {
	pos = vector3_35,
	rot = cFrame27
}
local vector3_36 = Vector3.new(0, 0, 0)
local cFrame28 = CFrame.Angles(0, 0, 0)
local t92 = {
	pos = vector3_36,
	rot = cFrame28
}
formPresets = {
	["Penis Head"] = t68,
	["L Shape"] = t74,
	["Ice Cream"] = t80,
	Dog = t86,
	Square = {
		Torso = t87,
		["Right Arm"] = t88,
		["Left Arm"] = t89,
		["Right Leg"] = t90,
		["Left Leg"] = t91,
		Head = t92
	}
}
function toy_spawn(p295, p296, p297)
    local v1622 = typeof(p297) == "string" and (string.lower(p297) == "headup" and CFrame.new(p296.Position + Vector3.new(0, 1, 0), p296.Position) * CFrame.Angles(3.141592653589793, 0, 0)) or p296
    task.spawn(function()
        SpawnToyRF:InvokeServer(p295, v1622, typeof(p297) == "Vector3" and p297 or Vector3.zero)
    end)
    local timestamp = tick()
    local u1624
    local connection = BackPack.ChildAdded:Connect(function(child)
        if child.Name == p295 then
            u1624 = child
        end
    end)
    if not u1624 then
        if not (tick() - timestamp > 5) then
        end
    end
    repeat
        task.wait()
    until u1624 or tick() - timestamp > 5
    connection:Disconnect()

    return u1624
end
function UpdateRagdollPalletMenu()
    task.spawn(function()
        local PlayerGui = player:FindFirstChild("PlayerGui")
        if not PlayerGui then
            return
        end
        local MenuGui = PlayerGui:FindFirstChild("MenuGui")
        if not MenuGui or (not scriptRagdollToy or not scriptRagdollToy:FindFirstChild("ScriptRagdollID")) then
            return
        end
        local Contents = MenuGui.Menu.TabContents.ToyDestroy.Contents
        local ScriptRagdollIDValue = scriptRagdollToy.ScriptRagdollID.Value
        local t93 = {}
        local v2221, v2222, v2223 = ipairs(BackPack:GetChildren())
        local g2230
        while true do
            local v2224

            v2223, v2224 = v2221(v2222, v2223)

            if not v2223 then
                break
            end

            if v2224.Name == "RagdollPallet" or v2224.Name == "PalletLightBrown" then
                table.insert(t93, v2224)
            end
        end
        local n37 = 0
        local v2226, v2227, v2228 = ipairs(t93)
        repeat
            local v2229

            v2228, v2229 = v2226(v2227, v2228)

            if not v2228 then
                g2230 = true
            end

            if g2230 then
                break
            end
        until v2229:FindFirstChild("ScriptRagdollID") and ScriptRagdollIDValue == v2229.ScriptRagdollID.Value
        if not g2230 then
            n37 = v2228
        end
        g2230 = false
        if n37 == 0 then
            return
        end
        local n38 = 0
        for _, child in ipairs(Contents:GetChildren()) do
            if not (child.Name == "PalletLightBrown" and child:FindFirstChild("ViewItemButton")) then
                continue
            end

            n38 += 1

            if n38 == n37 then
                local ViewItemButton = child.ViewItemButton

                ViewItemButton.Text = "Ragdoll Controller (DO NOT DELETE)"
                ViewItemButton.TextScaled = true

                if ViewItemButton:FindFirstChild("LowResImage") then
                    ViewItemButton.LowResImage.Image = ""
                end

                return
            end
        end
    end)
end
function t2.value186()
    if not formEnabled or (scriptRagdollToy or isRespawning) then
        return
    end

    isRespawning = true

    local guid = HttpService:GenerateGUID(false)

    for _ = 1, 5 do
        local v1628 = player.Character and player.Character:FindFirstChild("Head")

        if not v1628 then
            isRespawning = false

            return
        end

        local v1629 = toy_spawn("PalletLightBrown", v1628, "headup")

        if v1629 then
            local StringValue = Instance.new("StringValue")

            StringValue.Name = "ScriptRagdollID"
            StringValue.Value = guid
            StringValue.Parent = v1629
            v1629.Name = "RagdollPallet"

            local SoundPart = v1629:WaitForChild("SoundPart", 5)

            if SoundPart then
                task.spawn(function()
                    while formEnabled and (SoundPart and SoundPart.Parent) do
                        if not SoundPart:FindFirstChild("PartOwner") or SoundPart.PartOwner.Value ~= player.Name then
                            SetNetworkOwner:FireServer(SoundPart, SoundPart.CFrame)
                        end

                        task.wait(0.05)
                    end
                end)

                local BodyVelocity = Instance.new("BodyVelocity", SoundPart)

                BodyVelocity.MaxForce = Vector3.new(0, 1e999, 0)
                BodyVelocity.Velocity = Vector3.new(0, 1000, 0)

                for _, child in pairs(v1629:GetChildren()) do
                    if child:IsA("BasePart") then
                        child.Transparency = 1
                        child.Size = Vector3.new(0.5, 0.5, 0.5)
                        child.CanCollide = false
                    end
                end

                if SoundPart:FindFirstChild("Wood") then
                    SoundPart.Wood:Destroy()
                end

                scriptRagdollToy = v1629
                RAGDOLL_UNIQUE_ID = guid
                isRespawning = false
                UpdateRagdollPalletMenu()

                return
            end
        end

        task.wait(0.3)
    end

    isRespawning = false
end
function DestroyRagdoll()
    if scriptRagdollToy and scriptRagdollToy.Parent then
        pcall(function()
            DestroyToyRF:FireServer(scriptRagdollToy)
        end)
        task.wait(0.1)
    end

    scriptRagdollToy = nil
end
function StartRagdollMonitor()
    if ragdollMonitor then
        task.cancel(ragdollMonitor)
    end

    ragdollMonitor = task.spawn(function()
        while formEnabled do
            task.wait(1)

            local v2235 = not scriptRagdollToy

            if not v2235 then
                v2235 = not scriptRagdollToy.Parent or (not scriptRagdollToy:FindFirstChild("ScriptRagdollID") or scriptRagdollToy.ScriptRagdollID.Value ~= RAGDOLL_UNIQUE_ID)
            end

            if v2235 then
                scriptRagdollToy = nil
                t2.value186()
            end
        end
    end)
end
BackPack.ChildAdded:Connect(function(child)
    if not formEnabled then
        return
    end

    task.wait(0.05)

    if child:FindFirstChild("ScriptRagdollID") and (child.ScriptRagdollID.Value == RAGDOLL_UNIQUE_ID and child.Parent) then
        scriptRagdollToy = child
        UpdateRagdollPalletMenu()
    end
end)
BackPack.ChildRemoved:Connect(function(child)
    if formEnabled and child == scriptRagdollToy then
        scriptRagdollToy = nil
        task.wait(0.5)

        if formEnabled and not scriptRagdollToy then
            t2.value186()
        end
    end
end)
function GetGrabbedCharacter()
    local GrabParts = workspace:FindFirstChild("GrabParts")

    if not GrabParts then
        return nil
    end

    local GrabPart = GrabParts:FindFirstChild("GrabPart")

    if not GrabPart then
        return nil
    end

    local v1639 = GrabPart:FindFirstChildOfClass("WeldConstraint") or GrabPart:FindFirstChild("Weld")

    return v1639 and (v1639.Part1 and v1639.Part1:FindFirstAncestorOfClass("Model"))
end
function RestoreCollisions(p298)
    if not p298 then
        return
    end

    if p298.torso and p298.torso.Parent then
        p298.torso.CanCollide = true
    end

    if p298.head and p298.head.Parent then
        p298.head.CanCollide = true
    end

    if p298.hrp and p298.hrp.Parent then
        p298.hrp.CanCollide = true
    end

    for _, v in ipairs(p298.limbs) do
        if v.part and v.part.Parent then
            v.part.CanCollide = true
        end
    end
end
function ApplyNoclipToForm(p299)
    if p299.torso and p299.torso.Parent then
        p299.torso.CanCollide = false
    end

    if p299.head and p299.head.Parent then
        p299.head.CanCollide = false
    end

    if p299.hrp and p299.hrp.Parent then
        p299.hrp.CanCollide = false
    end

    for _, v in ipairs(p299.limbs) do
        if v.part and v.part.Parent then
            v.part.CanCollide = false
        end
    end
end
function GetCharacterParts(p300)
    if not p300 then
        return nil
    end

    local Torso = p300:FindFirstChild("Torso")

    if not Torso then
        return nil
    end

    local t94 = {}

    for _, v in ipairs({
		"Left Arm",
		"Right Arm",
		"Left Leg",
		"Right Leg"
	}) do
        local v16 = p300:FindFirstChild(v)

        if v16 then
            local RagdollLimbPart = v16:FindFirstChild("RagdollLimbPart")

            if RagdollLimbPart and RagdollLimbPart:IsA("BasePart") then
                table.insert(t94, {
					part = RagdollLimbPart,
					name = v
				})
            end
        end
    end

    local Head = p300:FindFirstChild("Head")
    local HumanoidRootPart = p300:FindFirstChild("HumanoidRootPart")

    return {
		torso = Torso,
		head = Head,
		hrp = HumanoidRootPart,
		limbs = t94
	}
end
function t2.value187()
    local Character = player.Character

    if not Character then
        return
    end

    local v1656 = Character:FindFirstChild("Torso") or (Character:FindFirstChild("UpperTorso") or Character:FindFirstChild("HumanoidRootPart"))

    if not v1656 then
        return
    end

    local parts = activeForm.parts

    if parts.hrp and parts.hrp.Parent then
        parts.hrp.CFrame = CFrame.new(0, 0, 0)
        parts.hrp.AssemblyLinearVelocity = Vector3.zero
        parts.hrp.AssemblyAngularVelocity = Vector3.zero
    end

    local Unit = Vector3.new(v1656.CFrame.LookVector.X, 0, v1656.CFrame.LookVector.Z).Unit
    local v1659 = Vector3.new(v1656.Position.X, v1656.Position.Y, v1656.Position.Z) + Unit * formDistance
    local v1660 = CFrame.new(v1659, v1659 + Unit) * CFrame.Angles(0, math.rad(formOrientation), 0)

    ApplyNoclipToForm(parts)
    parts.torso.AssemblyLinearVelocity = Vector3.zero
    parts.torso.AssemblyAngularVelocity = Vector3.zero
    parts.torso.Anchored = false
    parts.torso.CFrame = v1660

    if parts.head and parts.head.Parent then
        local Head = Character:FindFirstChild("Head")

        if Head then
            parts.head.AssemblyLinearVelocity = Vector3.zero
            parts.head.AssemblyAngularVelocity = Vector3.zero
            parts.head.Anchored = false
            parts.head.CFrame = v1660 * v1656.CFrame:ToObjectSpace(Head.CFrame)
        end
    end

    local v1662 = Character:FindFirstChild("Left Arm") or Character:FindFirstChild("LeftUpperArm")
    local v1663 = Character:FindFirstChild("Right Arm") or Character:FindFirstChild("RightUpperArm")
    local v1664 = Character:FindFirstChild("Left Leg") or Character:FindFirstChild("LeftUpperLeg")
    local v1665 = Character:FindFirstChild("Right Leg") or Character:FindFirstChild("RightUpperLeg")

    limbMap = {
		["Left Arm"] = v1662,
		["Right Arm"] = v1663,
		["Left Leg"] = v1664,
		["Right Leg"] = v1665
	}

    for _, v in ipairs(parts.limbs) do
        local v1668 = limbMap[v.name]

        if v.part and (v.part.Parent and v1668) then
            v.part.AssemblyLinearVelocity = Vector3.zero
            v.part.AssemblyAngularVelocity = Vector3.zero
            v.part.Anchored = false

            local v1669 = v1656.CFrame:ToObjectSpace(v1668.CFrame)

            v.part.CFrame = v1660 * v1669 * CFrame.Angles(0, 1.5707963267948966, 4.71238898038469) * CFrame.new(0.4, 0, 0)
        end
    end
end
function ApplyForm()
    if not activeForm or not formEnabled then
        return
    end

    local Head = activeForm.char:FindFirstChild("Head")

    if not Head or not Head:FindFirstChild("PartOwner") then
        return
    end

    if copyMovementEnabled then
        t2.value187()

        return
    end

    local parts = activeForm.parts
    local Character = player.Character

    if not Character then
        return
    end

    local v1673 = Character:FindFirstChild("Torso") or Character:FindFirstChild("HumanoidRootPart")

    if not v1673 or (not parts.torso or not parts.torso.Parent) then
        return
    end

    if parts.hrp and parts.hrp.Parent then
        parts.hrp.CFrame = CFrame.new(0, 0, 0)
        parts.hrp.AssemblyLinearVelocity = Vector3.zero
        parts.hrp.AssemblyAngularVelocity = Vector3.zero
    end

    local Unit = Vector3.new(v1673.CFrame.LookVector.X, 0, v1673.CFrame.LookVector.Z).Unit
    local v1675 = Vector3.new(v1673.Position.X, v1673.Position.Y, v1673.Position.Z) + Unit * formDistance
    local v1676 = CFrame.new(v1675, v1675 + Unit) * CFrame.Angles(0, math.rad(formOrientation), 0)
    local v1677 = formPresets[currentPreset]

    ApplyNoclipToForm(parts)
    parts.torso.AssemblyLinearVelocity = Vector3.zero
    parts.torso.AssemblyAngularVelocity = Vector3.zero
    parts.torso.Anchored = false
    parts.torso.CFrame = v1676 * CFrame.new(v1677.Torso.pos) * v1677.Torso.rot

    if parts.head and parts.head.Parent then
        parts.head.AssemblyLinearVelocity = Vector3.zero
        parts.head.AssemblyAngularVelocity = Vector3.zero
        parts.head.Anchored = false
        parts.head.CFrame = v1676 * CFrame.new(v1677.Head.pos) * v1677.Head.rot
    end

    for _, v in ipairs(parts.limbs) do
        if v.part and v.part.Parent then
            v.part.AssemblyLinearVelocity = Vector3.zero
            v.part.AssemblyAngularVelocity = Vector3.zero
            v.part.Anchored = false

            local v1680 = v1677[v.name]

            if v1680 then
                v.part.CFrame = v1676 * CFrame.new(v1680.pos) * v1680.rot
            end
        end
    end
end
function SetupForm(p301)
    if not formEnabled then
        return
    end

    local Humanoid30 = p301:FindFirstChildOfClass("Humanoid")

    if not Humanoid30 then
        return
    end

    task.wait(0.3)

    local v1683 = GetCharacterParts(p301)

    if not v1683 then
        return
    end

    activeForm = {
		char = p301,
		parts = v1683,
		isGrabbed = true,
		connection = nil
	}
    task.spawn(function()
        while activeForm and (activeForm.char == p301 and (p301.Parent and formEnabled)) do
            local Head = p301:FindFirstChild("Head")

            if not Head or (not Head:FindFirstChild("PartOwner") or Head.PartOwner.Value ~= player.Name) then
                local v2237 = player.Character and player.Character:FindFirstChild("HumanoidRootPart")

                if Head and (v2237 and (v2237.Position - Head.Position).Magnitude <= 60) then
                    SetNetworkOwner:FireServer(Head, Head.CFrame)
                end
            end

            local Ragdolled = Humanoid30:FindFirstChild("Ragdolled")

            if Ragdolled and (not Ragdolled.Value and scriptRagdollToy) then
                local SoundPart = scriptRagdollToy:FindFirstChild("SoundPart")

                if SoundPart and Head then
                    firetouchinterest(SoundPart, Head, 0)
                    task.wait()
                    firetouchinterest(SoundPart, Head, 1)
                end
            end

            task.wait(0.1)
        end
    end)
    activeForm.connection = t1.value2.Heartbeat:Connect(function()
        if not formEnabled then
            return
        end

        local v2240 = GetGrabbedCharacter()

        activeForm.isGrabbed = v2240 == p301
        ApplyForm()
    end)
end
function StopCurrentForm()
    if activeForm then
        if activeForm.parts then
            RestoreCollisions(activeForm.parts)
        end

        if activeForm.connection then
            activeForm.connection:Disconnect()
        end
    end

    activeForm = nil
end
FormTab:CreateLabel("Form Grab", "Hand")
FormTab:CreateToggle({
	Name = "Enable Form Grab   <font face=\"GothamBlack\" color=\"rgb(240,184,111)\">PALLET</font>   <font face=\"GothamBlack\" color=\"rgb(0,140,255)\">RAGDOLL</font>",
	CurrentValue = false,
	Flag = "FormGrabToggle",
	Callback = function(p302)
    formEnabled = p302

    if p302 then
        t2.value186()
        StartRagdollMonitor()

        return
    end

    StopCurrentForm()
    DestroyRagdoll()

    if ragdollMonitor then
        task.cancel(ragdollMonitor)
        ragdollMonitor = nil
    end
end
})
FormTab:CreateSlider({
	Name = "Distance   <font face=\"GothamBlack\" color=\"rgb(0,184,111)\">STUDS</font>",
	Range = {
		0,
		20
	},
	Increment = 1,
	CurrentValue = 10,
	Flag = "FormDistance",
	Callback = function(p303)
    formDistance = p303
end
})
FormTab:CreateSlider({
	Name = "Orientation\t  <font face=\"GothamBlack\" color=\"rgb(0,255,15)\">ROTATION</font>",
	Range = {
		0,
		360
	},
	Increment = 5,
	CurrentValue = 0,
	Flag = "FormOrientation",
	Callback = function(p304)
    formOrientation = p304
end
})
FormTab:CreateDropdown({
	Name = "Form   <font face=\"GothamBlack\" color=\"rgb(0,59,255)\">DROPTOWN</font>",
	Options = {
		"Penis Head",
		"L Shape",
		"Ice Cream",
		"Dog",
		"Square"
	},
	CurrentOption = { "Penis Head" },
	Flag = "FormPreset",
	Callback = function(p305)
    if copyMovementEnabled then
        return
    end

    currentPreset = p305[1]
end
})
FormTab:CreateToggle({
	Name = "Copy Movement\t<font face=\"GothamBlack\" color=\"rgb(240,140,0)\">TUFF</font>\t  <font face=\"GothamBlack\" color=\"rgb(39,245,218)\">PREMIUM</font>",
	CurrentValue = false,
	Flag = "CopyMovement",
	Callback = function(p306)
    copyMovementEnabled = p306
end
})
FormTab:CreateButton({
	Name = "Drop Current Target\t  <font face=\"GothamBlack\" color=\"rgb(255,5,8)\">STOP</font>",
	Callback = function()
    StopCurrentForm()
end
})
FormTab:CreateParagraph({
	Title = "NOTE",
	Content = "DO   <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">NOT ENABLE</font>   Form Grab in House.  Form Grab Work on <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">NPC</font> and <font face=\"GothamBlack\" color=\"rgb(255,0,0)\">PLAYER</font>"
})
coroutine.wrap(function()
    while task.wait(0.1) do
        if formEnabled then
            pcall(function()
                local v2241 = GetGrabbedCharacter()

                if v2241 and not activeForm then
                    SetupForm(v2241)
                end

                if activeForm and not activeForm.char or not activeForm.char.Parent then
                    t2.value6:Notify({
						Title = "ERROR",
						Image = "x",
						Content = "Target Lost",
						Duration = 3
					})
                    StopCurrentForm()

                    return
                end

                if activeForm and activeForm.char then
                    local Character = player.Character
                    local Head = activeForm.char:FindFirstChild("Head")

                    if Character and Head then
                        local HumanoidRootPart = Character:FindFirstChild("HumanoidRootPart")

                        if HumanoidRootPart and (HumanoidRootPart.Position - Head.Position).Magnitude > 30 then
                            t2.value6:Notify({
								Title = "ERROR",
								Image = "x",
								Content = "Target exceeded 30 studs - Drop",
								Duration = 3
							})
                            StopCurrentForm()

                            return
                        end
                    end
                end

                if activeForm and activeForm.char then
                    local player30 = t2.value96:GetPlayerFromCharacter(activeForm.char)

                    if player30 then
                        local v2246 = workspace:FindFirstChild("Players") and workspace.Players:FindFirstChild(player30.Name)

                        if v2246 then
                            local InPlot = v2246:FindFirstChild("InPlot")

                            if InPlot and InPlot.Value == true then
                                t2.value6:Notify({
									Title = "ERROR",
									Image = "x",
									Content = "Target in plot - Drop",
									Duration = 3
								})
                                StopCurrentForm()

                                return
                            end
                        end

                        local InPlot = player30:FindFirstChild("InPlot")

                        if InPlot and InPlot.Value == true then
                            t2.value6:Notify({
								Title = "ERROR",
								Image = "x",
								Content = "Target in plot - Drop",
								Duration = 3
							})
                            StopCurrentForm()

                            return
                        end
                    end
                end
            end)
        end
    end
end)()
player.CharacterAdded:Connect(function()
    if activeForm and activeForm.connection then
        activeForm.connection:Disconnect()
    end

    activeForm = nil
end)
notify("Bloody [PREMIUM]", "V2")
