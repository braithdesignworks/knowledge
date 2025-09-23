---
{"dg-publish":true,"permalink":"/fusion-360-t-splines/"}
---


###### T-Spline modeling in Fusion 360 combines the organic flexibility of subdivision surfaces with NURBS precision, enabling intuitive creation of complex, smooth forms through push-pull operations.

## [[Fusion 360 T-Splines Modeling Theory\|Fusion 360 T-Splines Modeling Theory]]

## Once you have read through that, it is time to start modeling.

- Start by making the defining features of your model. Start off with the most similar shape from the **Form > Create** panel.
- Set up [[Fusion 360 T-Spline Symmetry\|Fusion 360 T-Spline Symmetry]]
- Start modifying the shapes. Delete faces, move vertices, edges, or faces with the [[Fusion 360 Edit Form\|Fusion 360 Edit Form]] command. [[Fusion 360 T-Spline Modifications\|Fusion 360 T-Spline Modifications]]
- Hold *option* while using the edit form command to create new edges rather than moving existing ones.
- Weld individual shapes together, or bridge to fill gaps.


## Topology Cleanup
Make sure to keep your topology nice and clean. If things get out of hand, use these tools to help clean up:
[[Fusion 360 Good vs Bad Topology\|Fusion 360 Good vs Bad Topology]]
###### **Make Uniform** 
**Form > Utilities > Make Uniform**
Evenly distributes the angles at the intersection of star points, makes faces as uniform as possible, and optionally converts all T-Points to star points on a selected T-Spline body.
###### Smooth
**Form > Modify > Smooth**
Smooths out the faces of a T-Spline body via a smoothing rate.