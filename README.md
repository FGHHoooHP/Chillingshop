
local validKey = "keyez"

-- ฟังก์ชั่นตรวจสอบ Key จากตัวแปร G.key
local function checkKey()
    if G.key == validKey then
        -- ถ้า Key ถูกต้อง
        print("Key valid!")
        -- ทำการดำเนินการต่างๆ ที่ต้องการเมื่อ Key ถูกต้อง
    else
        -- ถ้า Key ไม่ถูกต้อง
        game.Players.LocalPlayer:Kick("Invalid key!")
    end
end

-- เรียกใช้ฟังก์ชั่นตรวจสอบ key
checkKey()  -- ตรวจสอบ key ที่เก็บใน G.key
