---
author: jasonsandlin
title: "PFUserDataRecordDictionaryEntry"
description: "Dictionary entry for an associative array with PFUserDataRecord values."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFUserDataRecordDictionaryEntry  

Dictionary entry for an associative array with PFUserDataRecord values.  

## Syntax  
  
```cpp
typedef struct PFUserDataRecordDictionaryEntry {  
    const char* key;  
    PFUserDataRecord const* value;  
} PFUserDataRecordDictionaryEntry;  
```
  
### Members  
  
**`key`** &nbsp; const char*  
*is null-terminated*  
  
TBD  
  
**`value`** &nbsp; [PFUserDataRecord](pfuserdatarecord.md) const*  
  
TBD  
  
  
## Requirements  
  
**Header:** PFTypes.h
  
## See also  
[PFTypes members](../pftypes_members.md)  

  
  
