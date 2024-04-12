# CSIRTs Network - Critical PAN-OS vulnerability exploited (CVE-2024-3400)
|   |   |
|---|---|
| **Date** | 12-04-2024 |
| **Number** | CNW-2024-07 | 
| **Keywords** | Palo Alto PAN-OS | 
| **CVE** | [CVE-2024-3400](https://security.paloaltonetworks.com/CVE-2024-3400) | 
| **Details** | A command injection vulnerability in the GlobalProtect feature of Palo Alto Networks PAN-OS software for specific PAN-OS versions and distinct feature configurations enables an unauthenticated attacker to execute arbitrary code with root privileges on the firewall. Fixes for PAN-OS 10.2, PAN-OS 11.0, and PAN-OS 11.1 are expected to be released by April 14, 2024. Cloud NGFW, Panorama appliances, and Prisma Access as well as other versions of PAN-OS are not impacted by this vulnerability.  |
| **Mitigation** | [The vendor advises customers with a Threat Prevention subscription to enable the available rule (Threat ID 95187)](https://live.paloaltonetworks.com/t5/globalprotect-articles/applying-vulnerability-protection-to-globalprotect-interfaces/ta-p/340184). Customers unable to apply the Threat Prevention can mitigate the impact of this vulnerability by temporarily disabling device telemetry until the device is upgraded to a fixed PAN-OS version. For additional details please refer to the specific CNW member advisories referenced below. |

## List of CSIRTs Network member alerts

| Country | Organisation | Language | Warning |
| :-----: | :----------: | :------: | :------ | 
| AT | CERT.at | DE | [Kritische Sicherheitslücke in Palo Alto PAN-OS (Global Protect) ](https://cert.at/de/warnungen/2024/4/palo-alto-cve-2024-3400) |
| BE | CERT.be | EN | |
| BG | CERT Bulgaria | BG | |
| CZ | CSIRT.CZ | CS | |
| CZ | GovCERT.CZ | CS | |
| CY | CSIRT-CY | EN | |
| DE | CERT-Bund | DE | [Palo Alto Networks Firewalls: Aktive Ausnutzung einer ungepatchten Schwachstelle](https://www.bsi.bund.de/SharedDocs/Cybersicherheitswarnungen/DE/2024/2024-231856-1032) |
| DK | CFCS | DA | |
| EE | CERT-EE | EE | |
| ES | CCN-CERT | ES | |
| ES | INCIBE | ES | [Vulnerabilidad de inyección de comandos en Palo Alto Networks PAN-OS](https://www.incibe.es/incibe-cert/alerta-temprana/avisos/vulnerabilidad-de-inyeccion-de-comandos-en-palo-alto-networks-pan-os) |
| EU | CERT-EU | EN | |
| FI | NCSC-FI | FI | [Kriittinen haavoittuvuus Palo Alton GlobalProtect Gateway -tuotteessa](https://www.kyberturvallisuuskeskus.fi/fi/haavoittuvuus_12/2024) |
| FR | CERT-FR | FR | |
| GR | GR-CSIRT | EL | |
| HR | CERT.hr | HR | |
| HR | CERT ZSIS | HR | |
| HU | NCSC-HU | HU | |
| IE | CSIRT-IE | EN | [Critical vulnerability Palo Alto_PAN_OS](https://www.ncsc.gov.ie/pdfs/2404120137_Critical_vuln_Palo_Alto_PAN_OS.pdf) |
| IT | CSIRT-ITA | IT | [Palo Alto Networks risolve vulnerabilità in PAN-OS (AL03/240412/CSIRT-ITA)](https://www.csirt.gov.it/contenuti/palo-alto-networks-risolve-vulnerabilita-in-pan-os-al03-240412-csirt-ita) |
| LT | CERT-LT | LT | |
| LU | CIRCL | EN | [TR-84 - PAN-OS (Palo Alto Networks) OS Command Injection Vulnerability in GlobalProtect Gateway - CVE-2024-3400](https://www.circl.lu/pub/tr-84/) |
| MT | CSIRTMalta | EN | |
| NL | NCSC-NL | NL | [NCSC-2024-0170 Kwetsbaarheid ontdekt in Palo Alto PAN-OS****](https://advisories.ncsc.nl/advisory?id=NCSC-2024-0170) |
| NL | CSIRT-DSP | NL | |
| PL | CERT.PL | PL | |
| PT | CERT.PT | PT | |
| RO | CERT-RO | RO | |
| SE | CERT-SE | SV | [Kritisk sårbarhet i PAN-OS](https://www.cert.se/2024/04/kritisk-sarbarhet-i-pan-os.html) |
| SI | SI-CERT | SL | |
| SK | SK-CERT | SK | |

 

For more information on the CSIRTs Network Members please visit https://csirtsnetwork.eu/ 
