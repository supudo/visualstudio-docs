---
title: "Possible problem detected while building assembly: &lt;error&gt;"
ms.custom: na
ms.date: 10/10/2016
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-csharp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 4bc5108a-a96e-43be-8bba-a47441a25f3e
caps.latest.revision: 9
manager: douge
translation.priority.ht: 
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - ru-ru
  - zh-cn
  - zh-tw
translation.priority.mt: 
  - cs-cz
  - pl-pl
  - pt-br
  - tr-tr
---
# Possible problem detected while building assembly: &lt;error&gt;
The ALink tool, called by the Visual Basic compiler, reports an error building the assembly. One possible cause is a signed assembly making reference to an unsigned assembly.  
  
 This message is a warning. The compiler is continuing to generate the assembly. For more information on hiding warnings or treating warnings as errors, please see [Configuring Warnings in Visual Basic](../VS_IDE/Configuring-Warnings-in-Visual-Basic.md).  
  
 **Error ID:** BC40009  
  
### To correct this error  
  
1.  Examine the quoted error message and take appropriate action.  
  
2.  Compile the program again to see if the error recurs.  
  
3.  If the error recurs, reinstall the Visual Basic compiler.  
  
4.  If the error persists after reinstallation, gather information about the circumstances and notify Microsoft Product Support Services.  
  
## See Also  
 [PAVEOVER Product Support and Accessibility](assetId:///14e1d293-7b6d-40a6-bf3e-a92f8ee6c88c)