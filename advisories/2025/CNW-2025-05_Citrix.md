# CSIRTs Network - Citrix NetScaler ADC and NetScaler Gateway Vulnerability Exploitation (CVE-2025-6543 and CVE-2025-5777)
|   |   |
|---|---|
| **Date** | 18-07-2025 |
| **Number** | CNW-2025-05 | 
| **Keywords** | Citrix Bleed 2 | 
| **CVE** | [CVE-2025-6543](https://euvd.enisa.europa.eu/vulnerability/CVE-2025-6543),[CVE-2025-5777](https://euvd.enisa.europa.eu/vulnerability/CVE-2025-5777) | 
| **Details** | Citrix acknowledges active exploitation of CVE-2025-6543 and are providing limited technical details to assist customers in assessing potential compromise. On July 11 CISA added CVE-2025-5777 to its Known Exploited Vulnerabilities Catalog. As of publication of this advisory page CNW members have reportedly observed exploitation of these vulnerabilities. |
| **Mitigation** | For users operating affected NetScaler ADC builds configured as a Gateway (VPN virtual server, ICA Proxy, CVPN, RDP Proxy) or AAA virtual server, immediate installation of the recommended builds is critically advised due to identified vulnerabilities. There are no available mitigations. After upgrading all NetScaler appliances in an HA pair or cluster, it is also recommended to terminate all active ICA and PCoIP sessions by running the commands kill icaconnection -all and kill pcoipConnection -all. For additional details please refer to the specific CNW member advisories referenced below. |

## List of CSIRTs Network member alerts

| Country | Organisation | Language | Warning |
| :-----: | :----------: | :------: | :------ | 
| AT | CERT-AT | DE | [CERT-AT Warnungen](https://cert.at/de/meldungen/warnungen/) |
| BG | CERT.bg | BG | [Warnings](https://www.govcert.bg/en/category/warnings/) |
| BE | CERT.be | EN | [CERT.be Advisories](https://cert.be/en/advisories-0) |
| CY | CSIRT-CY | EN | [CSIRT-CY Advisories](https://csirt.cy/cve/) |
| CZ | CERT.cz | CS | [Aktuálně z bezpečnosti](https://csirt.cz/cs/kyberbezpecnost/aktualne-z-bezpecnosti/) |
| CZ | GovCERT.CZ | CS | [Hrozby a zranitelnosti](https://nukib.gov.cz/cs/infoservis/hrozby/) |
| DE | BSI | DE | **[Citrix NetScaler ADC und NetScaler Gateway: Kritische Sicherheitslücken geschlossen und teils aktiv ausgenutzt](https://www.bsi.bund.de/SharedDocs/Cybersicherheitswarnungen/DE/2025/2025-254480-1032.pdf?__blob=publicationFile)** |
| DK | CFCS | DA | [Trusselsvurderinger](https://www.cfcs.dk/da/cybertruslen/trusselsvurderinger/) |
| EE | CERT-EE | EE | [Turvanõrkuste ülevaated](https://www.ria.ee/kuberturvalisus/kuberruumi-analuus-ja-ennetus/turvanorkused) |
| ES | CCN-CERT | ES | [Alertas CCN-CERT](https://www.ccn-cert.cni.es/es/seguridad-al-dia/alertas-ccn-cert?format=html) |
| ES | INCIBE-CERT | ES | [Múltiples vulnerabilidades en NetScaler ADC y NetScaler Gateway de Citrix](https://www.incibe.es/incibe-cert/alerta-temprana/avisos/multiples-vulnerabilidades-en-netscaler-adc-y-netscaler-gateway-de-citrix) |
| EUI | CERT-EU | EN | **[Severe Vulnerabilities in Citrix Products](https://cert.europa.eu/publications/security-advisories/2025-022/)** |
| FI | NCSC-FI | FI | **[Kriittinen ja hyväksikäytetty haavoittuvuus NetScaler ADC ja NetScaler Gateway -tuotteissa ](https://www.kyberturvallisuuskeskus.fi/fi/haavoittuvuus_13/2025)** |
| FR | CERT-FR | FR | **[Multiples vulnérabilités dans Citrix NetScaler ADC et NetScaler Gateway](https://www.cert.ssi.gouv.fr/alerte/CERTFR-2025-ALE-009/)** |
| GR | GR-CSIRT | EN | [Vulnerability Archive](https://csirt.cd.mil.gr/category/vulnerabilities/) |
| HR | CERT.hr | HR | [cert cve](https://cve.cert.hr/) |
| HR | CERT ZSIS | HR | [Security announcements](https://www.zsis.hr/default.aspx?id=12) |
| HU | NCSC-HU | HU | [Sérülékenységek](https://nki.gov.hu/figyelmeztetesek/cve-serulekenysegek/) |
| IE | NCSC-IE | EN | **[Critical Vulnerabilities in Citrix NetScaler ADC & Gateway CVE-2025-5777, CVE-2025-5349](https://www.ncsc.gov.ie/pdfs/2506190185_CVE-2025-5777.pdf)** |
| IT | CERT Italia | IT | **[CitrixBleed2: dettagli e mitigazioni per la CVE-2025-5777 relativa a Citrix NetScaler ADC e Gateway](https://www.acn.gov.it/portale/w/citrixbleed2-dettagli-e-mitigazioni-per-la-cve-2025-5777-relativa-a-citrix-netscaler-adc-e-gateway)** |
| LT | CERT LT | LT | [Rekomendacijos](https://www.nksc.lt/rekomendacijos.html) |
| LU | CIRCL | EN | [Publications](https://www.circl.lu/pub/) |
| LV | CERT-LV | LV | [Brīdinājumi](https://cert.lv/lv/incidenti/bridinajumi) |
| MT | CSIRTMalta | EN | |
| NL | NCSC-NL | NL | **[Kwetsbaarheden verholpen in Citrix NetScaler ADC en NetScaler Gateway](https://advisories.ncsc.nl/advisory?id=NCSC-2025-0196)** |
| PL | CERT-PL | PL | [Aktywnie wykorzystywane krytyczne podatności narzędzia Citrix NetScaler](https://moje.cert.pl/komunikaty/2025/17/aktywnie-wykorzystywane-krytyczne-podatnosci-narzedzia-citrix-netscaler/) |
| PT | CNCS | PT | [CNCS Alertas](https://dyn.cncs.gov.pt/pt/alertas) |
| RO | DNSC | RO | [CERT-RO ALERTĂ](https://dnsc.ro/tag/alerte) |
| SE | CERT-SE | SV | **[Sårbarheter i Citrix NetScaler](https://cert.se/2025/06/sarbarheter-i-citrix-netscaler.html)** |
| SI | SI-CERT | SL | [Varnostna obvestila](https://www.cert.si/category/varnostna-obvestila/) |
| SK | SK-CERT | SK | [Aktuálne hrozby](https://www.sk-cert.sk/threat/index.html) |








 

For more information on the CSIRTs Network Members please visit https://csirtsnetwork.eu/ 
