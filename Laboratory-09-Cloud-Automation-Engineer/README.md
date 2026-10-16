# Laboratory 09 - Cloud Automation Engineer

## Mission Overview

This mission shows how Bash scripts and cron jobs can be used to automate repeated cloud administration tasks, such as creating backups of application data.

## Objectives

- Learn the basic use of Bash scripts and variables.
- Create and run a backup script.
- Use `chmod` to give a script permission to run.
- Compress application files into an archive with a timestamp.
- Schedule automatic backups using cron.
- Record the steps and results using Markdown.

## Commands Executed

```bash
mkdir app-data
echo "This is critical client data." > app-data/data.txt
cat app-data/data.txt
nano backup.sh
chmod +x backup.sh
./backup.sh
ls -l backups/
tar -tzf backups/*.tar.gz
crontab -l
env EDITOR=nano crontab -e
```

## Skills Learned

In this laboratory, I learned how to create and run a Bash script, use variables to store information, compress files into backup archives, and change file permissions using `chmod`. I also learned how to use Linux cron to schedule tasks that can run automatically on a regular basis.
