
<p align="center"><img src="graphics/CSIRT_logo.7d731656.png" alt="CSIRTs Network" width="600"/></p>

For more information about the EU CSIRTs network, its members and how to get in contact please visit https://csirtsnetwork.eu/

*Please note that the list of publications by CSIRTs NW members and partners is currently under construction.*

# CSIRTs Network - Security Guidance
## Guidance publications
- [CNW Guidance](guidance/README.md)

## Advisory collections
- [CNW Advisories](advisories/README.md)

## Security best-practices
- [Business Continuity](#business-continuity)
   - [Backups](#backups)
   - [DDoS protection](#ddos-protection)
- [Authentication](#authentication)
- [Network Security / Architecture](#network-security--architecture)
- [Cloud Security](#cloud-security)
- [Monitoring / Logging](#monitoring--logging)
- [Email Security](#email-security)
- [Incident Response](#incident-response)
- [Industrial Control System / IOT Security](#industrial-control-system--iot-security)
- [Webserver Security](#webserver-security)
- [Additional Publications](#additional-publications)

## Vulnerability Handling
- [Vulnerability Disclosure Policies](#vulnerability-disclosure-policies)
- [Vulnerability Scanning](#vulnerability-scanning)
- [Known Exploited Vulnerabilities](kev.csv)

## CNW Member Warnings and Advisories
- [CNW Member Warnings and Advisories](#cnw-member-warnings-and-advisories-1)

## CNW Member Repositories
- [CNW Member Repositories](#cnw-member-repositories-1)

## Trainings
- [Training Material](#training-material)

### Business Continuity

#### Backups
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| EU | ENISA | EN | [Guidance on Secure Backups (1 September 2021)](https://www.enisa.europa.eu/securesme/cyber-tips/strengthen-technical-measures/secure-backups) |
| LU | CIRCL | EN | [TR-55 - SquashFu - an alternate Open Source Backup solution, resilient to Crypto Ransomware attacks (12 September 2018)](https://www.circl.lu/pub/tr-55/) |

#### DDoS protection
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| AT | CERT-AT | DE | [DDoS Angriffe gegen Unternehmen in Österreich](https://cert.at/de/warnungen/2021/6/ddos-angriffe-gegen-unternehmen-in-osterreich) |
| BE | CERT.be | FR | [DDOS: protection et prévention [PDF]](https://cert.be/fr/paper/ddos-protection-et-prevention) |
| DE | BSI | DE | [Praktische Informationen zur Vermeidung von DDoS-Anfällen und Hilfestellungen bei der Reaktion](https://www.allianz-fuer-cybersicherheit.de/Webs/ACS/DE/Informationen-und-Empfehlungen/Empfehlungen-nach-Gefaehrdungen/DDoS/ddos_node.html) |
| FI | NCSC-FI | FI | [Neuvoja palvelunestohyökkäyksen estämiseksi [PDF]](https://www.kyberturvallisuuskeskus.fi/fi/julkaisut/neuvoja-palvelunestohyokkayksen-estamiseksi) |
| FR | CERT-FR | FR | [Comprendre et anticiper les attaques DDoS [PDF]](https://www.ssi.gouv.fr/administration/guide/comprendre-et-anticiper-les-attaques-ddos/) |
| HU | NCSC-HU | HU | [Védekezés a szolgáltatás megtagadásra irányuló DOS támadások ellen [PDF] (10 March 2022)](https://nki.gov.hu/wp-content/uploads/2022/03/DOS_tamadasok_elleni_vedekezes-1.pdf) |
| LT | CERT-LT | LT | [APSAUGA NUO PASLAUGŲ TRIKDYMO KIBERNETINIŲ ATAKŲ [PDF] (5 November 2021)](https://www.nksc.lt/doc/biuleteniai/2021-11-05_DDoS.pdf) |
| LU | CIRCL | EN | [TR-19 - UDP Protocols Security - Recommendations To Avoid or Limit DDoS reflection / amplification (8 July 2015)](https://www.circl.lu/pub/tr-19/) |
| NL | NCSC-NL | NL | [Factsheet Continuïteit van online diensten (02 March 2023)](https://www.ncsc.nl/documenten/factsheets/2019/juni/01/factsheet-continuiteit-van-onlinediensten) |
| NL | NCSC-NL | NL | [Factsheet Technische maatregelen voor continuïteit voor online diensten (02 March 2023)](https://www.ncsc.nl/documenten/factsheets/2019/juni/01/factsheet-technische-maatregelen-voor-continuiteit-van-online-diensten) |
| PL | KNF CSIRT | PL | [Dobre praktyki w zakresieprzeciwdziałania atakom DDoS [PDF]](https://www.knf.gov.pl/knf/pl/komponenty/img/Dobre%20praktyki%20w%20zakresie%20przeciwdzia%C5%82ania%20atakom%20DDoS_77247.pdf) |
| PL | KNF CSIRT | EN | [Good Practices in DDoS countermeasures [PDF]](https://www.knf.gov.pl/knf/pl/komponenty/img/Good_practice_against_DDoS_EN_78023.pdf) |
| SE | CERT-SE | SE | [Råd gällande förebyggande och hantering av överbelastningsangrepp (21 February 2023)](https://www.cert.se/tema/ddos/) |

### Authentication
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| NL | NCSC-NL | EN | [Factsheet Mature authentication - use of secure authentication tools (09 June 2022)](https://english.ncsc.nl/publications/factsheets/2022/juni/9/factsheet-mature-authentication---use-of-secure-authentication-tools) |
| NL | NCSC-NL | NL | [Factsheet Gebruik tweefactorauthenticatie (17 March 2023)](https://www.ncsc.nl/documenten/factsheets/2019/juni/01/factsheet-gebruik-tweefactorauthenticatie) |
| PL | CERT-PL | PL | [Hasła - Materiałów, kierowany do wielu grup odbiorców](https://cert.pl/hasla/) |

### Network Security / Architecture
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| NL | NCSC-NL | EN | [Factsheet Prepare for Zero Trust (18 August 2021)](https://english.ncsc.nl/publications/factsheets/2021/augustus/18/factsheet-prepare-for-zero-trust) |
| NL | NCSC-NL | NL | [Factsheet SOC inrichten: begin klein (03 May 2023)](https://www.ncsc.nl/documenten/factsheets/2019/juni/01/soc-inrichten) |
| NL | NCSC-NL | EN | [Factsheet Managing edge devices (10 June 2024)](https://english.ncsc.nl/publications/factsheets/2024/june/10/factsheet-managing-edge-devices) |
| NL | NCSC-NL | NL | [Kennisproduct Omgaan met edge devices (10 June 2024)](https://www.ncsc.nl/documenten/factsheets/2024/juni/10/kennisproduct-omgaan-met-edge-devices) |

### Cloud Security
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| DE | BSI | DE | [Cloud Computing Grundlagen](https://www.bsi.bund.de/dok/6622124) |
| FR | ANSSI | FR | [Prestataires de service d’informatique en nuage (SecNumCloud)](https://www.ssi.gouv.fr/administration/qualifications/prestataires-de-services-de-confiance-qualifies/prestataires-de-service-dinformatique-en-nuage-secnumcloud/) |
| FR | ANSSI | FR | [RECOMMANDATIONS POUR L’HÉBERGEMENT DANS LE CLOUD DES SYSTÈMES D’INFORMATION SENSIBLES [PDF]](https://cyber.gouv.fr/sites/default/files/document/recommandations_hebergement_cloud_systemes_information_sensible.pdf) |
| FR | ANSSI | FR | [Recommendations on hosting sensitive IS in the cloud](https://cyber.gouv.fr/sites/default/files/document/anssi_Recommendations%20on%20hosting%20sensitive%20IS%20in%20the%20cloud.pdf) |
| EU | ENISA | EN | [Cloud Security - Publication Node](https://www.enisa.europa.eu/topics/cloud-and-big-data/cloud-security) |
| NL | NCSC-NL | EN | [Factscheet 5 recommendations for securely purchasing cloud services (31 December 2020)](https://english.ncsc.nl/publications/factsheets/2020/december/31/factsheet-5-recommendations-for-securely-purchasing-cloud-services) |

### Monitoring / Logging
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| EU | ENISA | EN | [Proactive detection – Measures and information sources (26 May 2020)](https://www.enisa.europa.eu/publications/proactive-detection-measures-and-information-sources) |

### Email Security
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| CZ | NÚKIB | EN | [Methods of increasing the protection of email systems [PDF]](https://www.nukib.cz/download/uredni_deska/2021-10-08_OchranneOpatreni_final_ENG.pdf) |
| EUI | CERT-EU | EN | [E-Mail Sender Adress Forgery Mitigation [PDF]](https://media.cert.europa.eu/static/WhitePapers/CERT-EU-SWP_14_005_v1_0.pdf) |
| EUI | CERT-EU | EN | [DMARC — Defeating E-Mail Abuse [PDF]](https://cert.europa.eu/static/WhitePapers/Updated-CERT-EU_Security_Whitepaper_DMARC_17-001_v1_2.pdf) |
| LU | CIRCL | EN | [TR-60 - Phishing - Effects and precautions (26 June 2020)](https://www.circl.lu/pub/tr-60/) |
| PL | CERT-PL | PL | [Mechanizmy weryfikacji nadawcy wiadomości](https://cert.pl/posts/2021/10/mechanizmy-weryfikacji-nadawcy-wiadomosci/) |

### Incident Response
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| EUI | CERT-EU | EN | [Data Acquisition Guidelines for Investigation Purposes (2019)](https://cert.europa.eu/static/WhitePapers/CERT-EU-SWP2012-004.pdf) |
| EU | ENISA | EN | [Standards and tools for exchange and processing of actionable information (19 January 2015)](https://www.enisa.europa.eu/publications/standards-and-tools-for-exchange-and-processing-of-actionable-information) |

### Webserver Security
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| LU | CIRCL | EN | [TR-26 - Security Recommendations for Web Content Management Systems and Web Servers (28 April 2015)](https://www.circl.lu/pub/tr-26/) |
| LU | CIRCL | EN | [TR-66 - Webservers with mod_status like debug modules publicly available leak information (6 December 2021)](https://www.circl.lu/pub/tr-66/) |

### Industrial Control System / IOT Security
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| DE | BSI | EN | [Industrial Control System Security](https://www.bsi.bund.de/EN/Topics/Industry_CI/ICS/ics_node.html) |
| DE | BSI | DE | [Industrielle Steuerungs- und Automatisierungssysteme (ICS)](https://www.bsi.bund.de/ICS)] |
| DE | BSI | EN | [Industrial Control System Security: Top 10 threats and countermeasures 2022](https://www.allianz-fuer-cybersicherheit.de/SharedDocs/Downloads/Webs/ACS/DE/BSI-CS/BSI-CS_005E.html) |
| HU | NCSC-HU & SeConSys | HU | [Villamosenergetikai ipari felügyeleti rendszerek kiberbiztonsági kézikönyve 2022 [PDF] (3 March 2022)](https://nki.gov.hu/wp-content/uploads/2022/04/SeConSys_online_kezikonyv_2022_FINAL_22-03-03.pdf) |
| NL | NCSC-NL | NL | [Basis-beveiligingsmaatregelen Slimme Apparaten (IoT) (25 March 2023)](https://www.ncsc.nl/documenten/factsheets/2019/juni/01/factsheet-beveilig-apparaten-gekoppeld-aan-internet) |

### Additional Publications
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| FI | NCSC-FI | EN | [Applying artificial intelligence in cybersecurity [PDF] (13 March 2024)](https://www.kyberturvallisuuskeskus.fi/sites/default/files/media/file/Applying%20AI%20in%20cybersecurity_EN.pdf) |
| EUI | CERT-EU / ENISA | EN | [Boosting your Organisation's Cyber Resilience - Joint Publication (14 February 2022)](https://www.enisa.europa.eu/publications/boosting-your-organisations-cyber-resilience) |
| EUI | CERT-EU | EN | [Cybersecurity mitigation measures against critical threats [PDF] (09 March 2022)](https://media.cert.europa.eu/static/WhitePapers/TLP-WHITE-CERT-EU_Security_Guidance-22-001_v1_0.pdf) |
| FI | NCSC-FI | EN | [Keeping your information secure both at home and at work (12 May 2020)](https://www.kyberturvallisuuskeskus.fi/en/ncsc-news/instructions-and-guides/keeping-your-information-secure-both-home-and-work) |
| NL | NCSC-NL | EN | [Guide to Cyber Security Measures (05 August 2021)](https://english.ncsc.nl/publications/publications/2021/august/4/guide-to-cyber-security-measures) |
| NL | NCSC-NL | NL | [Factsheet Open Source Security (24 May 2023)](https://www.ncsc.nl/documenten/factsheets/2022/december/12/factsheet-open-source-security) |
| LU | CIRCL | EN | [TR-47 - Recommendations regarding Abuse handling for ISPs and registrars (23 February 2017)](https://www.circl.lu/pub/tr-47/) |

## Vulnerability Handling
### Vulnerability Disclosure Policies
| Country | Organisation | Language | CNA | Policy/Reporting |
| :-----: | :----------: | :------: | :------: | :------ |
| BE | CCB | EN | No | [Vulnerability reporting to the CCB (15 February 2023)](https://ccb.belgium.be/en/vulnerability-reporting-ccb) |
| BE | CCB | FR | No | [Signalement des vulnérabilités au CCB (15 février 2023)](https://ccb.belgium.be/fr/signalement-des-vuln%C3%A9rabilit%C3%A9s-au-ccb) |
| DE | CERT-Bund | DE | No | [Leitlinie und Richtlinie für Sicherheitsforschende (Dezember 2022)](https://www.bsi.bund.de/DE/IT-Sicherheitsvorfall/IT-Schwachstellen/it-schwachstellen_node.html) |
| DE | CERT-Bund | EN | No | [BSI CVD guideline for security researchers (December 2022)](https://www.bsi.bund.de/EN/IT-Sicherheitsvorfall/IT-Schwachstellen/it-schwachstellen_node.html) |
| ES | INCIBE-CERT | EN | Yes | [Vulnerability disclosure policy](https://www.incibe.es/incibe-cert/alerta-temprana/vulnerabilidades/asignacion-publicacion-cve) |
| ES | INCIBE-CERT | ES | Yes | [CVE Assignment and publication](https://www.incibe.es/en/incibe-cert/early-warning/vulnerabilities/cve-assignment-publication) |
| EU | ENISA | EN | Yes | [ENISA Coordinated Vulnerability Disclosure Policy](https://csirtsnetwork.eu/homepage?tab=cvd) |
| EUI | CERT-EU | EN | No | [Coordinated vulnerability disclosure policy](https://cert.europa.eu/coordinated-vulnerability-disclosure-policy) 
| FI | NCSC-FI | EN | Yes | [Vulnerability Coordination and Reporting](https://www.kyberturvallisuuskeskus.fi/en/our-services/situation-awareness-and-network-management) |
| FR | ANSSI | FR | No | [Vous souhaitez déclarer une faille de sécurité ?](https://www.ssi.gouv.fr/actualite/vous-souhaitez-declarer-une-faille-de-securite/) |
| MT | CIPD | EN | No | [National Coordinated Vulnerability Disclosure Policy](https://www.mdia.gov.mt/ncvdp/) |
| NL | NCSC-NL | EN | Yes | [Coordinated Vulnerability Disclosure: the Guideline (02 October 2018)](https://english.ncsc.nl/publications/publications/2019/juni/01/coordinated-vulnerability-disclosure-the-guideline) |
| PL | CERT-PL | EN | Yes | [Reporting vulnerabilities to CERT Polska](https://cert.pl/en/cvd/) |
| SK | SK-CERT | EN | Yes | [Vulnerability Reporting Guideline (07 October 2019)](https://www.sk-cert.sk/en/vulnerability-reporting/index.html) |
| LU | CIRCL | EN | No | [Responsible Vulnerability Disclosure (October 2019)](https://circl.lu/pub/responsible-vulnerability-disclosure/) |
| LV | CERT-LV | EN | No | [Responsible Vulnerability Disclosure (September 2019)](https://cert.lv/en/2016/09/cert-lv-responsible-disclosure-policy) |

### Vulnerability Scanning
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| DE | BSI | DE | [Schwachstellen-Analyse in Netzen unter Einsatz von OpenVAS [PDF]](https://www.allianz-fuer-cybersicherheit.de/SharedDocs/Downloads/Webs/ACS/DE/BSI-CS/BSI-CS_007.pdf?__blob=publicationFile&v=1) |
| PL | CERT-PL | EN | [Artemis vulnerability scanner is now open source](https://cert.pl/en/posts/2023/02/artemis-open-source/) |

## CNW Member Warnings and Advisories
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| AT | CERT-AT | DE | [CERT-AT Warnungen](https://cert.at/de/meldungen/warnungen/) |
| AT | CERT-AT | DE | [CERT-AT Aktuelles](https://cert.at/de/meldungen/aktuelles/) |
| BG | CERT.bg | BG | [Warnings](https://www.govcert.bg/en/category/warnings/) |
| BE | CERT.be | EN | [CERT.be Advisories](https://cert.be/en/advisories-0) |
| CZ | CERT.cz | CS | [Aktuálně z bezpečnosti](https://csirt.cz/cs/kyberbezpecnost/aktualne-z-bezpecnosti/) |
| CZ | GovCERT.CZ | CS | [Hrozby a zranitelnosti](https://nukib.gov.cz/cs/infoservis/hrozby/) |
| DE | CERT-Bund | DE | [WID - Aktuelle Sicherheitshinweise](https://wid.cert-bund.de/portal/wid/kurzinformationen) |
| DE | BSI | DE | [Cyber-Sicherheitswarnungen](https://www.bsi.bund.de/SiteGlobals/Forms/Suche/BSI/Sicherheitswarnungen/Sicherheitswarnungen_Formular.html) |
| EE | CERT-EE | EE | [Turvanõrkuste ülevaated](https://www.ria.ee/kuberturvalisus/kuberruumi-analuus-ja-ennetus/turvanorkused) |
| ES | CCN-CERT | ES | [Alertas CCN-CERT](https://www.ccn-cert.cni.es/es/seguridad-al-dia/alertas-ccn-cert?format=html) |
| ES | CCN-CERT | ES | [Avisos CCN-CERT](https://www.ccn-cert.cni.es/seguridad-al-dia/avisos-ccn-cert.html) |
| ES | INCIBE-CERT | ES | [Avisos de seguridad](https://www.incibe-cert.es/alerta-temprana/avisos-seguridad) |
| ES | INCIBE-CERT | ES | [Avisos SCI](https://www.incibe-cert.es/alerta-temprana/avisos-sci) |
| EUI | CERT-EU | EN | [CERT-EU Security Advisories](https://cert.europa.eu/cert/newsletter/en/latest_SecurityBulletins_.html) |
| FI | NCSC-FI | FI | [Haavoittuvuudet](https://www.kyberturvallisuuskeskus.fi/fi/haavoittuvuudet) |
| FI | NCSC-FI | EN | [Alerts](https://www.kyberturvallisuuskeskus.fi/en/varoitukset) |
| FR | CERT-FR | FR | [Alerte de sécurité](https://www.cert.ssi.gouv.fr/alerte/) |
| FR | CERT-FR | FR | [Avis de sécurité](https://www.cert.ssi.gouv.fr/avis/) |
| GR | GR-CSIRT | EN | [Vulnerability Archive](https://csirt.cd.mil.gr/category/vulnerabilities/) |
| HR | CERT.hr | HR | [cert cve](https://cve.cert.hr/) |
| HR | ZSIS | HR | [Security announcements](https://www.zsis.hr/default.aspx?id=12) |
| HU | NCSC-HU | HU | [Sérülékenységek](https://nki.gov.hu/figyelmeztetesek/cve-serulekenysegek/) |
| IE | NCSC-IE | EN | [Alerts & Advisories](https://www.ncsc.gov.ie/news/) |
| IT | CERT Italia | IT | [CERT News](https://www.csirt.gov.it/contenuti) |
| LT | CERT LT | LT | [Rekomendacijos](https://www.nksc.lt/rekomendacijos.html) |
| LU | CIRCL | EN | [Publications](https://www.circl.lu/pub/) |
| LV | CERT-LV | LV | [Brīdinājumi](https://cert.lv/lv/incidenti/bridinajumi) |
| NL | NCSC-NL | NL | [Overzicht gepubliceerde Advisories](https://advisories.ncsc.nl/advisories) |
| PL | CERT-PL | PL | [Kategoria CVE ](https://cert.pl/cve/) |
| PT | CNCS | PT | [CNCS Alertas](https://dyn.cncs.gov.pt/pt/alertas) |
| RO | DNSC | RO | [CERT-RO ALERTĂ](https://dnsc.ro/tag/alerte) |
| SE | CERT-SE | SV | [Nyheter](https://www.cert.se/nyheter/) |
| SK | SK-CERT | SK | [Aktuálne hrozby](https://www.sk-cert.sk/threat/index.html) |
| SI | SI-CERT | SL | [Varnostna obvestila](https://www.cert.si/category/varnostna-obvestila/) |

## CNW Member Repositories
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| AT | CERT-AT | EN | [CERT-AT Github](https://github.com/certat) |
| CZ | NÚKIB | EN/CS | [NÚKIB GitHub](https://github.com/NUKIB) |
| DE | BSI | EN | [BSI Github](https://github.com/bsi-bund) |
| DE | CERT-Bund | EN | [CERT-Bund Github](https://github.com/cert-bund) |
| EE | CERT-EE | EN | [CERT-EE Github](https://github.com/cert-ee) |
| ES | CCN-CERT | EN | [CCN-CERT Github](https://github.com/ccn-cert) |
| ES | INCIBE-CERT | EN | [INCIBE-CERT Github](https://github.com/INCIBE-CERT) |
| EUI | CERT-EU | EN | [CERT-EU Github](https://github.com/certeu) |
| EU | CNW Tooling WG | EN | [CSIRT Tooling Github](https://github.com/csirt-tooling-org) |
| FR | ANSSI | EN | [ANSSI Github](https://github.com/anssi-fr) |
| LU | CIRCL | EN | [CIRCL Github](https://github.com/CIRCL) |
| LU | Govert.LU | EN | [Govcert.lu Github](https://github.com/GOVCERT-LU) |
| NL | NCSC-NL | EN | [NCSC-NL Github](https://github.com/NCSC-NL/) |
| PL | CERT-PL | EN | [CERT-PL Github](https://github.com/CERT-Polska/) |
| SK | SK-CERT | EN | [SK-CERT Github](https://github.com/SK-CERT/) |

## Training Material
| Country | Organisation | Language | Material |
| :-----: | :----------: | :------: | :------ |
| EU | ENISA | EN | [Online Trainings Resources (Technical, Operational, Setting up a CSIRT, Legal & Cooperation](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material) |
| LU | CIRCL | EN | [MISP - Open Source Threat Intelligence Platform training materials](https://github.com/MISP/misp-training) |



For more information about CSIRTs Network Members and how to get in contact please visit https://csirtsnetwork.eu/
