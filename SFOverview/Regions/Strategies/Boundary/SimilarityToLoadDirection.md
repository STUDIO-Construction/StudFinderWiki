# Similarity to Load Direction

The similarity to load direction strategy operates on the MemberTypes of members in any given region. It seeks to apply different MemberTypes based on their orientation relative to the region's local plane Y-vector. The Y-vector is typically either World Z or World Y, depending on whether the region is drawn vertically like a wall or in the XY Plane.


To use this strategy, you must provide the MemberType to use for the vertical members and the MemberType to use for the horizontal members. Additionally, a threshold (a number between 0.0 and 1.0) can be defined to determine whether a member is classified as vertical or horizontal.  If no threshold is provide by the user it is by default set to 0.5.

![Parallel Member](/assets/objects/regions/strategies/boundary/SimilarityToLoadDirection.png/)