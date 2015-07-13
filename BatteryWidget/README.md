## Battery widget
Simple and easy-to-install widget for Awesome Window Manager.

Basically this widget consists of an icon which shows the battery status: ![Battery Widget](./batWid1.png)

And a pop-up window, which shows up when you hover over it: ![Battery Widget](./batWid2.png)

## Installation

This widget uses the output of acpi tool.
- install `acpi` tool:
```
sudo apt-get install acpi
```
- clone/copy battery.lua file and battery-icons folder to your ~/home/username/.config/awesome/ folder;

- include `battery.lua` and add battery widget to your wibox in rc.lua:
```
require("battery")
...
right_layout:add(batteryIcon)
```