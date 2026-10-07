# System Baseline Report

## Purpose

This report records the initial health of the Linux host before deploying the Nginx web server.

## Memory (RAM)

* Total RAM: [               total        used        free      shared  buff/cache   available
Mem:           1.9Gi       411Mi       1.1Gi       1.1Mi       497Mi       1.5Gi
Swap:          1.0Gi          0B       1.0Gi
]
* Command used: `free -h`
* Evidence: `screenshots/memory-check.png`

## Disk Storage

* Root filesystem total capacity: [IFilesystem      Size  Used Avail Use% Mounted on]
* Available storage: [/dev/vda1        19G  5.5G   13G  30% /]
* Command used: `df -h /`
* Evidence: `screenshots/disk-check.png`

## Importance of Disk Monitoring

Checking disk space before a traffic surge is important because the server needs enough storage for application files, logs, and other data. If the disk becomes full, the application or other system services may encounter errors.

