# DDD Printable Wall Control System Source Designs


---

## Parametic templates in Fusion360 & STEP formats


These are for designing your own tool holders. 

| [Centerpiece Template](Fusion360/Parametric%20Centerpiece%20Template.f3d) | |
| --- | --- |
| [<img src="images/centerpiece_template.png?raw=true" width="288">](Fusion360/Parametric%20Centerpiece%20Template.f3d) | [Parametric Centerpiece Template](Fusion360/Parametric%20Centerpiece%20Template.f3d) is a simple centerpiece template for starting the design of your own tool holders. Specify parameters for the size and number of mounting tabs, then add your own sketches for custom fit holders. Also availabe in [STEP](Step/Parametric%20Centerpiece%20Template.f3d) format.|

| [Divider Rack Template](Fusion360/Parametric%20Centerpiece%20Divider%20Rack%20Template.f3d) | |
| --- | --- |
| [<img src="images/divider_rack_template.png?raw=true" width="288">](Fusion360/Parametric%20Centerpiece%20Divider%20Rack%20Template.f3d) | [Parametric Divider Rack Template](Fusion360/Parametric%20Centerpiece%20Divider%20Rack%20Template.f3d) is a simple centerpiece template for starting the design of storage for odd shaped items like pliers, brushes, phones, and more. Specify parameters for the size and number of mounting tabs, and the number of divded slots. Tall items (more than about 5 or 6cm) aren't able to be attached to [sidepieces](../Sidepieces/] first, and then attached to the wall control panel. They won't be able to lean back far enough for the mounting tabs to slot into the panel. So this template creates slots instead of tabs for the divider rack. Use the [4mmx10mmx8mm](../Accessories/4x10x8mm%20Pin.stl) pin provided in the [Accessories](../Accessories/), and press it into the sidepiece you choose. Then mount the sidepieces on the panel first, and you'll be able to attach the divider rack between them by lowering it onto the sidepiece tabs, and sliding it backwards to lock into place. The tolerances here are pretty generous so even if your printer isn't perfectly tuned, it should still fit. Also availabe in [STEP](Step/Parametric%20Centerpiece%20Divider%20Rack%20Template.step) format.|


---

## Using Parametric Source Files
These source files aren't directly printable and will need to be modified to suit your needs with some CAD tool that can use (or convert) F360 or Step formats. They use metric measurments. 

Save the template as a new file (to preserve the original template) and then modify as needed. You can specify the width (in "Units" on the Wall Control Board), Depth, and Height as well as the number of mounting tabs to use for attaching to [sidepieces](../Sidepieces/]. Then you can add your own sketches and extrusions to make holders for your own tools, and export that as a mesh to your slicer for printing. 

A "Width Unit" here is the meaurement between mounting slots, minus the mounting tabs. Vertical wall control panels have 14 units of width, and horizontal panels have 31. 

Available User Parameters

CenterPieceWidthUnits: Number of spaces on the wall control pegboard.  Minimum 1,  maximum 14 for vertical wall control panels and 31 for horizonal panels.  Realistically your printer dimensions will determin how big you can make this.

CenterPieceDepth: Depth measurement from the wall control board extending out into space.  Minimum 17mm to fit at least one mounting tab.  Maximum  ¯\\_(ツ)_/¯
CenterPieceThickness: Lower measurements make for good shelf-like objects,  taller measurement make for better custom tool holders.  Minimum 5mm to ensure there's enough space for mounting tabs. Maximum  ¯\\_(ツ)_/¯

CountMountingTabs: Specify the number of mounting tabs to attach a sidepiece

DividerWallThickness: Specify the thickness of the divider walls (including the outter side and back walls)

DividerWallHeight: Specify how tall the divider walls should be (including the outter side and back walls)

DividerSlots: Specify the number of tool storage slots.  Minimum 1 for a single compartment (one divider wall is always combined inside of a side wall).  Maximum  ¯\\_(ツ)_/¯


