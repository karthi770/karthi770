# Karthikeyan Selvaraj

### Aspiring Systems Administrator

I'm working toward a systems administrator role. I learn by building real infrastructure in labs, breaking it on purpose, fixing it, and writing down what happened. The projects below are the evidence.

---

## Featured project

### [Secure AWS Infrastructure & Operations](https://github.com/karthi770/secure-aws-infrastructure-operations) (in progress)

A CloudFormation-managed AWS environment in `ca-central-1`, built to practise operating infrastructure securely, not just deploying it.

**Built so far**
- Dev and prod VPCs deployed from one parameterized template
- VPC peering with routes on both sides, verified with ping in both directions
- EC2 instances with no inbound SSH, administered through Session Manager using an IAM role
- Security groups limited to ICMP from the peer VPC
- Templates version-controlled in Git, with changes reviewed through change sets before applying

**Next:** encrypted S3, least-privilege IAM, CloudWatch alarms, and deliberate failure labs (configuration drift, failed updates, access denied, restore from backup), each documented in a runbook.

`CloudFormation` `VPC` `EC2` `IAM` `Systems Manager` `Git`

---

## More projects

| Project | What it covers |
|---|---|
| [Azure_VNet_NSG_Bastion](https://github.com/karthi770/Azure_VNet_NSG_Bastion) | Nginx web server on an Azure VM inside a virtual network, locked down with an NSG and reached through Azure Bastion |
| [CICD_Terraform_DevSecOps](https://github.com/karthi770/CICD_Terraform_DevSecOps) | AWS infrastructure provisioned with Terraform and delivered through an automated CI/CD pipeline |
| [CICD-Pipeline-EKS-cluster](https://github.com/karthi770/CICD-Pipeline-EKS-cluster) | Pipeline that deploys applications to an Amazon EKS cluster |
| [CICD_pipeline_with_ArgoCD](https://github.com/karthi770/CICD_pipeline_with_ArgoCD) | GitOps-style deployments to Kubernetes with ArgoCD |
| [EC2-tagging-Boto3](https://github.com/karthi770/EC2-tagging-Boto3) | Python and Boto3 automation for tagging EC2 instances |

---

## My goal

To become a systems administrator who keeps Windows and Linux environments running reliably, securely and well documented.

**Currently building toward**
- Windows Server and Active Directory, including Group Policy
- Linux administration
- Virtualization with Proxmox
- Backup and disaster recovery
- PowerShell and Bash automation
- Network troubleshooting

Every project here follows the same loop: build it, break it on purpose, fix it, write it down.

---

## Connect

[LinkedIn](https://www.linkedin.com/in/karthikeyan-selvaraj-73b6067a/)
