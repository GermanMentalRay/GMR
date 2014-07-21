# Mel Scripts

-   *sciListAttributes:*	
	Display all attributes, their type and values in the script editor. Also display whether its a multi/parent/child. 
-   *sciCreateNode:*	
    	Create a node.
    	Select a container, if you want the node be a part of it. If the node is of type shape, also the parent transform will be included.
    	Second parameter : "skipSelect", if you do not want the created node(s) be automatically selected.
-   *sciGetSelectedNodeTypes:*	
    	Get all nodes form the current selection which have the input nodeType. If the selected node is of type transform, its shape will be returned. 
-   *sciLoadPlugin:*
	Load a plugin. Return a string array. If the procedure fails, the first element of the array is an empty string. If it succeeds, the name of the plugin is returned. 
-   *sciToggleViewportRenderer:*
	Toggle between vp2 and the old standard viewport renderer.
-   *sciConnectLightAndObject:*
	Create lightLinker connections between light and object.
   
