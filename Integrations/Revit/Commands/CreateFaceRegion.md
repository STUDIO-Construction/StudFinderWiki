# Create Face Region

Creates a new StudFinder region based on a selection of face of any Revit element. You will need to provide a recipe from the recipe selection window before generating regions. 

This command can be used to quickly apply regions and recipes to faces of mass elements, walls or any other element.

**NOTE**: 
- Currently you are limited to selecting planar faces.
- The generated StudFinder Region will not track changes to the face used to generate it.


### Input
One or more Revit faces.

Options | Description
---------| ---------
Recipe | Desired Recipe to be used to generate the framing for this region.  This can be changed after the command is run through the StudFinder Side Panel.