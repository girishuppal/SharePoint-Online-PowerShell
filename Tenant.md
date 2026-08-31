# Tenant Settings

Get all tenant settings

`Get-SPOTenant`


Export settings to csv file

`Get-SPOTenant | Export-Csv "C:\Reports\SPOTenantSettings.csv" -NoTypeInformation`

Set one tenant setting

`Set-SPOTenant -SharingCapability ExternalUserAndGuestSharing`

Multiple tenant settings changes

`Set-SPOTenant -SharingCapability ExternalUserSharingOnly -DefaultSharingLinkType Internal -OneDriveStorageQuota 2000`
