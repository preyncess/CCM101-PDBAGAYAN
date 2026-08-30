# CCM101 – Cloud Computing Laboratory Activities

## Laboratory Overview

This laboratory activity introduced the fundamental concepts of cloud computing and cloud infrastructure. Through the KillerCoda Linux environment, I explored a cloud-based server, examined its available resources, identified important infrastructure components, compared major cloud service providers, and created a basic cloud infrastructure design.

The activities gave me a better understanding of how **compute, storage, networking, and the operating system** work together to support a cloud environment.

---

## Learning Objectives

After completing the laboratory activities, I was able to:

1. Examine the resources available on a Linux-based cloud server.
2. Identify the major parts of cloud infrastructure.
3. Understand the functions of compute, storage, networking, and operating systems.
4. Compare infrastructure services from AWS, Microsoft Azure, and Google Cloud.
5. Recognize equivalent services offered by different cloud providers.
6. Create a basic diagram representing a cloud infrastructure.
7. Use Linux commands to collect and examine server information.

---

## Infrastructure Resources Identified

### 1. Compute

Compute resources provide the processing capability needed to execute commands, run applications, and handle server operations.

**Detected Resources:**

| Resource | Result |
|---|---|
| CPU | Intel Xeon E312xx |
| CPU Cores | 1 |
| RAM | 1.9 GiB |

---

### 2. Storage

Storage is responsible for keeping the operating system, applications, configurations, and other files used by the server.

**Main Storage Details:**

| Storage Information | Result |
|---|---|
| Primary Disk | `/dev/vda1` |
| Capacity | 19 GB |
| Main Mount Point | `/` |

Other mounted file systems identified include:

- `/boot`
- `/boot/efi`
- `/run`
- `/dev/shm`

---

### 3. Networking

Networking provides communication between the cloud server and other devices, services, and networks.

**Network Information:**

| Network Detail | Result |
|---|---|
| Hostname | `ubuntu` |
| IP Address | `172.30.1.2` |
| Additional IP | `172.17.0.1` |

---

### 4. Operating System

The operating system manages the server's hardware and software resources and provides the environment where commands and applications can run.

**Operating System Information:**

| Information | Result |
|---|---|
| OS | Ubuntu 24.04.4 LTS |
| Codename | Noble Numbat |
| Kernel | 6.8.0-138-generic |

---

## Tools and Platforms Used

The following tools and platforms supported the completion of the activities:

| Tool / Platform | Main Use |
|---|---|
| KillerCoda | Provided the cloud-based Linux environment |
| Ubuntu Linux | Operating system examined during the activity |
| Linux Terminal | Used for executing system commands |
| GitHub | Used for storing and organizing documentation |
| Markdown | Used to create the laboratory report |
| Diagramming Tool | Used to create the cloud infrastructure diagram |

---

## Linux Commands and Their Functions

| Linux Command | Function |
|---|---|
| `cat /etc/os-release` | Displays operating system details |
| `uname -r` | Displays the current kernel version |
| `lscpu` | Provides information about the CPU |
| `nproc` | Shows the number of available CPU cores |
| `free -h` | Displays memory and RAM information |
| `df -h` | Shows disk usage and available storage |
| `findmnt` | Displays mounted file systems |
| `hostname` | Displays the server hostname |
| `hostname -I` | Displays the server's IP addresses |
| `ip addr` | Shows detailed network interface information |

---

## Skills and Knowledge Gained

Throughout the laboratory activities, I developed the following skills:

- Using basic Linux terminal commands.
- Checking the operating system and kernel version.
- Identifying CPU and RAM specifications.
- Examining disk space and mounted file systems.
- Finding the hostname and IP addresses of a server.
- Understanding the basic elements of cloud infrastructure.
- Comparing services from AWS, Microsoft Azure, and Google Cloud.
- Recognizing compute, storage, networking, and IAM services.
- Creating a simple cloud infrastructure diagram.
- Creating technical documentation using Markdown.
- Organizing and maintaining laboratory files in GitHub.

---

## Problems and Challenges

One difficulty I experienced was remembering which Linux command should be used for specific system information. I also accidentally typed `hostanme -I` instead of the correct command `hostname -I`, which caused a **command not found** error.

Another challenge was understanding the relationship between the different cloud infrastructure components. It was also slightly confusing at first because AWS, Microsoft Azure, and Google Cloud use different service names even when the services have similar functions.

I was able to overcome these difficulties by carefully reviewing the command results, correcting the typing error, and comparing each cloud service according to its purpose and function.
