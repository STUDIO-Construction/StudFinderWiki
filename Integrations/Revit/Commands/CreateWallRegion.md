# Create Wall Region

Creates a new StudFinder region based on a selection of Revit Wall Elements. The newly created region will be created at the center of the "Structural" layer of the wall.  If no "Structural" layer exists as defined in its Type Properties StudFinder will default to the center of the first layer from the exterior. You will need to provide a recipe from the recipe selection window before generating regions. The new StudFinder Region will respond to updated profiles of the wall based on movement of doors, windows, or other elements that will cut the wall geometry. 

This command can be used to quickly generate multiple regions at one time from multiple wall selections. 

**NOTE**: Currently you are limited to selecting planar walls.

### Input
One or more Revit wall elements.

Options | Description
---------| ---------
Recipe | Desired Recipe to be used to generate the framing for this region.  This can be changed after the command is run through the StudFinder Side Panel.