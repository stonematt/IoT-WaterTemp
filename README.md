# IoT-WaterTemp
collection of temperature sensors with 7-segment display to show current and recent history.

The plan is to deploy this sensor array to a passive solar hot water system that will be used for an off-grid shower at the cabin.

in the end, there will be 2 water proof sensors (top and bottom of the tank) and an ambient air temp and a 7segment display that will cycle through the current and last 24h max/min temp history upon a button push.

hints:
in /etc/rc.local
insmod w1-gpio-custom bus0=0,19,0

list devices:
cat /sys/devices/w1_bus_master1/w1_master_slaves

also ln -s www directory into web server somewhere