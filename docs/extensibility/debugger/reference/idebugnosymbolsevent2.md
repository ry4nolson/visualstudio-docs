---
title: "IDebugNoSymbolsEvent2 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-sdk"
ms.topic: "conceptual"
helpviewer_keywords: 
  - "IDebugNoSymbolsEvent2 interface"
ms.assetid: f6fb6388-47f6-4385-9ad5-95d62f9a7592
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# IDebugNoSymbolsEvent2
Signals the [!INCLUDE[vsprvs](../../../code-quality/includes/vsprvs_md.md)] debugger UI to warn the user that symbols could not be located for the launched executable.  
  
## Syntax  
  
```  
IDebugNoSymbolsEvent2 : IUnknown  
```  
  
## Notes for Implementers  
 Implemented by debug engines and consumed by the [!INCLUDE[vsprvs](../../../code-quality/includes/vsprvs_md.md)] debugger UI.  
  
## Requirements  
 Header: Msdbg.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll