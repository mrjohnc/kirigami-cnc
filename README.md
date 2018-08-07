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
* **12x** Fixer 
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
* **4x10mm** M3 bolts
* **8x10mm** M3 bolts
* **9x18mm** M3 bolts
* **12x35mm** M3 bolts
* **1x** Large sheet of ply wood or similar stiff material



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
Parts needed
* **1x18mm** M3 bolt
* **1x** M3 square nut
* **1x** blade


#### Control board
<p align="left">
  <img height="200" src="/Photos/PCB.jpg">
</p>
Parts needed
* **4x20mm** M3 bolts

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


1. 




