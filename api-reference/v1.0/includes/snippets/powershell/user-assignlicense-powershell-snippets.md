---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Users.Actions

$params = @{
	AddLicenses = @(
		@{
			DisabledPlans = @(
				"11b0131d-43c8-4bbb-b2c8-e80f9a50834a"
			)
			SkuId = "guid"
		}
	)
	RemoveLicenses = @(
		"bea13e0c-3828-4daa-a392-28af7ff61a0f"
	)
}

# A UPN can also be used as -UserId.
Set-MgUserLicense -UserId $userId -BodyParameter $params

```