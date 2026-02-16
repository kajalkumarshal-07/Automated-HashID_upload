The Ultimate Solution for Autopilot Device Registration
⚡ No typing required. Fully automated. OOBE ready.

📌 Overview

The Windows Autopilot Fully Automated Upload Tool eliminates the need to manually type complex PowerShell commands during Windows OOBE (Out-of-Box Experience).

This tool provides a complete GUI-based automation solution that:

Installs required Autopilot modules

Collects device hardware hash

Opens Intune authentication

Automates upload process

Displays real-time device information

Requires zero manual command entry

🎯 Why This Tool?

Traditional method requires:

Manual PowerShell execution

Typing long commands in OOBE

Installing modules manually

Navigating multiple steps

Risk of human error

✅ With This Tool:

Copy script to USB or network share

Run as Administrator during OOBE

Click UPLOAD NOW

Done.

No typing. No errors. No complexity.

🖥 Interface Preview

⚙️ Key Features
🔹 Fully Automated Intune Upload

Installs Get-WindowsAutopilotInfo module (if missing)

Configures required PowerShell settings

Opens Intune authentication portal

Automates hardware hash upload workflow

🔹 Device Information Panel

Displays:

Computer Name

Serial Number

Manufacturer

Model

Windows Version

PowerShell Admin Status

Module Installed Status

Internet Connectivity

🔹 OOBE Ready

Designed specifically to run during:

Windows Out-of-Box Experience (OOBE)


Perfect for:

IT deployment engineers

MSP technicians

Enterprise provisioning teams

Bulk device enrollment

🚀 How to Use
Step 1 — Prepare USB

Copy the script:

AutopilotUploadTool.ps1


To:

USB Drive

Network Share

Step 2 — During OOBE

Press:

Shift + F10


Then run:

powershell.exe -ExecutionPolicy Bypass
.\AutopilotUploadTool.ps1

Step 3 — Click “UPLOAD NOW”

The tool will:

Install module (if required)

Configure environment

Open Intune portal

Guide upload automatically

🔐 Requirements

Windows 10 / 11

Internet connection

Admin privileges

Microsoft Intune access

Azure AD permissions for device enrollment

🛡 Security Considerations

No credentials stored locally

Uses secure Microsoft authentication flow

No hardcoded secrets

Designed for enterprise compliance

📊 Business Benefits
Benefit	Impact
⏱ Deployment Speed	90%+ Faster
❌ Human Error	Eliminated
👨‍💻 Technician Effort	Reduced
📦 Bulk Enrollment	Simplified
🛡 Compliance	Standardized
🏗 Ideal For

Enterprise IT Departments

Managed Service Providers (MSPs)

Large-scale device rollouts

Pre-provisioning workflows

Autopilot white-glove deployments

🔮 Roadmap

 Offline CSV export option

 Bulk hash collection mode

 Logging dashboard

 Silent background upload mode

 Intune API direct upload integration

 Auto group assignment

👨‍💻 Author

Kajal Kumar Shal
Enterprise Automation Engineer
PowerShell | SCCM | Intune | Azure Automation

📜 License

MIT License
(Modify as needed)
