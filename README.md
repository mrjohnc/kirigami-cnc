# kirigami-cnc
A CNC machine to mark, cut and fold paper

It is based around the design principles of: 

* Being as self replicating as practical
* All materials as accessible as possible to make it as easy to build and improve the design as possible
* Strong enough to allow the cutting of many materials
* To be easy to construct
* To be affordable

The project is inspired by the work of Sam Calisch at MIT
https://www.youtube.com/watch?v=JtKi8lNSqvw


The current design is largely inspired by Maslow CNC, an open source CNC router with a design similar to a hanging plotter. 
https://github.com/MaslowCNC


## Current status
### Done
A very basic first version has been created moves but has no toolchain (click image for video). There is one toolhead for a craft knife which cuts paper.

[![](http://img.youtube.com/vi/BQzhzq3MdRw/0.jpg)](http://www.youtube.com/watch?v=BQzhzq3MdRw "First Kirigami CNC test moves")

### Biggest issues
#### Hardware
* Find a better way to attach belt to ring with less wobbliness
* Replace plastic bearings with real bearings on motor plate
* Find way for machine to understand its position
* More tools
* Find way to raise and lower tools
* Find way to add more weight to the toolhead so it can cut consistently
* Some way to create a board that can operate at 45% so it can apply enough force to cut properly

#### Software
* Everything


## Building a Kirigami CNC
#### Printed parts
Printed parts are available in the STLs folder. Print each file the number of times shown, files were printed successfully in PLA using an 0.4mm nozzle with 20% infill and 1.2mm top, bottom and sides.

* **1x** Base 
* **2x** Counterweight cylinder top 
* **2x** Counterweight cylinder 
* **2x** Counterweight lid
* **2x** Counterweight 
* **16x** Fixer 
* **2x** Large wheel inner
* **4x** Large wheel outer 
* **2x** Motor bracket
* **1x** Motor stencil
* **2x** Ring bearing holder part 1
* **2x** Ring bearing holder part 2
* **4x** Ring spacer
* **1x** Ring 
* **6x** Small wheel inner
* **12x** Small wheel outer 
* **1x** Tool bearing holder
* **1x** Tool blade holder 
* **8x** Wheel spacer


#### Non printed parts
* **1x** Snap off utility knife blade
* **2x** NEMA 17 motors
* **2x** GT2 belts
* **2x** GT2 belt gears
* **3x** 608 bearings
* **1x** 3D printer control board
* **1x** Power supply
* **1x** 3D printer thermister
* **1kg/2lbs** Table salt (used in counterwiegh)
* **6x** Cable ties
* **1x** M3 square nut
* **5x10mm** M3 bolts
* **8x10mm** M3 bolts
* **9x18mm** M3 bolts
* **12x35mm** M3 bolts
* **1x** Large sheet of ply wood or similar stiff material

#### Software
(A first version, likely to change)
* Slic3r
* Pronterface



### Construction
#### Motor mount
<p align="left">
  <img height="200" src="/Photos/Motor mount.jpg">
</p>
Printed parts:
* **8x** Fixer 
* **2x** Large wheel inner
* **4x** Large wheel outer 
* **2x** Motor bracket
* **1x** Motor stencil
* **6x** Small wheel inner
* **12x** Small wheel outer 
* **8x** Wheel spacer


Non printed parts:
* **4x10mm** M3 bolts (bolt motors into plate)
* **8x35mm** M3 bolts (for outside corners where a printed bearing is used)
* **1x18mm** M3 bolt (for top corner opposite large gear)
* **1x** Large sheet of ply wood or similar stiff material
* **1x** GT2 belt
* **2x** NEMA 17 motors


1. Use the **Motor stencil** draw the shapes in the top left and right **ply wood** to cut, the outer edge of the stencil should be at least 10 cm from the side edges of the material to allow for space for the counterwight to go up and down.
2. Cut out the shape of the motor and drill the holes for the bolts, using a 3mm drill will allow the screws to bite into the material as well as being attached using the fixers.
3. Screw the motor to the Motor bracket using the 10mm bolts
4. Create each of the plastic bearings for the GT2 belt using a **Small wheel inner** placed between two **Small wheel outer**s and screw a 35mm bolt through till it reaches the top of the bolt.
5. Screw a **Wheel spacer** onto the back of the plastic bearing you've just made
6. Screw the bolt with the parts on into one of the positions shown above, attaching it to the plywood board.
7. Repeat for the other small wheels and the big wheel, making sure the big wheel is on the outside edge of the board.


#### Base
<p align="left">
  <img height="200" src="/Photos/Base.jpg">
</p>
Printed parts:
* **1x** Base 
* **2x** Ring bearing holder part 1
* **2x** Ring bearing holder part 2
* **4x** Ring spacer
* **1x** Ring 

Non printed parts
* **4x18mm** M3 bolts (outside ring)
* **4x35mm** M3 bolts (inside ring) 
* **3x608** bearing


#### Cutting head
<p align="left">
  <img height="200" src="/Photos/Cutting head 1.jpg">
</p>
<p align="left">
  <img height="200" src="/Photos/Cutting head 2.jpg">
</p>
Printed parts
* **1x** Tool blade holder 

Non printed parts
* **1x18mm** M3 bolt
* **1x10mm** M3 bolt
* **1x** M3 square nut
* **1x** blade

1. Push the square but into the hole in the **Tool blade holder**
2. Screw the bolt into the hole on the **Tool blade holder** that is the opposite side to the nut, so the bolt goes throught the middle, don't tighten it.
3. Snap two section off the blade
4. Slide the snapped off blades in to the slot in the **Tool blade holder** so that it is poking out the bottom the depth of the material you want to cut, make sure the edge of the blade lines up with the line on the bottom. BE CAREFUL NOT TO CUT YOURSELF
5. Tighten the nut so that the knife blade doesn't move.


#### Control board
<p align="left">
  <img height="200" src="/Photos/PCB.jpg">
</p>
Parts needed
* **4x??mm** M3 bolts
* **1x** 3D printer control board
* **8x** Fixer 

1. Put the control board where you want to mount it on the plywood board, between the motors away from anything moving is sensible.
2. Mark on the board using the mounting holes on the board where you will drill the mounting holes in the plywood board
3. Drill the holes
4. Slide the bolt through the board and add a fixer to the back of each bolt to create a gap between the board and the plywood.
5. Mount the board on the plywood
6. Attach on the back using the remianing 4 fixers.
7. Wire up the motors
8. Add the thermistor (the thermistor is used to not trip the mintemp sensor in Pronterface



#### Counterweight
<p align="left">
  <img height="200" src="/Photos/Counterweight.jpg">
</p>
Parts needed (per counterwieght)
Printed parts:

* **1x** Counterweight cylinder top 
* **1x** Counterweight cylinder 
* **1x** Counterweight lid
* **1x** Counterweight 

Non printed parts
* **2x18mm** M3 bolts
* **1kg/2lbs** Table salt

1. Fill each of the counterweights to the top with table
2. Push the **Counterweight cylinder top** intot the hole in the **Counterweight**
3. Screw the **Counterweight cylinder top** followed by the **Counterweight cylinder** onto the 18mm bolt.
4. Screw the bolt into the hole in the counterweight, this will stop the lid coming off
5. Loop the GT2 belt around the **Counterweight cylinder** teeth facing inwards so they will fit together
6. Cable tie the belt together, don't worry about excess belt, don't cut it in case you want to use a larger board in future


#### First movements
DONT MOUNT THE KNIFE TOOL FOR THIS TEST, USE A PEN IF YOU LIKE
1. Tape a large piece of paper to the plywood board
2. Put the toolhead roughly in the middle
3. Open Pronterface and connect to the control board
4. Write down the thermistor temperature
3. Load a simple shape in Slic3r that is 0.2mm thick (I used Tinkercad to make a circle)
4. Slice the shape like you're printing on a 3D printer, make the layer height 0.2mm, set the hotend temperature to a few degrees lower than the room temperature
5. Export the GCode
6. Open up the GCode in a text editor and remove the first few lines to make sure you got rid of any endstop homing commands
7. Load the file in Pronterface and press start
8. The machine should roughly make the shape

This is as far as I've got.......


