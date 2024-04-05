# CSIRTs Network - XZ Utils Backdoor (CVE-2024-3094)
|   |   |
|---|---|
| **Date** | 05-04-2024 |
| **Number** | CNW-2024-06 | 
| **Keywords** | XZ Utils Data Compression Library, backdoor | 
| **CVE** | [CVE-2024-3094](https://www.openwall.com/lists/oss-security/2024/03/29/4) | 
| **Details** | While debugging some performance issue on an sshd daemon a backdoor was discovered in the xz-utils package. Xz-utils is commonly used compression utility integrated into many popular distributions of Linux, e.g. for compressing release tarballs, software packages, kernel images, initramfs images and many others. The xz-utils package includes the liblzma library used by various other software packages, including sshd. |
| **Mitigation** | Affected organisations are advised to immediately stop using Fedora 41 or Fedora Rawhide, and to downgrade XZ Utils to an uncompromised version such as XZ Utils 5.4.6 Stable. Organisations that have versions 5.6.0 or 5.6.1 installed are advises to review their system logs for suspicious activity. Additionally, for those running openSUSE distributions, SUSE has published a downgrade procedure at https://build.opensuse.org/request/show/1163302. For additional details please refer to the specific CNW member advisories referenced below. |

## List of CSIRTs Network member alerts

| Country | Organisation | Language | Warning |
| :-----: | :----------: | :------: | :------ | 
| AT | CERT.at | DE | [Kritische Sicherheitslücke/Hintertüre in xz-utils (CVE-2024-3094)](https://cert.at/de/warnungen/2024/3/kritische-sicherheitslucke-in-fedora-41-und-fedora-rawhide-bibliothek-xz) |
| AT | CERT.at | DE | [Blog - Staatlich gesponserte "Entwicklung" quelloffener Software](https://cert.at/de/blog/2024/4/staatlich-gesponserte-entwicklung-quelloffener-software) |
| BE | CERT.be | EN |[CVE-2024-3094, A BACKDOOR IN THE LINUX XZ LIBRARY VERSIONS 5.6.0 & 5.6.1, CAN LEAD TO SSH AUTHENTICATION BYPASS](https://cert.be/en/advisory/warning-cve-2024-3094-backdoor-linux-xz-library-versions-560-561-can-lead-ssh) |
| BG | CERT Bulgaria | BG | |
| CZ | CSIRT.CZ | CS | |
| CZ | GovCERT.CZ | CS | |
| CY | CSIRT-CY | EN | |
| DE | CERT-Bund | DE | [Kritische Backdoor in XZ für Linux (2024-223608-1132)](https://www.bsi.bund.de/SharedDocs/Cybersicherheitswarnungen/DE/2024/2024-223608-1032.pdf?__blob=publicationFile) |
| DK | CFCS | DA | |
| EE | CERT-EE | EE | |
| ES | CCN-CERT | ES | [CCN-CERT AV 06/24 Actualizaciones de seguridad para XZ Utils](https://www.ccn-cert.cni.es/es/seguridad-al-dia/avisos-ccn-cert/12929-ccn-cert-av-06-24-actualizaciones-de-seguridad-para-xz-utils.html) |
| ES | INCIBE | ES | [Inyección de código malicioso en la librería XZ Utils](https://www.incibe.es/incibe-cert/alerta-temprana/avisos/inyeccion-de-codigo-malicioso-en-la-libreria-xz-utils) |
| EU | CERT-EU | EN | |
| FI | NCSC-FI | FI | [Kriittinen haavoittuvuus Linux-jakeluissa XZ Utils -tiedonpakkausohjelmistossa](https://www.kyberturvallisuuskeskus.fi/fi/haavoittuvuus_10/2024) |
| EU | CERT-EU | EN | [Critical Vulnerability in XZ Utils (Security Advisory 2024-032)](https://cert.europa.eu/publications/security-advisories/2024-032/) |
| FR | CERT-FR | FR | [Bulletin d’actualité CERTFR-2024-ACT-015](https://www.cert.ssi.gouv.fr/actualite/CERTFR-2024-ACT-015/) |
| GR | GR-CSIRT | EL | |
| HR | CERT.hr | HR | |
| HR | CERT ZSIS | HR | |
| HU | NCSC-HU | HU | |
| IE | CSIRT-IE | EN | [Critical Vulnerability in XZ Utils (CVE-2024-3094)](https://www.ncsc.gov.ie/pdfs/2403290139_Critical_vulnerability_in_XZ_Utils.pdf) |
| IT | CSIRT-ITA | IT |[ Rilevata backdoor in XZ Utils (AL01/240330/CSIRT-ITA) - Aggiornamento](https://www.csirt.gov.it/contenuti/rilevata-backdoor-in-xz-utils-al01-240330-csirt-ita)|
| LT | CERT-LT | LT | |
| LU | CIRCL | EN | [TR-82 - backdoor discovered in xz-utils - CVE-2024-3094](https://circl.lu/pub/tr-82/)|
| MT | CSIRTMalta | EN | |
| NL | NCSC-NL | NL | |
| NL | CSIRT-DSP | NL | |
| PL | CERT.PL | PL | |
| PT | CERT.PT | PT | |
| RO | CERT-RO | RO | |
| SE | CERT-SE | SV | [Kritisk sårbarhet i XZ Utils (xz/liblzma)](https://www.cert.se/2024/03/kritisk-sarbarhet-i-xz-utils.html) |
| SI | SI-CERT | SL | |
| SK | SK-CERT | SK | [Zadné vrátka v ssh serveri, spôsobené kompresnou knižnicou XZ/LZMA – aktualizujte ihneď!](https://www.sk-cert.sk/sk/zadne-vratka-v-ssh-serveri-sposobene-kompresnou-kniznicou-xz-lzma-aktualizujte-ihned/index.html) |
| SK | SK-CERT | SK | [SK-CERT Bezpečnostné varovanie V20240404-01](https://www.sk-cert.sk/threat/sk-cert-bezpecnostne-varovanie-v20240404-01/index.html) |

 

For more information on the CSIRTs Network Members please visit https://csirtsnetwork.eu/ 
