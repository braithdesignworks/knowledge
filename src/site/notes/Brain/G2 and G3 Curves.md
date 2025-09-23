---
{"dg-publish":true,"permalink":"/brain/g2-and-g3-curves/"}
---

Reference Video: https://youtu.be/BFHaQGhxURs?si=bqiM8g2ubshG96w1
![G0, G1, G2, and G3 Curves.png](/img/user/Brain/G0,%20G1,%20G2,%20and%20G3%20Curves.png)

## Seamless Transitions
G2 and G3 curves are ways to smooth out the transition between shapes. 
###### *G1 is typically used for engineering, G2 for product design, and G3 for automotive design.*

Note, that because you need time for the curvature to smoothly start, your curvature will need to start further back than with a simple fillet.

###### G2 Curvature is built into 2D sketches - [[Fusion 360 Curvature Constraint\|Fusion 360 Curvature Constraint]]
## 2D Construction of G3 Curvature
- Using a control point spline, create 3 control points co-linear with your line, 1 intermediary, and 3 more co-linear with the other line. 
- Constraints won't be created automatically, so use the [[Fusion 360 Coincident Constraint\|Fusion 360 Coincident Constraint]] by selecting the line leading into the transition, and then the 3 control points.
- Space out the control points with the [[Fusion 360 Equal Constraint\|Fusion 360 Equal Constraint]] and dimensions. Make the first 2 segments on both ends equal, and the remaining 2 in the middle equal to each other. Consult 5:26 on [this video](https://youtu.be/BFHaQGhxURs?si=nWRbe9xrlS7jewWs&t=326) if you are lost.
- Typically, a good starting point for the dimension of the 2 middle segments of the control point spline, is half of the overall effective radius of the curve you are making.
- 

#### 3D Construction
###### *Loft, Fillet, and Patch all have built in ability to use G2.*
