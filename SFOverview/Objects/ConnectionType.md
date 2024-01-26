# ConnectionType
MemberTypes are what define the properties of a member and associate a member with a machine for fabrication.

Property | Type | Description
---------| ---------| ---------
Name | *string* | The name of the object
LengthUnits | *LengthUnits* | The units that lengths/distances are defined in for the member type
ValidMemberTypeTypes | *HashSet\<Type>* | The valid MemberType types in this connection type

<!--/See also [StudDimpleConnectionType](ConnectionType/StudDimpleConnectionType.md), [StudHandshakeConnectionType](ConnectionType/StudHandshakeConnectionType), [StudFlangeWebConnectionType](ConnectionType/StudFlangeWebConnectionType)-->