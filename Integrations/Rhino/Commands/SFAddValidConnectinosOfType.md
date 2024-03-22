# SFAddValidConnectionsOfType

Running this command will attempt to add connections of the user selected type to any selected structures.  For any structure to be selected you only need to select one member from each desired structure.  This command will only add existing possible connections without impacting the current state of solve. The next time a structure gets solved it will continue to add the selected types of connections to this structure. 

### Input
Atleast one member from each structure to add connections to.

Options | Description
---------| ---------
Type | Connection type to be added to the allowed connections list of this structure and to be generated. By default this is set to "Stud_Dimple_Connections"