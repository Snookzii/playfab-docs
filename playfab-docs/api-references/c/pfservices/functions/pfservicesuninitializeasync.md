---
author: jasonsandlin
title: "PFServicesUninitializeAsync"
description: "Cleanup PlayFab Services global state."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFServicesUninitializeAsync  

Cleanup PlayFab Services global state.  

## Syntax  
  
```cpp
HRESULT PFServicesUninitializeAsync(  
    XAsyncBlock* async  
)  
```  
  
### Parameters  
  
**`async`** &nbsp; XAsyncBlock*  
  
XAsyncBlock for the async operation.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
## Remarks  
  
This will internally call PFUninitializeAsync() if PFServicesInitialize() needed to call PFInitialize() interally. Asynchronous result returned via XAsyncGetStatus.
  
## Requirements  
  
**Header:** PFServices.h
  
## See also  
[PFServices members](../pfservices_members.md)  

  
  
