---
title: Reference Meshes
description: Move, copy, mirror and repeat an imported STL to model against it.
icon: 🗿
pro: false
---

# Reference Meshes

An STL you import with **Import File** becomes a reference mesh: it is drawn see-through so you can model against it, and sketch Tools snap to its corners. It isn't a solid, so Features that reshape solids (Extrude Cut, Fillet, Boolean and the like) don't take it. It is listed under **Reference Meshes** in the Solids tab.

## Place and copy it

Transform, Clone, Mirror, Linear Array and Circular Array take a reference mesh as they take a solid:

1. Open the Tool from the sidebar.
2. Pick the mesh: tap its row under **Reference Meshes** in the Solids tab, or click it in the canvas with the Pencil, mouse or trackpad. You can pick solids in the same go.
3. Set the Tool up as usual and tap **Apply**.

Each Tool adds a Feature to the History, as it does for solids, so you can edit it later and it follows your Parameters. A Transform moves the mesh; Clone, Mirror and the Arrays add copies, listed under **Reference Meshes** next to the mesh they copy.

With a mesh picked, **Merge Solids** (Mirror, Arrays) and **Linked** / **Detached** (Clone) don't show: a mesh's copy never merges and never changes.

## Rename, color, hide and delete

Tap a mesh's row in the Solids tab for **Hide**, **Color**, **Rename** and **Delete**. A copy has no Delete: delete or edit the Feature that made it. Deleting a mesh takes it out of every Feature that moves or copies it, and a Feature left with nothing to act on goes with it. Undo brings everything back.
