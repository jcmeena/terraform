# 🛠️ Infrastructure as Code (IaC) Portfolio

Welcome to my central repository for **Terraform** configurations and cloud architecture templates. This portfolio showcases my hands-on experience in designing, automating, and deploying secure, scalable, and reproducible cloud infrastructure across multiple cloud providers.

---

### 📂 Featured Infrastructure Projects

#### 🌐 [AWS Static Website Hosting](https://github.com/jcmeena/public_static_site_aws)
*   **Provider:** AWS
*   **Description:** Automates a serverless static website hosting environment using an Amazon S3 bucket, configured with strict explicit public access settings, standard bucket policies (`s3:GetObject`), and object provisioning for `index.html`.
*   **Key Resources:** `aws_s3_bucket`, `aws_s3_bucket_website_configuration`, `aws_s3_bucket_public_access_block`, `aws_s3_bucket_policy`

#### ☁️ [Multi-AZ VPC Network Architecture](https://github.com)  <!-- Update later -->
*   **Provider:** AWS 
*   **Description:** Sets up a highly available Virtual Private Cloud (VPC) spanned across multiple Availability Zones, featuring public/private subnets, NAT Gateways for secure egress routing, and Network ACLs.
*   **Key Resources:** `aws_vpc`, `aws_subnet`, `aws_nat_gateway`, `aws_route_table`

#### ☸️ [Production-Ready Kubernetes Infrastructure](https://github.com)  <!-- Update later -->
*   **Provider:** AWS (EKS) 
*   **Description:** Provisions a fully managed, production-grade Kubernetes cluster. Configures isolated node groups, IAM roles for service accounts (IRSA), and integrated cluster autoscaling.
*   **Key Resources:** `aws_eks_cluster`, `aws_eks_node_group`, `kubernetes_namespace`

#### 🚀 [Terraform CI/CD Automation Pipeline](https://github.com/jcmeena/terraform-cicd-project)
*   **Provider:** AWS / GitHub Actions
*   **Description:** Implements a complete GitOps CI/CD automation workflow using GitHub Actions to continuously check formatting (`terraform fmt`), validate configuration syntax, generate execution logs during code reviews (`terraform plan`), and seamlessly apply infrastructure modifications upon main branch merges.
*   **Key Controls:** GitHub Actions Runner Engine, Workflow automation triggers, Secure credential mapping.




---

### 📫 Connect With Me
*   **GitHub Main Profile:** [@jcmeena](https://github.com)
*   **Email:** [jcmeena@gmail.com](mailto:jcmeena@gmail.com)
