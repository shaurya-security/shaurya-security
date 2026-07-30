# Shaurya (Aman Kumar)
Blue Team · Cloud Security · Detection-Focused Projects

Four detection engineering projects, plus a Terraform infrastructure-as-code rebuild. All deployed. All documented.

Blue team focus: cloud detection pipelines, active response automation, SIEM rule authoring, and infrastructure-as-code on AWS.

---

## What I'm building

Structured path from Linux and networking foundations to cloud detection engineering. Phases 1–6 complete. Phase 7 focused on portfolio projects and practical detection workflows.

---

## Projects

**[wazuh-active-response-containment](https://github.com/shaurya-security/wazuh-active-response-containment)**
SSH brute-force detection and automated containment on AWS. Custom Wazuh correlation rule fires on threshold, triggers `firewall-drop` active response, inserts an iptables block for the attacker IP, and auto-removes it after 120 seconds. Full chain validated: attack → detection → alert → containment → recovery.

- *Demonstrates: detection engineering, active response automation, iptables, MITRE T1110, AWS networking, troubleshooting.*

**[aws-cloud-detection-pipeline](https://github.com/shaurya-security/aws-cloud-detection-pipeline)**
Cloud detection pipeline on AWS using CloudTrail, VPC Flow Logs, and Wazuh. Validated the full telemetry pipeline across host, network, and API log sources before implementing detections. Custom rules for AWS enumeration and SSH brute force. Entire environment provisioned from the CLI.

- *Demonstrates: telemetry pipeline design, IAM least-privilege, detection engineering, alert investigation.*

**[aws-infra-cli](https://github.com/shaurya-security/aws-infra-cli)**
Bash-based AWS infrastructure toolkit with 8 modules and 110+ functions for VPC, networking, EC2, NAT, and security group management. Built entirely on AWS CLI without Terraform or CloudFormation.

- *Demonstrates: AWS networking internals, Bash scripting, infrastructure automation, dependency management.*

**[terraform-aws-vpc-ssm](https://github.com/shaurya-security/terraform-aws-bastion-nat/tree/v2.0.0)**
Declarative rebuild of the same VPC/EC2 architecture from `aws-infra-cli`, now on v2: managed NAT Gateway (replacing a bastion-as-NAT instance), SSM-only instance access with no SSH exposure, S3 remote state with native locking, and a GitHub Actions pipeline running `terraform fmt`, `terraform validate`, and Checkov (38 checks passing). v1 (the original bastion-as-NAT build) lives at [terraform-aws-bastion-nat](https://github.com/shaurya-security/terraform-aws-bastion-nat/tree/v1.0.0).

- *Demonstrates: Infrastructure-as-Code, Terraform, AWS NAT/SSM/IAM, CI/CD, policy-as-code with Checkov.*

**[wazuh-custom-rule-detection](https://github.com/shaurya-security/wazuh-custom-rule-detection)**
Local KVM lab. Custom level-12 Wazuh rule mapped to MITRE ATT&CK T1110. Wrote the rule, triggered the attack, validated the alert, wrote the investigation report. Complete chain: activity → log → rule → alert → investigation.

- *Demonstrates: custom detection rule authoring, MITRE mapping, SOC triage workflow.*

**[from-packets-to-siem](https://github.com/shaurya-security/from-packets-to-siem)**
Six phases of learning, reconstructed and documented honestly. Notes, labs, summaries — what clicked, what broke, what I'd do differently.

---

## Stack

`Wazuh` `AWS` `CloudTrail` `VPC Flow Logs` `Bash` `Python` `KVM` `Linux` `MITRE ATT&CK` `IAM` `S3` `SIEM` `iptables` `Terraform` `Checkov` `GitHub Actions` `SSM`

---

## Where I am

- [x] Phases 1–6 complete
- [x] Portfolio Entry 1 — SSH brute force detection (local lab)
- [x] Portfolio Entry 2 — AWS infrastructure CLI toolkit
- [x] Portfolio Entry 3 — Cloud detection pipeline (AWS + Wazuh)
- [x] Portfolio Entry 4 — Automated containment with Wazuh Active Response
- [x] Portfolio Entry 5 — Terraform IaC rebuild (v1 → v2: NAT Gateway + SSM + CI/Checkov)
- [ ] Phase 8 — Certification (AWS SAA - Ongoing)
- [ ] Phase 9 — Job applications

---

## Links

GitHub: https://github.com/shaurya-security
LinkedIn: https://www.linkedin.com/in/aman-kumar-141495411/
