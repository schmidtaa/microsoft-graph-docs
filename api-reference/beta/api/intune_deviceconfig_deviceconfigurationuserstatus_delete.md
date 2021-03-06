﻿# Delete deviceConfigurationUserStatus> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://www.microsoft.com/en-us/cloud-platform/microsoft-intune-pricing) by the customer.
Deletes a [deviceConfigurationUserStatus](../resources/intune_deviceconfig_deviceconfigurationuserstatus.md).
### Prerequisites
One of the following **scopes** is required to execute this API:

*DeviceManagementConfiguration.ReadWrite.All*
### HTTP Request
<!-- {
  "blockType": "ignored"
}
-->
```http
DELETE /deviceManagement/deviceConfigurations/{id}/userStatuses/{id}
DELETE /deviceManagement/deviceConfigurations/{id}/rootCertificate//userStatuses/{id}
DELETE /deviceManagement/deviceConfigurations/{id}/microsoft.graph.iosScepCertificateProfile/rootCertificate//userStatuses/{id}
DELETE /deviceManagement/deviceConfigurations/{id}/microsoft.graph.macOSScepCertificateProfile/rootCertificate//userStatuses/{id}
DELETE /deviceManagement/deviceConfigurations/{id}/microsoft.graph.windows10VpnConfiguration/identityCertificate//userStatuses/{id}
DELETE /deviceManagement/deviceConfigurations/{id}/microsoft.graph.windowsPhone81VpnConfiguration/identityCertificate//userStatuses/{id}
```

### Request headers
|Header|Value|
|---|---|
|Authorization|Bearer &lt;token&gt; Required.|
|Accept|application/json|

### Request body
Do not supply a request body for this method.

### Response
If successful, this method returns a `204 No Content` response code.

### Example
##### Request
Here is an example of the request.
```http
DELETE https://graph.microsoft.com/beta/deviceManagement/deviceConfigurations/{id}/userStatuses/{id}
```

##### Response
Here is an example of the response. Note: The response object shown here may be truncated for brevity. All of the properties will be returned from an actual call.
```http
HTTP/1.1 204 No Content
```



