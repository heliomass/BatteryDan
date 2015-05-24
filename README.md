![](logo.png)

BatteryDan v1.0

By Daniel Demby
heliomass@gmail.com
http://heliomass.com

A simple script to display the battery status for your Mac.


To install:

git clone git://github.com/heliomass/BatteryDan.git


To see the full range of commands:

battery_dan --help


Basic invocation:

battery_dan
◉ 96%

If you want to round up to 100% when your Mac is plugged in and almost charged:
battery_dan --round_up
◉ 100%