---
title: "importedWindowsAutopilotDeviceIdentity resource type"
description: "Imported windows autopilot devices."
author: "tfitzmac"
localization_priority: Normal
ms.prod: "Intune"
---

# importedWindowsAutopilotDeviceIdentity resource type

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Imported windows autopilot devices.

## Methods
|Method|Return Type|Description|
|:---|:---|:---|
|[List importedWindowsAutopilotDeviceIdentities](../api/intune-enrollment-importedwindowsautopilotdeviceidentity-list.md)|[importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md) collection|List properties and relationships of the [importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md) objects.|
|[Get importedWindowsAutopilotDeviceIdentity](../api/intune-enrollment-importedwindowsautopilotdeviceidentity-get.md)|[importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md)|Read properties and relationships of the [importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md) object.|
|[Create importedWindowsAutopilotDeviceIdentity](../api/intune-enrollment-importedwindowsautopilotdeviceidentity-create.md)|[importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md)|Create a new [importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md) object.|
|[Delete importedWindowsAutopilotDeviceIdentity](../api/intune-enrollment-importedwindowsautopilotdeviceidentity-delete.md)|None|Deletes a [importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md).|
|[Update importedWindowsAutopilotDeviceIdentity](../api/intune-enrollment-importedwindowsautopilotdeviceidentity-update.md)|[importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md)|Update the properties of a [importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md) object.|
|[import action](../api/intune-enrollment-importedwindowsautopilotdeviceidentity-import.md)|[importedWindowsAutopilotDeviceIdentity](../resources/intune-enrollment-importedwindowsautopilotdeviceidentity.md) collection|Not yet documented|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object|
|orderIdentifier|String|Order Id of the Windows autopilot device.|
|serialNumber|String|Serial number of the Windows autopilot device.|
|productKey|String|Product Key of the Windows autopilot device.|
|importId|String|The Import Id of the Windows autopilot device.|
|hardwareIdentifier|Binary|Hardware Blob of the Windows autopilot device.|
|state|[importedWindowsAutopilotDeviceIdentityState](../resources/intune-enrollment-importedwindowsautopilotdeviceidentitystate.md)|Current state of the imported device.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.importedWindowsAutopilotDeviceIdentity"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.importedWindowsAutopilotDeviceIdentity",
  "id": "String (identifier)",
  "orderIdentifier": "String",
  "serialNumber": "String",
  "productKey": "String",
  "importId": "String",
  "hardwareIdentifier": "binary",
  "state": {
    "@odata.type": "microsoft.graph.importedWindowsAutopilotDeviceIdentityState",
    "deviceImportStatus": "String",
    "deviceRegistrationId": "String",
    "deviceErrorCode": 1024,
    "deviceErrorName": "String"
  }
}
```





