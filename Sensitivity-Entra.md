# Sensitivity Entra
---

#### Enable Sensitivity label at a Entra level


---
### Install Graph Module

`Install-Module Microsoft.Graph.Authentication -Scope CurrentUser`

`Install-Module Microsoft.Graph.Beta.Identity.DirectoryManagement -Scope CurrentUser`

---

### Connect to Graph

`Connect-MgGraph -Scopes "Directory.ReadWrite.All"`

---

`$grpUnifiedSetting.Values`
`$grpUnifiedSetting = Get-MgBetaDirectorySetting | Where-Object { $_.Values.Name -eq "EnableMIPLabels" }`
`$grpUnifiedSetting.Values`

---