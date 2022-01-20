# How to Change the Switches on Your Mechanical Keyboard
A mechanical keyboard is a special type of keyboard that emphasizes user experience. A mechanical keyboard is best understood by its key switches, which can vary in the way that they depress or "click" and register a keystroke. A user may want to swap their keys for a different typing feel; provided is a guide on how to do so.
<hr>

### Required Materials
- Non-hotswappable mechanical keyboard
- A set of replacement switches
- Soldering kit
  - a soldering kit should provide all necessary equipment including a soldering iron, solder wire, a pump, soldering iron stand
- A means of grounding yourself
- Fume mask if not working in open air
- protective eyewear
-online key checking program

### ⚠ CAUTION:
- Soldering should ideally be performed outside as dangerous fumes are produced. If this is not possible, a fume mask should be utilized.
- A soldering iron tends to operate at around 350 to 400 degrees Fahrenheit. Exhibit caution when the iron is hot and make sure it is truly off when you believe it to be.

#### Notes:
- A hotswappable keyboard makes changing keys trivially easy at the cost of a price premium. If your mechanical keyboard is hotswappable, you do not need this guide.
- Some useful information is stored in text that appears when each image is hovered over.


## Instructions
### (optional) Practice soldering and desoldering
- The process of soldering and desoldering takes practice to get used to. If you have a spare PCB (Printed Circuit Board), practice applying a clean solder connection and then removing it.

### 1. Prepare equipment
- Make sure that all protective gear is being used correctly. Keep all materials easily in reach. Make sure that the soldering iron is not in a volatile location as it will be extremely hot during the process. Make sure you are comfortable using the iron and moving it from a working position to and from its stand.

### 2. Determine how to open the keyboard.
- keyboards are kept together in various ways. Most commonly they are held together by finger clips or screws. Determine how your keyboard is constructed, either via its manual or by inspection.

### 3. Carefully open the keyboard
- The internal hardware of a keyboard is very volatile. Make sure your keyboard is unplugged prior to opening it. Open your keyboard slowly and with caution, being careful not to damage the main green PCB or any connections.

### 4. Separate the  internals of your keyboard
- The PCB will contain I/O connections that allow it to connect to other machines. There will likely be a 4 or 8 pin connector that interfaces the PCB to some output port, either micro USB or USB C. Disconnect this connection and any other structural connections to obtain the PCB as a single component.

![alt text](https://github.com/jackveithPITT/Directions-Markdown/blob/main/PCB.jpg "The backside of a keyboard PCB. Note the conical metal lumps: these are the soldered connections of the switches.")

### 5. Desolder and remove switches
- each switch on the PCB will have two corresponding solder connections on the back of the board, for the two pins on the switch. Heat the lump of solder and pump the liquid metal up. If done correctly there should be little to no excess metal on the contact point. desolder the other pin, remove the switch, and repeat.

### 6 and 7. Insert new switches and resolder
- You can insert all switches at once and then solder all of them, or complete one at a time. Once a switch is inserted, move the solder wire close the the contact point and heat it. Pull away the wire quickly after a puddle of metal has formed, connecting the pin and contact point. Repeat for all pins.

![alt text](https://github.com/jackveithPITT/Directions-Markdown/blob/main/soldering.jpg "A soldering iron in use. The tip heats the soldering wire to melt the metal and connect the switch pins to the contact point.")

### 8. Verify connections
- Check all connections to make sure the pin and contact point are properly connected. Resolder any connections that do not look adequate.

### 9. Reassemble the keyboard
- Reassemble the keyboard by reversing the steps taken to disassemble iit. Make sure the I/O connection has been restored so that data can flow from the PCB into the corresponding machine.

### 10. Test the keys
- Plug your keyboard into the machine you will test it with. Use an online key checker to validate that all keys are working as intended. If a key fails to register a keystroke, recheck the solder as you may have created a faulty connection.

![alt text](https://github.com/jackveithPITT/Directions-Markdown/blob/main/keychecker.png "A useful keychecker that allows you to test the functionality of your keys.")

### 11. Enjoy your new switches
- As long as everything has been completed correctly, you now have what feels like a new keyboard. You may also have learned the valuable skill of soldering, along with learning about hardware internals. Use this information wisely and enjoy.
