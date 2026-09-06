# 👋 Hi, I'm Aman Kumar (Shaurya)

### Cloud • Linux • Detection Engineering • Automation

<p>
  <img src="https://skillicons.dev/icons?i=aws,linux,bash,terraform,git,vscode" />
</p>

> Most of my open-source work is published under the name **Shaurya**.

I build hands-on cloud/security labs — real infrastructure, real telemetry, and
documented engineering decisions.

---

## 🧭 Project Progression

<p align="center">
  <img src="project_progression_1.png" alt="Project Progression" width="100%">
</p>

> The diagram shows how projects evolved and depend on one another; the sections
> below classify them by primary focus.

---

## 📂 Projects

> Projects are grouped by track. The **Project Progression** diagram above shows their chronological development and dependencies.

<p align="center">
  🔵 <strong>Foundation</strong> &nbsp;·&nbsp;
  🔴 <strong>Detection &amp; Response</strong> &nbsp;·&nbsp;
  🟢 <strong>Infrastructure as Code</strong> &nbsp;·&nbsp;
  🟣 <strong>Automation &amp; Tooling</strong>
</p>

---

### 🔵 Foundation

<sub>Baseline projects that establish the capabilities used by later work.</sub>

| Repo | What it is | Supports |
|---|---|---|
| 🔵 [sec-cloud-foundations](https://github.com/shaurya-security/sec-cloud-foundations) | Six-phase cloud security foundation, documented through hands-on labs | 🔴 Detection & Response |
| 🟢 [iac-aws-secure-vpc](https://github.com/shaurya-security/iac-aws-secure-vpc) | Secure Terraform VPC with SSM-only access + CI security checks | 🟢 Infrastructure as Code |
| 🟣 [tools-aws-bash-cli](https://github.com/shaurya-security/tools-aws-bash-cli) | 110+ function Bash/AWS CLI toolkit for VPCs, EC2 & routing | 🔴 Detection & Response |

---

### 🔴 Detection & Response

| Repo | What it is | Extends / Uses |
|---|---|---|
| 🔴 [sec-wazuh-ssh-detection](https://github.com/shaurya-security/sec-wazuh-ssh-detection) | SSH brute-force detection + MITRE ATT&CK mapping | `sec-cloud-foundations` |
| 🔴 [sec-aws-wazuh-pipeline](https://github.com/shaurya-security/sec-aws-wazuh-pipeline) | CloudTrail + VPC Flow Logs → Wazuh on EC2 | `sec-wazuh-ssh-detection` · `tools-aws-bash-cli` |
| 🔴 [sec-wazuh-active-response](https://github.com/shaurya-security/sec-wazuh-active-response) | Detection → automated containment → recovery on EC2 | `sec-wazuh-ssh-detection` · `tools-aws-bash-cli` |
| 🔴 [sec-wazuh-windows-detection](https://github.com/shaurya-security/sec-wazuh-windows-detection) | 3 Windows attack → detection → remediation simulations | `sec-wazuh-active-response` · `iac-aws-secure-vpc` |

---

### 🟢 Infrastructure as Code & DevOps

| Repo | What it is | Extends |
|---|---|---|
| 🟢 [devops-aws-ecs-flask](https://github.com/shaurya-security/devops-aws-ecs-flask) | Flask on ECS Fargate with OIDC + Checkov | `iac-aws-secure-vpc` |
| 🟢 [iac-aws-secure-eks](https://github.com/shaurya-security/iac-aws-secure-eks) | EKS + RDS + ALB Ingress | `iac-aws-secure-vpc` |

---

## 💻 Stack

`AWS` `Terraform` `Linux` `Bash` `Wazuh` `MITRE ATT&CK` `Docker` `ECS` `EKS` `GitHub Actions`

---

## Connect

💼 [LinkedIn](https://www.linkedin.com/in/aman-kumar-141495411/)
