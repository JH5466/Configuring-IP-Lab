# Configuring-IP-Lab

## 🧑‍💻 About This Lab
In this lab, I configured a static IPv4 address on a Windows machine to restore proper network connectivity. The device initially had no network access due to a misconfigured network adapter, and because the system was intended to function as a server, assigning a static IP was the appropriate solution.

## 🛠️ Tools Used
- Windows 10 / Windows 11
- Network & Sharing Center
- Command Prompt

## 📝 Steps Performed
- Identified that the device had no network connectivity
- Opened the network adapter settings to review the configuration
- Assigned a static IPv4 address:
  - IP Address: 192.168.1.11
  - Subnet Mask: 255.255.255.0
  - Default Gateway: 192.168.1.1
  - DNS Server: 192.168.1.1
- Verified the configuration using basic network testing commands

## ⭐ Skills Demonstrated
- Static IP configuration
- Network troubleshooting
- Understanding of IPv4 addressing
- Connectivity verification using ping
- Windows network administration

## 📸 Screenshots
- **initial-no-connectivity.png** — The device shows no network connectivity due to a misconfigured network adapter, preventing it from obtaining a valid IP address.
- **static-ip-configuration.png** — Assigning a static IPv4 address, subnet mask, default gateway, and DNS server to properly configure the network adapter.
- **connectivity-tests-successful.png** — Verifying successful connectivity by pinging localhost, the default gateway, and an external website to confirm access beyond the local network.

## 🗒️ Notes
This section contains the commands used to verify network connectivity after applying the static IP configuration.

## 📂 Repository Structure
Configuring-IP-Lab/
- Screenshots/
  - initial-no-connectivity.png
  - static-ip-configuration.png
  - connectivity-tests-successful.png
- Notes/
- README.md




