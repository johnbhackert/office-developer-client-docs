---
title: "PidTagIpmWastebasketEntryId Canonical Property"
description: Outlines the PidTagIpmWastebasketEntryId canonical property, which contains the entry identifier of the standard IPM Deleted Items folder.
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidTagIpmWastebasketEntryId
api_type:
- HeaderDef
ms.assetid: 0f8dd043-66f0-4193-9b95-853bc3827f73
---

# PidTagIpmWastebasketEntryId Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains the entry identifier of the standard interpersonal message (IPM) Deleted Items folder. 
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_IPM_WASTEBASKET_ENTRYID  <br/> |
|Identifier:  <br/> |0x35E3  <br/> |
|Data type:  <br/> |PT_BINARY  <br/> |
|Area:  <br/> |Folder  <br/> |
   
## Remarks

A client application should move deleted interpersonal messages to the Deleted Items folder. If the message is already in this folder, or if this property is not supported, the client should delete the message. 
  
## Related resources

### Header files

Mapidefs.h
  
> Provides data type definitions.
    
Mapitags.h
  
> Contains definitions of properties listed as alternate names.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

