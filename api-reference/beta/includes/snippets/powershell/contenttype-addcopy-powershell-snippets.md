---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Sites

$params = @{
	ContentType = "https://graph.microsoft.com/beta/sites/id/contentTypes/0x0101"
}

Add-MgSiteListContentTypeCopy -SiteId $siteId -ListId $listId -BodyParameter $params

```