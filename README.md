# ActiveDirectoryTools

## Revision History

### 2.1.0.0
Added dependency to BAMCIS.Common, BAMCIS.Logging, BAMCIS.TokenManipulation, and BAMCIS.FileIO for shared cmdlets.

Added cmdlets:
		Rename-ADSite
		Add-ADSiteSubnet
		Get-ADSysvolLocalPath
		Enable-ADRecycleBin
		Enable-ADCentralPolicyStore
		Enable-MSSGPOSettings
		Get-ADForestTrust
		Set-ADForestTrustSIDFiltering
		Get-ADForestTrustSelectiveAuthentication
		Set-ADForestTrustSelectiveAuthentication
		Set-ADForestTrustKerberosAESEncryption
		New-ADForestTrust

### 2.0.0.9
Added the Get-ADComputerSite cmdlet.

### 2.0.0.8
Changed the name of the Get-ADNestedGroupMembership cmdlet to Get-ADPrincipalGroupMembership. Added the Get-ADGroupMembers cmdlet.