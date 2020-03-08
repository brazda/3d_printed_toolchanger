
For anyone interested in multiple fan control in klipper. Here is a macro to let you specify multiple fans. 
I forked vladbabii's project and modified it to get it working the way I want it. I took the entire project just to play around with but currently only worked on the fan control.


#Multible Fan controls
examples
M106 S(0-255)
M106 S255 (Will always default to the first fan)

M106 P(Fan Number)  S(speed)
M106 P1 S255 (Will go to the second fan)

You can also use 
FANSPEED FAN=1 SPEED=255

Add to your klipper config file


To setup

For the responces in terminal to verify it is passing the correct information add this to your config

[respond]
default_type: echo

Then disable any FAN and include multiple_fans.cfg

remove [fan] from your config

Add to config
[include klipper/config/multiple_fans.cfg]

Copy the macros/multiple_fans.cfg to klipper/config/multiple_fans.cfg 

At the bottom of the file edit your fans pinout. 
