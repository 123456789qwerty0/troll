local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/miroeramaa/TurtleLib/main/TurtleUiLib.lua"))()
local window1 = library:Window("FE SPAM SOUNDS BY SUSMIC123_REAL")
window1:Toggle("ON/OFF", false, function(State1)
    getgenv().hit = State1
    while wait() do
        if getgenv().hit then
            for i,v in pairs(game.Workspace:GetDescendants()) do
                if v:IsA("Sound") then 
                    v:Play()
                end
            end
        end
    end
end)
