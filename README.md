## Hi there 👋

<!--
**Atouba64/Atouba64** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

👋 About Me
Dynamic and results-oriented Cloud Security Engineer specializing in Microsoft Azure. Passionate about architecting and implementing robust security solutions to protect cloud infrastructure and data assets. Proven expertise in threat detection, vulnerability management, and incident response within Azure environments.

Keen interest and developing skills in:

Cybersecurity Operations: Proactive threat hunting, security analytics, and automated incident response.

Data Security & Governance: Secure data handling, extraction, exfiltration prevention, and compliance.

Data Engineering: Building secure and efficient data pipelines (ETLs) for security data analysis using Python and Pandas.

AI & Automation: Leveraging AI/ML and LLMs for intelligent security automation, threat prediction, and anomaly detection.

I am actively seeking challenging roles where I can contribute to enhancing cloud security posture and leverage data-driven insights to mitigate risks.

Connect with me:

LinkedIn: [Your LinkedIn Profile URL]

Email: [Your Email Address]

(Optional) Blog/Website: [Your Blog/Website URL]

Kompetensi Inti & Keterampilan Teknis
☁️ Cloud Security (Microsoft Azure)
Identity & Access Management: Azure Active Directory (Azure AD), Conditional Access, PIM, MFA, Role-Based Access Control (RBAC).

Network Security: Azure Firewall, Network Security Groups (NSGs), Application Security Groups (ASGs), Azure WAF, Azure Private Link, VPN Gateway, ExpressRoute.

Data Security: Azure Key Vault, Azure Storage Service Encryption, Azure Disk Encryption, Azure SQL Database security features, Data Loss Prevention (DLP) concepts.

Threat Protection: Microsoft Defender for Cloud, Azure Sentinel (SIEM/SOAR), Azure Monitor, Log Analytics.

Security Operations: Incident Response, Vulnerability Management, Security Auditing & Compliance (e.g., ISO 27001, NIST, GDPR concepts).

Infrastructure as Code (IaC) Security: Securing ARM templates, Bicep, Terraform.

Container & Kubernetes Security (Azure): AKS security, Azure Container Registry security.

🛡️ Cybersecurity
Threat Modeling, Risk Assessment, Penetration Testing Concepts.

Intrusion Detection/Prevention Systems (IDS/IPS).

Security Information and Event Management (SIEM).

Security Orchestration, Automation and Response (SOAR).

Digital Forensics and Incident Response (DFIR) principles.

🐍 Data & Programming
Python: Proficient in Python for scripting, automation, data analysis, and API interaction.

Pandas & NumPy: Data manipulation, analysis, and transformation.

ETL & Data Pipelines: Designing and building data extraction, transformation, and loading processes (e.g., with Azure Data Factory, custom Python scripts).

APIs: Working with RESTful APIs for service integration.

Shell Scripting: Bash, PowerShell.

🤖 AI, Automation & LLMs
AI/ML Concepts: Understanding of machine learning principles for security applications (e.g., anomaly detection, classification).

LLM Integration: Experience or strong interest in utilizing Large Language Models (e.g., OpenAI GPT-series, Azure OpenAI) for tasks like threat intelligence analysis, security report generation, or automating responses.

Automation Tools: Azure Logic Apps, Azure Functions, Ansible (conceptual).

🛠️ Tools & Technologies
Azure Portal, Azure CLI, Azure PowerShell

Version Control: Git, GitHub

SIEM/Log Management: Azure Sentinel, Log Analytics Workspace, KQL (Kusto Query Language)

Virtualization & Containerization: Docker, Kubernetes (AKS)

Operating Systems: Windows Server, Linux

🚀 Featured Projects
Here are some projects that showcase my skills and interests. (You will need to build these projects and link your actual GitHub repositories).

1. Project Sentinel: AI-Powered Azure Phishing Email Analyzer
Description: Developed a Python-based solution that integrates with Azure Sentinel to analyze suspicious emails. The system extracts email content and headers, leverages an LLM (e.g., Azure OpenAI Service) to identify phishing indicators (e.g., sender impersonation, malicious links, urgent language), and automatically creates a high-fidelity incident in Azure Sentinel with enriched data for security analysts.

Technologies Used:

Azure Sentinel (SIEM/SOAR)

Azure Logic Apps (for email ingestion or workflow automation)

Azure Functions (Python runtime for analysis logic)

Python (Core logic, API interaction)

LLM API (e.g., Azure OpenAI Service)

Microsoft Graph API (for email access if applicable)

Key Features & Accomplishments:

Automated ingestion and parsing of email data.

Intelligent phishing detection using NLP capabilities of LLMs.

Seamless incident creation and enrichment in Azure Sentinel.

Reduced manual effort for phishing analysis and improved response times.

