# Paint bomber
This device is designed to release paint onto the canvas in one large, uniform drop at a single moment. The source files were developed in Fusion 360. The device consists of a vertical tube, at the bottom of which there is a movable diaphragm. When the button is pressed, the diaphragm opens and the paint loaded into the tube falls down as one large drop.

To assemble the "dropper/bomber" you will need:
- 3D printing of all parts using any plastic  
- 8 × M3 screws and heat-set inserts  
- Any Arduino Nano-sized board  
- A modified laser module taken from a construction laser level  
- 2 push buttons  
- A servo of MG90 or SG90 type  

In my version the device is powered from a power bank through the Arduino USB port, but you can also make it with a standalone battery power supply.  

The firmware depends on the specific features of each individual build, but the general logic is the same: when the button is pressed, the Arduino slightly rotates the servo shaft, which is connected to the moving disk that controls the diaphragm petals.

![Paint bomber](screenshot.png)
