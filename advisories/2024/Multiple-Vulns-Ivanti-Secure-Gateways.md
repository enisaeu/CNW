# CSIRTs Network - Exploitation of Ivanti Connect Secure and Ivanti Policy Secure Gateway Zero-Days
|   |   |
|---|---|
| **Date** | 10-01-2024 (last updated 06-02-2024) |
| **Number** | CNW-2024-01 | 
| **Keywords** | Ivanti Connect Secure (formerly known as Pulse Connect Secure) and Policy Secure Gateway | 
| **CVE** | [CVE-2023-46805, CVE-2024-21887, CVE-2024-21888, CVE-2024-21893](https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways) | 
| **Details** | The mentioned vulnerabilities impact all supported versions – Version 9.x and 22.x - of Ivanti Connect Secure (ICS) and Ivanti Policy Secure (IPS). On 31 January, Ivanti disclosed two additional vulnerabilities impacting the Connect and Policy Connect Secure products, CVE-2024-21888 and CVE-2024-21893. These vulnerabilities allow an unauthenticated threat actor to execute arbitrary commands on the appliance with elevated privileges. Zero-day exploitation in the wild seems to have started as early as 03 December, 2023. Broader exploitation started in mid January. |
| **Mitigation** | It is critically important that organisations take immediate action and respond appropriately to the latest developments in order to resume critical business activities. The application of patches now made available have to conclude a factory reset of the devive. However, this will not necessarily resolve a past compromise. Systems should simultaneously be thoroughly analyzed per the details described in the Ivanti KB article. Furthermore, it is important that organisations running ICS VPN appliances review their logs, network telemetry, and Integrity Checker Tool results (past and present) to look for any signs of successful compromise. Initial sets of various indicators have been published by [Volexity](https://www.volexity.com/blog/2024/01/18/ivanti-connect-secure-vpn-exploitation-new-observations/) and [Mandiant](https://www.mandiant.com/resources/blog/investigating-ivanti-zero-day-exploitation). For additional details please refer to the specific CNW member advisories referenced below. |

## List of CSIRTs Network member alerts

| Country | Organisation | Language | Warning |
| :-----: | :----------: | :------: | :------ | 
| AT | CERT.at | DE | [Kritische Sicherheitslücken in Ivanti Connect Secure und Ivanti Policy Secure - aktiv ausgenützt](https://cert.at/de/warnungen/2024/1/kritische-sicherheitslucken-in-ivanti-connect-secure-und-ivanti-policy-secure-aktiv-ausgenutzt) |
| BE | CERT.be | EN | [WARNING: 2 ACTIVELY EXPLOITED ZERO-DAY VULNERABILITIES AFFECTING IVANTI CONNECT SECURE AND IVANTI POLICY SECURE – ACT NOW](https://www.cert.be/en/advisory/warning-2-actively-exploited-zero-day-vulnerabilities-affecting-ivanti-connect-secure-and-0) |
| BG | CERT Bulgaria | BG | |
| CZ | CSIRT.CZ | CS | |
| CZ | GovCERT.CZ | CS | |
| CY | CSIRT-CY | EN | |
| DE | CERT-Bund | DE | [Zero-Day Schwachstellen bei Cyber-Angriffen auf verschiedene Ivanti-Produkte genutzt](https://www.bsi.bund.de/SharedDocs/Cybersicherheitswarnungen/DE/2024/2024-205101-1032.pdf?__blob=publicationFile) |
| DK | CFCS | DA | [Varsel: Kritiske sårbarheder i netværksenheder](https://www.cfcs.dk/da/handelser/varsler/kritiske-sarbarheder-i-netvarksenheder/) |
| EE | CERT-EE | EE | |
| ES | CCN-CERT | ES | [CCN-CERT AL 01/24 Explotación de vulnerabilidades 0-day en Ivanti Connect Secure VPN](https://www.ccn-cert.cni.es/es/seguridad-al-dia/alertas-ccn-cert/12875-ccn-cert-al-01-24-explotacion-de-vulnerabilidades-0-day-en-ivanti-connect-secure-vpn.html)  |
| ES | INCIBE | ES | [Múltiples vulnerabilidades en productos Ivanti](https://www.incibe.es/incibe-cert/alerta-temprana/avisos/multiples-vulnerabilidades-en-productos-ivanti) |
| EU | CERT-EU | EN | [Critical Vulnerabilities in Ivanti Connect Secure](https://cert.europa.eu/publications/security-advisories/2024-004/) |
| FI | NCSC-FI | FI | [Ivantin tuotteissa kriittisiä hyväksikäytettyjä haavoittuvuuksia](https://www.kyberturvallisuuskeskus.fi/fi/haavoittuvuus_2/2024) |
| FR | CERT-FR | FR | [CERTFR-2024-ALE-001	Multiples vulnérabilités dans Ivanti Connect Secure et Policy Secure Gateways](https://www.cert.ssi.gouv.fr/alerte/CERTFR-2024-ALE-001/) |
| GR | GR-CSIRT | EL | |
| HR | CERT.hr | HR | [UPOZORENJE! IVANTI KRITIČNE RANJIVOSTI](https://www.cert.hr/upozorenje-ivanti-kriticne-ranjivosti/) |
| HR | CERT ZSIS | HR | |
| HU | NCSC-HU | HU | [Riasztás Ivanti termékeket érintő 0. napi kritikus sérülékenységekről](https://nki.gov.hu/figyelmeztetesek/riasztas/riasztas-ivanti-termekeket-erinto-0-napi-kritikus-serulekenysegekrol/) |
| IE | CSIRT-IE | EN | [Multiple vulnerabilities discovered within Ivanti products](https://www.ncsc.gov.ie/pdfs/Multiple_vulnerabilities_discovered_within_Ivanti_products_240110.pdf) |
| IT | CSIRT-ITA | IT | [Rilevato sfruttamento in rete delle CVE-2023-46805 e CVE-2024-21887 relative a prodotti Ivanti (AL01/240111/CSIRT-ITA)](https://www.csirt.gov.it/contenuti/rilevato-sfruttamento-in-rete-delle-cve-2023-46805-e-cve-2024-21887-relative-a-prodotti-ivanti-al01-240111-csirt-ita) |
| LT | CERT-LT | LT | |
| LV | CERT.LV | LV | [Kritiskas ievainojamības Ivanti programmatūrā Ivanti Connect Secure un Ivanti Policy Secure](https://cert.lv/lv/2024/01/kritiskas-ievainojamibas-ivanti-programmatura-ivanti-connect-secure-un-ivanti-policy-secure) |
| LU | CIRCL | EN | [TR-78 - CVE-2023-46805 (Authentication Bypass) & CVE-2024-21887 (Command Injection) for Ivanti Connect Secure and Ivanti Policy Secure Gateways](https://www.circl.lu/pub/tr-78/) |
| MT | CSIRTMalta | EN | |
| NL | NCSC-NL | NL | [Vier kritieke kwetsbaarheden in Ivanti Connect Secure en Policy Secure](https://www.ncsc.nl/actueel/nieuws/2024/februari/2/vier-kritieke-kwetsbaarheden-in-ivanti-connect-secure-en-policy-secure) |
| NL | CSIRT-DSP | NL | |
| PL | CERT.PL | PL | |
| PT | CERT.PT | PT | [Alerta de Vulnerabilidades - Ivanti Connect Secure e Policy Secure Gateways](https://dyn.cncs.gov.pt/pt/alerta-detalhe/art/135820/alerta-de-vulnerabilidades-ivanti-connect-secure-e-policy-secure-gateways) |
| RO | CERT-RO | RO | [ALERTA: Ivanti lansează o actualizare de securitate pentru gateway-urile Connect Secure și Policy Secure](https://dnsc.ro/citeste/alerta-ivanti-lanseaz-o-actualizare-de-securitate-pentru-gateway-urile-connect-secure-i-policy-secure) |
| SE | CERT-SE | SV | [Kritiska sårbarheter i Ivanti Connect Secure och Policy Secure](https://www.cert.se/2024/01/kritiska-sarbarheter-i-ivanti-connect-secure-och-policy-secure.html) |
| SI | SI-CERT | SL | [SI-CERT 2024-01 / Ranljivosti Ivanti Connect Secure VPN](https://www.cert.si/si-cert-2024-01/) |
| SK | SK-CERT | SK | [Varovanie pred kritickými zraniteľnosťami v produktoch od spoločnosti Ivanti](https://www.sk-cert.sk/sk/varovanie-pred-kritickymi-zranitelnostami-v-produktoch-od-spolocnosti-ivanti/index.html) |

 

For more information on the CSIRTs Network Members please visit https://csirtsnetwork.eu/ 
