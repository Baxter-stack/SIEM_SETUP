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
![Baxter_VM_SC](https://github.com/Baxter-stack/SIEM/assets/173977594/4d1e0946-5034-4416-8485-5239ec6d2642)
![Baxer_LAW_AZ](https://github.com/Baxter-stack/SIEM/assets/173977594/86acce30-69f8-4d67-a1cf-9a677124389c)
![AZ Sentinel](https://github.com/Baxter-stack/Baxter/assets/173977594/29215914-782b-4a43-b7d1-eda9bbbaf69e)

## <b><i>Firewall turned off to make VM discoverable by TAs</i></b>
![image](https://github.com/Baxter-stack/Baxter/assets/173977594/c13d8ac4-7ace-4b77-8bcb-1310512f298a)

## <b><i>Set an API key on VM for GEO and executed PS script</i></b>
![PS Script for API](https://github.com/Baxter-stack/Baxter/assets/173977594/1dafb425-285a-42bb-9d92-ccb5abe6ce11)

## <b><i>Custom Logs extracted from VM into Azure Log Analytics Workspace</i></b>
![image](https://github.com/Baxter-stack/Baxter/assets/173977594/80f70ab6-10d8-47f2-9f03-8c970f657775)

## <b><i>Query & Map Images of Failed RDP attempts</i></b>
![image](https://github.com/Baxter-stack/SIEM/assets/173977594/f61e6d31-3729-4c94-b6bc-dfa9ed07fcbe)
