# MemberType
MemberTypes are what define the properties of a member and associate a member with a machine for fabrication.

Property | Type | Description
---------| ---------| ---------
Name | *string* | The name of the object
Height | *double* | The height of the MemberType section, measured parallel to a member normal
Width | *double* | The width of the MemberType section, measured perpendicular to a member normal
LengthUnits | *LengthUnits* | The units that lengths/distances are defined in for the member type
Machine | *IMachine* | The machine associated with the MemberType

<!-- See also [StudMemberType](MemberTypes/StudMemberType.md), [HSSMemberType](MemberTypes/HSSMemberType.md) -->