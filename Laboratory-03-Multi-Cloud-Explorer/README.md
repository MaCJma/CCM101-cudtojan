# Laboratory Activity 3: Mission 3 - Become a Multi-Cloud Explorer

**Course:** Cloud Computing  
**Author:** Christian Jay Udtojan 
**Repository:** Cloud Computing Portfolio  

---

## Overview
This directory contains research, comparisons, and recommendation documentation for public cloud platforms (AWS, Azure, GCP).

## Portfolio Structure
- `docs/aws-research.md` - AWS capabilities, global infrastructure, and core services.
- `docs/azure-research.md` - Azure platform analysis and enterprise features.
- `docs/gcp-research.md` - GCP evaluation focusing on data, containers, and AI.
- `docs/cloud-platform-comparison.md` - Multi-cloud comparison matrix and equivalency tables.
- `docs/client-recommendations.md` - Real-world scenario architectures and decision matrix.

---

## Checkpoint 7: Linux Instance Assessment (KillerCoda Environment)

### Terminal Command Output Data
The following system metrics were collected inside the Linux KillerCoda terminal session:

* **Operating System:** Ubuntu 22.04 LTS (`cat /etc/os-release` or `lsb_release -a`)
* **CPU Information:** x86_64 Architecture, 2 vCPUs (`lscpu` or `nproc`)
* **Memory (RAM):** ~4.0 GB Total RAM (`free -h`)
* **Disk Space:** ~30.0 GB Root Partition (`df -h /`)
---

### Cloud Hosting Migration Mapping

If this Linux server environment were to be migrated to the public cloud, it could be hosted on the following equivalent compute services:

* **Amazon Web Services (AWS):** Hosted as an **Amazon EC2** instance (e.g., `t3.medium` instance type with 2 vCPUs, 4 GB RAM, and a 30 GB EBS General Purpose SSD volume).
* **Microsoft Azure:** Hosted as an **Azure Virtual Machine** (e.g., `Standard_B2s` instance size with 2 vCPUs, 4 GB RAM, and a 30 GB Premium SSD Managed Disk).
* **Google Cloud Platform (GCP):** Hosted as a **Google Compute Engine (GCE)** instance (e.g., `e2-medium` or `n2-standard-2` custom machine type with 30 GB Persistent Disk).
