---
{"dg-publish":true,"permalink":"/fusion-360-t-splines-modeling-theory/"}
---

[Reference Video](https://youtu.be/Gf1lNAGEalQ?si=bRh2YGC7fWFIAQVn)
## How to think when using T-Splines
###### "Ring around the detail"
![Loops and Rings for T-Spline Modeling.png](/img/user/Loops%20and%20Rings%20for%20T-Spline%20Modeling.png)

###### Keep detail levels the same for easier transitions
- Try and line up ring edges between objects to be joined
- Try to match densities
- Weld connections where it makes sense (and bridge when it doesn't)
- Fill holes with 4-sided faces
![Fusion 360 T-Spline Modeling Detail Levels.png](/img/user/Fusion%20360%20T-Spline%20Modeling%20Detail%20Levels.png)

###### Less is more
- Try to pare down control points as much as possible
![Fusion 360 T-Spline Modeling Less is More.png](/img/user/Fusion%20360%20T-Spline%20Modeling%20Less%20is%20More.png)

###### Avoid pinch points
- Try to avoid junctions where loops create anything other than a + shape.
- Use the "repair body" tool to highlight pinch points among other problems.
![Fusion 360 T-Spline Modeling Pinch Points.png](/img/user/Fusion%20360%20T-Spline%20Modeling%20Pinch%20Points.png)

###### Don't feel constrained within the sculpt environment.
It's okay to use the patch environment later to connect T-Spline faces cleanly.
![Fusion 360 T-Spline Modeling Use Other Tools.png](/img/user/Fusion%20360%20T-Spline%20Modeling%20Use%20Other%20Tools.png)

###### Use "overbuilt" models to create cleaner geometry
- Use other T-Spline surfaces to trim edges to more precisely control geometry.
![Fusion 360 T-Spline Modeling Overbuild.png](/img/user/Fusion%20360%20T-Spline%20Modeling%20Overbuild.png)
