# SFCreateModifyMembers

Allows you to modify one or multiple members and their associated properties.  Properties that can be modified include MemberType, Priority, and Normal.

NOTE: If you run this command on members that are part of a region the region will automatically convert to a generic structure.

### Input
One or more StudFinder Members.

Options | Description
---------| ---------
MemberType (*Optional*) | Desired new MemberType for the selected member(s). If nothing is provided the existing property will be unchanged.
Priority (*Optional*) | New integer to be used for the priority of the selected member(s). If nothing is provided the existing property will be unchanged.
Normal (*Optional*) |  Desired new Normal guide for the selected member(s). You will have to click the start and end points of the desired normal vector. If nothing is provided the existing property will be unchanged.