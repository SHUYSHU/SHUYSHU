if game.PlaceId == 6284583030 then
   local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
    local Window = Library.CreateLib("Pet Sim X (CuteScript) - Made By Shu Shu", "Sentinel")
     local Player = Window:NewTab("Player")
    local PlayerSection = Player:NewSection("Player")
     PlayerSection:NewSlider("Walkspeed", "Changes the walkspeed", 500, 16, function(v)
        
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
     PlayerSection:NewSlider("Jumppower", "Changes the jumppower", 500, 50, function(v)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = v  


    end)    
    end)
   end 
   
