README for Header files, Alias files, content, and you!

The header files have 4 versions, located in the Headerfiles folder.
The contents include the label and ID available for the project content. For example: Product_Code with ID of 1.

In Data/Alias.xml is the file path and name associated with the label and ID, such as the path for Product_Code with ID of 1. The Alias.js file directs a call for loading that file by the entered value(s)!

===========================
HOW DO I LINK TO THIS STUFF?
===========================

You will need to write a link to call the popup code and the CSH Identifier.  This sample is a JavaScript popup:

<a href=”#” onclick=”return pop(‘MyWebHelp/Default_CSH.htm#Product_Code’)”> <img src=”ThingToLinkTo.jpg” border=”0″></a>

‘MyWebHelp/Default_CSH.htm#Product_Code’  in this would be that Default_CSH file in the GitHub! I am guessing the content of that file provides the JavaScript connection for the Alias.JS. Probably also controlled the look and feel. 

This is in many ways.....SUCKIE. I am sure there is a better way. 

===================================================

I would love to help come up with a better way!

<3 Lori