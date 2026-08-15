# Checkpoint 7 – Linux Investigation

## Linux System Information

The Linux system was investigated using the KillerCoda Playground. I used basic Linux commands to check the operating system, CPU, memory, and disk space.

### 1. Operating System

Command used:

```bash
cat /etc/os-release
```

**Result:**

* Operating System: "Ubuntu 24.04.4 LTS"
* Version: 24.04.4 LTS (Noble Numbat)"

### 2. CPU Information

Command used:

```bash
lscpu
```

**Result:**

* Architecture: x86_64
* CPU(s):32-bit, 64-bit
* Model Name: Intel Xeon E312xx (Sandy Bridge, IBRS update)

### 3. Memory

Command used:

```bash
free -h
```

**Result:**

* Total Memory: 1.9Gi

### 4. Disk Space

Command used:

```bash
df -h
```

**Result:**

* Disk Size: 19GB
* Used Space: 5.4GB
* Available Space: 13GB

## Cloud Migration

If this Linux server were migrated to the cloud, it could be hosted using a virtual machine service from each cloud provider.

| Cloud Provider        | Service                |
| --------------------- | ---------------------- |
| AWS                   | Amazon EC2             |
| Microsoft Azure       | Azure Virtual Machines |
| Google Cloud Platform | Compute Engine         |

These services can provide virtual machines where a Linux operating system can run. The best choice would depend on the company's budget, location, performance needs, and other requirements.



![KillerCoda Terminal](screenshots/killercoda-terminal.png)

