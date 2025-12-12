# Tools
[Online MP3 File Merger](https://mp3chapters.github.io/merge/)

[Cobalt](https://cobalt.tools/)

# Adblocklisten
https://raw.githubusercontent.com/DandelionSprout/adfilt/master/LegitimateURLShortener.txt

https://raw.githubusercontent.com/gijsdev/ublock-hide-yt-shorts/master/list.txt

https://raw.githubusercontent.com/autinerd/anti-axelspringer-hosts/master/axelspringer-hosts

# Scripts
## Anti AFK Batch:
```
@if (@CodeSection == @Batch) @then
@echo off set SendKeys=CScript //nologo //E:JScript "%~F0" cls color 0a :loop %SendKeys% "{NUMLOCK}" %SendKeys% "{NUMLOCK}" timeout /t 290 /nobreak >nul goto :loop @end
var WshShell = WScript.CreateObject("WScript.Shell"); WshShell.SendKeys(WScript.Arguments(0));
```

## PHP Server starten:
php -S localhost:8000
