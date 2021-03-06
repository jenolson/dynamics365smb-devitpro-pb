---
title: "CompanyName Method"
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
# CompanyName Method
Gets the current company name.


## Syntax
```
Name :=   Database.CompanyName()
```
> [!NOTE]  
> This method can be invoked using property access syntax.  
> [!NOTE]  
> This method can be invoked without specifying the data type name.  


## Return Value
*Name*  
&emsp;Type: [String](../string/string-data-type.md)  
The name of the company, or an empty string if no company has been selected.  


[//]: # (IMPORTANT: END>DO_NOT_EDIT)

## Example  
 This example requires that you create the following variables and text constants.  
  
|Variable name|DataType|Length|  
|-------------------|--------------|------------|  
|CompName|Text|1024|  
  
|Name|ConstValue|  
|----------|----------------|  
|Text000|The name is %1.|  
  
```  
CompName := COMPANYNAME;  
MESSAGE(Text000, CompName);  
```  

## See Also
[Database Data Type](database-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)