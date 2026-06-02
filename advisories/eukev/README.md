# EU CNW Known Exploited Vulnerabilities (EU KEV)

The EU CNW KEV is noting *confirmed* exploitation activity controlled by EU CSIRTs network members and ENISA. 
It assembles a *validated listing of vulnerabilities knowingly exploited during attacks targeting entities within the EU*.

## EU KEV format and description of fields:

| Name                    | Status   | Description |
| --------                | -------- | --------    |
| cveID                   | optional | CVE ID of the vulnerability |
| euvdID                  | required | EUVD ID of the vulnerability |
| vendorProject           | required | Vendor or project name for the vulnerability |
| product                 | required | The vulnerable product |
| vulnerabilityName       | optional | Name of the vulnerability |
| dateReported            | required | Date the vulnerability was added to the catalog in the format YYYY-MM-DD |
| patchedSince            | optional | Date the vulnerability was patched in the format YYYY-MM-DD |
| originSource            | required | `Name of specific team` initially monitoring the vulnerability exploitation; `CNW` if monitored by multiple CNW members / in case of undisclosed reporting |
| shortDescription        | required | Short description of the vulnerability |
| exploitationType        | required | `Ransomware` if this vulnerability is known to have been used by a ransomware group; `APT` if known to have been used by an unspecific state-nexus groups; `unknown` if the reporting member CNW lacks confirmation that the vulnerability has been utilized by a specific entity |
| threatActorsExploiting  | optional | List of Threat Actors known for exploiting the vulnerability |
| cwes                    | optional | Common Weakness Enumeration (CWE) codes associated with this vulnerability. CWEs are in the format CWE-NNNN; note that the number portion can have any number of digits |
| notes                   | optional | Additional notes related to the vulnerability |

The EU KEV list is ordered by `dateReported` and new entries should be added to the top of the list. By default, the list is appended only. Confirmed errors may be corrected and need to be communicated to the CVD WG.

## EU KEV Publication
### Public repository

Public version (JSON format): https://github.com/enisaeu/CNW/blob/main/advisories/eukev/eukev.json

### EUVD Integration

Monitored vulnerability exploitation provided via EU KEV is added to the European Vulnerability Database (EUVD) in the following format:

```Added to EU KEV: YYYY-MM-DD 00:00```

### Vulnerability-Lookup integration of EU KEV 

A [feeder has been implemented](https://github.com/vulnerability-lookup/vulnerability-lookup/commit/bd4dc2b7394fc99e22c0ced16d261f6605c8c2b0) making listings available in Vulnerability-Lookup. 


For more information about the EU CSIRTs network, its members and how to get in contact please visit https://csirtsnetwork.eu/
