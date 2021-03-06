---
title: "windowsInformationProtectionResourceCollection resource type"
description: "Windows Information Protection Resource Collection"
author: "tfitzmac"
localization_priority: Normal
ms.prod: "Intune"
doc_type: resourcePageType
---

# windowsInformationProtectionResourceCollection resource type

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Windows Information Protection Resource Collection

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Display name|
|resources|String collection|Collection of resources|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windowsInformationProtectionResourceCollection"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsInformationProtectionResourceCollection",
  "displayName": "String",
  "resources": [
    "String"
  ]
}
```



