---
{"dg-publish":true,"permalink":"/fusion-360-side-table-demo/"}
---

Start by making sure your document settings are in inches. Find those in the [[Brain/Fusion 360 Interface#^f1cb41\|browser tree]] under document settings. Click on the pencil next to the "units" tab to change  default units.

## Step 1: Sketch 1
Start by creating a sketch on the front plane of the origin. Click create sketch in the top left of the app, and it should show 3 orange squares along with the X, Y, and Z axes. Looking at the front (X/Z) plane, you should see your [[Brain/Fusion 360 Interface#^f1cb41\|View Cube]] displaying "front" facing you. Click on that orange rectangle to create the sketch on that plane.
Then recreate this sketch:
![Pasted image 20250926122754.png](/img/user/Pasted%20image%2020250926122754.png)
This sketch started as the outermost rectangle created as a [[Fusion 360 Sketch Rectangle#^2ec480\|center point rectangle]]. 
I then used [[Fusion 360 Offset Sketch Geometry#^df2df8\|offset]] to offset it inward (making my offset value negative) 0.75".
Then use 4 small line segments as shown to divide it into parts. Diagonal on the top, and a vertical one on the bottom.
Make sure to use the [[Fusion 360 Horizontal Vertical Constraint\|horizontal/vertical constraint]] on the center point of your rectangle and the origin point to constrain the box from being able to move side to side.
Also dimension the bottom edge from the origin point 1.5" as shown in the image.
Now finish sketch.
{ #b0781e}

 - Note that all of the lines in the sketch are black. A black line is a fully constrained line. If you have blue or orange lines, they need to be constrained either via a [[Fusion 360 Sketch Dimensions\|dimension]] or one of the [[Fusion 360 Sketch Constraints\|constraints]].
## Step 2: Extrude
Next, use the extrude command to extrude the top and bottom 12 inches as shown here:
![Pasted image 20250926132608.png](/img/user/Pasted%20image%2020250926132608.png)
**Once you hit "OK" or enter to complete the extrusion, your sketch will disappear.**
We are going to find the sketch and toggle it back on in the [[Brain/Fusion 360 Interface#^f1cb41\|browser tree]]. You may need to click the little arrow next to "sketches" to drop that folder open.

With that sketch visible again, we are going to now extrude the sides 12 inches.
![Pasted image 20250926133137.png](/img/user/Pasted%20image%2020250926133137.png)
**NOTE THAT THE OPERATION** (at the bottom of the edit feature dialogue box) **HAS BEEN CHANGED FROM "JOIN" TO "NEW BODY"** 
- This is very important, as if you leave it as "join," it will connect with any bodies it touches as a single body. We want each piece as a separate body so that later on when we go to manufacture this with the laser cutter as a scale model, or the CNC at full scale, we can pull apart all of the pieces digitally, and lay them out flat to cut them out of a single piece of material.

## Step 3: Offset Extrude
Next, we are going to create an "offset extrude" so that the back face of this side table is inset 1/8" when viewed from the back. This creates a "reveal" or an *intentional setback* of that surface. 
- Reveals are often used, both to allow a slight shadow, which gives more depth to the object's shape, but also so that you don't need as tight of a tolerance when constructing.

Okay, so start by opening your extrude tool, and selecting selecting the inset rectangle on the sketch you made as so:
![Pasted image 20250926135053.png](/img/user/Pasted%20image%2020250926135053.png)
Under the dialogue box, you see a list of variables like "Type," "Profiles," "Start," etc... We want to change the "Start" from *profile plane* to *offset*. This changes your extruded body from starting on the plane your sketch was drawn on, to starting at an offset from that plane. Once you change to offset, another box will appear for a numerical value for the offset. We are going to input 0.125". 
Now in the distance numerical value (so the thickness of the extrusion,) put 0.75."

**Remember to change the operation to *new body*** otherwise it will join all your bodies into one.

- Note that your value may need to be negative - keep an eye on which direction the offset is putting your extrusion. 

## Step 4: Sketch 2
Start another sketch, this time on the bottom surface of your cabinet.
We are going to toggle into the construction geometry mode by pressing "X" on your keyboard, or finding [[Fusion 360 Sketches#^4f0cd1\|the toggle in the sketch palette]].
Next, create a line diagonally across the bottom surface of the cabinet. This will help us find the center of the piece.
![Pasted image 20250926140855.png](/img/user/Pasted%20image%2020250926140855.png)
- Notice that the line is dotted. This is because it is a construction line. If yours isn't, select it, and press "X" on your keyboard to toggle linetype.
Then, create a center rectangle just like in [[Fusion 360 Side Table Demo#^b0781e\|Step 1]]. Offset that with the [[Fusion 360 Offset Sketch Geometry#^df2df8\|offset tool]] 1.25" and draw in the line segments dividing the shape as shown:
![Pasted image 20250926141416.png](/img/user/Pasted%20image%2020250926141416.png)
- Note that all of the lines in the sketch are black. A black line is a fully constrained line. If you have blue or orange lines, they need to be constrained either via a [[Fusion 360 Sketch Dimensions\|dimension]] or one of the [[Fusion 360 Sketch Constraints\|constraints]].
Then, finish sketch.

## Step 5: Plinth Extrusion
Extrude 2 opposing sides of the sketch we just created 1.25" as new bodies. Just like we did earlier; preserving the separate bodies for individual pieces.
![Pasted image 20250926142658.png](/img/user/Pasted%20image%2020250926142658.png)