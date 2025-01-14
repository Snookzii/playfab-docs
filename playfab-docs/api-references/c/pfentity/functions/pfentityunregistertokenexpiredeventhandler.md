---
author: jasonsandlin
title: "PFEntityUnregisterTokenExpiredEventHandler"
description: "Unregisters a previously registered callback."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFEntityUnregisterTokenExpiredEventHandler  

Unregisters a previously registered callback.  

## Syntax  
  
```cpp
void PFEntityUnregisterTokenExpiredEventHandler(  
    PFRegistrationToken token  
)  
```  
  
### Parameters  
  
**`token`** &nbsp; PFRegistrationToken  
  
The token returned from PFEntityRegisterTokenExpiredEventHandler.  
  
  
### Return value
Type: void
  

  
  
## Requirements  
  
**Header:** PFEntity.h
  
## See also  
[PFEntity members](../pfentity_members.md)  

  
  
