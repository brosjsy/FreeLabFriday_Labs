# Course Navigation

Work through the sections in order. Inside every section the pages are numbered in reading order (lesson, then readings, then each lab followed by its solution), and each section folder has a README with the same list.

Tool write-ups (Hayabusa, Volatility, Zeek, ...) are collected under [Tool Documentation](#tool-documentation).

***
### 00 - [Welcome](./courseFiles/Section_00-welcome/README.md)

1. **Lesson** - [Welcome & how to get support](./courseFiles/Section_00-welcome/01-welcome.md)
   - [Start Here!](./courseFiles/Section_00-welcome/01-welcome.md#start-here)
   - [Getting Support](./courseFiles/Section_00-welcome/01-welcome.md#getting-support)

***
### 01 - [Log Analysis Basics](./courseFiles/Section_01-logAnalysis_Basics/README.md)

1. **Lesson** - [Log Analysis Basics](./courseFiles/Section_01-logAnalysis_Basics/01-logAnalysis_basics.md)
   - [Windows Event Logs](./courseFiles/Section_01-logAnalysis_Basics/01-logAnalysis_basics.md#windows-event-logs)
   - [Sysmon Logs](./courseFiles/Section_01-logAnalysis_Basics/01-logAnalysis_basics.md#sysmon-logs)
   - [Authentication Logs](./courseFiles/Section_01-logAnalysis_Basics/01-logAnalysis_basics.md#authentication-logs)
   - [Tools to Learn](./courseFiles/Section_01-logAnalysis_Basics/01-logAnalysis_basics.md#tools-to-learn)
2. **Lab** - [Hayabusa Log Analysis Lab](./courseFiles/Section_01-logAnalysis_Basics/02-logAnalysisBasics_Lab.md)

***
### 02 - [Security Tools & Foundational Platforms](./courseFiles/Section_02-toolsAndPlatforms/README.md)

1. **Lesson** - [Security Tools & Foundational Platforms](./courseFiles/Section_02-toolsAndPlatforms/01-toolsAndPlatforms.md)
   - [Intro](./courseFiles/Section_02-toolsAndPlatforms/01-toolsAndPlatforms.md#intro)
   - [LimaCharlie Hands-On](./courseFiles/Section_02-toolsAndPlatforms/01-toolsAndPlatforms.md#limacharlie-hands-on)
   - [Elastic SIEM Hands-On](./courseFiles/Section_02-toolsAndPlatforms/01-toolsAndPlatforms.md#elastic-siem-hands-on)
   - [Viewing Alerts & Logs](./courseFiles/Section_02-toolsAndPlatforms/01-toolsAndPlatforms.md#viewing-alerts--logs)
   - [Writing & Modifying Basic Detection Rules](./courseFiles/Section_02-toolsAndPlatforms/01-toolsAndPlatforms.md#writing--modifying-basic-detection-rules)
   - [Telemetry Searching](./courseFiles/Section_02-toolsAndPlatforms/01-toolsAndPlatforms.md#telemetry-searching)
2. **Lab** - [LimaCharlie Lab - Part 1](./courseFiles/Section_02-toolsAndPlatforms/02-lima_charlie_lab_part1.md)
3. **Lab** - [LimaCharlie Lab - Part 2](./courseFiles/Section_02-toolsAndPlatforms/03-lima_charlie_lab_part2.md)
4. **Lab** - [Elastic SIEM Lab (Cloud version)](./courseFiles/Section_02-toolsAndPlatforms/04-elasticLabCloud.md)
5. **Lab** - [Elastic SIEM Lab (Local version, alternative to 04)](./courseFiles/Section_02-toolsAndPlatforms/05-elasticLabLocal.md)

***
### 03 - [Detection & Threat Behavior](./courseFiles/Section_03-detectionAndThreatBehavior/README.md)

1. **Lab** - [Detection & Threat Behavior (lesson + lab)](./courseFiles/Section_03-detectionAndThreatBehavior/01-detectionAndThreatBehavior.md)
   - [Intro Lab](./courseFiles/Section_03-detectionAndThreatBehavior/01-detectionAndThreatBehavior.md#intro)
2. **Reading** - [The MITRE ATT&CK Framework](./courseFiles/Section_03-detectionAndThreatBehavior/02-MITRE_ATTACK.md)
   - [Mapping Log Events to ATT&CK Techniques](./courseFiles/Section_03-detectionAndThreatBehavior/02-MITRE_ATTACK.md#mapping-log-events-to-attck-techniques)
   - [Open Source Projects](./courseFiles/Section_03-detectionAndThreatBehavior/02-MITRE_ATTACK.md#open-source-projects)

***
### 04 - [Scripting for SOC Tasks](./courseFiles/Section_04-socScripting/README.md)

1. **Lesson** - [Scripting for SOC Tasks](./courseFiles/Section_04-socScripting/01-socScripting.md)
   - [Intro](./courseFiles/Section_04-socScripting/01-socScripting.md#intro)
   - [Python Scripting Basics](./courseFiles/Section_04-socScripting/01-socScripting.md#python-scripting-basics)
   - [Powershell Basics](./courseFiles/Section_04-socScripting/01-socScripting.md#powershell-basics)
2. **Reading** - [Python & PowerShell scripting notes](./courseFiles/Section_04-socScripting/02-scripting_for_soc.md)
3. **Reading** - [PowerShell for SOC (command reference)](./courseFiles/Section_04-socScripting/03-powershell_for_soc.md)
4. **Lab** - [Lab 1 - Detect Brute Force (Python)](./courseFiles/Section_04-socScripting/04-lab1_detect_brute_force.md)
5. **Solution** - [Lab 1 - Solution](./courseFiles/Section_04-socScripting/05-lab1_solution_step_by_step.md)
6. **Lab** - [Lab 2 - Collect System Info (PowerShell)](./courseFiles/Section_04-socScripting/06-lab2_collect_system_info.md)
7. **Solution** - [Lab 2 - Solution](./courseFiles/Section_04-socScripting/07-lab2_solution_step_by_step.md)
8. **Reading** - [Scapy Documentation - Part 1 (tools folder)](./courseFiles/tools/scapy_documentation_part1.md)
9. **Reading** - [Scapy Documentation - Part 2 (tools folder)](./courseFiles/tools/scapy_documentation_part2.md)
10. **Lab** - [Lab 3 - Covert TCP Channel with Scapy](./courseFiles/Section_04-socScripting/08-scapy_lab.md)
11. **Solution** - [Lab 3 - Solution](./courseFiles/Section_04-socScripting/09-scapy_lab_solution.md)

***
### 05 - [Networking & Telemetry 101](./courseFiles/Section_05-networkingAndTelemetry/README.md)

1. **Lesson** - [Networking & Telemetry 101](./courseFiles/Section_05-networkingAndTelemetry/01-networkingAndTelemetry.md)
   - [Understanding Key Network Protocols](./courseFiles/Section_05-networkingAndTelemetry/01-networkingAndTelemetry.md#understanding-key-network-protocols)
   - [Identifying Network Logs](./courseFiles/Section_05-networkingAndTelemetry/01-networkingAndTelemetry.md#identifying-network-logs)
   - [Examining Packet Captures](./courseFiles/Section_05-networkingAndTelemetry/01-networkingAndTelemetry.md#examining-packet-captures)
   - [Metadata NetFlow vs Full Packet Capture](./courseFiles/Section_05-networkingAndTelemetry/01-networkingAndTelemetry.md#metadata-netflow-vs-full-packet-capture)
2. **Reading** - [Key Network Protocols](./courseFiles/Section_05-networkingAndTelemetry/02-network_protocols.md)
3. **Reading** - [Understanding Network Logs](./courseFiles/Section_05-networkingAndTelemetry/03-network_logs.md)
4. **Reading** - [NetFlow vs Full Packet Capture](./courseFiles/Section_05-networkingAndTelemetry/04-netflow_vs_full_packet_capture.md)
5. **Lab** - [Wireshark LDAP Lab](./courseFiles/Section_05-networkingAndTelemetry/05-wireshark_ldap_lab.md)
6. **Solution** - [Wireshark LDAP Lab - Solution](./courseFiles/Section_05-networkingAndTelemetry/06-wireshark_ldap_lab_solution.md)
7. **Lab** - [IDS Lab (Snort & Suricata)](./courseFiles/Section_05-networkingAndTelemetry/07-ids_lab.md)
8. **Lab** - [Zeek Lab](./courseFiles/Section_05-networkingAndTelemetry/08-zeek_lab.md)
9. **Solution** - [Zeek Lab - Results](./courseFiles/Section_05-networkingAndTelemetry/09-zeek_lab_results.md)
10. **Lab** - [RITA Lab - Part 1 (slow_steady_beacon)](./courseFiles/Section_05-networkingAndTelemetry/10-rita_lab/01-ritaLab1.md)
11. **Lab** - [RITA Lab - Part 2 (beacon_jitter)](./courseFiles/Section_05-networkingAndTelemetry/10-rita_lab/02-ritaLab2.md)
12. **Lab** - [RITA Lab - Part 3 (icedid)](./courseFiles/Section_05-networkingAndTelemetry/10-rita_lab/03-ritaLab3.md)
13. **Lab** - [RITA Lab - Part 4 (randomized redirectors)](./courseFiles/Section_05-networkingAndTelemetry/10-rita_lab/04-ritaLab4.md)
14. **Lab** - [RITA Lab - Part 5 (teamviewer)](./courseFiles/Section_05-networkingAndTelemetry/10-rita_lab/05-ritaLab5.md)
15. **Lab** - [RITA Lab - Part 6 (specula)](./courseFiles/Section_05-networkingAndTelemetry/10-rita_lab/06-ritaLab6.md)
16. **Lab** - [RITA Lab - Part 7 (RDP / MS dev tunnels)](./courseFiles/Section_05-networkingAndTelemetry/10-rita_lab/07-ritaLab7.md)

***
### 06 - [Web Security](./courseFiles/Section_06-webSecurity/README.md)

1. **Lesson** - [Web Security](./courseFiles/Section_06-webSecurity/01-webSecurity.md)
   - [Overview](./courseFiles/Section_06-webSecurity/01-webSecurity.md#overview)
   - [Types of Attacks](./courseFiles/Section_06-webSecurity/01-webSecurity.md#types-of-attacks)
   - [Common Web Attacks](./courseFiles/Section_06-webSecurity/01-webSecurity.md#common-web-attacks)
2. **Lab** - [SQL Injection Lab - Part 1](./courseFiles/Section_06-webSecurity/02-webLabPart1.md)
3. **Lab** - [SQL Injection Lab - Part 2](./courseFiles/Section_06-webSecurity/03-webLabPart2.md)
4. **Reading** - [Browser Malware](./courseFiles/Section_06-webSecurity/04-browser_malware.md)
5. **Lab** - [Browser Malware Lab](./courseFiles/Section_06-webSecurity/05-browser_malware_lab.md)

***
### 07 - [Browser & Cloud Security Fundamentals](./courseFiles/Section_07-browserAndCloudSecurity/README.md)

1. **Lesson** - [Browser & Cloud Security Fundamentals](./courseFiles/Section_07-browserAndCloudSecurity/01-browserAndCloudSecurity.md)
   - [Browser Extension Attacks](./courseFiles/Section_07-browserAndCloudSecurity/01-browserAndCloudSecurity.md#browser-extension-attacks)
   - [OAuth & SSO Attacks](./courseFiles/Section_07-browserAndCloudSecurity/01-browserAndCloudSecurity.md#oauth--sso-attacks)
   - [Azure Logs](./courseFiles/Section_07-browserAndCloudSecurity/01-browserAndCloudSecurity.md#azure-logs)
   - [M365 Audit Logs](./courseFiles/Section_07-browserAndCloudSecurity/01-browserAndCloudSecurity.md#m365-audit-logs)
2. **Lab** - [Azure Lab](./courseFiles/Section_07-browserAndCloudSecurity/02-azureLab.md)

***
### 08 - [Deception Systems](./courseFiles/Section_08-deceptionSystems/README.md)

1. **Lesson** - [Deception Systems](./courseFiles/Section_08-deceptionSystems/01-deceptionSystems.md)
   - [Intro to Deception Techniques](./courseFiles/Section_08-deceptionSystems/01-deceptionSystems.md#intro-to-deception-techniques)
   - [Generating Traps](./courseFiles/Section_08-deceptionSystems/01-deceptionSystems.md#generating-traps)
   - [Active Defense & Cyber Deception](./courseFiles/Section_08-deceptionSystems/01-deceptionSystems.md#active-defense--cyber-deception)
   - [Legal Notes](./courseFiles/Section_08-deceptionSystems/01-deceptionSystems.md#legal-notes)
2. **Lab** - [Dionaea Lab](./courseFiles/Section_08-deceptionSystems/02-dionaeaLab.md)
3. **Lab** - [Beelzebub Lab](./courseFiles/Section_08-deceptionSystems/03-beelzebubLab.md)
4. **Lab** - [CanaryToken Lab](./courseFiles/Section_08-deceptionSystems/04-CanaryToken_lab.md)

***
### 09 - [Forensics Fundamentals](./courseFiles/Section_09-forensicsFundamentals/README.md)

1. **Lesson** - [Forensics Fundamentals](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md)
   - [Overview](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md#overview)
   - [Order of Volatility](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md#order-of-volatility)
   - [FTK Imager - Evidence Acquisition](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md#ftk-imager---evidence-acquisition)
   - [Autopsy – Evidence Analysis](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md#autopsy--evidence-analysis)
   - [Memory Forensics (Volatility Framework)](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md#memory-forensics-volatility-framework)
   - [Common Artifacts](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md#common-artifacts)
   - [Workflow Example](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md#workflow-example)
   - [Legal and Ethical Considerations](./courseFiles/Section_09-forensicsFundamentals/01-forensicsFundamentals.md#legal-and-ethical-considerations)
2. **Lab** - [Volatility Lab - Part 1](./courseFiles/Section_09-forensicsFundamentals/02-volatilityLab1.md)
3. **Lab** - [Volatility Lab - Part 2](./courseFiles/Section_09-forensicsFundamentals/03-volatilityLab2.md)
4. **Lab** - [Volatility Lab - Part 3](./courseFiles/Section_09-forensicsFundamentals/04-volatilityLab3.md)
5. **Lab** - [Volatility Lab - Part 4](./courseFiles/Section_09-forensicsFundamentals/05-volatilityLab4.md)

***
### 10 - [Email Fundamentals](./courseFiles/Section_10-emailFundamentals/README.md)

1. **Lesson** - [Email Fundamentals](./courseFiles/Section_10-emailFundamentals/01-emailFundamentals.md)
   - [Identifying Phishing](./courseFiles/Section_10-emailFundamentals/01-emailFundamentals.md#identifying-phishing)
   - [Common Email-Based Attacks](./courseFiles/Section_10-emailFundamentals/01-emailFundamentals.md#common-email-based-attacks)
   - [Email Security Solutions](./courseFiles/Section_10-emailFundamentals/01-emailFundamentals.md#email-security-solutions)
   - [Projects to Try](./courseFiles/Section_10-emailFundamentals/01-emailFundamentals.md#projects-to-try)
2. **Lab** - [Phishing Email Lab](./courseFiles/Section_10-emailFundamentals/02-phishing_email_lab.md)
3. **Solution** - [Phishing Email Lab - Solution](./courseFiles/Section_10-emailFundamentals/03-phishing_email_lab_solution.md)
4. **CTF** - [Email Analysis CTF 01](./courseFiles/Section_10-emailFundamentals/04-email01_ctf.md)
5. **CTF** - [Email Analysis CTF 02](./courseFiles/Section_10-emailFundamentals/05-email02_ctf.md)
6. **CTF** - [Email Analysis CTF 03](./courseFiles/Section_10-emailFundamentals/06-email03_ctf.md)
7. **CTF** - [Email Analysis CTF 04](./courseFiles/Section_10-emailFundamentals/07-email04_ctf.md)
8. **CTF** - [Email Analysis CTF 05](./courseFiles/Section_10-emailFundamentals/08-email05_ctf.md)
9. **CTF** - [Email Analysis CTF 06](./courseFiles/Section_10-emailFundamentals/09-email06_ctf.md)
10. **CTF** - [Email Analysis CTF 07](./courseFiles/Section_10-emailFundamentals/10-email07_ctf.md)
11. **CTF** - [Email Analysis CTF 08](./courseFiles/Section_10-emailFundamentals/11-email08_ctf.md)

***
### 11 - [Malware Forensics](./courseFiles/Section_11-malwareForensics/README.md)

1. **Lesson** - [Malware Forensics with Radare2 & IDA](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md)
   - [Introduction](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#introduction)
   - [The Malware Analysis Workflow](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#the-malware-analysis-workflow)
   - [Malware Execution Chain](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#malware-execution-chain)
   - [Safe Analysis Environment](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#safe-analysis-environment)
   - [Static Analysis](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#static-analysis)
   - [Dynamic Analysis](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#dynamic-analysis)
   - [Behavioral Forensics and IOC(Indicators Of Compomise) Extraction](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#behavioral-forensics-and-iocindicators-of-compomise-extraction)
   - [Basic Unpacking and Deobfuscation](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#basic-unpacking-and-deobfuscation)
   - [Reverse Engineering](./courseFiles/Section_11-malwareForensics/01-malwareForensics.md#reverse-engineering)
2. **Lab** - [Malware Forensics Lab](./courseFiles/Section_11-malwareForensics/02-Lab_MalwareForensics.md)

***
### 12 - [Documentation & Case Notes](./courseFiles/Section_12-documentationAndCaseNotes/README.md)

1. **Lesson** - [Documentation & Case Notes](./courseFiles/Section_12-documentationAndCaseNotes/01-documentationAndCaseNotes.md)
   - [Case Notes — The Analyst’s Daily Log](./courseFiles/Section_12-documentationAndCaseNotes/01-documentationAndCaseNotes.md#case-notes---the-analysts-daily-log)
   - [Writing an Incident Timeline](./courseFiles/Section_12-documentationAndCaseNotes/01-documentationAndCaseNotes.md#writing-an-incident-timeline)
   - [Writing an Alert Triage Summary](./courseFiles/Section_12-documentationAndCaseNotes/01-documentationAndCaseNotes.md#writing-an-alert-triage-summary)
   - [Real-World Examples](./courseFiles/Section_12-documentationAndCaseNotes/01-documentationAndCaseNotes.md#real-world-examples)
2. **Lab** - [Documentation Lab](./courseFiles/Section_12-documentationAndCaseNotes/02-documentationLab.md)

***
### 13 - [Soft Skills](./courseFiles/Section_13-softSkills/README.md)

1. **Lesson** - [Soft Skills](./courseFiles/Section_13-softSkills/01-softSkills.md)
   - [Ask Questions](./courseFiles/Section_13-softSkills/01-softSkills.md#ask-questions)
   - [Explain Your Process](./courseFiles/Section_13-softSkills/01-softSkills.md#explain-your-process)
   - [Start a Blog](./courseFiles/Section_13-softSkills/01-softSkills.md#start-a-blog)
   - [Learn & Teach](./courseFiles/Section_13-softSkills/01-softSkills.md#learn--teach)
   - [Final Exercise](./courseFiles/Section_13-softSkills/01-softSkills.md#final-exercise)

***
### Tool Documentation

- [Autopsy Documentation](./courseFiles/tools/Autopsy.md)
- [Setup](./courseFiles/tools/Binary_Ninja.md)
- [Dionaea Documentation](./courseFiles/tools/Dionaea.md)
- [Elastic Cloud Documentation](./courseFiles/tools/Elastic_Doc_Cloud.md)
- [Elastic Local Documentation](./courseFiles/tools/Elastic_Doc_Local.md)
- [FTK Imager Documentation](./courseFiles/tools/FTK-Imager.md)
- [Setup](./courseFiles/tools/Hayabusa.md)
- [Overview](./courseFiles/tools/IDA_Free.md)
- [PEstudio for Linux](./courseFiles/tools/PEStudio.md)
- [Setup](./courseFiles/tools/Rita.md)
- [Volatility Documentation](./courseFiles/tools/Volatility.md)
- [Windows Event Viewer](./courseFiles/tools/WinEventViewer.md)
- [Scapy - part 1](./courseFiles/tools/scapy_documentation_part1.md)
- [Scapy - part 2](./courseFiles/tools/scapy_documentation_part2.md)
- [Snort](./courseFiles/tools/snort.md)
- [Suricata](./courseFiles/tools/suricata.md)
- [tcpdump](./courseFiles/tools/tcpdump.md)
- [Wireshark](./courseFiles/tools/wireshark.md)
- [Zeek — SOC Analyst Playbook (Cheat-sheet + Expanded)](./courseFiles/tools/zeek.md)

***

<i>[<< Back to Course Home Page](../README.md)</i>
