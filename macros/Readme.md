Add to your klipper config file

# Enable the "M118" and "RESPOND" extended commands.
[respond]
default_type: echo
#    Sets the default prefix of the "M118" and "RESPOND" output to one of
#    the following:
#        echo: "echo: " (This is the default)
#        command: "// "
#        error: "!! "
# default_prefix: echo:
#    Directly sets the default prefix. If present, this value will override
#    the "default_type".

Disable any FAN and include multiple_fans.cfg

#[fan]
#pin: ar9
# Load Multible Fans
[include klipper/config/multiple_fans.cfg]

Copy the macros/multiple_fans.cfg to klipper/config/multiple_fans.cfg 

At the bottom of the file edit your fans pinout. 
