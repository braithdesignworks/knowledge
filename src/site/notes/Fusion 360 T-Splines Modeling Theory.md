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
![Pasted image 20250922232819.png](/img/user/Pasted%20image%2020250922232819.png)

###### Less is more
- Try to pare down control points as much as possible
![Pasted image 20250922233119.png](/img/user/Pasted%20image%2020250922233119.png)

###### Avoid pinch points
- Try to avoid junctions where loops create anything other than a + shape.
- Use the "repair body" tool to highlight pinch points among other problems.
![Pasted image 20250922233312.png](/img/user/Pasted%20image%2020250922233312.png)

###### Don't feel constrained within the sculpt environment.
It's okay to use the patch environment later to connect T-Spline faces cleanly.
![Pasted image 20250922233641.png](/img/user/Pasted%20image%2020250922233641.png)

###### Use "overbuilt" models to create cleaner geometry
- Use other T-Spline surfaces to trim edges to more precisely control geometry.
![Pasted image 20250922233926.png](/img/user/Pasted%20image%2020250922233926.png)
