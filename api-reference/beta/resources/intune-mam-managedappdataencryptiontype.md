---
title: "managedAppDataEncryptionType enum type"
description: "Represents the level to which app data is encrypted for managed apps"
author: "rolyon"
localization_priority: Normal
ms.prod: "Intune"
doc_type: enumPageType
---

# managedAppDataEncryptionType enum type

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Represents the level to which app data is encrypted for managed apps

## Members
|Member|Value|Description|
|:---|:---|:---|
|useDeviceSettings|0|App data is encrypted based on the default settings on the device.|
|afterDeviceRestart|1|App data is encrypted when the device is restarted.|
|whenDeviceLockedExceptOpenFiles|2|App data associated with this policy is encrypted when the device is locked, except data in files that are open|
|whenDeviceLocked|3|App data associated with this policy is encrypted when the device is locked|




