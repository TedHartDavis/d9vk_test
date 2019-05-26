BioShock 2

Tested on build from May 20th 2019

Launch options used (if any):
From git bash:
export DXVK_HUD=1
export DXVK_LOG_LEVEL=none
./Bioshock2.exe -dx9

Symptoms:
Launches to splash, then segfaults with DXVK
Unlike original, launches with normal DX9
Tried dx9 apitrace, launches but seems to softlock instead of loading into a game

Remarks:
See log, crashdump and apitrace
