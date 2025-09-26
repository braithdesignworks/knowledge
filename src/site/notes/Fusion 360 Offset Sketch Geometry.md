---
{"dg-publish":true,"permalink":"/fusion-360-offset-sketch-geometry/"}
---

# Offset sketch geometry

Learn how to use the **Offset** tool to offset sketch geometry to a specified distance in an active sketch in Fusion.

Note: Before you can modify sketch geometry, use the **Create Sketch** tool ![create sketch icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sketch/images/icon/skt/create.png) and use the create tools to create new sketch geometry or right-click an existing sketch and select **Edit Sketch** to enter the **Sketch** contextual environment.

1. On the **Sketch** contextual tab, select **Modify > Offset** ![offset icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sketch/images/icon/skt/offset.png).
    
    The **Offset** dialog displays.
    
2. In the **Canvas**, select the sketch curve, a chain of connected sketch curves, or a sketch profile to offset.
    
{ #df2df8}

3. In the dialog, select a **Direction** to offset and then specify the distance to offset:
    
    - **One Side**: Offsets on one side of the selected curve.
        - **Distance**: Specify the distance to offset.
    - **Two Sides**: Offsets a unique distance on each side of the selected curve.
        - **Distance 1**: Specify the distance to offset on one side.
        - **Distance 2**: Specify the distance to offset on the other side.
    - **Symmetric**: Offsets symmetrically on both sides of the selected curve.
        - **Distance**: Specify the distance to offset on both sides.
4. Click **OK**.
    

The offset geometry, offset distance dimensions, and offset constraints display in the canvas.

## Tips

- Valid selections highlight when you pause the cursor over them.
- If you select an ellipse by clicking near its major or minor axis, the offset result is an ellipse. The axis displays in the preview, and the offset distance is the same at the major and minor axes. Since an ellipse is created, the offset distance varies around the rest of the ellipse.
- If you select an ellipse by clicking away from its major or minor axis, the offset result is an oval. The axis does not display in the preview, and the offset distance is the same around the entire ellipse.
- To remove the association between the original sketch geometry and the offset sketch geometry, delete the offset glyph in the canvas.
- To maintain the offset relationship, but unlock the offset distance, delete the offset dimension.
    - To restore the dimension, right-click the offset glyph, then select **Add Offset Dimension** or add a regular sketch dimension.