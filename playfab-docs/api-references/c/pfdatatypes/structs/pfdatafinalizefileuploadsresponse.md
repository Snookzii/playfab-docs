---
author: jasonsandlin
title: "PFDataFinalizeFileUploadsResponse"
description: "PFDataFinalizeFileUploadsResponse data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFDataFinalizeFileUploadsResponse  

PFDataFinalizeFileUploadsResponse data model.  

## Syntax  
  
```cpp
typedef struct PFDataFinalizeFileUploadsResponse {  
    PFEntityKey const* entity;  
    PFDataGetFileMetadataDictionaryEntry const* metadata;  
    uint32_t metadataCount;  
    int32_t profileVersion;  
} PFDataFinalizeFileUploadsResponse;  
```
  
### Members  
  
**`entity`** &nbsp; [PFEntityKey](../../pftypes/structs/pfentitykey-c.md) const*  
*may be nullptr*  
  
(Optional) The entity id and type.
  
**`metadata`** &nbsp; PFDataGetFileMetadataDictionaryEntry const*  
*may be nullptr*  
  
(Optional) Collection of metadata for the entity's files.
  
**`metadataCount`** &nbsp; uint32_t  
  
Count of metadata
  
**`profileVersion`** &nbsp; int32_t  
  
The current version of the profile, can be used for concurrency control during updates.
  
  
## Requirements  
  
**Header:** PFDataTypes.h
  
## See also  
[PFDataTypes members](../pfdatatypes_members.md)  

  
  
