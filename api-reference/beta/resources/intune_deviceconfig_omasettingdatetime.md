﻿# omaSettingDateTime resource type

OMA Settings DateTime definition.

Inherits from [omaSetting](../resources/intune_deviceconfig_omasetting.md)

### Properties
|Property|Type|Description|
|---|---|---|
|displayName|String|Display Name. Inherited from [omaSetting](../resources/intune_deviceconfig_omasetting.md)|
|description|String|Description. Inherited from [omaSetting](../resources/intune_deviceconfig_omasetting.md)|
|omaUri|String|OMA. Inherited from [omaSetting](../resources/intune_deviceconfig_omasetting.md)|
|value|DateTimeOffset|Value.|

### Relationships
None
### JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.omaSettingDateTime"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.omaSettingDateTime",
  "displayName": "String",
  "description": "String",
  "omaUri": "String",
  "value": "String (timestamp)"
}
```



