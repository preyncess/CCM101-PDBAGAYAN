# CCM101 Cloud Computing

## Laboratory Activity 1 – Mission 1: Introduction to the Cloud

### Overview

This laboratory activity introduces the basic skills needed in working with cloud infrastructure. It focuses on using a Linux environment, managing files and folders, checking system information, and creating a GitHub portfolio for documenting technical activities.

## Objectives

After completing this activity, I was able to:

- Access an Ubuntu Linux environment using KillerCoda.
- Open and use the Linux terminal.
- Create a new Linux user account.
- Set up the user with:
  - Bash shell
  - Home directory
  - `sudo` privileges
- Log in using the newly created account.
- Check the username, current directory, and hostname using Linux commands.

# Checkpoint 1 – Enter the Cloud

In this activity, I learned the basic use of a Linux environment for cloud computing. I accessed an Ubuntu Linux playground through KillerCoda and created a new Linux user account named **pdbagayan**. I also configured the account with a Bash shell, home directory, and `sudo` access. After that, I logged in to the new account and used different Linux commands to check the username, current working directory, and hostname.

### User Information

| Information | Result |
|---|---|
| Username | pdbagayan |
| Working Directory | `/home/pdbagayan` |
| Hostname | [Your Hostname] |

## Mission Tasks

### 1. Access the Linux Playground

I accessed the Linux Playground through **KillerCoda** and selected **Ubuntu 24.04** or the latest Ubuntu version available.

**KillerCoda Playground:**  
[https://killercoda.com/playgrounds](https://killercoda.com/playgrounds)

### 2. Commands Used

After starting the playground, I opened the terminal and checked if the Linux environment was working correctly.

The following commands were used:

```bash
sudo adduser pdbagayan
sudo usermod -aG sudo pdbagayan
su - pdbagayan

whoami
pwd
hostname
