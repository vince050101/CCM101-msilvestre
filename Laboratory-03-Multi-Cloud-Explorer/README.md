# Laboratory 03: Multi-Cloud Explorer

## Mission Overview
This laboratory explores the three major cloud platforms: AWS, Azure, and GCP, comparing their services and recommending solutions for different business scenarios. As a Cloud Solutions Consultant, I researched each platform's core services, strengths, and ideal use cases to provide data-driven recommendations for various client scenarios.

## Linux Server Investigation

### System Information
- **Operating System:** Ubuntu 24.04.1 LTS (Noble Numbat)
- **CPU:** Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz (4 vCPUs)
- **Memory:** 15.3 GiB (approximately 16 GB total)
- **Disk Space:** 78.2 GB available (98 GB total)

### Cloud Migration Options

If this Linux server were migrated to the cloud, here are the equivalent services:

| **Cloud Provider** | **Service** | **Description** |
|---|---|---|
| **AWS** | EC2 | Migrate as a Linux EC2 instance with Ubuntu 24.04 AMI (t3.xlarge or similar) |
| **Azure** | Virtual Machines | Azure Ubuntu Linux Virtual Machine (Standard D4s v3 or similar) |
| **GCP** | Compute Engine | Google Compute Engine with Ubuntu 24.04 (e2-standard-4 or similar) |

### Migration Considerations

When migrating this Linux server to the cloud, the following factors should be considered:

| **Factor** | **AWS** | **Azure** | **GCP** |
|---|---|---|---|
| **VM Size Equivalent** | t3.xlarge (4 vCPU, 16 GB RAM) | D4s v3 (4 vCPU, 16 GB RAM) | e2-standard-4 (4 vCPU, 16 GB RAM) |
| **Storage** | EBS (gp3) with 98 GB | Managed Disks with 98 GB | Persistent Disks with 98 GB |
| **Cost (approx.)** | ~$0.166/hr | ~$0.204/hr | ~$0.160/hr |

### Screenshots
- [KillerCoda Terminal](./screenshots/killercoda-terminal.png)
- [GitHub Repository Structure](./screenshots/github-repository.png)

---

## What I Learned

### Cloud Platform Understanding
- **AWS** offers the broadest range of services and is ideal for startups and global applications
- **Azure** excels with Microsoft integration and hybrid cloud scenarios
- **GCP** leads in AI/ML capabilities and Kubernetes management

### Key Takeaways
1. **Business Requirements Drive Decisions:** There's no single "best" cloud provider—each has unique strengths that align with different client needs

2. **Platform Strengths:**
   - AWS: Market leader with comprehensive services
   - Azure: Best for Microsoft-centric enterprises
   - GCP: Strongest in data analytics and AI

3. **Linux Migration:** All three platforms support Linux workloads equally well, making the choice depend on other business factors

4. **Documentation Skills:** Writing clear technical documentation and comparisons is essential for cloud architects

### GitHub Portfolio Update
This laboratory added structured research files, comparison tables, and client recommendations to my portfolio. I've improved my ability to present technical information professionally using Markdown.

---

## Repository Structure

CCM101-msilvestre/
├── README.md
├── Laboratory-01-Welcome-to-the-Cloud/
└── Laboratory-03-Multi-Cloud-Explorer/
├── README.md
├── aws-research.md
├── azure-research.md
├── gcp-research.md
├── cloud-platform-comparison.md
├── client-recommendations.md
├── reflection.md
└── screenshots/
├── aws-homepage.png
├── azure-homepage.png
├── gcp-homepage.png
├── killercoda-terminal.png
└── github-repository.png
