# Restrict One Drive and SharePoint Sites
---

Get Error help link for SharePoint site acess restriction

`Get-SPOTenant | select RestrictedAccessControlForSitesErrorHelpLink` 

---

Set Error help link for SharePoint site acess restriction

`Set-SPOTenant -RestrictedAccessControlForSitesErrorHelpLink "https://girishuppal.com"`

---

Get Error help link for OneDrive access restriction
`Get-SPOTenant | select RestrictedAccessControlForOneDriveErrorHelpLink`

---

Set Error help link for OneDrive access restriction

`Set-SPOTenant -RestrictedAccessControlForOneDriveErrorHelpLink "https://girishuppal.com"`

 ---

 Restrict Content Discovery for SharePoint site

 `Set-SPOSite -Identity <site-url> -RestrictContentOrgWideSearch $true`
 
 ---

Check Restricted Content Discovery status for a site
 `Get-SPOSite -Identity <site-url> | Select RestrictContentOrgWideSearch`

 ---
 

