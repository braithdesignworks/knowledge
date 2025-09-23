---
{"dg-publish":true,"permalink":"/fusion-360-good-vs-bad-topology/"}
---

[Reference Video - 1:20](https://help.autodesk.com/view/fusion360/ENU/?guid=GUID-CC28C71A-2BF1-43D4-B3A2-3783246DBA10)

Topology is the organization of faces, edges, and vertices on a T-Spline body. Separate bodies can have the same topology (number of faces, edges, and vertices) but appear different (position of faces and transition between faces). Box and quadball are an example of bodies with the same topology but different shapes.

There is also good and bad topology. Bad topology can be control frame edges that intersect or faces that self intersect. Bad topology often prevents the T-Spline body from converting to a BREP body. Use box display or control frame display to manage topology.

**Keep faces 4 sided, and avoid star points.**
