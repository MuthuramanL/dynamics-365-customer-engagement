---
title: "AnchorElement | MicrosoftDocs"
description: "The topic explains about <AnchorElement> element which is one of the binding elements of the WebDDA."
ms.date: 08/23/2017
ms.topic: article
author: mh-jaya
ms.author: v-jmh
manager: shujoshi
search.audienceType: 
  - customizer
  - developer
search.app: 
  - D365CE
  - D365USD
ms.custom: 
  - dyn365-USD
---
# AnchorElement
`<AnchorElement>` element is one of the binding elements of the WebDDA.  
  
## \<AnchorElement> syntax  
 `<AnchorElement>` associates a named control to an `<a/> HTML`  element. The following code snippet shows how `<AnchorElement>` is used.  
  
```xml  
<AnchorElement name="control name">  
Search Path Elements  
</AnchorElement>  
  
```  
  
## \<AnchorElement> elements  
 The following table describes the various elements of `<AnchorElement>`:  
  
|Element|Descripton|  
|-------------|----------------|  
|`FindControl`|Returns **True** or **False** depending on whether the control can be found on the user interface (UI).|  
|`GetControlValue`|Returns the URL text.|  
|`SetControlValue`|Throws an `UnsupportedControlOperation` exception.|  
|`ExecuteControlAction`|Navigates to the specified URL.|  
  
### See also  
 [WebDDA](../unified-service-desk/web-dda.md)   
 [Use Data Driven Adapters (DDAs)](../unified-service-desk/use-data-driven-adapters-ddas.md)


[!INCLUDE[footer-include](../includes/footer-banner.md)]
