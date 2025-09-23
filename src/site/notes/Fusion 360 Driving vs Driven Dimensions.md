---
{"dg-publish":true,"permalink":"/fusion-360-driving-vs-driven-dimensions/"}
---

## Driving dimensions

A **Driving** dimension is a dimension that is used to explicitly define measurement values of geometry.

**Driving** dimensions are the default type of dimension created by the **Sketch Dimension** tool, unless the dimension will over-constrain the sketch.

Note: When a sketch is over-constrained, you can choose to make a dimension **Driven** instead of **Driving**.

## Driven dimensions

A **Driven** dimension is a dimension whose value is flexible, and is determined by geometry or other dimensions, parameters, or expressions.

**Driven** dimensions:

- Are automatically added when the dimension you are adding will over-constrain the sketch.
- Display their calculated value in parentheses.
- Update automatically as the geometry, dimensions, parameters, or expressions that drive them change.
- Display as read-only values in the **Parameters** dialog, in parentheses and greyed out.

You can reference a **Driven** dimension within the same sketch, across different sketches, and in modeling features.