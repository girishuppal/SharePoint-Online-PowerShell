# Sensitivity Label
---

`Enable Support for Sensitivity Label`
Set-SPOTenant -EnableAIPIntegration $true

---


Disable Sensitivity label for SharePoint / OneDrive
`Set-SPOTenant -EnableAIPIntegration $false`


---

Enable Sensitivity Label for OneNote
`Set-SPOTenant -EnableSensitivityLabelforOneNote $true`

---
Enable Sensitivity Label for Video files
`Set-SPOTenant -EnableSensitivityLabelForVideoFiles $true`

---

Enable Sensitivity Label for video files
`Get-SPOTenant | Select-Object EnableSensitivityLabelForVideoFiles`

---
Enable Sensitivity Label for PDF documents
`Set-SPOTenant -EnableSensitivityLabelforPDF $true
