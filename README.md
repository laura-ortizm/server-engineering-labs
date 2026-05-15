# Server Engineering Labs

Technical portfolio based on practical server engineering labs focused on Linux administration, system hardening, monitoring, benchmarking, and containerized services.

## Overview

This repository contains cleaned and rewritten technical reports based on several server engineering labs. The original academic exercises have been reorganized into professional documentation, with sensitive information removed or anonymized.

The goal of this repository is to demonstrate practical experience with:

- Linux server administration
- Logical Volume Management (LVM)
- SSH configuration and hardening
- Firewall management
- Fail2ban intrusion prevention
- Apache and MariaDB deployment
- SELinux troubleshooting
- Zabbix monitoring
- Docker and Docker Compose
- Benchmarking with ApacheBench, Phoronix Test Suite, and JMeter

## Reports

| Report | Topic |
|---|---|
| `01-linux-storage-lvm.pdf` | LVM storage management and `/var` migration |
| `02-ssh-hardening-fail2ban.pdf` | SSH hardening, firewall rules, and Fail2ban |
| `03-lamp-stack-selinux.pdf` | Apache, MariaDB, PHP, and SELinux configuration |
| `04-zabbix-monitoring.pdf` | Zabbix server and agent monitoring setup |
| `05-benchmarking-docker-jmeter.pdf` | Docker, microservices, benchmarking, and load testing |

## Lab Environment

The labs were performed in a virtualized environment using Linux virtual machines. The setup included Debian-based and Rocky Linux-based systems configured in a client-server architecture.

All IP addresses, usernames, passwords, hostnames, and personal data shown in the original work have been anonymized in this public version.

## Repository Structure

```text
server-engineering-labs/
├── README.md
├── reports/
│   ├── 01-linux-storage-lvm.tex
│   ├── 02-ssh-hardening-fail2ban.tex
│   ├── 03-lamp-stack-selinux.tex
│   ├── 04-zabbix-monitoring.tex
│   └── 05-benchmarking-docker-jmeter.tex
└── images/
