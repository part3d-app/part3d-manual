---
title: Circular Array
description: Copy shapes around a center point.
icon: 🔄
pro: true
featurebase_id: "3969265"
---

# Circular Array

> [!IMPORTANT]
> **Pro:** Circular Array is part of Part3D Pro.

Circular Array makes copies of shapes in a [Sketch](../../02-concepts/sketches/index.md) around a center point, like the bolts on a flange. The copies stay tied to the original.

## When to use it

Use Circular Array for a ring of holes, the spokes of a wheel or a gear's teeth. For a row of copies, use [Linear Array](../linear-array/index.md).

## Make a Circular Array

1. While you edit a sketch, tap the wrench icon at the top of the sidebar to show the sketch Tools, then tap **Circular Array**.

   ![The Circular Array Tool in the sidebar](images/circular-array-01-open-tool.png)

2. The step bar shows **Circular Array**, **Select entities**. Tap each shape to copy, then tap **Next**. If you picked them before opening the Tool, it skips this step.

   ![Selecting the shape to copy](images/circular-array-02-select-entities.png)

3. The bar asks you to **Tap a point for the center**. Tap the point the copies turn around. Points you can pick show a ring; the origin is one of them.

   ![Picking the center](images/circular-array-03-pick-center.png)

4. The copies appear as a preview with two tags: how many there are (×6) and the angle they cover (360°). Tap a tag and enter a new value.

   ![The count and angle tags](images/circular-array-04-count-and-angle.png)

5. Tap **Apply**.

   ![The finished circular array](images/circular-array-05-result.png)

## Options

- **Count** is how many shapes there are, the original included. It starts at 6.
- **Angle** is how far round the copies go. At the full 360° they are spaced evenly all the way round. At a smaller angle they are spread from the original to the last copy across that angle.
- The handle at the center picks a different center. The handle on the other end of the arc changes the angle: drag it round the center.
- The **✕** in the bar cancels the Tool.

The copies are linked to the original by Constraints. To free a copy, select it, tap **⋯** and pick **Detach from Circular Array**.

## Change a Circular Array

1. Select the original or any copy, tap **⋯** and pick **Edit Circular Array…**. You can also double-tap a copy.
2. The count and angle tags appear on the array. Tap one and enter a new value. The array changes as soon as you set it: there is no Apply.

   ![The count and angle tags on the array](images/circular-array-06-edit-tags.png)

3. Tap **Done** when you're finished. Each change is its own step, so **Undo** takes back the last one.

   ![Eight copies, spaced evenly round](images/circular-array-07-edited.png)

- At 360°, a new count spaces all the copies evenly again. At a smaller angle, the last copy stays at the end of it.
- A lower count deletes the copies past it, with any Constraints on them. A copy you deleted or detached stays out when you change the count.
- If you delete the original or the center, the copies stay as ordinary shapes and the array can't be edited any more.

## Common problems

- **Next stays greyed out:** pick at least one shape first.
- **The copies turn around the wrong point:** tap the center handle and tap another point, or tap **Keep Current** to leave it as it was.
- **I can't tap the point I want:** only points are offered as the center. Draw a [Point](../point/index.md) there first.

> [!NOTE]
> **On Mac:** click wherever this page says tap. To change a tag, click it and type the value; there is no numpad.
