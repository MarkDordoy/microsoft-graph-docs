---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Mail

$params = @{
	"@odata.type" = "microsoft.graph.mailSearchFolder"
	FilterQuery = "contains(subject, 'Analytics')"
}

Update-MgUserMailFolder -UserId $userId -MailFolderId $mailFolderId -BodyParameter $params

```