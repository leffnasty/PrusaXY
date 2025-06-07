# PrusaXY
Stock prusa mk3 implemented with Klipper - Recreate as many prusa features as possible

/klipper-prusa-mk3s/ folder has some reference configurations
/klipper-input-shaping-mk3s-upgrade/ has further layers added for reference configs, it is also from a better maintained repo.

Primary folder for customization is /prusa-mk3-stock-GCODE/


## 06 June 2025 ##
Working:
-stock mk3 gcode is running and functioning nicely
-PA values are passed from prusaslicer
-build sheets are good to go
-pause and resume are working sorta, see to-do

to-do / fixes:
-tune m600 material change
-tune bed leveling macro
-occasionally strange z limit errors, build sheet surface is located at like -4.0 mm
-Resume print needs to be correctly mapped to scroll wheel click after pause / material change

Not yet implemented:
-


Dervied From:
1. klipper-prusa-mk3s by dz0ny 
    https://github.com/dz0ny/klipper-prusa-mk3s 

2. klipper-input-shaping-mk3s-upgrade by charminULTRA (Fork of dz0ny's) 
    https://github.com/charminULTRA/Klipper-Input-Shaping-MK3S-Upgrade/blob/main/LICENSE


Other citations below:
1. Build sheet management: 
    https://github.com/garethky/klipper-voron2.4-config/blob/mainline/printer_data/config/build-sheets.cfg

2. Prusa's mk3 marlin code - as inspiration and reference
    https://github.com/prusa3d/Prusa-Firmware
