# Getting Started with a new Zuno
![annotated](zuno_r03_annotated_topview.jpg)

The Zuno you received should already have the RAM loaded with monitor and disk-on-module loaded with CP/M 2.2 and CP/M 3 software. Connect a USB cable to the USB serial adapter. Set the terminal property to 115200-N-8-1, no handshake. Connect a 2.1mmX5.5mm power plug and apply +5V power to the board. The current consumption should be around 150mA. You should see this sign-on message:
```
Z80SBC64 Monitor v0.7 9/10/19


>
```
Type 'h' to get a list of monitor commands. Please refer to the [ZMon64](https://github.com/Plasmode/Z80SBC64/blob/main/Manuals/ZMon.md) manual for more information on the monitor.

At the monitor prompt, type 'b2' to boot CP/M 2 or 'b3' to boot CP/M 3. You can also type 'b1' to bring up SCMonitor.

builderpages/plasmo/zuno/zuno_getting_started.txt · Last modified: 
