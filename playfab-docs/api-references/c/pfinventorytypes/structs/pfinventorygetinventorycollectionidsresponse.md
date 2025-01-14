---
author: jasonsandlin
title: "PFInventoryGetInventoryCollectionIdsResponse"
description: "PFInventoryGetInventoryCollectionIdsResponse data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFInventoryGetInventoryCollectionIdsResponse  

PFInventoryGetInventoryCollectionIdsResponse data model.  

## Syntax  
  
```cpp
typedef struct PFInventoryGetInventoryCollectionIdsResponse {  
    const char* const* collectionIds;  
    uint32_t collectionIdsCount;  
    const char* continuationToken;  
} PFInventoryGetInventoryCollectionIdsResponse;  
```
  
### Members  
  
**`collectionIds`** &nbsp; const char* const*  
*may be nullptr*  
  
(Optional) The requested inventory collection ids.
  
**`collectionIdsCount`** &nbsp; uint32_t  
  
Count of collectionIds
  
**`continuationToken`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) An opaque token used to retrieve the next page of collection ids, if any are available.
  
  
## Requirements  
  
**Header:** PFInventoryTypes.h
  
## See also  
[PFInventoryTypes members](../pfinventorytypes_members.md)  

  
  
