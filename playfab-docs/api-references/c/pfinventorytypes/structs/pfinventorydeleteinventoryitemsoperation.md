---
author: jasonsandlin
title: "PFInventoryDeleteInventoryItemsOperation"
description: "PFInventoryDeleteInventoryItemsOperation data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFInventoryDeleteInventoryItemsOperation  

PFInventoryDeleteInventoryItemsOperation data model.  

## Syntax  
  
```cpp
typedef struct PFInventoryDeleteInventoryItemsOperation {  
    PFInventoryInventoryItemReference const* item;  
} PFInventoryDeleteInventoryItemsOperation;  
```
  
### Members  
  
**`item`** &nbsp; [PFInventoryInventoryItemReference](pfinventoryinventoryitemreference.md) const*  
*may be nullptr*  
  
(Optional) The inventory item the operation applies to.
  
  
## Requirements  
  
**Header:** PFInventoryTypes.h
  
## See also  
[PFInventoryTypes members](../pfinventorytypes_members.md)  

  
  
