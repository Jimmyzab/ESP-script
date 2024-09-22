while game:GetService("RunService").RenderStepped:wait() do
    for i, children in ipairs(workspace:GetDescendants()) do
        if children:FindFirstChild("Humanid") then
            if not children:FindFirstChild("EspBox") then
                if children ~= game.Players.LocalPlayer.Character then
                    local esp = Instance.new("BoxHandleAdornment", children)
                    esp.Adornee = children

                    esp.ZIndex = 0
                    esp.Size = Vector3.new(5, 5, 2)
                    esp.Transparency = 0.70
                    esp.Color3 = Color3.fromRGB(255, 0, 0)
                    esp.AlwaysOnTop = true
                    esp.Name = "EspBox"
                end
            end
        end
    end
end
