---
{"dg-publish":true,"permalink":"/fusion-360-t-spline-modifications/"}
---

# T-Spline modifications

The tools in the **Design** workspace, **Form** contextual environment, on the **Modify** panel let you modify T-Spline bodies in Fusion.

You can use the following tools to modify a T-Spline body:

- **Edit Form** ![edit form icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/edit-form.png)
- **Edit By Curve** ![edit by curve icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/edit-by-curve.png)
- **Insert Edge** ![insert edge icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/insert-edge.png)
- **Subdivide** ![subdivide icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/subdivide.png)
- **Insert Point** ![insert point icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/insert-point.png)
- **Merge Edge** ![merge edge icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/merge-edge.png)
- **Bridge** ![bridge icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/bridge.png)
- **Fill Hole** ![fill hole icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/fill-hole.png)
- **Erase and Fill** ![erase and fill icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/erase-fill.png)
- **Weld Vertices** ![weld vertices icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/weld.png)
- **UnWeld Edges** ![unweld edges icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/unweld.png)
- **Crease** ![crease icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/crease.png)
- **UnCrease** ![uncrease icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/uncrease.png)
- **Bevel Edge** ![bevel edge icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/bevel-edge.png)
- **Slide Edge** ![slide edge icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/slide-edge.png)
- **Smooth** ![smooth icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/smooth.png)
- **Cylindrify** ![cylindrify icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/cylindrify.png)
- **Pull** ![pull icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/pull.png)
- **Flatten** ![flatten icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/flatten.png)
- **Straighten** ![straighten icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/straighten.png)
- **Match** ![match icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/match.png)
- **Interpolate** ![interpolate icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/interpolate.png)
- **Thicken** ![thicken icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/thicken.png)
- **Freeze** ![freeze icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/freeze.png)
- **Unfreeze** ![unfreeze icon](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/icon/form/unfreeze.png)

## Edit Form

The **Edit Form** tool moves, rotates, and scales T-Spline geometry. The exact behavior depends on the selected geometry.

Select faces, edges, or vertices to enable the manipulator. Double click a face or edge to select a loop.

Hold the `Alt` key and drag a manipulator to insert new geometry based on the action.

## Edit By Curve

The **Edit By Curve** tool manipulates T-Spline edges using a driving curve.

Select edges to create a driving curve. Move the control points to adjust the shape of the T-Spline edges.

Note: Adjust the **Display Mode** to see the effect of **Curve Fit** more easily. Use **Box Display** for **Control Points** and **Smooth Display** for **Surface Points**. **Control Points** (curve fitting only) performs faster than **Surface Points** (curve and surface fitting).

## Insert Edge

The **Insert Edge** tool moves the selected edge along the control polygon.

Select an edge or double click to select a loop, then specify the position of the new edge.

Set **Insertion Mode** to **Exact** to insert the edge without changing the shape of the T-Spline, however this will add more faces to maintain the shape.

## Subdivide

The **Subdivide** tool divides one or more faces into a subset of faces.

Select the faces to divide. Hold `Ctrl` (Windows) or `Command` (MacOS) to select multiple faces.

Enable the **Specify** option and set the number of faces that are added.

## Insert Point

The **Insert Point** tool inserts an edge by selecting two points.

Select a point on an edge to start. Continue selecting points on additional edges to divide multiple faces.

Slide the pointer along the edge until a red dot is shown, this is the midpoint of the edge. Set **Insertion Mode** to **Exact** to insert the point without changing the shape of the T-Spline body. This will add more faces to maintain the shape.

## Merge Edge

The **Merge Edge** tool aligns the first set of selected edges to a second set of selected edges.

Select the first set of edges then the second set of edges.

Use **Merge Edge** in place of **Weld Vertices** when connecting multiple vertices along the selected edges.

## Bridge

The **Bridge** tool creates segments to connect two opposing faces within a body or between two bodies.

Select the first set of edges then select the second set of edges. The number of edges on each side must be equal to or a multiple of each other.

You can specify the number of faces between the edges. The **Follow Curve** option will use a sketch curve to influence the shape of the bridged faces.

## Fill Hole

The **Fill Hole** tool fills an internal hole in T-Spline body.

Select the edge of the hole and set the fill type.

**Fill Star** will fill using a single face. **Reduced Star** will fill with mulitple faces to minimize star points. **Collapse** brings all vertices together at a single vertex.

## Erase and Fill

The **Erase and Fill** tool deletes a part of connected T-Spline geometry and fills new gaps with faces. You can use this to remove struts or bridges.

Select the faces to erase and set the fill type.

**Fill Star** will fill using a single face. **Reduced Star** will fill with multiple faces to minimize star points.

## Weld Vertices

