### csgo-config

# change hand
```
alias handSwitch righthand;alias righthand "cl_righthand 1; alias handswitch lefthand";alias lefthand "cl_righthand 0; alias handswitch righthand";bind mouse4 handswitch
```

# toggle mic
```
alias mic "mikeon";alias mikeon "+voicerecord; alias mic mikeoff";alias mikeoff "-voicerecord; alias mic mikeon";bind "F1" "mic"
```

# toggle crosshair
```
alias changeCross myCross;alias myCross "cl_crosshairalpha 255;cl_crosshaircolor 4;cl_crosshairdot 0;cl_crosshairgap -13;cl_crosshairsize 3;cl_crosshairstyle 5;cl_crosshairusealpha 1;cl_crosshairthickness 0;cl_crosshair_drawoutline 0;cl_crosshair_sniper_width 1;cl_crosshaircolor_r 255;cl_crosshaircolor_g 0;cl_crosshaircolor_b 255;alias changeCross proCross"; alias proCross "cl_crosshairalpha 255; cl_crosshaircolor 4; cl_crosshairdot 1; cl_crosshairgap -2; cl_crosshairsize 1; cl_crosshairstyle 5; cl_crosshairusealpha 1; cl_crosshairthickness 0; cl_crosshair_drawoutline 0; cl_crosshair_sniper_width 1; cl_crosshaircolor_r 255; alias changeCross myCross"; bind alt changeCross
```
