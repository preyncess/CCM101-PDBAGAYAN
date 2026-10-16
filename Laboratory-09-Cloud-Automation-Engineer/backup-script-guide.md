# Backup Script Guide

## 1. Purpose

The backup script is used to automatically compress the application data folder and save it as a `.tar.gz` file with a timestamp in its filename.

## 2. Full Bash Script

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

cd /root || exit 1

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Starting automated backup..."

mkdir -p "$BACKUP_DIR"
tar -czf "$BACKUP_DIR/backup_$TIMESTAMP.tar.gz" "$SOURCE_DIR"

echo "Backup finished successfully at $TIMESTAMP!"
```

## 3. File Permissions

The command `chmod +x backup.sh` gives the backup script permission to execute. This allows the script to run like a normal program.

## 4. Cron Schedule

```cron
0 2 * * * /root/backup.sh
```

### Cron Field Breakdown

| Field | Value | Meaning |
|---|---|---|
| Minute | 0 | Runs at minute 0 |
| Hour | 2 | Runs at 2 AM |
| Day of Month | * | Runs every day |
| Month | * | Runs every month |
| Day of Week | * | Runs every day of the week |

This cron schedule makes the backup script run automatically every day at 2:00 AM based on the server's local time.

## 5. Verification

I tested the backup by running the script manually and checking the `backups` folder for the created archive. I also used `crontab -l` to check if the scheduled backup task was properly saved.
