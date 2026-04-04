# ⚙️ Setup Process

## 1. Virtual Machine Creation

- Created VM using VirtualBox
- OS: Ubuntu Server (ISO)
- Configured RAM, CPU, and disk

## 2. Ubuntu Installation

- Selected English language
- Used default installation (Ubuntu Server)
- Network configured via DHCP (NAT)
- Proxy skipped
- Mirror passed successfully

## 3. Storage Configuration

- Used guided storage
- Default disk layout

## 4. User Setup

- Created user and password
- Hostname: soc-lab (or homelab-soc)

## 5. SSH Setup

- Enabled SSH during installation

## 6. First Boot

- Logged into system successfully
- Verified network IP

## 7. Wazuh Installation

```bash
sudo bash wazuh-install.sh -a -i
* Used -i to ignore OS compatibility check (Ubuntu 24.04 not officially supported)