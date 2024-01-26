# Connection
Connections are interactions between members.

Property | Type | Description
---------| ---------| ---------
Name | *string* | The name of the object
ConnectionType | *ConnectionType* | The currently assigned type for this connection
Members | *List\<Member>* | The members involved in this connection
MemberOperations | *Dictionary<Member, List\<IOperation>>* | Dictionary of operations for each member needed for this connection
IntersectionPoint | *Triple* | Average of the closest point on each member axis to the other member axis
IntersectionSpring | *Line* | The line (or spring) between the axes of the member axes of this connection
PlanarityTolerance | *double* | Allowed tolerance, in degrees, between ideal connection normal and actual connection
IntersectionTolerance | *double* | Allowed tolerance for connection between ideal connection distance and actual connection distance