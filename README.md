\---



\# Project Walkthrough



\## Architecture



| Screenshot | Description |

|------------|-------------|

| Architecture/16-NSG-Inbound-RDP-Rule.png | Network Security Group with restricted RDP access |

| Architecture/17-NSG-Inbound-Outbound-Rules.png | Inbound and outbound NSG rules |

| Architecture/18-NSG-Multiple-RDP-Rules.png | Additional RDP rule configuration |



\### Network Security Group (NSG)



The Network Security Group (NSG) was configured to control inbound and outbound network traffic to the Windows 10 virtual machine.



The following configurations were implemented:



\- Allowed Remote Desktop Protocol (RDP) access.

\- Restricted access using custom inbound security rules.

\- Verified default Azure inbound and outbound security rules.

\- Reviewed multiple RDP rule configurations during testing.



\#### Screenshots



!\[NSG RDP Rule](Screenshots/Architecture/16-NSG-Inbound-RDP-Rule.png)



\*Figure 1: Custom RDP inbound rule.\*



!\[NSG Rules](Screenshots/Architecture/17-NSG-Inbound-Outbound-Rules.png)



\*Figure 2: Default inbound and outbound security rules.\*



!\[Multiple RDP Rules](Screenshots/Architecture/18-NSG-Multiple-RDP-Rules.png)



\*Figure 3: Multiple RDP rule configurations used during testing.\*



\## Microsoft Defender



| Screenshot | Description |

|------------|-------------|

| Screenshots/01-Advanced-Hunting-Process-Events.png | Advanced Hunting process events |

| Screenshots/02-Advanced-Hunting-Timeline.png | Timeline visualization |

| Screenshots/03-Device-Inventory-Overview.png | Device inventory overview |

| Screenshots/04-Device-Response-Actions.png | Device response actions |

| Screenshots/07-Device-Timeline-Events.png | Device timeline |

| Screenshots/08-Device-Inventory-All-Devices.png | Device inventory |



\## Microsoft Sentinel



| Screenshot | Description |

|------------|-------------|

| Screenshots/05-Microsoft-Sentinel-Analytics.png | Sentinel Analytics |

| Screenshots/06-Sentinel-Analytics-Migration-Notice.png | Sentinel migration notice |

| Screenshots/09-Sentinel-Workbook-Failed-Login-Report.png | Failed login workbook |

| Screenshots/11-Azure-Security-Monitoring-Workbook.png | Security monitoring dashboard |



\## KQL Queries



| Screenshot | Description |

|------------|-------------|

| Screenshots/10-KQL-Failed-Login-Query.png | Failed login query |

| Screenshots/12-KQL-Failed-Login-Trend-Query.png | Failed login trend |

| Screenshots/19-KQL-Query-Error-SecurityEvent-NotFound.png | Troubleshooting KQL query |



\## Microsoft Defender for Cloud



| Screenshot | Description |

|------------|-------------|

| Screenshots/13-Microsoft-Defender-for-Cloud-Overview.png | Defender for Cloud overview |

| Screenshots/14-Defender-for-Cloud-Security-Recommendations.png | Security recommendations |

| Screenshots/15-Azure-Secure-Score-Dashboard.png | Secure Score dashboard |



\## Azure Monitor Alerts



| Screenshot | Description |

|------------|-------------|

| Screenshots/20-Failed-Login-Alert-Details.png | Failed login alert details |

| Screenshots/21-Azure-Monitor-Failed-Login-Alert-Email.png | Alert email notification |

| Screenshots/22-Failed-Login-Alert-History.png | Alert history |

