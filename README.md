
cmd:
```
powershell -Command "Invoke-WebRequest https://github.com/1089x/curseurs/raw/refs/heads/main/majeur_link_up_down.ani -Outfile curseur_m.ani" & 
reg add "HKCU\Control Panel\Cursors" /v Hand /t REG_EXPAND_SZ /d "%cd%/curseur_m.ani" /f
```
