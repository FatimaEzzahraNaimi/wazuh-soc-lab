# Wazuh SOC Lab

## Project Overview

This project demonstrates the deployment of a mini Security Operations Center (SOC) using Wazuh SIEM.

The objective is to monitor a Linux server, collect logs, detect suspicious activities, and analyze security events in real time.

## Technologies Used

- Wazuh SIEM
- Linux
- AWS Cloud
- SSH
- Log Analysis

## Project Architecture

Client → Linux Server → Wazuh Agent → Wazuh Manager → Dashboard

## Learning Objectives

- Understand SIEM concepts
- Monitor Linux systems
- Detect suspicious behavior
- Analyze security events
- Improve incident response skills

## Skills Developed

- Security Monitoring
- Threat Detection
- Linux Administration
- Cloud Security
- Log Analysis

## Future Improvements

- Add attack simulations
- Create custom detection rules
- Integrate threat intelligence feeds
## Environment

### Infrastructure

| Component | Operating System | Role |
|------------|-----------------|------|
| Wazuh Server | Ubuntu 22.04 | Manager, Indexer, Dashboard |
| Linux Client | Ubuntu 22.04 | Monitored Endpoint |
| Windows Client | Windows Server 2025 | Monitored Endpoint |

### AWS Deployment

The infrastructure was deployed inside AWS using EC2 instances within the same VPC.

Instances deployed:

- wazuh_all_in_one_new
- linux_client_new
- windows_client_new

## Security Scenarios Tested

### Linux

- Failed SSH login attempts
- Privilege escalation using sudo
- File integrity monitoring (/etc/passwd)

### Windows

- User account creation
- Administrator group modification
- Authentication monitoring
- Audit policy changes

## Threat Hunting

The project included:

- Agent filtering
- Event correlation
- MITRE ATT&CK mapping
- Authentication anomaly detection
- Privileged access monitoring

## Key Skills Demonstrated

- SIEM Deployment
- EDR Monitoring
- Linux Security
- Windows Security Monitoring
- Threat Hunting
- AWS Cloud Security
- Security Operations Center (SOC)
## Author

Fatima Ezzahra Naimi  
Cybersecurity Student at UM6P
