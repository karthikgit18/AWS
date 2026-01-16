
# 🚀 Production-End-to-End AWS Linux Web App 


Build an end‑to‑end AWS architecture that mirrors actual enterprise environments.





## 🏗️ Key Architecture Principles

- High Availability → Multi-AZ deployment ensures the application remains accessible during AZ failures

- Scalability → Auto Scaling dynamically adjusts capacity based on traffic and load

- Security → Private subnets, least-privilege IAM roles, and tightly scoped security groups

- Reliability → Health checks, self-healing infrastructure, and automatic instance replacement 
- Production Readiness → Designed with real-world failure scenarios in mind
- Fault Tolerance → Load balancer routes traffic only to healthy instances





## Architecture Overview

    User
     ↓
    Application Load Balancer (ALB)
     ↓
    Auto Scaling Group (EC2 – Amazon Linux)
     ↓
    Apache + PHP Application
     ↓
    Amazon RDS (MySQL)
    
    
    

## Repository Structure

    📁 WHAT GOES INTO GITHUB (FINAL STRUCTURE)

    Create this structure locally:

    aws-production-linux-web-app/
    │
    ├── README.md
    ├── architecture/
    │   └── architecture-diagram.png
    │
    ├── setup/
    │   ├── iam.md
    │   ├── security-groups.md
    │   ├── rds.md
    │   ├── ec2-linux.md
    │   ├── alb.md
    │   ├── asg.md
    │   ├── s3.md
    │   └── cloudwatch.md
    │
    ├── app/
    │   └── index.php
    │
    ├── scripts/
    │   └── linux-setup.sh
    │
    └── testing/
      └── end-to-end-testing.md



## Author

karthik
- Linkedin - https://www.linkedin.com/in/karthik-m-62a355252/
- Github - https://github.com/karthikgit18
- Mail - karthikviswa760@gmail.com 
