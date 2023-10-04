A compact board that adds USB charging capability to the Dualshock 4's EXT port.

Features:
* Choice of either a micro USB or USB C port. (Combined version only)
* Includes pads for 5.1k&#937; resistors, to allow the use of 'smart' chargers (USB C only).
* No alteration to the outside of the controller is necessary.

A USB C only version of the board is also available, which removes the need to solder the jumper.

Included in this repository are the KiCAD files for this design. If you're only interested in having the board manufactured, gerbers are available under 'releases'.

Parts List:
* 1x 16 pin USB type C port/1x 5 pin micro USB port
* 2x 0603 5.1k&#937; resistors (optional)

For more information, take a look at [my blog post](https://qubitsandbytes.co.uk/post/dualshock-4-ext-port-charger).

## Images
Top:

![Top of the board](ds4-ext-charger-render-top.webp?raw=true "KiCAD render of the top of the board")

Bottom:

![Bottom of the board](ds4-ext-charger-render-bottom.webp?raw=true "KiCAD render of the bottom of the board")

## KiCAD
The files in this project were created using KiCAD 6, which introduced a new file format not compatible with older versions. Ensure you are using KiCAD 6 if you wish to open the files.

In addition, the USB Type C port pictured in the 3D render can be found [over here](https://github.com/ai03-2725/Type-C.pretty) - the file you're looking for is 'HRO TYPE-C-31-M-12.step'. It's not required, unless you want to see the part populated using the 3D viewer.
