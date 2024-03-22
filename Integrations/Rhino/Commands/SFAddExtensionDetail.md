# SFAddExtensionDetail

Adds a HOWICK XTENDA extension detail to the selected member or members with a desired overlap.  To use this commmand you will first need to select the existing members you want to add this detail to, followed by a planar surface that represents the plane that this detail is to be placed on.

### Input
One or more StudFinder members.

Planar surface(s) that represent the plane the detail is to be placed on

Options | Description
---------| ---------
ExtensionMemberType | Desired MemberType to be used by this extension detail.  You will only be able to select HOWICK Ribbed Stud MemberTypes.
Overlap | Integer of overlap between the ribbed stud and the existing stud.  This integer is in the units that your current Rhino project is in.  By default this is set to 8.