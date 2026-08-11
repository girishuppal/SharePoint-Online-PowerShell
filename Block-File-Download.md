# Block File Download from SharePoint site
---

### Connect to SharePoint Admin Centre
`Connect-SPOService -Url https://girishmvp-admin.sharepoint.com`

---

*Replace below URL with your corresponding site Url*

### Block File Download
Set-SPOSite -Identity https://girishmvp.sharepoint.com/sites/Brisbane -BlockDownloadPolicy $true

### Enable File Download
Set-SPOSite -Identity https://girishmvp.sharepoint.com/sites/Brisbane -BlockDownloadPolicy $false


