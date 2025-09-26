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
## Step 2: Extrude
Next, use the extrude command to extrude the top and bottom 12 inches as shown here:
![Pasted image 20250926132608.png](/img/user/Pasted%20image%2020250926132608.png)
**Once you hit "OK" or enter to complete the extrusion, your sketch will disappear.**
We are going to find the sketch and toggle it back on in the [[Brain/Fusion 360 Interface#^f1cb41\|browser tree]]. You may need to click the little arrow next to "sketches" to drop that folder open.

With that sketch visible again, we are going to now extrude the sides 12 inches.
![Pasted image 20250926133137.png](/img/user/Pasted%20image%2020250926133137.png)
**NOTE THAT THE OPERATION** (at the bottom of the edit feature dialogue box) **HAS BEEN CHANGED FROM "JOIN" TO "NEW BODY"** 
- This is very important, as if you leave it as "join," it will connect with any bodies it touches as a single body. We want each piece as a separate body so that later on when we go to manufacture this with the laser cutter as a scale model, or the CNC at full scale, we can pull apart all of the pieces digitally, and lay them out flat to cut them out of a single piece of material.
