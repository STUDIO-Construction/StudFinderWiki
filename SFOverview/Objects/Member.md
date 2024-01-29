# Member
Members are the fundamental building blocks of StudFinder Projects. Members are individual fabricatable objects that are defined primarily by an Axis (ICurve) that runs the length of the Member. Members also have a MemberType, which prescribes much of the properties and behavior of the Member, including its profile/3D geometry and its path to fabrication.

Property | Type | Description
---------| ---------| ---------
Name | *string* | The name of the object
Analytical Axis | *ICurve* | The original axis of the member, without adjusted endpoints
Axis | *ICurve* | The axis of the member
Normal | *Triple* | The currently assigned normal for this member
Length | *double* | The length of the member
Priority | *int* | The priority of the member
MemberType | *IMemberType* | The currently assigned type for this member