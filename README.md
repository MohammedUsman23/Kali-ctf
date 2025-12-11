# Kali-ctf
A professionally engineered CTF virtual machine built on Kali Linux, designed to simulate real-world vulnerabilities and support hands-on practice in enumeration, exploitation, and privilege escalation.
Custom Capture The Flag (CTF) Virtual Machine — Kali Linux (OVA)

Custom Capture The Flag (CTF) Virtual Machine — Kali Linux (OVA)

A purpose-built virtual environment for hands-on cybersecurity practice

📌 Project Overview

This repository contains a custom-developed Capture The Flag (CTF) virtual machine, engineered using Kali Linux and intentionally configured with real-world security flaws.
The VM provides a controlled environment for practicing:

• System enumeration
• Vulnerability identification
• Privilege escalation
• Misconfiguration exploitation
• Credential attacks
• CTF-style flag discovery

It is designed to support both offensive security learning and analytical workflows commonly used in SOC environments.

Due to GitHub’s file-size limitations, the virtual machine is distributed externally as a 6.19 GB OVA file.

📥 Download the Virtual Machine

The OVA package can be downloaded from the link below:

👉 Google Drive: [Insert your drive link here]

Ensure the sharing permissions are set to: “Anyone with the link” → Viewer.

🛠️ Technical Specification

• Base OS: Kali Linux (Customized)
• File Format: OVA (Open Virtual Appliance)
• Image Size: 6.19 GB
• Minimum RAM Recommended: 2–4 GB
• Minimum Disk Space: 20 GB
• Supported Platforms: VirtualBox, VMware Workstation/Player

🎯 Learning Objectives

This VM is structured to simulate realistic vulnerability scenarios and assist learners in developing practical cybersecurity competencies, specifically:

• Service and network enumeration
• Linux privilege escalation methodologies
• Exploiting weak configurations and insecure permissions
• Password discovery and credential reuse
• Challenge-based problem-solving
• Analysis of system behavior through logs and clues
• Step-by-step exploitation chains

🏁 Flag Structure

Multiple flags are embedded throughout the machine.
All flags follow a standardized format:

FLAG{example_flag_here}


Flags are strategically placed across:

• User directories
• Misconfigured services
• Hidden/obfuscated files
• Escalation stages

📘 Deployment Instructions
Using VirtualBox

• Open VirtualBox
• Navigate to File → Import Appliance
• Select the .ova file
• Proceed with default settings unless modification is required
• Import and launch the VM

Using VMware Workstation / Player

• Open VMware
• Go to File → Open
• Choose the .ova file to begin the import
• VMware will convert the appliance to its own format
• Power on the VM once import is complete

🧰 Recommended Tools for Solving the VM

You may use the following tools for enumeration and exploitation:

• Nmap
• Gobuster / Dirb
• Enum4linux
• Hydra
• LinPEAS / LinEnum
• John the Ripper
• Wireshark (optional)

These utilities will assist in systematically identifying and exploiting the machine’s vulnerabilities.

📊 Difficulty Level

Intermediate

This VM is suitable for learners with foundational knowledge of:

• Linux system operations
• Basic exploitation concepts
• Network and service enumeration
• File and permission analysis

👤 Author

Mohammed Usman
BCA Graduate • Cybersecurity Enthusiast
Focused on SOC operations, threat analysis, and hands-on security challenges.

🤝 Contributions

Feedback, suggestions, and improvements are welcome.
You may open an Issue or submit a Pull Request for review.

⚖️ Legal Disclaimer

This project is intended strictly for educational, ethical, and research purposes.
Unauthorized use of the techniques or concepts demonstrated in this VM is strictly prohibited.
