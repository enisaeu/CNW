**CSIRTs network – Vulnerability affecting several programming languages (CVE-2024-1874, CVE-2024-22423, CVE-2024-24576, CVE-2024-3566)**

|   |   |
|---|---|
| Date | 16-04-2024 |
| Number | CNW-2024-08 |
| Keywords | BatBadBut, Windows applications |
| CVE | CVE-2024-1874, CVE-2024-22423, CVE-2024-24576, CVE-2024-3566 |
| Details | Command injection vulnerability affecting several programming languages (Rust, Haskell, Node.js, PHP, yt-dlp), when running on Microsoft Windows, allows attackers to execute arbitrary code disguised as arguments to the command. |
| Mitigation | Update the runtime environment by installing the patch that can prevent abuse of this vulnerability. Move the batch files to a directory that is not included in the PATH environement variable and specify the full path to avoid unexpected execution. For additional details, please refer to the specific CNW member advisories referenced below. |

**List of CSIRTs Network member alerts**

| Country | Organisation | Language | Warning |
| :-----: | :----------: | :------: | :------ | 
| AT | CERT.at | DE | |
| BE | CERT.be | EN | |
| BG | CERT Bulgaria | BG | |
| CZ | CSIRT.CZ | CS | |
| CZ | GovCERT.CZ | CS | |
| CY | CSIRT-CY | EN | |
| DE | CERT-Bund | DE | |
| DK | CFCS | DA | |
| EE | CERT-EE | EE | |
| ES | CCN-CERT | ES | |
| ES | INCIBE | ES | [CVE-2024-3566](https://www.incibe.es/incibe-cert/alerta-temprana/vulnerabilidades/cve-2024-3566), [CVE-2024-24576](https://www.incibe.es/incibe-cert/alerta-temprana/vulnerabilidades/cve-2024-24576), [CVE-2024-22423](https://www.incibe.es/incibe-cert/alerta-temprana/vulnerabilidades/cve-2024-22423)  |
| ES | INCIBE | ES | [BatBadBut: vulnerabilidad crítica en Rust](https://www.incibe.es/incibe-cert/alerta-temprana/avisos/batbadbut-vulnerabilidad-critica-en-rust) |
| EU | CERT-EU | EN | [Security Advisory 2024-035](https://cert.europa.eu/publications/security-advisories/2024-035/) |
| FI | NCSC-FI | FI | |
| FR | CERT-FR | FR | [Multiples vulnérabilités dans PHP](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0300/) |
| FR | CERT-FR | FR | [Bulletin d’actualité CERTFR-2024-ACT-017](https://www.cert.ssi.gouv.fr/actualite/CERTFR-2024-ACT-017/) |
| GR | GR-CSIRT | EL | |
| HR | CERT.hr | HR | [CVE-2024-24576](https://cve.cert.hr/cve/CVE-2024-24576), [CVE-2024-22423](https://cve.cert.hr/cve/CVE-2024-22423) |
| HR | CERT ZSIS | HR | [KRITIČNA RANJIVOST U PROGRAMSKIM JEZICIMA NA WINDOWS PLATFORMI - BATBADBUT](https://www.zsis.hr/default.aspx?id=563) |
| HU | NCSC-HU | HU | |
| IE | CSIRT-IE | EN | |
| IT | CSIRT-ITA | IT | [Vulnerabilità in Rust (AL04/240412/CSIRT-ITA)](https://www.csirt.gov.it/contenuti/vulnerabilita-in-rust-al04-240412-csirt-ita) |
| IT | CSIRT-ITA | IT | [Vulnerabilità in PHP (AL01/240415/CSIRT-ITA)](https://www.csirt.gov.it/contenuti/vulnerabilita-in-php-al01-240415-csirt-ita) | 
| LT | CERT-LT | LT | |
| LU | CIRCL | EN | |
| LV | CERT.lv | LV | |
| MT | CSIRTMalta | EN | |
| NL | NCSC-NL | NL | |
| NL | CSIRT-DSP | NL | |
| PL | CERT.PL | PL | |
| PT | CERT.PT | PT | |
| RO | CERT-RO | RO | |
| SE | CERT-SE | SV | |
| SI | SI-CERT | SL | |
| SK | SK-CERT | SK | |

