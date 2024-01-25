# Structure
A Structure is the highest level Assembly type in a Stud Finder Project. It contains a collection of Members, as well as a collection of Connections that define interconnectivity between the Members. A Structure can also contain a collection of nested sub-Assemblies, groups of Members and/or Assemblies that form the building blocks of higher level Assemblies.
Structures maintain constraints associated with both Members and Connections. Creating a structure involves a “solving” of these constraints (i.e. the structure sets values on Member and Connection variables that are consistent with constraints). It is possible that a structure can be over-constrained, in which case a solution does not exist, and the structure will fail to generate. In this case, you must adjust your design to make it solvable.
## Create Structure
To create a structure, use the StructureBuilder class. At a minimum, you must provide at least 1 Member to the StructureBuilder. Other structure properties are optional—if you do not supply them, they will be generated automatically based on default settings.
### Add Members
You must add at least one member to the structure builder (although a single member structure is atypical—structures usually contain at least a handful of members, if not hundreds).
It is common to set Member properties before adding them to the StructureBuilder. For example, you may want to set the Name or Priority of a Member, or you may set the NormalGuide and/or MemberTypeGuide that guide the Solver as it selects values for Members.
### Add Connections
You can add your own pre-generated connections, or you can rely on the ConnectionGenerator in the StructureBuilder object to generate them for you. The default ConnectionGenerator generates connections at every intersection between Member Analytical Axes. You can replace the default ConnectionGenerator.
If you supply any pre-generated connections, the ConnectionGenerator will not run automatically. However, you can still use the ConnectionGenerator by calling StructureBuilder.GenerateConnections().
If you add any Connections that contain references to (IDs of) Members that are not present in the StructureBuilder, those connections will be thrown out when the Structure is built.
### Add MemberTypes and ConnectionTypes
You can add specific MemberTypes and ConnectionTypes that you want to be included in the Structure. If you do not add MemberTypes or ConnectionTypes, the default Types will be used.
You can pull Types from the TypeLibrary or from the current Project to be added to the StructureBuilder. Adding a Type to the StructureBuilder will also add the Type to the current Project, if it has not already been added.