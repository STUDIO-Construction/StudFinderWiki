# Create Ceiling Region

Creates a new StudFinder region based on a selection of Revit Ceiling Elements. The newly created region will be created at the center of the "Structural" layer of the ceiling.  If no "Structural" layer exists as defined in its Type Properties StudFinder will default to the center of the first layer from the exterior. You will need to provide a recipe from the recipe selection window before generating regions. The new StudFinder Region will respond to updated profiles of the ceiling based on movement of hosted elements, shafts or other elements that cut the geometry of the ceiling element. 

This command can be used to quickly generate multiple regions at one time from multiple ceiling selections. 

**NOTE**: Currently you are limited to selecting planar ceilings.

### Input
One or more Revit ceiling elements.

Options | Description
---------| ---------
Recipe | Desired Recipe to be used to generate the framing for this region.  This can be changed after the command is run through the StudFinder Side Panel.