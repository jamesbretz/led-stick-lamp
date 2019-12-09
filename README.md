# led-stick-lamp
LED Stick Lamp, RGB+CCT strip with Gledopto Zigbee Controller

### Materials

- [Gledopto RGB CCT Strip](https://www.aliexpress.com/item/32990834544.html/ "Gledopto RGB CCT Strip") 
- [Gledopto RGB CCT Zigbee Controller](https://www.aliexpress.com/item/32858603964.html "Gledopto RGB CCT Zigbee Controller")
- [Aluminum Extrusion LED Profile](https://www.aliexpress.com/item/4000050935203.html "Aluminum Extrusion LED Profile")
- 24v 3a Power Supply
- 3D printed parts (base, shell, cap)

### Printing
- For the shell, rotate the model 150 degrees so the slanted face is against the buildplate. Use tree supports or equivalent to support the extrusion tabs. Use the largest brim you can, as this thing wants to peel off due to the orientation.
- The base and cap are straightforward prints.
- Use at least a 20% infill to give everything some weight. The base isn't super stable, so the more weight the better.
- Total print time is ~30hrs on an Ender 3 with a standard PLA profile at .2mm layer height.

![rotate shell](https://github.com/jamesbretz/led-stick-lamp/blob/master/images/shell.png)

![printed](https://github.com/jamesbretz/led-stick-lamp/blob/master/images/shell_print.JPG)

![all](https://github.com/jamesbretz/led-stick-lamp/blob/master/images/base_shell.JPG)

### Assembly
- Cut the extrusion to length, which will be dependant on the cut lines of your LED strip. Remember that 24v strip usually has less cut lines than 12v strip.
- Clean the face of the aluminum with isoprpyl alchohol and apply the LED strip using the adhesive backing.
- Slide the extrusion on to the shell. Fitment is extremely tight, but some gentle taps with a hammer will seat the extrusion fairly easily. Mind the wiring for the LED strip.
- Route and connect the LED strip wiring, power supply, and LED controller.
- Push the base and shell together, they are friction fit. You may need to tap the extrusion down a bit further once the base is attached.
- Pop the cap on the top and fire it up. 

![strip install](https://github.com/jamesbretz/led-stick-lamp/blob/master/images/strip_install.JPG)

![wiring](https://github.com/jamesbretz/led-stick-lamp/blob/master/images/wiring_1.JPG)

![wiring](https://github.com/jamesbretz/led-stick-lamp/blob/master/images/wiring_2.JPG)

![wiring](https://github.com/jamesbretz/led-stick-lamp/blob/master/images/wiring_3.JPG)

### Finish

Add homekit support with the homebridge-hue plugin.

![dog tax](https://github.com/jamesbretz/led-stick-lamp/blob/master/images/dog_tax.JPG)



