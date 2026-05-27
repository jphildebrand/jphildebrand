<div align="center">
  <img src="https://github.com/jphildebrand/jphildebrand/blob/main/Matrix.jpg" alt="Banner of a developer sitting in front of a Matrix-style desk">
</div>

<div align="center">

## Jeffrey Hildebrand

[![Email](https://img.shields.io/badge/Email-jphildebrand@madisoncollege.edu-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jphildebrand@madisoncollege.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jeffrey_Hildebrand-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeffrey-hildebrand)
[![GitHub](https://img.shields.io/badge/GitHub-jphildebrand-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jphildebrand)
[![Location](https://img.shields.io/badge/📍-Marshall,_WI-blue?style=flat-square)]()

![Profile Views](https://komarev.com/ghpvc/?username=jphildebrand&color=blueviolet&style=flat-square)

</div>

---

## 🎓 About Me

Cloud DevOps & Systems Administration student at **Madison College** graduating **December 2026**, pursuing dual AAS degrees. Currently seeking full-time opportunities in **DevOps**, **Cloud Infrastructure**, **Platform Engineering**, or **Systems Administration**.

I build and automate infrastructure across hybrid cloud and on-prem environments — from standing up Active Directory forests on Windows Server Core to deploying IaC pipelines on AWS and Azure. My background includes an **AAS in Network Security**, a **CCNA certification**, IT security internship experience at **TDS Telecom**, and a previous career as a **commercial airline pilot** (First Officer, CL-65 type rating). I bring the same systematic, checklist-driven discipline from the cockpit into infrastructure work.

---

## 🚀 Current Focus

- 🔨 **Building:** Azure IaaS migrations — moving ASP.NET apps from PaaS (App Service) to IaaS (VMs with IIS + SQL Server)
- 🏗️ **Automating:** Infrastructure as Code pipelines — Packer → OpenTofu → ASG → ALB → Route 53
- 🖥️ **Administering:** Multi-site Active Directory environments with PowerShell-driven automation
- 📚 **Learning:** Kubernetes orchestration, Python scripting, CI/CD pipeline optimization
- 💼 **Seeking:** DevOps / Cloud Infrastructure / Platform Engineering / SysAdmin roles

---

## 🛠️ Tech Stack

#### Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)

#### Infrastructure as Code & Automation
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?style=flat-square&logo=opentofu&logoColor=black)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-02A8EF?style=flat-square&logo=packer&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat-square&logo=amazonwebservices&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

#### Scripting & Languages
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)

#### OS & Platforms
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

#### Networking & Security / DevSecOps
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

#### CI/CD & DevOps
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

#### Monitoring & Observability
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

---

## 💻 Technical Projects & Experience

### 🖥️ Windows Server & Active Directory

#### AllMashBrew.local — Multi-Site AD Forest (PowerShell / Server Core)
Built a full Active Directory environment for a fictional brewery across three geographic sites (Wisconsin, Montana, Vermont) — almost entirely through PowerShell on **Windows Server Core**. Domain controller `MashCore01` running AD DS, DNS, and DHCP with four Hyper-V client VMs.

- **333 users** imported via CSV, organized into departmental OUs with AGDLP group nesting
- **53 security groups** with proper Global → Domain Local nesting for NTFS/share permissions
- **13 network shares** at `C:\Shares\` with group-based NTFS permissions and logon-based drive mapping via Item-Level Targeting GPOs
- **15 GPOs** covering wallpaper delivery, drive maps, password policy, and delegation
- Home directory provisioning, Helpdesk delegation, and a consolidated PowerShell verification script outputting to `AllMash_Verification_Report.txt`
- 📁 [**Code & Docs →**](ActiveDirectory/AllMashBrew/) | [Implementation Guide (v7 FINAL)](ActiveDirectory/AllMashBrew/AllMash_Brewery_Implementation_Guide_v7_FINAL.docx) | [Final Verification Report](ActiveDirectory/AllMashBrew/AllMashBrew-Final-Report.docx)

#### JHAquaRescue.local — Multi-Site AD Forest (GUI-Based)
GUI-based Active Directory deployment across four coastal sites (Mystic CT, Woods Hole MA, Miami FL, San Diego CA). CSV-driven user/group/computer provisioning via PowerShell, individual `New-ADComputer` entries, OU structuring, and cross-site replication.

---

### ☁️ Azure Cloud & DevOps

#### ASP.NET Resume Portfolio — PaaS to IaaS Migration (Spring 2026 Final Project)
Migrated an ASP.NET Core 8 resume portfolio web app from Azure PaaS (App Service + Azure SQL) to IaaS (Azure VMs running IIS + SQL Server). Full lifecycle from resource provisioning through CI/CD pipeline configuration.

- **PaaS stack:** App Service `hildebrand-resume-final`, SQL Server + database, Azure DevOps build & release pipelines
- **IaaS migration:** Two VMs (`hild-web-vm` / `hild-sql-vm`, `Standard_D2s_v5`), IIS configuration, .NET publish from Visual Studio, RDP file copy, `IIS_IUSRS` permission fixes
- Automated PaaS resource creation first in **Bash/Azure CLI**, then rebuilt in **PowerShell** using the Az module
- Resource group: `Spring2026-Azure-Hildebrand-Final-Project` (centralus)

#### Azure IaaS Labs — Linux VM + LAMP Stack
Deployed Ubuntu VMs on Azure with Apache, MySQL, and PHP. Wrote automation scripts for provisioning and configuration. Covered NSGs, ASGs, service tags, and Azure networking fundamentals.

---

### 🏗️ DevOps IaC Pipeline — Immutable Infrastructure on AWS

End-to-end Infrastructure as Code pipeline building **immutable, fault-tolerant infrastructure** with zero-downtime deployments:

**Packer** → **OpenTofu** → **Auto Scaling Group** → **Application Load Balancer** → **Route 53**

- Packer builds golden AMIs with application baked in (shift-left approach)
- OpenTofu declares the full infrastructure stack (VPC, subnets, ASG, ALB, DNS)
- ASG handles scaling and self-healing; ALB distributes traffic
- Route 53 manages DNS for the public endpoint
- Drift remediation through declarative state management

---

### 🔒 Security & DevSecOps

#### Network Security Internship — TDS Telecom
Applied security fundamentals in a production ISP environment. Hands-on with network monitoring, vulnerability assessment, and incident response workflows. Gained experience with least-privilege access controls and secrets management practices.

---

## 🏆 Certifications

- 🎖️ **Cisco Certified Network Associate (CCNA)**
- 🎖️ **Cisco Certified Entry Networking Technician (CCENT)**
- 🎖️ **AWS Cloud Security Badge**
- 🎖️ **Microsoft Certified Professional**
- 🎖️ **Microsoft Specialist — Windows**

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jphildebrand&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jphildebrand&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=jphildebrand&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

**💼 Open to Opportunities | 🎓 Graduating December 2026**

*Cloud DevOps · Platform Engineering · Systems Administration · Infrastructure Automation*

</div>
