---
author: jasonsandlin
title: "PFEntityIsTitlePlayer"
description: "Convenience method to check if an Entity is a Title Player. This is equivalent to calling PFEntityGetEntityKey and comparing entityKey.type to PFTitlePlayerEntityType."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFEntityIsTitlePlayer  

Convenience method to check if an Entity is a Title Player. This is equivalent to calling PFEntityGetEntityKey and comparing entityKey.type to PFTitlePlayerEntityType.  

## Syntax  
  
```cpp
HRESULT PFEntityIsTitlePlayer(  
    PFEntityHandle entityHandle,  
    bool* isTitlePlayer  
)  
```  
  
### Parameters  
  
**`entityHandle`** &nbsp; PFEntityHandle  
  
PFEntityHandle returned from a auth call.  
  
**`isTitlePlayer`** &nbsp; bool*  
*output*  
  
Will be set to true if the entity is a TitlePlayer and false otherwise.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
  
## Requirements  
  
**Header:** PFEntity.h
  
## See also  
[PFEntity members](../pfentity_members.md)  

  
  
