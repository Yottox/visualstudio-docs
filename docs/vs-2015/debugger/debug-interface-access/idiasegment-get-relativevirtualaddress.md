---
title: "IDiaSegment::get_relativeVirtualAddress | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IDiaSegment::get_relativeVirtualAddress method"
ms.assetid: b6a573a1-3671-4c1c-a5c2-2ab8f07fd510
caps.latest.revision: 12
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# IDiaSegment::get_relativeVirtualAddress
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDiaSegment::get_relativeVirtualAddress](https://docs.microsoft.com/visualstudio/debugger/debug-interface-access/idiasegment-get-relativevirtualaddress).  
  
Retrieves the relative virtual address (RVA) of the beginning of the section.  
  
## Syntax  
  
```cpp#  
HRESULT get_relativeVirtualAddress (   
   DWORD* pRetVal  
);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] Returns the RVA of the beginning of the section.  
  
## Return Value  
 If successful, returns `S_OK`. Returns `S_FALSE` if this property is not supported. Otherwise, returns an error code.  
  
## See Also  
 [IDiaSegment](../../debugger/debug-interface-access/idiasegment.md)



