---
author: jasonsandlin
title: "PFCatalogGetEntityItemReviewResponse"
description: "PFCatalogGetEntityItemReviewResponse data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFCatalogGetEntityItemReviewResponse  

PFCatalogGetEntityItemReviewResponse data model.  

## Syntax  
  
```cpp
typedef struct PFCatalogGetEntityItemReviewResponse {  
    PFCatalogReview const* review;  
} PFCatalogGetEntityItemReviewResponse;  
```
  
### Members  
  
**`review`** &nbsp; [PFCatalogReview](pfcatalogreview.md) const*  
*may be nullptr*  
  
(Optional) The review the entity submitted for the requested item.
  
  
## Requirements  
  
**Header:** PFCatalogTypes.h
  
## See also  
[PFCatalogTypes members](../pfcatalogtypes_members.md)  

  
  
