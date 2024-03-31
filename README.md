local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Templarios Hub", HidePremium = false, SaveConfig = false, ConfigFolder = "AdmBrookhaven"})
 
local Tab = Window:MakeTab({
    Name = "Scripts",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
local Tab2 = Window:MakeTab({
    Name = "Tools",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
local Tab3 = Window:MakeTab({
    Name = "Kill",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
 local Tab4 = Window:MakeTab({
    Name = "Trolar",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
 local Tab5 = Window:MakeTab({
    Name = "Avatar",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
 local Tab6 = Window:MakeTab({
    Name = "Rejoin",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
 local Tab7 = Window:MakeTab({
    Name = "Segredos",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
Tab:AddButton({
    Name = "Executar Infinite Yield",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
    end
})
 
 Tab:AddButton({
    Name = "Executar Nameless (Risco de ban)",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Nameless-Admin-FE-11243"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Ice Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/JulHubz/JulHub/main/JulHub"))()
    end
})
 
Tab:AddButton({
    Name = "Executar RedzHub",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-RedZHub-9326"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Clone Speed",
    Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe/main/obf_11l7Y131YqJjZ31QmV5L8pI23V02b3191sEg26E75472Wl78Vi8870jRv5txZyL1.lua.txt"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Vfly",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-VFly-script-8160"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Fly V3",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Fly-v3-7412"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Shift Lock",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Permanent-Shiftlock-7513"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Emote",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Ragdoll-Engine-BEST-SCRIPT-WORKING-SystemBroken-7544"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Chat Admin",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/game-hax/uca/main/release/uca.min.lua"))()
    end
})
 
 Tab:AddButton({
    Name = "Executar Ghost Hub",
    Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
    end
})
 
 Tab:AddButton({
    Name = "Executar Brookhaven R4D",
    Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/M1ZZ001/BrookhavenR4D/main/Brookhaven%20R4D%20Script'))()
    end
})
 
Tab2:AddButton({
    Name = "TpTool",
    Callback = function()
        mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "Equip to Click TP"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack
    end
})
 
Tab2:AddButton({
    Name = "Punch Fling",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Fe-Punch-Tool-7383"))()
    end
})
 
Tab2:AddButton({
    Name = "Pegar Sofa",
    Callback = function()
        local args = {
    [1] = "PickingTools",
    [2] = "Couch"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Too1l"):InvokeServer(unpack(args))
 
    end
})
 
 Tab2:AddButton({
    Name = "Telekinesis",
    Callback = function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/SAZXHUB/Control-update/main/README.md'),true))()
    end
})
 
 Tab2:AddButton({
    Name = "Remover Todos Os Items",
    Callback = function()
        local args = {
    [1] = "ClearAllTools"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clea1rTool1s"):FireServer(unpack(args))

    end
})
 
Tab3:AddButton({
    Name = "Kill Troll By Serpent X (Kill Principal)",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/KillTrollByDefense.dev/main/Troll.lua"))()
    end
})
 
Tab3:AddButton({
    Name = "Fling All",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/zqyDSUWX"))()
    end
})

Tab4:AddButton({
    Name = "Ficar Super Pequeno",
    Callback = function()
        local args = {
    [1] = "CharacterSizeDown",
    [2] = 4
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

    end
})

Tab4:AddButton({
    Name = "Voltar para o tamanho normal",
    Callback = function()
        local args = {
    [1] = "CharacterSizeUp",
    [2] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

    end
})
local args = {
    [1] = "CharacterSizeUp",
    [2] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args)) Tab5:AddButton({
    Name = "FE Headless (By RedzHub)",
    Callback = function()
        local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 134082579
    },
    [3] = "by:REDz"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))

    end
}) Tab5:AddButton({
    Name = "FE Korblox (By RedzHub)",
    Callback = function()
        local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "by:REDz"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))

    end
})

Tab5:AddButton({
    Name = "FE R6 Animation",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-from-R15-to-R6-9639"))()
    end
})

Tab5:AddButton({
    Name = "Ficar Com a Roupa Dos Templarios",
    Callback = function()
        local args = {
    [1] = "AskIfIdAvailable",
    [2] = "15388922202"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

    end
})

Tab6:AddButton({
    Name = "Rejoin",
    Callback = function()
        -- Função para rejoin
function rejoin()
    game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
end

-- Chame a função para reentrar no jogo
rejoin()

    end
})

Tab7:AddButton({
    Name = "Teleportar Para O Portal",
    Callback = function()
        local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Templarios Hub", HidePremium = false, SaveConfig = false, ConfigFolder = "AdmBrookhaven"})
 
local Tab = Window:MakeTab({
    Name = "Scripts",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
local Tab2 = Window:MakeTab({
    Name = "Tools",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
local Tab3 = Window:MakeTab({
    Name = "Kill",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
 local Tab4 = Window:MakeTab({
    Name = "Trolar",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
 local Tab5 = Window:MakeTab({
    Name = "Avatar",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
 local Tab6 = Window:MakeTab({
    Name = "Rejoin",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
 
Tab:AddButton({
    Name = "Executar Infinite Yield",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
    end
})
 
 Tab:AddButton({
    Name = "Executar Nameless (Risco de ban)",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Nameless-Admin-FE-11243"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Ice Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/JulHubz/JulHub/main/JulHub"))()
    end
})
 
Tab:AddButton({
    Name = "Executar RedzHub",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-RedZHub-9326"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Clone Speed",
    Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe/main/obf_11l7Y131YqJjZ31QmV5L8pI23V02b3191sEg26E75472Wl78Vi8870jRv5txZyL1.lua.txt"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Vfly",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-VFly-script-8160"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Fly V3",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Fly-v3-7412"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Shift Lock",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Permanent-Shiftlock-7513"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Emote",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Ragdoll-Engine-BEST-SCRIPT-WORKING-SystemBroken-7544"))()
    end
})
 
Tab:AddButton({
    Name = "Executar Chat Admin",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/game-hax/uca/main/release/uca.min.lua"))()
    end
})
 
 Tab:AddButton({
    Name = "Executar Ghost Hub",
    Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
    end
})
 
 Tab:AddButton({
    Name = "Executar Brookhaven R4D",
    Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/M1ZZ001/BrookhavenR4D/main/Brookhaven%20R4D%20Script'))()
    end
})
 
Tab2:AddButton({
    Name = "TpTool",
    Callback = function()
        mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "Equip to Click TP"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack
    end
})
 
Tab2:AddButton({
    Name = "Punch Fling",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Fe-Punch-Tool-7383"))()
    end
})
 
Tab2:AddButton({
    Name = "Pegar Sofa",
    Callback = function()
        local args = {
    [1] = "PickingTools",
    [2] = "Couch"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Too1l"):InvokeServer(unpack(args))
 
    end
})
 
 Tab2:AddButton({
    Name = "Telekinesis",
    Callback = function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/SAZXHUB/Control-update/main/README.md'),true))()
    end
})
 
 Tab2:AddButton({
    Name = "Remover Todos Os Items",
    Callback = function()
        local args = {
    [1] = "ClearAllTools"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clea1rTool1s"):FireServer(unpack(args))

    end
})
 
Tab3:AddButton({
    Name = "Kill Troll By Serpent X (Kill Principal)",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/KillTrollByDefense.dev/main/Troll.lua"))()
    end
})
 
Tab3:AddButton({
    Name = "Fling All",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/zqyDSUWX"))()
    end
})

Tab4:AddButton({
    Name = "Ficar Super Pequeno",
    Callback = function()
        local args = {
    [1] = "CharacterSizeDown",
    [2] = 4
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

    end
})

Tab4:AddButton({
    Name = "Voltar para o tamanho normal",
    Callback = function()
        local args = {
    [1] = "CharacterSizeUp",
    [2] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

    end
})
local args = {
    [1] = "CharacterSizeUp",
    [2] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args)) Tab5:AddButton({
    Name = "FE Headless (By RedzHub)",
    Callback = function()
        local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 134082579
    },
    [3] = "by:REDz"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))

    end
}) Tab5:AddButton({
    Name = "FE Korblox Perna Direita (By RedzHub)",
    Callback = function()
        local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "by:REDz"
}

Tab5:AddButton({
    Name = "FE Korblox Perna Esquerda (By RedzHub)",
    Callback = function()
        local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 139607673,
        [6] = 1
    },
    [3] = "by:REDz"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))

    end
})

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))

    end
})

Tab5:AddButton({
    Name = "FE R6 Animation",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-from-R15-to-R6-9639"))()
    end
})

Tab5:AddButton({
    Name = "Ficar Com a Roupa Dos Templarios",
    Callback = function()
        local args = {
    [1] = "AskIfIdAvailable",
    [2] = "15388922202"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

    end
})

Tab6:AddButton({
    Name = "Rejoin",
    Callback = function()
        -- Função para rejoin
function rejoin()
    game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
end

-- Chame a função para reentrar no jogo
rejoin()

    end
})

Tab7:AddButton({
    Name = "Teleportar Para o Portal",
    Callback = function()
        -- Exemplo de script de teleporte em Lua
-- Suponha que você tenha as coordenadas x, y e z desejadas

local jogador = game.Players.LocalPlayer -- Obtém o jogador local
local coordenadaX = 695 -- Substitua pelo valor da coordenada X desejada
local coordenadaY = 5 -- Substitua pelo valor da coordenada Y desejada
local coordenadaZ = -294 -- Substitua pelo valor da coordenada Z desejada

-- Teleporta o jogador para as coordenadas especificadas
jogador.Character:SetPrimaryPartCFrame(CFrame.new(coordenadaX, coordenadaY, coordenadaZ))

    end
})
-- Exemplo de script de teleporte em Lua
-- Suponha que você tenha as coordenadas x, y e z desejadas

local jogador = game.Players.LocalPlayer -- Obtém o jogador local
local coordenadaX = 695 -- Substitua pelo valor da coordenada X desejada
local coordenadaY = 5 -- Substitua pelo valor da coordenada Y desejada
local coordenadaZ = -294 -- Substitua pelo valor da coordenada Z desejada

-- Teleporta o jogador para as coordenadas especificadas
jogador.Character:SetPrimaryPartCFrame(CFrame.new(coordenadaX, coordenadaY, coordenadaZ))

    end
})
