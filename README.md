# Windows-Firewall-Configuration
## 🧰 Tools Used
- Windows Defender Firewall with Advanced Security

## 🎯 Objective
Configure and test firewall rules by blocking Telnet traffic (Port 23), then restore the system.

## 📌 Steps Performed

1. Opened **Windows Defender Firewall with Advanced Security**.
2. Created a new inbound rule:
- Protocol: TCP
- Specific Port: 23 (Telnet)
- Action: Block the connection
- Profile: Domain, Private, Public
- Name: `Block Telnet Port 23`
3. Verified the rule was added and active.
4. Deleted the rule to restore original settings.

## 🖼️ Screenshots


## 🔒 Key Concepts Learned
- Basic use of Windows Firewall
- Blocking specific ports
- Importance of disabling insecure protocols (like Telnet)
- Safely restoring original firewall configuration
