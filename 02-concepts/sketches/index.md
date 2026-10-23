---
title: Sketches
description: What a Sketch is and where you can draw one.
icon: ✏️
pro: false
featurebase_id: "0300654"
---

# Sketches

A **Sketch** is a flat, 2D drawing on a plane. Lines, circles, arcs and rectangles you draw make closed outlines, and a modeling Tool such as [Extrude](../../05-modeling/extrude/index.md) turns an outline into a solid. Almost every solid starts as a sketch.

You don't have to read this page to follow the tutorial. It explains what you are drawing on, and why.

## Where a Sketch can sit

A Sketch always sits on something flat:

- an **Origin Plane**: Top, Front or Right, which every Document has,
- a **Construction Plane** you made yourself,
- or **any flat face of a solid** you already built.

Tap **Create Sketch** in the sidebar and pick one of these to start. See [Planes](../planes/index.md) for the first two.

A Sketch on a face or on a Construction Plane depends on it: if you change the solid or the plane earlier in the History, the Sketch follows and is rebuilt in the new place.

## Sketch Faces

When a Sketch has a closed outline, the area inside it is a **Sketch Face**. Tools like Extrude ask you to select one. If tapping a Sketch picks nothing, its outline probably has a gap.

## Finishing a Sketch

Tap **Finish Sketch** to finish the Sketch. It becomes a step in the History, and you can come back to it later: select it in the History and tap **Edit**.

## What's next

- [Constraints](../constraints/index.md) keep a Sketch's shapes at the sizes and angles you want.
- [Text](../../04-sketching/text/index.md) adds lettering to a Sketch, to raise or engrave on a solid.
