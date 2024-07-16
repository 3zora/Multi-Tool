@echo off
chcp 65001
setlocal enabledelayedexpansion

title made by 3zora
color 3
:menu
cls
echo                                   [37m  _______   ________   _________  ______   ___   ___     
echo                                   /_______/\ /_______/\ /________/\/_____/\ /__/\ /__/\                               
echo                                   [37m\[94m::: [94m_  [94m\ \\::: _  \ \\__.::.__\/\:::__\/ \::\ \\  \ [37m\                         [94m│────────────────────────────────
echo                                   [37m \[94m::[94m(_)  [94m\/_\::(_)  \ \  \::\ \   \:\ \  __\::\/_\ .\[37m \                        [94m│[37mMade by 3zora
echo                                   [37m  \[94m::  [94m_  [94m\ \\:: __  \ \  \::\ \   \:\ \/_/\\:: ___::\[37m \                       [94m│────────────────────────────────
echo                                   [37m   \[94m::[94m(_)  [94m\ \\:.\ \  \ \  \::\ \   \:\_\ \ \\: \ \\::\[37m \                      [94m│[37mhttps://discord.gg/ZHGhJeV57N
echo                                       [37m\_______\/ \__\/\__\/   \__\/    \_____\/ \__\/ \::\/                      [94m│────────────────────────────────
echo                               [94m╔───────────────────────────────────────────────────────────────────╗              
echo                               [94m│[37m(1) = Find first part of token                                     │                                                                                                                         
echo                               [94m│                                                                   [94m│                                                                     
echo                               [94m│[37m(2) = Password breach checker                                      │                                                                                                                                          
echo                               [94m│                                                                   [94m│                                                                     
echo                               [94m│[37m(3) = Ip lookup                                                    │                                                                                                                                          
echo                               [94m│                                                                   [94m│                                                                     
echo                               [94m│[37m(4) = Pinger                                                       │                                                                                                                                          
echo                               [94m│                                                                   [94m│                                                                     
echo                               [94m│[37m(5) = Password gen                                                 │                                                                                                                                          
echo                               [94m╚───────────────────────────────────────────────────────────────────╝   
    
echo                                                   ┌──────────────────────┐
echo                                                   │[37mhttps://discord.gg/ZHGhJeV57N [94m│
echo                                                   [94m└──────────────────────┘  
echo                                                        [37mMade By 3zora  
echo                                                    [37mType 0 to enter web                                                    
                            
                          

for /f "tokens=2 delims==" %%u in ('echo %USERNAME%') do set "username=%%u"


<nul set /p "=┌─── (user@%username%) "
echo.
<nul set /p "=└─# "
set /p choice=

if "%choice%"=="1" goto encode
if "%choice%"=="2" goto breachchecker
if "%choice%"=="3" goto ipGeoLookup
if "%choice%"=="4" goto ipPinger
if "%choice%"=="5" goto password_generator
if "%choice%"=="0" goto open_myth_rip


:password_generator
cls
echo    Password Generator

set /p "length=Enter desired length of password: "

setlocal enabledelayedexpansion
set "chars=ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789!@#$%^&*()_-+=[]{}|;:,.<>/?"
set "password="

for /l %%i in (1,1,%length%) do (
    set /a idx=!random! %% 87
    for /l %%j in (!idx!,1,!idx!) do (
        set "char=!chars:~%%j,1!"
        set "password=!password!!char!"
    )
)

echo Generated Password: %password%
pause
goto menu



:ipPinger
cls
echo           [94m▪  [37m ▄▄▄·    [94m ▄▄▄[37m·▪   ▐ ▄ [94m ▄▄ • [37m▄▄▄ .[94m▄▄▄  
echo           [94m██ [37m▐█ ▄█    [94m▐█ ▄[37m███ •█▌▐█[94m▐█ ▀ ▪[37m▀▄.▀·[94m▀▄ █·
echo           [94m▐█·[37m ██▀·    [94m ██▀[37m·▐█·▐█▐▐▌[94m▄█ ▀█▄[37m▐▀▀▪▄[94m▐▀▀▄ 
echo           [94m▐█▌[37m▐█▪·•    [94m▐█▪·[37m•▐█▌██▐█▌[94m▐█▄▪▐█[37m▐█▄▄▌[94m▐█•█▌
echo           [94m▀▀▀[37m.▀       [94m.▀  [37m ▀▀▀▀▀ █▪[94m·▀▀▀▀ [37m ▀▀▀ [94m.▀  ▀
set /p "ip=Enter ip address: "

ping %ip%
pause
exit /b


:encode
cls

echo [94m███████╗██╗███╗   ██╗██████╗     ████████╗ ██████╗ ██╗  ██╗███████╗███╗   ██╗    
echo [37m██╔════╝██║████╗  ██║██╔══██╗    ╚══██╔══╝██╔═══██╗██║ ██╔╝██╔════╝████╗  ██║    
echo [94m█████╗  ██║██╔██╗ ██║██║  ██║       ██║   ██║   ██║█████╔╝ █████╗  ██╔██╗ ██║    
echo [37m██╔══╝  ██║██║╚██╗██║██║  ██║       ██║   ██║   ██║██╔═██╗ ██╔══╝  ██║╚██╗██║    
echo [94m██║     ██║██║ ╚████║██████╔╝       ██║   ╚██████╔╝██║  ██╗███████╗██║ ╚████║    
echo [37m╚═╝     ╚═╝╚═╝  ╚═══╝╚═════╝        ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝    
                                                                                                                                                                  
set /p userid= Enter in somones discord id:
for /f %%i in ('powershell -NoProfile -Command "[Convert]::ToBase64String([Text.Encoding]::UTF8.GetBytes('%userid%'))"') do set encodedStr=%%i
echo.
echo Users first part of token : %encodedStr%
pause >nul
goto menu

:breachchecker
cls
color 4
echo                       ┌───────┐   ╔════════════════════╗
echo                       │ ════ o│   ║                    ║
echo                       ├───────┤   ║                    ║
echo    ╔══════════════╗   │[■■■■]o│   ║                    ║
echo    ║              ║   ├───────┤   ║                    ║
echo    ║              ║   │       │   ╚════════╤══╤══════o═╝
echo    ║              ║   │       │─────┘  ____│__│____
echo    ║              ║   │       │─┐     /____________\
echo    ╚══════════════╝   └───────┘ │ ________________
echo   /::::::::::::::::\      │     └/::::::::::::::::\
echo  /:::::════════:::::\    /T\    /:::::════════:::::\
echo  ════════════════════    \_/    ════════════════════

set /p password=Enter a password to check for breaches:
for /f %%i in ('powershell -NoProfile -Command "$password = '%password%'; $sha1 = [System.Security.Cryptography.SHA1]::Create(); $hash = $sha1.ComputeHash([System.Text.Encoding]::UTF8.GetBytes($password)); $hashedPassword = -join ($hash | ForEach-Object { $_.ToString('x2') }).ToUpper(); Write-Output $hashedPassword"') do set hashedPassword=%%i
set prefix=%hashedPassword:~0,5%
set suffix=%hashedPassword:~5%
powershell -NoProfile -Command "$prefix = '%prefix%'; $suffix = '%suffix%'; $url = 'https://api.pwnedpasswords.com/range/' + $prefix; $response = (Invoke-WebRequest -Uri $url).Content; if ($response -match $suffix) { Write-Host 'This password has been breached. It is not secure.' } else { Write-Host 'This password has not been breached. It is secure.' }"
pause
goto menu

:ipGeoLookup
cls
echo [37m╔═══════════════════════════════╗
echo ║    [94m╦[37m╔═╗  [94m╦  [37m╔═╗[94m╔═╗[37m╦╔═[94m╦ ╦[37m╔═╗[37m   ║
echo ║    [94m║[37m╠═╝  [94m║  [37m║ ║[94m║ ║[37m╠╩╗[94m║ ║[37m╠═╝[37m   ║
echo ║    [94m╩[37m╩    [94m╩═╝[37m╚═╝[94m╚═╝[37m╩ ╩[94m╚═╝[37m╩  [37m   ║
echo [37m╚═══════════════════════════════╝  
set /p "ip=[94mE[37mn[94mt[37me[94mr [37ma[94mn [37mI[94mP [37ma[97m[37md[97md[37mre[97ms[37ms: "             
echo.
curl -s ipinfo.io/%ip% | findstr /R /C:"\"city\":" /C:"\"postal\":" /C:"\"country\":" /C:"\"loc\":" /C:"\"timezone\":"
echo.
echo [94m╚═════════════════════════════════════════════
pause
exit /b

:open_myth_rip
start https://discord.gg/ZHGhJeV57N
goto menu

:exit
exit
