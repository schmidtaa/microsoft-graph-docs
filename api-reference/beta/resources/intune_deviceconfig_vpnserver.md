﻿# vpnServer resource type> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://www.microsoft.com/en-us/cloud-platform/microsoft-intune-pricing) by the customer.

VPN Server definition.
### Properties
|Property|Type|Description|
|---|---|---|
|description|String|Description.|
|ipAddressOrFqdn|String|IP Address or FQDN.|
|isDefaultServer|Boolean|Default server.|

### Relationships
None
### JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.vpnServer"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.vpnServer",
  "description": "String",
  "ipAddressOrFqdn": "String",
  "isDefaultServer": true
}
```



