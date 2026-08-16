# Devin Laws

### Systems Administrator | Cloud Infrastructure & Security

Hollywood, Florida
[LinkedIn](https://www.linkedin.com/in/dlaws2030)

> Building secure, automated cloud infrastructure across Azure, Terraform, Active Directory, Microsoft Sentinel, Splunk, and Windows Server.

---

## About Me

I am a Systems Administrator focused on cloud infrastructure, automation, and security engineering.

My portfolio documents hands-on environments built across Microsoft Azure and AWS, with an emphasis on secure infrastructure design, Infrastructure as Code, identity administration, Windows systems, SIEM monitoring, and cloud governance.

I use Terraform to build repeatable infrastructure, Active Directory and Group Policy to manage Windows identity and security controls, and Microsoft Sentinel and Splunk to investigate authentication activity and develop security-monitoring workflows.

Each project documents the architecture, implementation process, security decisions, troubleshooting, validation, and operational considerations involved in building the environment.

### Current Focus

* Azure infrastructure and network security
* Infrastructure as Code with Terraform
* Active Directory and Windows Server administration
* Microsoft Sentinel and KQL detection engineering
* Splunk SIEM and SPL-based log analysis
* Azure governance, RBAC, and policy enforcement
* Cloud automation and CI/CD
* Infrastructure security validation

---

## Featured Projects

| Project                                                                                                                | Focus                                                                                                                             | Key Technologies                                                           |
| ---------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [Isolated Penetration Testing Lab — Kali Linux + DVWA](https://github.com/devinlaws50-wq/azure-kali-dvwa-pentest-lab)  | Isolated attacker/target environment, network egress control, SQL injection, service fingerprinting, and manual HTTP interception | Kali Linux, DVWA, Terraform, Azure Bastion, sqlmap, Metasploit, Burp Suite |
| [Azure Hub-and-Spoke Firewall Architecture](https://github.com/devinlaws50-wq/terraform-azure-hub-spoke-firewall)      | Centralized network security, traffic inspection, forced routing, and workload segmentation                                       | Azure Firewall, Terraform, VNets, UDRs, Bastion                            |
| [Azure Landing Zone with Terraform](https://github.com/devinlaws50-wq/terraform-azure-landing-zone)                    | Segmented cloud foundation with networking, policy, monitoring, and SSH-secured workloads                                         | Terraform, Azure Policy, NSGs, Log Analytics                               |
| [Microsoft Sentinel Security Monitoring](https://github.com/devinlaws50-wq/azure-sentinel-security-monitoring)         | Linux Syslog ingestion, KQL hunting, authentication correlation, and scheduled detection                                          | Microsoft Sentinel, KQL, Log Analytics, Terraform                          |
| [Windows Server Domain Controller with Terraform](https://github.com/devinlaws50-wq/terraform-azure-domain-controller) | Automated Windows Server and Active Directory Domain Services deployment                                                          | Terraform, Azure, Windows Server, AD DS, DNS                               |
| [Windows Server GPO Hardening](https://github.com/devinlaws50-wq/windows-server-gpo-hardening)                         | Centralized Windows security policy, privileged-access control, and domain hardening                                              | Active Directory, Group Policy, Windows Server                             |
| [Splunk Linux Security Monitoring](https://github.com/devinlaws50-wq/splunk-linux-security-monitoring)                 | Authentication monitoring, failed-login detection, privileged activity, and SOC dashboards                                        | Splunk Enterprise, SPL, Linux, Azure                                       |
| [Windows File Server Access Control](https://github.com/devinlaws50-wq/windows-file-server-access-control)             | Least-privilege SMB access using AD groups, share permissions, and NTFS ACLs                                                      | Windows Server, Active Directory, SMB, NTFS                                |
| [Azure Governance and RBAC](https://github.com/devinlaws50-wq/azure-governance-rbac-policy)                            | Least-privilege access, Azure Policy enforcement, and cost governance                                                             | Azure RBAC, Azure Policy, Entra ID                                         |
| [Azure Infrastructure Stack](https://github.com/devinlaws50-wq/terraform-azure-infrastructure-stack)                   | Reusable Azure infrastructure deployment with Terraform                                                                           | Terraform, AzureRM, Networking, Compute                                    |
| [Cloud Security Foundations Archive](https://github.com/devinlaws50-wq/cyber-notes)                                    | Foundational AWS, Azure, networking, identity, and security labs                                                                  | AWS, Azure, IAM, Wireshark, Key Vault                                      |

---

## Technical Skills

| Category               | Technologies                                                                  |
| ---------------------- | ----------------------------------------------------------------------------- |
| Cloud Platforms        | Microsoft Azure, Amazon Web Services                                          |
| Infrastructure as Code | Terraform, HCL, AzureRM Provider                                              |
| Identity and Access    | Active Directory, Microsoft Entra ID, Azure RBAC, AWS IAM, Group Policy       |
| SIEM and Monitoring    | Microsoft Sentinel, Splunk Enterprise, KQL, SPL, Log Analytics, Azure Monitor |
| Windows Infrastructure | Windows Server 2022, AD DS, DNS, GPO, SMB, NTFS permissions                   |
| Linux                  | Ubuntu Server, SSH, Syslog, authentication-log analysis                       |
| Networking             | VNets, VPCs, subnets, NSGs, security groups, routing, Azure Firewall          |
| Scripting and Tools    | PowerShell, Bash, Azure CLI, Git, GitHub                                      |
| CI/CD                  | GitHub Actions, automated Terraform formatting and validation                 |
| Governance             | Azure Policy, cost-management budgets, RBAC scoping, landing-zone design      |

---

## What My Projects Demonstrate

* Designing segmented Azure network architectures
* Deploying repeatable cloud infrastructure through Terraform
* Automating Terraform validation with GitHub Actions
* Applying least-privilege identity and access controls
* Building and administering Active Directory environments
* Hardening Windows systems with Group Policy
* Managing local administrator access centrally
* Building Microsoft Sentinel detections with KQL
* Analyzing Linux authentication events with Splunk and SPL
* Managing SMB and NTFS permissions through Active Directory groups
* Implementing Azure governance with RBAC and Policy
* Validating deployments through logs, screenshots, CLI output, and functional testing
* Troubleshooting cloud, identity, networking, and security-control failures
* Applying secure repository and credential-handling practices

---

## Infrastructure Validation & CI

Several Terraform projects include GitHub Actions workflows that automatically run:

```text
terraform fmt -check -recursive
terraform init -backend=false
terraform validate
```

on pushes to `main` and pull requests.

These pipelines validate formatting and Terraform configuration without deploying cloud resources or requiring Azure credentials.

---

## Currently Building

* Additional Microsoft Sentinel detection and investigation use cases
* Azure infrastructure automation and governance projects
* Expanded detection engineering with KQL and SPL
* Penetration-testing lab using Kali Linux and DVWA
* Additional CI/CD and Infrastructure as Code security controls
* Continued development toward cloud infrastructure and security engineering roles

---

## Connect

[LinkedIn](https://www.linkedin.com/in/dlaws2030)

---

*This portfolio is continuously updated as new cloud infrastructure, automation, administration, and security projects are completed.*
