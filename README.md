local v0=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/BlackKing/main/Gui%20Lib%20%5BLibrary%5D"))();local v1=loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/COLORS/main/README.md"))();local v2=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/Gui/main/Gui%20Lib%20%5BSaveManager%5D"))();local v3=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/BlackKing/main/Blackking%20%5BGuiNew!%5D"))();local v4=Instance.new("Sound");v4.Parent=game.SoundService;v4.SoundId="rbxassetid://4590657391";v4.Volume=5;v4.PlayOnRemove=true;v4:Destroy();v3:Introduction();wait(1);v0:Notify("Loaded");local v44=v0:CreateWindow({Title="YOU HUB SPEEDRUN" ,Center=true,AutoShow=true,TabPadding=5,MenuFadeTime=0.2 + 0 });local v45={Main=v44:AddTab("Main")};local v46=v45.Main:AddLeftGroupbox(" ");game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.speedkuys then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=_G.SelectBootst;end end);end);game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if (_G.SpeedHack and (game.Players.LocalPlayer.Character.Humanoid.WalkSpeed==(16))) then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=18;elseif (_G.SpeedHack and (game.Players.LocalPlayer.Character.Humanoid.WalkSpeed==(20))) then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=22;elseif (_G.SpeedHack and (game.Players.LocalPlayer.Character.Humanoid.WalkSpeed==(24)))) then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=26 ;elseif _G.SpeedHack then local v796=31 + 4 + game.Players.LocalPlayer.Character.Humanoid:GetAttribute("SpeedBoost") ;if (game.Players.LocalPlayer.Character.Humanoid.WalkSpeed<=v796) then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed+=_G.SelectBoots end end end);end);game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.FieldOfView then game:GetService("Workspace").Camera.FieldOfView=_G.FieldOfViewe;end end);end);v46:AddSlider("MySliderspeed",{Text="Thanh Tốc Độ",Default=6,Min=0 -0 ,Max=6,Rounding=1,Compact=true,Callback=function(v80)_G.SelectBoots=v80;end});v46:AddSlider("MySlider",{Text="Thanh Góc Nhìn ",Default=120,Min=1226 -(1074 + 82) ,Max=120,Rounding=0 -0 ,Compact=true,Callback=function(v81)_G.FieldOfViewe=v81;end});_G.SelectBoots=1790.5 -(214 + 1570) ;_G.FieldOfViewe=120;v46:AddToggle("MyToggle",{Text="Nhận Tốc Độ",Default=false,Tooltip="Nhận Tốc Độ Để Chạy Nhanh Hơn",Callback=function(v82)v0:Notify("");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();_G.SpeedHack=v82;if (_G.SpeedHack==false) then game:GetService("Players").LocalPlayer.PlayerGui.MainUI.MainFrame.Healthbar.Effects.SpeedBoost.Visible=false;elseif (_G.SpeedHack==true) then game:GetService("Players").LocalPlayer.PlayerGui.MainUI.MainFrame.Healthbar.Effects.SpeedBoost.Visible=true;end end});v46:AddToggle("MyToggle",{Text="Nhận Góc Nhìn",Default=false,Tooltip="Nhận Góc Nhìn Xa",Callback=function(v83)v0:Notify("Increase Field Of View Enable");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();local v84=1455 -(990 + 465) ;while true do if (0==v84) then if (v83==true) then local v449=0 + 0 ;local v450;while true do if (0==v449) then v450=game:GetService("TweenService");v450:Create(game.Workspace.CurrentCamera,TweenInfo.new(0.9),{FieldOfView=_G.FieldOfViewe}):Play();break;end end elseif (v83==false) then local v621=game:GetService("TweenService");v621:Create(game.Workspace.CurrentCamera,TweenInfo.new(0.9),{FieldOfView=31 + 39 }):Play();end wait(0.8 + 0 );v84=3 -2 ;end if (v84==1) then _G.FieldOfView=v83;break;end end end});local v46=v45.Main:AddRightGroupbox("");game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.FullBright then local v315=0 + 0 ;while true do if (v315==1) then game:GetService("Lighting").ClockTime=47 -33 ;game:GetService("Lighting").GlobalShadows=false;v315=2;end if (v315==0) then game:GetService("Lighting").FogEnd=100000;game:GetService("Lighting").Brightness=3;v315=1;end if (v315==(1996 -(109 + 1885))) then game:GetService("Lighting").OutdoorAmbient=Color3.new(1,1,1);break;end end end end);end);v46:AddButton({Text="Fullbright",Default=false,Tooltip="Fullbright",Callback=function(v88);if v88 then _G.FullBright=true;else _G.FullBright=false;game:GetService("Lighting").FogEnd=11111111533265722 -(802 + 24) ;game:GetService("Lighting").Brightness=5 -2 ;game:GetService("Lighting").ClockTime=20;game:GetService("Lighting").GlobalShadows=false;game:GetService("Lighting").OutdoorAmbient=Color3.new(1,1,1);end end});v46:AddButton({Text="Tăng Độ Hoạ Một Tí",Callback=function()v0:Notify("Đã nhận");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/BladeBallScript/main/FPSSCRIPTS"))();end,Default=false,Tooltip="Tăng Một Tí Độ Hoạ"});v46:AddButton({Text="Tự Động Chém Bóng Đỏ",Callback=function()v0:Notify("Đã nhận");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/BladeBallScript/main/BLADEBALL"))();end,Default=false,Tooltip="Tự Đánh Bóng Đỏ"});v46:AddButton({Text="Định Vị Tốc Độ Bóng",Callback=function()v0:Notify("Đã nhận");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/BladeBallScript/main/AutoParryBallByRechedmcvnAndWaterExecute"))();end,Default=false,Tooltip="Nhìn Trên Đầu Của Bạn Đó Là Tốc Độ Bóng"});v46:AddButton({Text="Thanh Coi Mượt & Lag",Callback=function()v0:Notify("Đã nhận");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/BladeBallScript/main/BarFPSms"))();end,Default=false,Tooltip="Thanh Coi Lag & Mượt"});
