# CAD models

Open [R300B.FCStd](R300B.FCStd) in FreeCAD 1.1.4 for the editable bent hold pose, or [R300B.step](R300B.step) in a STEP viewer. [R300B-pickup.FCStd](R300B-pickup.FCStd) and [R300B-pickup.step](R300B-pickup.step) show the open-jaw bench approach. The [baseline](baseline/) contains the first R300 design.

In the native R300B model, select **00 | Pose controls and travel limits** and edit its Data properties. `CarryHeight` drives the lift at a 300 mm radius (25 to 281.764 mm cube-center height); `Aperture` spans 40 to 66 mm. `YawCommand` spans -30 to +30 degrees, with actual yaw held at zero below 100 mm carry height. `ManualJointMode` exposes individual inspection controls. These are native expressions; no assembly add-on or macro is needed. Save edits to a separate copy.

See [fabrication and assembly](../design/fabrication.md) for fits, threads, material conditions and assembly order.
