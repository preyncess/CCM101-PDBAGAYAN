# Checkpoint 3 – Cloud Infrastructure Components

## A. Compute Resources

**System Details**

| Resource | Information |
|---|---|
| CPU | Intel Xeon E312xx (Sandy Bridge, IBRS update) |
| CPU Cores | 1 |
| RAM | 1.9 GiB |

**What It Does**

Compute resources are responsible for handling the processing and memory requirements of the server. The CPU executes system instructions and tasks, while RAM holds temporary information needed by running programs.

**Why It Matters in Cloud Computing**

Cloud applications require CPU and memory resources to operate efficiently. Instead of purchasing physical servers, cloud computing provides users with access to these resources through virtualized environments.

**Example in KillerCoda**

The KillerCoda environment provides an Intel Xeon E312xx processor with one CPU core and 1.9 GiB of RAM. These resources are enough to execute Linux commands and support lightweight applications and processes.

---

## B. Storage Resources

**System Details**

| Storage Information | Value |
|---|---|
| Primary Disk | `/dev/vda1` |
| Total Capacity | 19 GB |
| Used | 5.4 GB |
| Free Space | 13 GB |
| Root Mount | `/` |

**Additional Mounted File Systems**

- `/boot`
- `/boot/efi`
- `/run`
- `/dev/shm`
- `/run/lock`

**What It Does**

Storage resources provide a location for keeping the operating system, applications, configuration files, and user data. Unlike RAM, stored information remains available after a process is stopped or the system is restarted.

**Why It Matters in Cloud Computing**

Cloud systems need storage to maintain application data, operating system files, databases, and other resources. Reliable storage is essential for keeping important information accessible to applications and users.

**Example in KillerCoda**

The primary storage device is `/dev/vda1`, with a capacity of 19 GB. It is mounted at `/`, which serves as the main directory of the Ubuntu system. Separate file systems are also mounted for the boot and EFI components.

---

## C. Networking Resources

**System Details**

| Network Information | Value |
|---|---|
| Hostname | `ubuntu` |
| IP Address | `172.30.1.2` |
| Additional IP | `172.17.0.1` |

**What It Does**

Networking resources enable the server to exchange information with other systems and services. The hostname identifies the machine, while IP addresses provide network addresses used for communication.

**Why It Matters in Cloud Computing**

Networking is a major part of cloud computing because cloud servers must communicate with users, applications, databases, and other services. A working network connection allows resources to be accessed and data to be transferred.

**Example in KillerCoda**

The Linux environment is identified by the hostname `ubuntu`. It has the IP addresses `172.30.1.2` and `172.17.0.1`, which are used for communication within the available network environment.

---

## D. Operating System

**System Details**

| OS Information | Value |
|---|---|
| Operating System | Ubuntu 24.04.4 LTS |
| Codename | Noble Numbat |
| Kernel | 6.8.0-138-generic |

**What It Does**

The operating system acts as the main software layer that manages the server's hardware and software resources. It also provides the interface needed to execute commands and run applications.

**Why It Matters in Cloud Computing**

An operating system allows cloud infrastructure to manage CPU, memory, storage, networking, applications, and system processes. It provides the basic environment required for cloud services and applications to function.

**Example in KillerCoda**

The KillerCoda Linux environment runs Ubuntu 24.04.4 LTS, also known as Noble Numbat, using kernel version 6.8.0-138-generic. Ubuntu manages the server's available resources and provides the Linux terminal used to execute commands.
