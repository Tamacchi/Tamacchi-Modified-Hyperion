# Tamacchi Modified Hyperion Case and Lupinix PCB for SlimeVR

## Use caution for USB C Aux ports. The IMUs are not 5V compatible and will damage IMUs if plugged into other devices.

### Electronics
Uses 4-pin USB C Breakout Board for Aux. https://www.aliexpress.com/item/1005005187670446.html

Uses 1800mAh 804040 batteries, but can fit 804050 or 805040 batteries.

Requires you to manually wire 4 cables from the AUX pins to a USB C breakout board.

You must add at least 5 layers of paper tape between the USB C breakout board and the TP4056 beneath. Otherwise, it may contact the TP4056 below. 
Optionally, you may choose to print the Shielding STL that goes under the USB C breakout board. PLA not advised for this print, as it is located close to the TP4056 board which can generate a lot of heat. Please use PETG, ABS, ASA and etc.

Requires you to clip the sides of the USB C breakout board to fit into the printed notches. Then, add 3M tape on the empty spaces above the breakout board on the main case to minimize movement.

The TP4056 and Aux Case side of the USB C breakout board should be soldered directly onto the board without header pins.

### 3D Printing
The Forward Tray version pushes the TP4056's USB C port forward more, making it look neater and sit nicely in the printed USB C port hole.

Dual Color Printing stl files have a small 0.03mm indent on the top of the lid for the symbols and text. This allows you to separate them from the rest of the lid while printing everything on  the first layer when coloring in using Bambu Lab's color fill feature. 

Please rotate lid files with the top of the lid facing down on the bed before printing.

### Original File Sources

https://github.com/Smeltie/Hyperion

https://github.com/Lupinixx/SlimeVR-Hyperion-BMI160-PCB

I have originally contributed to the 804040 STL variants for the Lupinix PCB. If you would like to use those, please take the STL files from here instead as there were many changes to fix the flaws of the original case design. (Non-aux version)
