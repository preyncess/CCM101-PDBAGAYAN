# Checkpoint 2 – Cloud Server Infrastructure Report

## 1. Server Overview

The following information describes the current configuration of the cloud server:

| Category | Details |
|---|---|
| Operating System | Ubuntu 24.04.4 LTS (Noble Numbat) |
| Kernel | 6.8.0-138-generic |
| CPU | Intel Xeon E312xx (Sandy Bridge, IBRS update) |
| CPU Cores | 1 |
| RAM | 1.9 GiB |
| Disk Capacity | 19 GB |
| Hostname | ubuntu |
| IP Addresses | 172.30.1.2, 172.17.0.1 |

---

## 2. System Resources

### CPU
- **Processor:** Intel Xeon E312xx (Sandy Bridge, IBRS update)
- **CPU Cores:** 1

### Memory
- **Total RAM:** 1.9 GiB

### Storage
- **Total Disk Capacity:** 19 GB
- **Main Partition:** `/dev/vda1`

---

## 3. Mounted File Systems

The `df -h` command was used to check the available storage and mounted file systems.

| Filesystem | Size | Used | Available | Mount Point |
|---|---:|---:|---:|---|
| `tmpfs` | 191M | 996K | 190M | `/run` |
| `/dev/vda1` | 19G | 5.4G | 13G | `/` |
| `tmpfs` | 952M | 84K | 952M | `/dev/shm` |
| `tmpfs` | 5.0M | 0 | 5.0M | `/run/lock` |
| `/dev/vda16` | 881M | 117M | 703M | `/boot` |
| `/dev/vda15` | 105M | 6.2M | 99M | `/boot/efi` |

---

## 4. Disk Usage Summary

The main filesystem is mounted at `/` and uses the `/dev/vda1` partition.

- **Total:** 19 GB
- **Used:** 5.4 GB
- **Available:** 13 GB
- **Usage:** Approximately 29%

The server currently has sufficient available disk space for basic cloud server operations.

---

## 5. Network Information

Hostname: ubuntu
- IP Address 1: 172.30.1.2
- IP Address 2: 172.17.0.1
