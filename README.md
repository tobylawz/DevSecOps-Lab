# DevSecOps-Lab
My DevSecOps learning lab with terraform, Python, Docker and security automation.
Learning Git basics today!
Learning Git basics day 2!
Learning Git basics today!!
# DevSecOps Lab
## Steps
1. Create repo
2. Commit & push code
3. Branch & merge
4. Document progress in Jira
5. Make roadmap diagram
Practice commit #1.
Practice commit #2
Practice commit #3
Practice commit #4
Practice commit #5
Practice commit #6
Practice commit #7
Practice commit #8
Practice commit #9
Practice commit #10
practice commit #11
practice push #1
practice pull #1
practice branch #1
practice push #2
practice pull #2
practice branch #2
practice push #3
practice pull #3
practice branch #3
practice push #4
# Juice Shop Challenges

## Challenge 1: Score Board / First Steps
- **Completed on:** 21 Dec 2025
- **Screenshot:**
  
  ![Challenge 1 Screenshot](screenshot1.png)
  
- **Notes:**  
  Completed the first Juice Shop challenge by accessing the Score Board.  
  Learned how to navigate the application and identify basic OWASP Top 10 vulnerabilities.  
  Verified the server was running locally on port 3000 and successfully captured a screenshot as evidence.  
  This challenge introduced me to Juice Shop’s environment and how challenges are tracked.  
practice pull #4
practice branch #4

My DevSecOps learning lab with Terraform, Python, Docker, and security automation.

Practiced creating a Git repository, committing and pushing code, branching and merging, documenting progress in Jira, and making a roadmap diagram. Completed multiple practice commits (#1–#11), practice pushes and pulls (#1–#4), and practice branches (#1–#4).

For the final deliverables, I first signed up for an AWS account at [https://aws.amazon.com/](https://aws.amazon.com/), created an IAM user with **programmatic access**, downloaded the **Access Key ID** and **Secret Access Key**, and configured the AWS CLI locally using:

```bash
aws configure
Entering the credentials, default region us-east-1, and output format json. Verified AWS access by listing S3 buckets using:

bash
Copy code
aws s3 ls
to ensure the account was ready.

Next, I created a Terraform project folder locally with main.tf defining an EC2 instance and an S3 bucket, variables.tf for configuration variables, and outputs.tf to output the EC2 public IP and S3 bucket name. Initialized Terraform with:

bash
Copy code
terraform init
Checked the plan using:

bash
Copy code
terraform plan
And applied it with:

bash
Copy code
terraform apply
Confirming with yes. After deployment, verified the outputs: EC2 Public IP: 18.175.165.38 and S3 Bucket Name: tobyb-terraform-demo-2025-12-22-001, confirming Terraform successfully deployed the resources.

Then, I installed Docker Desktop, pulled the OWASP Juice Shop Docker image:

bash
Copy code
docker pull bkimminich/juice-shop
And ran the container locally:

bash
Copy code
docker run --rm -p 3000:3000 bkimminich/juice-shop
Opened a browser at http://localhost:3000 and confirmed that the Juice Shop homepage loaded successfully, verifying that Docker is running the application locally.

All deliverables were completed successfully: AWS account created and configured ✅, Terraform deployed EC2 and S3 successfully ✅, Docker running Juice Shop locally ✅, and all steps documented in GitHub ✅. Terraform state is managed locally, and the Docker container runs independently of Terraform.

My DevSecOps learning lab with Terraform, Python, Docker, and security automation.

Practiced creating a Git repository, committing and pushing code, branching and merging, documenting progress in Jira, and making a roadmap diagram. Completed multiple practice commits (#1–#11), practice pushes and pulls (#1–#4), and practice branches (#1–#4).

For the final deliverables, I first signed up for an AWS account at [https://aws.amazon.com/](https://aws.amazon.com/), created an IAM user with **programmatic access**, downloaded the **Access Key ID** and **Secret Access Key**, and configured the AWS CLI locally using:

```bash
aws configure
Entered the credentials, default region us-east-1, and output format json. Verified AWS access by listing S3 buckets using:

bash
Copy code
aws s3 ls
to ensure the account was ready.

Next, I created a Terraform project folder locally with main.tf defining an EC2 instance and an S3 bucket, variables.tf for configuration variables, and outputs.tf to output the EC2 public IP and S3 bucket name. Initialized Terraform with:

bash
Copy code
terraform init
Checked the plan using:

bash
Copy code
terraform plan
And applied it with:

bash
Copy code
terraform apply
Confirming with yes. After deployment, verified the outputs: EC2 Public IP: 18.175.165.38 and S3 Bucket Name: tobyb-terraform-demo-2025-12-22-001, confirming Terraform successfully deployed the resources.

Then, I installed Docker Desktop, pulled the OWASP Juice Shop Docker image:

bash
Copy code
docker pull bkimminich/juice-shop
And ran the container locally:

bash
Copy code
docker run --rm -p 3000:3000 bkimminich/juice-shop
Opened a browser at http://localhost:3000 and confirmed that the Juice Shop homepage loaded successfully, verifying that Docker is running the application locally.

All deliverables were completed successfully: AWS account created and configured ✅, Terraform deployed EC2 and S3 successfully ✅, Docker running Juice Shop locally ✅, and all steps documented in GitHub ✅. Terraform state is managed locally, and the Docker container runs independently of Terraform.
My DevSecOps learning lab with Terraform, Python, Docker, and security automation.

Practiced creating a Git repository, committing and pushing code, branching and merging, documenting progress in Jira, and making a roadmap diagram. Completed multiple practice commits (#1–#11), practice pushes and pulls (#1–#4), and practice branches (#1–#4).

For the final deliverables, I first signed up for an AWS account at [https://aws.amazon.com/](https://aws.amazon.com/), created an IAM user with **programmatic access**, downloaded the **Access Key ID** and **Secret Access Key**, and configured the AWS CLI locally using:

```bash
aws configure


Entered the credentials, default region us-east-1, and output format json. Verified AWS access by listing S3 buckets using:

aws s3 ls


to ensure the account was ready.

Next, I created a Terraform project folder locally with main.tf defining an EC2 instance and an S3 bucket, variables.tf for configuration variables, and outputs.tf to output the EC2 public IP and S3 bucket name. Initialized Terraform with:

terraform init


Checked the plan using:

terraform plan


And applied it with:

terraform apply


Confirming with yes. After deployment, verified the outputs: EC2 Public IP: 18.175.165.38 and S3 Bucket Name: tobyb-terraform-demo-2025-12-22-001, confirming Terraform successfully deployed the resources.

Then, I installed Docker Desktop, pulled the OWASP Juice Shop Docker image:

docker pull bkimminich/juice-shop


And ran the container locally:

docker run --rm -p 3000:3000 bkimminich/juice-shop


Opened a browser at http://localhost:3000 and confirmed that the Juice Shop homepage loaded successfully, verifying that Docker is running the application locally.

All deliverables were completed successfully: AWS account created and configured ✅, Terraform deployed EC2 and S3 successfully ✅, Docker running Juice Shop locally ✅, and all steps documented in GitHub ✅. Terraform state is managed locally, and the Docker container runs independently of Terraform.