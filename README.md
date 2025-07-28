# 🕵️‍♀️ Digital Forensics Case Study – Windows XP Image Analysis
Welcome to the repository for a digital forensics case study conducted by Laraib Rashid. This project explores the forensic analysis of a Windows XP disk image using industry-standard tools and methodologies. The investigation focuses on uncovering user activity, installed applications, account details, and potential evidence of suspicious behavior.

##📂 Project Overview
This case study simulates a forensic investigation scenario where a disk image is analyzed to extract critical information such as:

Operating system installation details
User account activity
Installed applications
Web browsing history
External device usage
Email account evidence
Volume Shadow Copy analysis

##🛠️ Tools Used
Autopsy 4.22.1 – For disk image analysis and artifact extraction
Registry Explorer v2.1.0 – For deep registry inspection
VSCMount 1.5.0 – To access Volume Shadow Copies (VSCs)
##🔍 Key Findings
###✅ Operating System
OS: Microsoft Windows XP
Installation Date: 2004-08-20 03:02:22 AEST
###👤 User Accounts
Active Account: Mr.evil
Created On: 2004-08-20 09:03:54 AEST
Password Policy: Minimum 18 characters, 42-day expiration
###🧩 Installed Applications (within 48 hours of OS install)
Microsoft Internet Explorer
Microsoft Data Access Components (MDAC)
Microsoft System Information Tools
Microsoft Web Folders & FrontPage Extensions
MSN Online Services
Microsoft Plus! System Agent
###🌐 Web Activity
Domains Accessed: ethereal.com, depaul.edu, maktoob.com, netstumbler.com, wardriving.com, msn.com
Timeframe: Between 09:00 and 18:00 AEST
###💾 External Devices
USB device detected via registry keys
Evidence of potential file transfers inferred from registry values
###📧 Email Evidence
Email account and ID linked to the suspect were identified
Screenshots and registry artifacts support the connection
##📁 Data Acquisition & Analysis
Disk images and registry hives were extracted and analyzed
Volume Shadow Copies were mounted to recover historical data
Manual registry inspection was required due to parsing limitations in Autopsy
##⚠️ Limitations
Some encrypted files could not be analyzed
Autopsy failed to parse certain registry artifacts
Volume Shadow Copy parsing required manual correlation


##📄 License
This project is for educational and research purposes only.
