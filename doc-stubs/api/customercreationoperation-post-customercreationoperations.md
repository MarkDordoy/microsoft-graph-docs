---
title: "Create customerCreationOperation"
description: "Create a new customerCreationOperation object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create customerCreationOperation
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [customerCreationOperation](../resources/customercreationoperation.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST /customerCreationOperations
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [customerCreationOperation](../resources/customercreationoperation.md) object.

You can specify the following properties when creating a **customerCreationOperation**.

|Property|Type|Description|
|:---|:---|:---|
|status|String|**TODO: Add Description** Required.|
|domain|String|**TODO: Add Description** Required.|



## Response

If successful, this method returns a `201 Created` response code and a [customerCreationOperation](../resources/customercreationoperation.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_customercreationoperation_from_customercreationoperations"
}
-->
``` http
POST https://graph.microsoft.com/beta/customerCreationOperations
Content-Type: application/json
Content-length: 113

{
  "@odata.type": "#microsoft.graph.customerCreationOperation",
  "status": "String",
  "domain": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.customerCreationOperation"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.customerCreationOperation",
  "status": "String",
  "domain": "String"
}
```
