# shaurya
Blue Team · Cloud Security · Detection Engineering
Self-taught. Building detection capability from scratch, in public.

---

## What I'm building

Structured path from Linux and networking foundations to cloud detection engineering. Phases 1–6 complete. Phase 7 focused on portfolio projects and practical detection workflows.

---

## Projects

**[aws-wazuh-active-response](https://github.com/shaurya-security/aws-wazuh-active-response)**
SSH brute-force detection and automated containment on AWS. Custom Wazuh correlation rule fires on threshold, triggers `firewall-drop` active response, inserts an iptables block for the attacker IP, and auto-removes it after 120 seconds. Full chain validated: attack → detection → alert → containment → recovery.

*Demonstrates: detection engineering, active response automation, iptables, MITRE T1110, AWS networking, troubleshooting.*

**[wazuh-cloud-detection-lab](https://github.com/shaurya-security/wazuh-cloud-detection-lab)**
Cloud detection pipeline on AWS using CloudTrail, VPC Flow Logs, and Wazuh. Validated the full telemetry pipeline across host, network, and API log sources before implementing detections. Custom rules for AWS enumeration and SSH brute force. Entire environment provisioned from the CLI.

*Demonstrates: telemetry pipeline design, IAM least-privilege, detection engineering, alert investigation.*

**[aws-infra-cli](https://github.com/shaurya-security/aws-infra-cli)**
Bash-based AWS infrastructure toolkit with 8 modules and 110+ functions for VPC, networking, EC2, NAT, and security group management. Built entirely on AWS CLI without Terraform or CloudFormation.

*Demonstrates: AWS networking internals, Bash scripting, infrastructure automation, dependency management.*

**[wazuh-ssh-bruteforce-detection](https://github.com/shaurya-security/wazuh-ssh-bruteforce-detection)**
Local KVM lab. Custom level-12 Wazuh rule mapped to MITRE ATT&CK T1110. Wrote the rule, triggered the attack, validated the alert, wrote the investigation report. Complete chain: activity → log → rule → alert → investigation.

*Demonstrates: custom detection rule authoring, MITRE mapping, SOC triage workflow.*

**[from-packets-to-siem](https://github.com/shaurya-security/from-packets-to-siem)**
Six phases of learning, reconstructed and documented honestly. Notes, labs, summaries — what clicked, what broke, what I'd do differently.

---

## Stack

`Wazuh` `AWS` `CloudTrail` `VPC Flow Logs` `Bash` `Python` `KVM` `Linux` `MITRE ATT&CK` `IAM` `S3` `SIEM` `iptables`

---

## Where I am

- [x] Phases 1–6 complete
- [x] Portfolio Entry 1 — SSH brute force detection (local lab)
- [x] Portfolio Entry 2 — AWS infrastructure CLI toolkit
- [x] Portfolio Entry 3 — Cloud detection pipeline (AWS + Wazuh)
- [x] Portfolio Entry 4 — Automated containment with Wazuh Active Response
- [ ] Phase 8 — Certification
- [ ] Phase 9 — Job applications

---

## Links

GitHub: https://github.com/shaurya-security
LinkedIn: https://www.linkedin.com/in/aman-kumar-141495411/

---

`amank.47659@gmail.com` · Bihar, India
