Final-Year-Project-

𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐓𝐢𝐭𝐥𝐞: “𝐅𝐢𝐥𝐞𝐥𝐞𝐬𝐬 𝐌𝐚𝐥𝐰𝐚𝐫𝐞 𝐃𝐞𝐭𝐞𝐜𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐌𝐢𝐭𝐢𝐠𝐚𝐭𝐢𝐨𝐧 𝐢𝐧 𝐎𝐩𝐞𝐫𝐚𝐭𝐢𝐨𝐧𝐚𝐥 𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐲 (𝐎𝐓) 𝐄𝐧𝐯𝐢𝐫𝐨𝐧𝐦𝐞𝐧𝐭𝐬”🖥️🔍

𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞:

To detect and mitigate fileless malware threats in Operational Technology (OT) systems using real-time memory forensics and network monitoring.

**Core Detection Capabilities:**

🧠 Memory Forensics Engine

Real-time process behavior analysis, Detects over 15 advanced attack patterns, including:

o PowerShell download cradles

o Base64-encoded command execution

o Reflective DLL injection

o Suspicious parent-child process chains

🌐 Network Inspection Layer

o Custom-built Suricata rules for deep traffic analysis

o Detects Living-Off-the-Land Binaries (LOLBins) like mshta and rundll32

o Flags registry-based persistence and WMI abuse

⚠️ Real-Time Alerts –

o Real-time alerts via email (smtplib) and desktop popups (plyer)

📊 Dashboard & Reporting –

o Built a Flask-based dashboard showing PID, process names, and 
 detection justifications.

🛠️𝐓𝐞𝐜𝐡 𝐒𝐭𝐚𝐜𝐤:

•Python backend with Flask dashboard 

•Psutil for live process monitoring

•Regex-based command line analysis

•Suricata IDS with custom rules

•Real-time alerts (Email + Desktop)
