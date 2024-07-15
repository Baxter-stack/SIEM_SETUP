# <b>SIEM SETUP IN AZURE</b>
# Project Objective 

I am building a comprehensive SIEM solution using Azure Sentinel. My goal is to centralize log collection, correlation, and analysis to enable proactive threat detection and incident response, improving overall cybersecurity posture. This project aims to provide real-time visibility into security events and enhance our incident response capabilities.

# Tools
- Azure Sentinel: Setting up SIEM system and centralizing log collection.
- PowerShell: Executing scripts to extract metadata from Windows Event Viewer and forward data to third-party APIs for geolocation.
- Azure Log Analytics Workspace: Accepting custom logs with geographic data and creating custom fields for enhanced analysis.
- Third-party APIs: Deriving geolocation information from extracted metadata.
- Azure Sentinel Workbooks: Designing visualizations to display global attack data.
- Windows Event Viewer: Source of metadata for security event logs.

# Skills Gained
- SIEM Configuration and Management: Setting up and managing SIEM systems like Azure Sentinel.
- PowerShell Scripting: Automating data extraction and integration with PowerShell.
- Log Analysis and Custom Field Creation: Analyzing logs and creating custom fields in Azure Log Analytics.
- SIEM Rule Tuning: Fine-tuning SIEM rules to reduce false positives and improve accuracy.
- Workbook Design and Visualization: Creating visualizations in Azure Sentinel for global attack data.
- Process Documentation: Documenting processes and configurations for consistency and knowledge transfer.

# Steps 

## <b><i>Virtual Machine, Log Analytics Workspace, and Sentinel Creation</i></b>
![image](https://github.com/user-attachments/assets/43ca95d8-9a63-4e02-a5f2-f3f56915a4db)
![image](https://github.com/user-attachments/assets/bc17a58f-247e-496e-9013-5430c4665eb8)
![image](https://github.com/user-attachments/assets/745e3b36-6fbc-400e-95a8-4e9f68a535ad)

## <b><i>Firewall turned off to make VM discoverable by TAs</i></b>
![image](https://github.com/Baxter-stack/SIEM_SETUP/assets/173977594/430bd2e6-e23f-4e49-861e-0661c67dabc6)

## <b><i>Set an API key on VM for GEO and executed PS script</i></b>
![PS Script for API](https://github.com/Baxter-stack/SIEM_SETUP/assets/173977594/8e2dc42f-7771-441d-bde1-27c83c849267)

## <b><i>Custom Logs extracted from VM into Azure Log Analytics Workspace</i></b>
![image](https://github.com/Baxter-stack/SIEM_SETUP/assets/173977594/eaaa5c64-320f-4406-8fcb-182df08a979f)

## <b><i>Query & Map Images of Failed RDP attempts</i></b>
![image](https://github.com/user-attachments/assets/cd4e896e-696f-47cb-bd02-967a77165af9)
