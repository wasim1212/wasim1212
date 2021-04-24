game:service'RunService'.RenderStepped:connect(function()
  pcall(function()
    game:service'Players'.LocalPlayer.Character.Action:Destroy();
  end)
end)
