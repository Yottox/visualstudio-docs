---
title: "IDebugEngine2::EnumPrograms | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugEngine2::EnumPrograms"
helpviewer_keywords: 
  - "IDebugEngine2::EnumPrograms"
ms.assetid: 56bf98eb-beec-4e5f-9ebe-46c922e54c56
caps.latest.revision: 11
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugEngine2::EnumPrograms
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugEngine2::EnumPrograms](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugengine2-enumprograms).  
  
Retrieves a list of all programs being debugged by a debug engine (DE).  
  
## Syntax  
  
```cpp#  
HRESULT EnumPrograms(   
   IEnumDebugPrograms2** ppEnum  
);  
```  
  
```csharp  
int EnumPrograms(   
   out IEnumDebugPrograms2 ppEnum  
);  
```  
  
#### Parameters  
 `ppEnum`  
 [out] Returns an [IEnumDebugPrograms2](../../../extensibility/debugger/reference/ienumdebugprograms2.md) object that contains a list of all programs being debugged by a DE.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugEngine2](../../../extensibility/debugger/reference/idebugengine2.md)   
 [IEnumDebugPrograms2](../../../extensibility/debugger/reference/ienumdebugprograms2.md)

