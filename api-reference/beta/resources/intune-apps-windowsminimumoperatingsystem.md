---
title: "windowsMinimumOperatingSystem resource type"
description: "The minimum operating system required for a Windows mobile app."
author: "rolyon"
localization_priority: Normal
ms.prod: "Intune"
doc_type: resourcePageType
---

# windowsMinimumOperatingSystem resource type

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

The minimum operating system required for a Windows mobile app.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|v8_0|Boolean|Windows version 8.0 or later.|
|v8_1|Boolean|Windows version 8.1 or later.|
|v10_0|Boolean|Windows version 10.0 or later.|
|v10_1607|Boolean|Windows 10 1607 or later.|
|v10_1703|Boolean|Windows 10 1703 or later.|
|v10_1709|Boolean|Windows 10 1709 or later.|
|v10_1803|Boolean|Windows 10 1803 or later.|
|v10_1809|Boolean|Windows 10 1809 or later.|
|v10_1903|Boolean|Windows 10 1903 or later.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windowsMinimumOperatingSystem"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsMinimumOperatingSystem",
  "v8_0": true,
  "v8_1": true,
  "v10_0": true,
  "v10_1607": true,
  "v10_1703": true,
  "v10_1709": true,
  "v10_1803": true,
  "v10_1809": true,
  "v10_1903": true
}
```




