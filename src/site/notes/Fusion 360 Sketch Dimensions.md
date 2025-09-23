---
{"dg-publish":true,"permalink":"/fusion-360-sketch-dimensions/"}
---

Use dimensions in tandem with [[[Fusion 360 Sketch Constraints\|[Fusion 360 Sketch Constraints]]] to fully constrain and "lock" your sketches.

## Create a dimension

1. In the **Design** workspace, create a new sketch or edit an existing sketch to enter the **Sketch** environment.
2. On the toolbar, on the **Sketch** contextual tab, select **Create > Sketch Dimension**.
3. Select sketch geometry:
    - Single lines, parallel lines, or two points create linear dimensions.
    - Non-parallel lines create angular dimensions.
    - Circles create diameter dimensions.
    - Arcs create radius dimensions.
4. Define the value of the dimension:
    - Enter a specific value.
    - Click an existing dimension to reference it as a parameter.
    - Enter a mathematical expression that contains values, parameters, or a mix of both.
5. Press **Enter** to accept the value or expression.
6. Move the mouse pointer away from the geometry, then click to place the dimension.
7. Optional: Repeat steps 2-3 to create another dimension.
8. Press **Esc** or start another tool.

The dimensions display in the canvas. Any sketch geometry that is constrained by the dimension displays black.

![dimensions animation](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sketch/images/animation/dimensions.gif)

## Edit a dimension

1. Double-click the dimension.
2. Enter a new value or expression for the dimension.

## Convert a driving dimension to a driven dimension (or vice versa)

1. Right-click the dimension you want to convert.
2. Select **Toggle Driven** or **Toggle Driving**.

## Reference a driven dimension in another dimension

1. In the active sketch, add a new dimension or double-click to edit the value of an existing dimension.
2. Refer to a driven dimension:
    - Click a driven dimension to reference it directly.
    - Enter an expression that includes the parameter name of a driven dimension.
3. Press **Enter** to complete the value.

The computed value for the dimension updates to reflect the value or expression that references the **Driven** dimension.

Note: You cannot reference **Driven** dimensions in **Tangent** or **Offset** dimensions. If a **Tangent** or **Offset** dimension is **Driven**, you cannot reference it in other dimensions.

## Tips

- Before you place a dimension in the canvas, right-click to access contextual options for it. Examples:
    - **Radius** or **Diameter**
    - **Driven** or **Driving**
    - **Pick Circle/Arc Center** or **Pick Circle/Arc Tangent**
- From the **Browser**, right-click a sketch and select **Show Dimensions** so you can easily reference dimensions in another sketch.
- From the **Parameters** dialog, you can also reference the parameter name of driven or driving dimensions in other sketches, modeling features, and parameter expressions. Click on any dimension to see "dx" in the bottom right of your screen.  