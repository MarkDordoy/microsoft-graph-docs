---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.WindowsUpdates

$params = @{
	UpdateCategory = "feature"
	MemberEntityType = "#microsoft.graph.windowsUpdates.azureADDevice"
	Ids = @(
		"String"
		"String"
		"String"
	)
}

Invoke-MgUnenrollWindowsUpdatesUpdatableAssetById -BodyParameter $params

```