The **Weld Vertices** tool joins two or more vertices.

Select two vertices to join. Window select vertices to weld within the specified tolerance.

Use the **Weld Mode** to weld the first vertex to the second or weld both selections to the midpoint.

## UnWeld Edges

The **UnWeld Edges** tool disconnects an edge or loop.

Select an edge or double click to select a loop. Hold `Ctrl` (Windows) or `Command` (MacOS) to select multiple edges.

A darker line indicates that the edge has been unwelded and is no longer connected.

## Crease

The **Crease** tool creates a sharp edge between faces.

Select edges to crease.

Regions around star/cap points (highlighted yellow) will cause edge creases to end abruptly. Boundary corner vertices (indicated by yellow dots at the surface boundary) can also be creased and uncreased.

## UnCrease

The **UnCrease** tool restores previously creased edges to their original state.

Select creased edges to uncrease.

Regions around star/cap points (highlighted yellow) will cause edge creases to end abruptly. Boundary corner vertices (indicated by yellow dots at the surface boundary) can also be creased and uncreased.

## Bevel Edge

The **Bevel Edge** tool replaces a single edge with a specified number of adjacent edges.

Select the edges then specify the position of the bevel.

The closer you make the bevel the sharper the corner will appear. The segment settings adds more edges to the beveled region.

## Slide Edge

The **Slide Edge** tool moves the selected edge along the control polygon.

Select the edges then specify the new position.

Slide the selected edge closer to another to make the transition between the two sharper.

## Smooth

The **Smooth** tool smoothes an area of the T-Spline geometry.

Select the faces to smooth and adjust the smoothing rate to see results in real time.

## Cylindrify

The **Cylindrify** tool forms uneven T-Spline geometry into a smooth cylindrical shape.

Select a face on the feature to cylindrify. The preview displays automatically in the canvas.

**Cylindrify** applies to all selected faces on a T-Spline body. You can select multiple strut or hole features on a T-Spline body at once, or uncheck **Auto Feature Selection** to select individual faces.

You can use **Cylindrify** to smooth uneven struts and holes from generative design results.

## Pull

The **Pull** tool snaps selected T-Spline vertices to a face or surface. The vertices could be control points or surface points.

Select the vertices to move and the vertices will automatically move to the nearest body.

Change the **Target Select** to specify targets. Set the **Pull Type** to move surface points or control points.

## Flatten

The **Flatten** tool projects vertices to a best fit or user defined plane.

Select the direction type then select the vertices or tangency handles to flatten.

If you flatten linked tangency handles, they will unlink from their vertices.

Note: Adjust the **Display Mode** to see the effect of each **Flatten Type** more easily. Use **Box Display** for **Control Points** and **Smooth Display** for **Surface Points**.

## Straighten

The **Straighten** tool straightens vertices to a best fit line, an existing line, or a line through two selected points.

Select the direction type, select a line or two points to define the line, then select the vertices or tangency handles to straighten.

If you straighten linked tangency handles, they will unlink from their vertices.

Note: Adjust the **Display Mode** to see the effect of each **Straighten Type** more easily. Use **Box Display** for **Control Points** and **Smooth Display** for **Surface Points**.

## Match

The **Match** tool aligns the edges of a T-Spline body with sketch curves or edges on a solid or surface body.

Select the T-Spline edges, then select the sketch curves or edges on a solid or surface body to match.

Check **Associative** to create an associative relationship between the T-Spline geometry and the parametric solid, surface, or sketch geometry. When you modify the solid, surface, or sketch geometry in the parametric design environment, the T-Spline edges will adjust to maintain their relationship with the match edges.

![associative match animation](https://help.autodesk.com/cloudhelp/ENU/Fusion-Sculpt/images/animations/match-associative.gif)

## Interpolate

The **Interpolate** tool switches the location of the surface and the control points to improve fitting. Select whether to move the control points to the surface or the surface to the control points.

Select the body then set whether you are moving control points or surface points.

**Interpolate** is best used in conjunction with the **Control Frame Display mode** (Ctrl + 2).

## Thicken

The **Thicken** tool creates a body offset.

Select the body then set the thickness and end treatments.

**Thicken** does not check for self intersections and may create surfaces that can not be converted to a solid body.

## Freeze

The **Freeze** tool freezes faces and edges on the model to prevent accidental changes.

Select faces or edges to freeze.

Light blue edges represent user-frozen regions. Darker blue edges show the buffer regions that are automatically locked to prevent shape changes in the user-frozen regions.

## Unfreeze

The **Unfreeze** tool unfreezes faces and edges that have previously been frozen.

Select faces or edges to unfreeze.

Light blue edges represent user-frozen regions. Darker blue edges show the buffer regions that are automatically locked to prevent shape changes in the user-frozen regions.