GitHub Repository: [Link to Your GitHub Repo for Project Sentinel]

2. Project Cerberus: Secure ETL Pipeline for Azure Security Log Consolidation & Anomaly Detection
Description: Designed and implemented a secure and scalable ETL pipeline to collect, process, and analyze security logs from diverse Azure services (e.g., Azure Activity Logs, NSG Flow Logs, Microsoft Defender for Cloud alerts, VM logs). The pipeline centralizes logs in Azure Data Lake Storage Gen2, performs transformations using Azure Databricks (with Python/PySpark and Pandas), and loads them into Azure Synapse Analytics for advanced querying. Implemented basic anomaly detection rules on aggregated data to flag unusual activities.

Technologies Used:

Azure Data Factory / Azure Synapse Pipelines (Orchestration)

Azure Data Lake Storage Gen2 (Raw and processed log storage)

Azure Databricks (Python, PySpark, Pandas for transformation and analysis)

Azure Synapse Analytics (Data warehousing and querying)

Azure Monitor (Log sources)

Python (Custom scripts, data analysis)

KQL (for querying in Log Analytics / Synapse)

Key Features & Accomplishments:

Robust and scalable ETL process for various Azure log types.

Secure data handling with encryption and access controls at each stage.

Centralized data repository for comprehensive security analysis.

Demonstrated ability to extract insights and detect anomalies from security data.

GitHub Repository: [Link to Your GitHub Repo for Project Cerberus]

3. Project Guardian: Automated Azure Security Configuration Auditor
Description: Created a Python-based tool that automates the auditing of Azure resource configurations against a custom security baseline (inspired by CIS Benchmarks or specific organizational policies). The tool uses the Azure SDK for Python to inspect resources like Virtual Machines, Storage Accounts, Key Vaults, and Network Security Groups. It generates a detailed HTML/CSV report highlighting non-compliant configurations and provides remediation guidance.

Technologies Used:

Python (Core logic, reporting)

Azure SDK for Python (Boto3 equivalent for Azure: azure-identity, azure-mgmt-compute, azure-mgmt-storage, etc.)

Pandas (Data organization for reporting)

(Optional) Jinja2 (for HTML report templating)

Key Features & Accomplishments:

Automated and repeatable security configuration checks.

Customizable audit policies.

Clear reporting of vulnerabilities and misconfigurations.

Reduced manual audit effort and improved compliance posture.

GitHub Repository: [Link to Your GitHub Repo for Project Guardian]

4. Project ExfilWatch: Azure Blob Storage Exfiltration Detector
Description: Developed a Python script that monitors Azure Blob Storage access logs (via Azure Monitor) for patterns indicative of potential data exfiltration. The script analyzes log data for anomalies such as unusually large data transfers, access from suspicious IP addresses/regions, or access to an abnormally high number of blobs by a single entity. It uses Pandas for data manipulation and can trigger alerts (e.g., email, or an Azure Sentinel alert).

Technologies Used:

Azure Blob Storage (with diagnostic logging enabled)

Azure Monitor (Log Analytics Workspace)

KQL (for initial log querying and filtering)

Python (Core analysis logic)

Pandas (Data analysis and pattern detection)

Azure Functions (for scheduled execution or event-driven triggers)

Key Features & Accomplishments:

Proactive monitoring of Blob Storage for exfiltration indicators.

Analysis of access patterns and data transfer volumes.

Integration with alerting mechanisms.

Demonstrates understanding of data exfiltration techniques and detection strategies in Azure.

GitHub Repository: [Link to Your GitHub Repo for Project ExfilWatch]

📜 Certifications (Optional but Highly Recommended)
[AZ-500: Microsoft Azure Security Technologies] - [Date Achieved/In Progress]

[SC-200: Microsoft Security Operations Analyst] - [Date Achieved/In Progress]

[CompTIA Security+] - [Date Achieved/In Progress]

(Optional) [CISSP: Certified Information Systems Security Professional] - [Date Achieved/In Progress]

(Optional) [CCSP: Certified Cloud Security Professional] - [Date Achieved/In Progress]

(Other relevant certifications)

🎓 Education & Experience
Education
[Your Degree] - [Your University] - [Year of Graduation]

Relevant coursework or projects.

Professional Experience (If applicable)
[Your Role] - [Company Name] - [Dates of Employment]

Briefly describe key responsibilities and achievements, focusing on security and Azure.

(Previous Roles)

🌱 Learning & Development
Actively exploring advanced topics in [mention a specific area like Zero Trust Architecture in Azure, AI for threat hunting, advanced KQL, etc.].

<!-- Regular contributor to [mention any relevant open-source projects if applicable].
Currently learning [new technology/skill, e.g., advanced Terraform for Azure, specific ML libraries].-->
