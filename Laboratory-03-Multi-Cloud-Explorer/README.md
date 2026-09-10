
## Mission Overview

This laboratory activity explores and compares three major cloud platforms: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). The goal is to understand their services, strengths, and appropriate use cases for different business requirements.

## Linux Server Investigation

The Linux server was investigated using the KillerCoda Linux environment.

### Operating System

The server is running Ubuntu Linux.

## Screenshot

<img width="985" height="390" alt="Terminal1" src="https://github.com/user-attachments/assets/49261866-6539-4039-adc6-bd281c5fc15e" />


### CPU

The CPU information was collected using the `lscpu` command.

## Screenshot

<img width="1122" height="104" alt="Terminal2" src="https://github.com/user-attachments/assets/ae6df4ed-7042-4559-9944-2df6f78f2b55" />


### Memory

The memory information was collected using the `free -h` command.

## Screenshot

<img width="1047" height="143" alt="Terminal3" src="https://github.com/user-attachments/assets/b11e0b12-e60c-4170-8178-bb5f0213d849" />


### Disk Space

The disk space was checked using the `df -h` command.

## Screenshot

<img width="618" height="232" alt="Terminal4" src="https://github.com/user-attachments/assets/6025568d-73dd-420a-891a-672fe9860122" />


## Linux Server Cloud Migration

If this Linux server were migrated to the cloud, it could be hosted using the following services:

| Cloud Provider | Virtual Machine Service |
|---|---|
| AWS | Amazon EC2 |
| Microsoft Azure | Azure Virtual Machines |
| Google Cloud Platform | Compute Engine |

These services provide virtual machines where a Linux operating system can be installed and used to run applications and workloads.

## Linux Commands Used

```bash
cat /etc/os-release
lscpu
free -h
df -h
