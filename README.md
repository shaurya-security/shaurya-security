<div align="center">

# 👋 Hi, I'm Aman Kumar (Shaurya)

### Cloud • Linux • Detection Engineering • Automation

<p>
  <img src="https://skillicons.dev/icons?i=aws,linux,bash,terraform,git,vscode" />
</p>

> Most of my open-source work is published under the name **Shaurya**.

I build hands-on cloud/security labs — real infra, real telemetry, real bugs, documented honestly.

</div>

---

## 🧭 Project Progression

```mermaid
flowchart LR
    P1["1 · cloud-security-learning-portfolio"]

    P1 --> P2["2 · wazuh-custom-rule-detection"]
    P1 --> P3["3 · aws-infra-cli"]
    P1 --> P6["6 · aws-secure-vpc-with-terraform"]

    P2 --> P4["4 · aws-cloud-detection-pipeline"]
    P2 --> P5["5 · wazuh-active-response-containment"]
    P5 --> P9["9 · wazuh-windows-soc-simulation"]

    P3 -.->|"infra via aws-infra-cli"| P4
    P3 -.->|"infra via aws-infra-cli"| P5

    P6 --> P7["7 · flask-ecs-devops-pipeline"]
    P6 --> P8["8 · secure-eks-platform"]

    classDef foundation fill:#1f6feb,stroke:#0d1117,color:#fff
    classDef detection fill:#da3633,stroke:#0d1117,color:#fff
    classDef infra fill:#238636,stroke:#0d1117,color:#fff
    classDef automation fill:#8957e5,stroke:#0d1117,color:#fff

    class P1 foundation
    class P2,P4,P5,P9 detection
    class P6,P7,P8 infra
    class P3 automation
```

🔵 Foundations · 🔴 Detection engineering (Wazuh, MITRE ATT&CK) · 🟢 Infrastructure as Code · 🟣 Automation tooling

---

## 📂 Projects

| # | Repo | What it is |
|---|---|---|
| 1 | [cloud-security-learning-portfolio](https://github.com/shaurya-security/cloud-security-learning-portfolio) | Learning cloud security from scratch — six phases, documented honestly |
| 2 | [wazuh-custom-rule-detection](https://github.com/shaurya-security/wazuh-custom-rule-detection) | SSH brute-force detection lab, MITRE ATT&CK mapping |
| 3 | [aws-infra-cli](https://github.com/shaurya-security/aws-infra-cli) | 110+ function Bash/AWS CLI toolkit — VPCs, EC2, routing, no Terraform |
| 4 | [aws-cloud-detection-pipeline](https://github.com/shaurya-security/aws-cloud-detection-pipeline) | CloudTrail + VPC Flow Logs into Wazuh, simulated on EC2 — *extends #2, infra via #3* |
| 5 | [wazuh-active-response-containment](https://github.com/shaurya-security/wazuh-active-response-containment) | Full detection → automated containment → recovery chain, simulated on EC2 — *extends #2, infra via #3* |
| 6 | [aws-secure-vpc-with-terraform](https://github.com/shaurya-security/aws-secure-vpc-with-terraform) | Terraform VPC, SSM-only access, CI security checks |
| 7 | [flask-ecs-devops-pipeline](https://github.com/shaurya-security/flask-ecs-devops-pipeline) | Flask on ECS Fargate, OIDC, Checkov — *extends #6* |
| 8 | [secure-eks-platform](https://github.com/shaurya-security/secure-eks-platform) | EKS + RDS + ALB Ingress — *extends #6* |
| 9 | [wazuh-windows-soc-simulation](https://github.com/shaurya-security/wazuh-windows-soc-simulation) | 3 Windows SOC simulations, attack to remediation, Terraform-provisioned — *extends #5* |

---

## 💻 Stack

`AWS` `Terraform` `Linux` `Bash` `Wazuh` `MITRE ATT&CK` `Docker` `ECS` `EKS` `GitHub Actions`

---

## Connect

💼 [LinkedIn](https://www.linkedin.com/in/aman-kumar-141495411/)
