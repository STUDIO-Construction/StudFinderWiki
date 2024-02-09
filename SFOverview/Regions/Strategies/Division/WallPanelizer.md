# WallPanelizer

The wall panelizer strategy will take a single region and break it up into multiple regions based on a provided origin, spacing and direction.  This is commonly used to take a region that is larger than can be prefabricated and divide it up into assemblies of an appropriate size for prefabrication.  Regions can only be panelized in one direction at a time, but two wall panelizer strategies can be used together to effectively subdivide a region in two directions.

If an origin is not provided by default the left more point in the region is used.  You must provide a spacing and direction to use this strategy.  The direction vector you provide is the direction the subdivision rays (or subsequent panel breaks) are going.

![WallPanelizer](/assets/objects/regions/strategies/divide/WallPanelizer.png/)

