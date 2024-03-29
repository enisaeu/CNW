# CSIRTs Network - 3CX DesktopApp incident

|   |   |
|---|---|
| **Date** | 30-03-2023 |
| **Number** | CNW-2023-03 | 
| **Keywords** | 3CX DesktopApp | 
| **Reference** | [3CX Security Alert](https://www.3cx.com/community/threads/3cx-desktopapp-security-alert.119951/) | 
| **Details** | On 29 March, 2023, unexpected malicious activity emanating from a legitimate, signed binary of the 3CXDesktopApp - a softphone application from 3CX - was observed. The trojanized 3CXDesktopApp is [reportedly](https://www.sentinelone.com/blog/smoothoperator-ongoing-campaign-trojanizes-3cx-software-in-software-supply-chain-attack/) the first stage in a multi-stage attack chain that pulls ICO files appended with base64 data from Github and ultimately leads to a 3rd stage infostealer DLL. [According to the reddit post by a security vendor](https://old.reddit.com/r/crowdstrike/comments/125r3uu/20230329_situational_awareness_crowdstrike/), observerd malicious activity includes beaconing to actor-controlled infrastructure, deployment of second-stage payloads, and, in a small number of cases, hands-on-keyboard activity. The trojanization affects the Windows Electron client for customers running update 7. At this time, it is not yet confirmed whether the Mac installer is similarly trojanized. Ongoing investigations also look into additional applications like the Chrome extension. |
| **Mitigation** | 3CX advises customers to uninstall the app and use the PWA client instead. |

## List of CSIRTs Network member alerts

| Country | Organisation | Language | Warning |
| :-----: | :----------: | :------: | :------ | 
| AT | CERT.at | DE | [3CX Desktop App aktuell unter Beschuss - Supply-Chain Attacke naheliegend](https://cert.at/de/aktuelles/2023/3/3cx-desktop-app-aktuell-unter-beschuss-supply-chain-attacke-naheliegend) |
| BE | CERT.be | EN | [Warning: Advanced Persistent Threat actors are actively exploiting a 3CX 0-Day vulnerability](https://cert.be/fr/warning-advanced-persistent-threat-actors-are-actively-exploiting-3cx-0-day-vulnerability) |
| BG | CERT Bulgaria | BG | |
| CZ | CSIRT.CZ | CS | |
| CZ | GovCERT.CZ | CS | |
| CY | CSIRT-CY | EN | |
| DE | CERT-Bund | DE | [Schadhafte Version der 3CX Desktop App im Umlauf [PDF]](https://www.bsi.bund.de/SharedDocs/Cybersicherheitswarnungen/DE/2023/2023-214778-1032.pdf?__blob=publicationFile) |
| DK | CFCS | DA | |
| EE | CERT-EE | EE | |
| ES | CCN-CERT | ES | |
| ES | INCIBE | ES | |
| EU | CERT-EU | EN | |
| FI | NCSC-FI | FI | [Toimitusketjuhyökkäys 3CXDesktopApp-videoneuvotteluohjelmistoon](https://www.kyberturvallisuuskeskus.fi/fi/ttn_30032023) |
| FR | CERT-FR | FR | [Objet: Compromission de l’application 3CX Desktop App](https://www.cert.ssi.gouv.fr/alerte/CERTFR-2023-ALE-003/) |
| GR | GR-CSIRT | EL | |
| HR | CERT.hr | HR | |
| HR | CERT ZSIS | HR | |
| HU | NCSC-HU | HU | |
| IE | CSIRT-IE | EN | [3CX Supply Chain Compromise [PDF]](https://www.ncsc.gov.ie/pdfs/3CX_Supply_Chain_Compromise.pdf) |
| IT | CSIRT-ITA | IT | [SmoothOperator: distribuita versione malevola del software 3CXDesktopApp](https://www.csirt.gov.it/contenuti/smoothoperator-distribuita-versione-malevola-del-software-3cxdesktopapp-al03-230330-csirt-ita) |
| LT | CERT-LT | LT | |
| LU | CIRCL | EN | |
| MT | CSIRTMalta | EN | |
| NL | NCSC-NL | NL | [NCSC waarschuwt voor supplychain-aanval 3CX](https://www.ncsc.nl/actueel/nieuws/2023/maart/30/ncsc-waarschuwt-voor-supplychain-aanval-3cx) |
| NL | CSIRT-DSP | NL | |
| PL | CERT.PL | PL | |
| PT | CERT.PT | PT | [Alerta de Código Malicioso - 3CX Desktop App](https://dyn.cncs.gov.pt/pt/alerta-detalhe/art/135767/alerta-de-codigo-malicioso-3cx-desktop-app) |
| RO | CERT-RO | RO | |
| SE | CERT-SE | SV | |
| SI | SI-CERT | SL | [SI-CERT 2023-01 / Uhajanje NTLM poverilnic preko Outlook ranljivosti](https://www.cert.si/si-cert-2023-02/) |
| SK | SK-CERT | SK | |

For more information on the CSIRTs Network Members please visit https://csirtsnetwork.eu/ 
