---
{"dg-publish":true,"permalink":"/fusion-360-unconstrained-and-constrained-sketches/"}
---

## Unconstrained and constrained sketches

In the **Sketch** environment, you can create sketches that are unconstrained, partially constrained, or fully constrained.

An **Unconstrained Sketch** contains geometry that is still free to move in space. The sketch is not fully locked by constraints and dimensions.

- In the **Browser**, the icon next to the sketch indicates that it is unconstrained: ![unconstrained sketch icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sketch/images/icon/skt/timeline-sketch.png).
- Unconstrained sketches are useful early in the design process. Unconstrained sketches are ideal when you’re experimenting and want flexibility in your early geometric design choices. You can gradually add constraints and dimensions to a sketch as you evolve your design. However, referencing unconstrained sketch geometry in downstream design features can cause unpredictable results in complex parametric assemblies.

A **Constrained Sketch** contains geometry that is locked in place by constraints and dimensions.

- In the **Browser**, the icon next to the sketch indicates that it is fully constrained: ![fully constrained sketch icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sketch/images/icon/browser/fc-sketch.png).
- Constrained sketch geometry cannot move when you try to drag it in the canvas. Constrained sketches are useful when you know the precise details of a design and are certain about your design intent. Their behavior in complex parametric designs is more predictable. However, be aware that constrained sketches can lock features in your design more robustly than you might want early in the design process. Be careful not to add too many constraints and dimensions to a sketch too early in the design process.

![unconstrained constrained animation](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sketch/images/animation/unconstrained-constrained.gif)