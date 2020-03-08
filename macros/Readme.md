Add to your klipper config file


[respond]
default_type: echo

Disable any FAN and include multiple_fans.cfg

remove [fan]
remove pin: ar9

Add to config
[include klipper/config/multiple_fans.cfg]

Copy the macros/multiple_fans.cfg to klipper/config/multiple_fans.cfg 

At the bottom of the file edit your fans pinout. 
