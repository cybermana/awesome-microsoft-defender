# Awesome Microsoft Defender [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources, repos, scripts, tools, queries and learning resouces about the Microsoft Defender suite. Inspired by Sindre Sorhus and his [awesome](https://github.com/sindresorhus/awesome) collection

## About Awesome Microsoft Defender

Imagine having end-to-end visibility into threats, risks and vulnerabilities across all of your identities, endpoints, email, document management tools, collaboration tools and cloud applications. Then use AI to stitch the signals together and tell you what’s most important, and how to respond proactively across your entire organisation. Microsoft Defender is a suite of next-generation, cloud-delivered security services that enables you to proactively protect, detect and respond to emerging threats and risks that impact your business.

Brought to you by [Cybermana](https://www.cybermana.net) - helping you unlock the power of your cyber resilience.

## Contents

- [Important Resources](#important-resources)
  - [Licensing](#licensing)
  - [Products by Region](#products-by-region)
  - [Updates and Roadmaps](#updates-and-roadmaps)
- [Technologies](#technologies)
  - [Microsoft Cloud App Security](#microsoft-cloud-app-security)
  - [Microsoft Defender for Endpoint](#microsoft-defender-for-endpoint)
  - [Microsoft Defender for Identity](###microsoft-defender-for-identity)
  - [Microsoft Defender for Office](###microsoft-defender-for-office)
- [Threat Hunting](##threat-hunting)
  - [Getting Started](###getting-started)
  - [Kusto Query Language (KQL)](###kusto-query-language)
  - [Threat Hunting with Microsoft 365 Defender](###threat-hunting-with-microsoft-365-defender)
- [Communities](##communities)
- [Learning Resources](##learning-resources)
  - [LEARN Microsoft Cloud App Security](###learn-microsoft-cloud-app-security)
  - [LEARN Microsoft Defender for Endpoint](###learn-microsoft-defender-for-endpoint)
  - [LEARN Microsoft Defender for Identity](###learn-microsoft-defender-for-identity)
  - [LEARN Microsoft Defender for Office](###learn-microsoft-defender-for-office)
  - [LEARN Threat Hunting](###learn-threat-hunting)

## Important Resources

> About this section. As well as learning about the tech, its important that you also get to know about the licensing, service availability and product roadmaps. We've collated some important resources that we think you should check out. Of course, if you'd prefer to jump straight into the interesting stuff then [click here](##technologies).

### Licensing

- [Microsoft 365 for Business Plans](https://www.microsoft.com/en-gb/microsoft-365/business/compare-all-microsoft-365-business-products) - Get to know whats available in each of the Microsoft 365 for Business plans.
- [Microsoft 365 Enterprise Plans](https://www.microsoft.com/en-gb/microsoft-365/compare-microsoft-365-enterprise-plans) - Get to know whats available in each of the Microsoft 365 Enterprise plans.
- [Microsoft 365 Enterprise License Comparison](https://www.microsoft.com/en-us/licensing/product-licensing/microsoft-365-enterprise?activetab=m365-enterprise%3aprimaryr5) - Get a side by side comparison of the Microsoft 365 Enterprise license plans.
- [Microsoft 365 Platform Service Descriptions](https://docs.microsoft.com/en-gb/office365/servicedescriptions/office-365-platform-service-description/office-365-platform-service-description) - Get to know the service descriptions for each of the Microsoft 365 products.
- [Microsoft 365 Licensing Diagrams by Aaron Dinnage](https://github.com/AaronDinnage/Licensing) - This is one of my favourites. Aaron has done an amazing job of visualising Microsoft 365 licensing so you can see which specific features you get with each license.

### Products by Region

It's important to understand which Microsoft Cloud Service is available within which Microsoft Region, as this may influence how you choose to use them.

- [Azure Data Centre Locations](https://azure.microsoft.com/en-gb/global-infrastructure/geographies/) - Learn more about where the Microsoft data centres are located and how that may impact your cloud journey.
- [Azure Products by Region](https://azure.microsoft.com/en-us/global-infrastructure/services/) - Learn more about which Microsoft products are available in which Microsoft Data Centre.
- [Microsoft 365 International Availability](https://www.microsoft.com/en-gb/microsoft-365/business/international-availability) - Understand the international availability of Microsoft 365 services.

### Updates and Roadmaps

- [**Roadmap**: Microsoft 365](https://www.microsoft.com/en-gb/microsoft-365/roadmap?filters=) - Learn more about the Microsoft 365 roadmap and what is in the pipeline for the future.
- [What's new in Microsoft Cloud App Security?](https://docs.microsoft.com/en-us/cloud-app-security/release-notes) - Learn more about what's new in Microsoft Cloud App Security.
- [What's new in Microsoft Defender for Endpoint?](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/whats-new-in-microsoft-defender-atp) - Learn more about what's new in Microsoft Defender for Endpoint.
- [What's new in Defender for Identity](https://docs.microsoft.com/en-us/defender-for-identity/whats-new) - Learn more about what's new in Microsoft Defender for Identity.
- [What's new in Microsoft Defender for Office](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/whats-new-in-office-365-atp?view=o365-worldwide) - Learn more about what's new in Microsoft Defender for Office.

## Technologies

This section focuses more on the specific technologies that make up the Microsoft Defender Suite.

### Microsoft Cloud App Security

- [What is Microsoft Cloud App Security?](https://docs.microsoft.com/en-us/cloud-app-security/what-is-cloud-app-security) - Get to know Microsoft Cloud App Security (MCAS), the Cloud Access Security Broker (CASB) platform from Microsoft.
- [Microsoft Cloud App Security Getting Started Guide](https://docs.microsoft.com/en-us/cloud-app-security/getting-started-with-cloud-app-security) - Get started with Microsoft Cloud App Security and learn how to get it setup in your environment.
- [Microsoft Cloud App Security Best Practices](https://docs.microsoft.com/en-us/cloud-app-security/best-practices) - Understand some of the best practices with Microsoft Cloud App Security (MCAS), so you can make best use of the platform.
- [Webinars: Microsoft Cloud App Security](https://docs.microsoft.com/en-us/cloud-app-security/webinars) - Learn about Microsoft Cloud App Security (MCAS) from the Experts and some of the tips and tricks to think about.

### Microsoft Defender for Endpoint

- [What is Defender for Endpoint?](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) - Get to know Microsoft Defender for Endpoint (MDE), the cloud-delivered Endpoint Detection and Response (EDR) platform from Microsoft.
- [Readiness: Planning your Microsoft Defender for Endpoint Deployment](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/deployment-strategy) - Plan your EDR journey with Microsoft Defender for Endpoint (MDE), so you can make best use of the platform.
- [Defender for Endpoint Deployment Phases](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/deployment-phases) - Work through the Microsoft Defender for Endpoint (MDE) deployment phases so you can accelerate your implementation.

### Microsoft Defender for Identity

- [What is Microsoft Defender for Identity](https://docs.microsoft.com/en-us/defender-for-identity/what-is) - Get to know Microsoft Defender for Identity (MDI), the cloud-delivered User & Entity Behaviour Analytics (UEBA) platform from Microsoft to detect lateral movement and mitigate against insider risk.
- [Defender for Identity Architecture](https://docs.microsoft.com/en-us/defender-for-identity/architecture) - Get to know the Microsoft Defender for Identity (MDI) architecture and the building blocks that make up the solution.
- [Readiness: Planning your Defender for Identity roadmap](https://docs.microsoft.com/en-us/defender-for-identity/resources) - Plan your UEBA and Insider Risk Management journey with Microsoft Defender for Identity (MDI), so you can make best use of the platform.

### Microsoft Defender for Office

- [What is Microsoft Defender for Office?](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/?view=o365-worldwide) - Get to know Microsoft Defender for Office (MDO), the cloud-delivered email and content security platform from Microsoft.
- [Readiness: Planning your Defender for Office Roadmap](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/security-roadmap?view=o365-worldwide) - Plan your Microsoft Defender for Office (MDO) journey and start protecting your business from email and content related threats.

## Threat Hunting

### Getting Started

COMING SOON

### Kusto Query Language

COMING SOON

### Threat Hunting with Microsoft Defender

- [Microsoft 365 Defender Hunting Queries by Microsoft](https://github.com/microsoft/Microsoft-365-Defender-Hunting-Queries)
- [Kusto Query Language (KQL) queries for Advanced Hunting by Wortell](https://github.com/wortell/KQL)
- [Advanced Hunting by Jan Geisbauer](https://github.com/jangeisbauer/AdvancedHunting)
- [Microsoft Defender for Endpoint Queries by Elli Schlomo](https://github.com/eshlomo1/Microsoft-Defender-for-Endpoint-Queries)
- [Blue Teaming with KQL by Ashwin Patil](https://github.com/ashwin-patil/blue-teaming-with-kql) - This is an awesome repo from Ashwin Patil that provides sample KQL queries for threat hunting.

## Communities

- [Tech Community: Microsoft Cloud App Security](https://techcommunity.microsoft.com/t5/microsoft-cloud-app-security/bd-p/MicrosoftCloudAppSecurity) - Join the Microsoft Tech Community to learn more about Microsoft Cloud App Security.
- [Tech Community: Microsoft Defender for Endpoint](https://techcommunity.microsoft.com/t5/microsoft-defender-for-endpoint/bd-p/MicrosoftDefenderATP) - Join the Microsoft Tech Community to learn more about Microsoft Defender for Endpoint.
- [Tech Community: Defender for Identity](https://techcommunity.microsoft.com/t5/microsoft-defender-for-identity/bd-p/AzureAdvancedThreatProtection) - Join the Microsoft Tech Community to learn more about Microsoft Defender for Identity.
- [Tech Community: Microsoft Defender for Office](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365) - Join the Microsoft Tech Community to learn more about Microsoft Defender for Office.
- [Tech Community: Microsoft 365 Defender](https://techcommunity.microsoft.com/t5/microsoft-365-defender/bd-p/MicrosoftThreatProtection) - Join the Microsoft Tech Community to learn more about Microsoft 365 Defender.

## Learning Resources

- [Become a Microsoft 365 Defender Ninja - October 2020](https://techcommunity.microsoft.com/t5/microsoft-365-defender/become-a-microsoft-365-defender-ninja/ba-p/1789376)
- [Become a Microsoft 365 Defender Ninja - January 2021 Update](<https://techcommunity.microsoft.com/t5/microsoft-365-defender/microsoft-365-defender-ninja-training-january-2021-update/ba-p/2103073>)
- [Introduction to threat protection with Microsoft 365](https://docs.microsoft.com/en-us/learn/modules/m365-security-threat-define/)
- [Mitigate incidents using Microsoft 365 Defender](https://docs.microsoft.com/en-gb/learn/modules/mitigate-incidents-microsoft-365-defender/)

### LEARN Microsoft Cloud App Security

- [Secure your cloud apps and services with Microsoft Cloud App Security](https://docs.microsoft.com/en-us/learn/modules/microsoft-cloud-app-security/)
- [Respond to data loss prevention alerts using Microsoft 365](https://docs.microsoft.com/en-gb/learn/modules/respond-to-data-loss-prevention-alerts-microsoft-365/)

### LEARN Microsoft Defender for Endpoint

- [Protect against threats with Microsoft Defender for Endpoint](https://docs.microsoft.com/en-us/learn/modules/m365-security-threat-protect/)
- [Deploy the Microsoft Defender for Endpoint Environment](https://docs.microsoft.com/en-gb/learn/modules/deploy-microsoft-defender-for-endpoints-environment/)
- [Implement Windows 10 security enhancements with Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/implement-windows-10-security-enhancements-with-microsoft-defender-for-endpoint/)
- [Manage alerts and incidents in Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/manage-alerts-incidents-microsoft-defender-for-endpoints/)
- [Perform device investigations in Microsoft Defender for Endpoint](<https://docs.microsoft.com/en-gb/learn/modules/perform-device-investigations-microsoft-defender-for-endpoints/>)
- [Perform actions on a device using Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/perform-actions-device-microsoft-defender-for-endpoint/)
- [Perform evidence and entities investigations using Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/perform-evidence-entities-investigations-microsoft-defender-for-endpoint/)
- [Configure and manage automation using Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/configure-manage-automation-microsoft-defender-for-endpoint/)
- [Configure for alerts and detections in Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/configure-settings-for-alerts-detections-microsoft-defender-for-endpoint/)
- [Utilize Threat and Vulnerability Management in Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/use-threat-vulnerability-management-microsoft-defender-for-endpoint/)

### LEARN Microsoft Defender for Identity

- [Safeguard your environment with Microsoft Defender for Identity](https://docs.microsoft.com/en-us/learn/modules/m365-threat-safeguard/)
- [Manage insider risk in Microsoft 365](https://docs.microsoft.com/en-us/learn/modules/m365-compliance-insider-manage-insider-risk/)

### LEARN Microsoft Defender for Office

- [Remediate risks with Microsoft Defender for Office 365](https://docs.microsoft.com/en-us/learn/modules/m365-threat-remediate/)

### LEARN Threat Hunting

- [Construct KQL statements for Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/construct-kusto-query-language-statements/)
- [Analyze query results using KQL](https://docs.microsoft.com/en-gb/learn/modules/analyze-results-kusto-query-language/)
- [Build multi-table statements using KQL](https://docs.microsoft.com/en-gb/learn/modules/build-multi-table-statements-kusto-query-language/)
- [Work with data in Azure Sentinel using Kusto Query Language](https://docs.microsoft.com/en-gb/learn/modules/work-with-data-kusto-query-language/)
- [Explain threat hunting concepts in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/what-is-threat-hunting-azure-sentinel/)
- [Threat hunting with Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/hunt-threats-sentinel/)
- [Hunt for threats using notebooks in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/perform-threat-hunting-sentinel-with-notebooks/)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

If you'd like to learn more about the Cybermana community then check us out at:

- [The Cybermana Website](https://www.cybermana.net)
- [Our LinkedIn Community](https://www.linkedin.com/company/cybermana)
- [Our Facebook Community](https://www.facebook.com/cybermanaUK/ )
- [Twitter](https://twitter.com/CybermanaUK )
