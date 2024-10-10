-- เช็คว่า KEY ถูกต้องหรือไม่
if getgenv().userInput ~= KEY then
    game.Players.LocalPlayer:Kick("KEY = false!") -- เตะผู้เล่นถ้าคีย์ผิด
end
