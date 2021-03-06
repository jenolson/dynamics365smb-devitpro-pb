---
title: "Create Method"
ms.author: solsen
ms.custom: na
ms.date: 10/01/2019
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
author: solsen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# Create Method
Creates an XmlElement node.


## Syntax
```
XmlElement :=   XmlElement.Create(LocalName: String, NamespaceUri: String, Content: Any,...)
```
## Parameters
*LocalName*  
&emsp;Type: [String](../string/string-data-type.md)  
The local name of the element to create.
        
*NamespaceUri*  
&emsp;Type: [String](../string/string-data-type.md)  
The namespace URI of the element to create.
        
*Content*  
&emsp;Type: [Any](../any/any-data-type.md)  
The content to add to the element to create.  


## Return Value
*XmlElement*  
&emsp;Type: [XmlElement](xmlelement-data-type.md)  
The created XmlElement node.  


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[XmlElement Data Type](xmlelement-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)