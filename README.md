game:GetService("RunService").RenderStepped:connect(function()
  pcall(function()
    game:GetService("Players").LocalPlayer.Character.Humanoid.creator:Destroy()
   end)
end)

game:service'RunService'.RenderStepped:connect(function()
  pcall(function()
    game:service'Players'.LocalPlayer.Character.Action:Destroy();
  end)
end)

game:service'RunService'.RenderStepped:connect(function()
  pcall(function()
    game:service'Players'.LocalPlayer.Character.Activity:Destroy();
  end)
end)

game:service'RunService'.RenderStepped:connect(function()
  pcall(function()
    game:service'Players'.LocalPlayer.Character.Killed:Destroy();
  end)
end)

game:service'RunService'.RenderStepped:connect(function()
  pcall(function()
    game:service'Players'.LocalPlayer.Character.Attacking:Destroy();
  end)
end)
