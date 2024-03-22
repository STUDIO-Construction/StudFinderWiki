# SFCreateRegion

Creates a new StudFinder region based on a closed boundary polyline and optional closed polylines representing openings in that region.  This allows you to quickly generate framing based on a selected StudFinder recipe.

### Input
This command expects a single closed boundary polyline.

Options | Description
---------| ---------
Name (*Optional*) | Desired name for the create region.  If you do not provide one this will be left blank
Openings (*Optional*) | Closed polylines that represent openings in the region.
Recipe | Desired Recipe to be used to generate the framing for this region.  This can be changed after the command is run through the StudFinder Side Panel.
MemberType (*Optional*) |  Desired MemberType to be used by the recipe.  If this is not provided the recipes default MemberType will be used.