---

# Infrastructure as Code with Terraform for AWS

This Terraform configuration provides an Infrastructure as Code (IaC) solution for deploying basic AWS resources including a VPC, security group, internet gateway (IGW), route table, subnet, network interface (NIC), and elastic IP (EIP).

## How to Run

1. **Prepare your working directory**:

   Copy all the code provided in this repository and adjust it as per your requirements. 

2. **Initialize your working directory**:

   Open your terminal or command prompt, navigate to the directory where your Terraform configuration files are located, and run the following command to initialize Terraform:

   ```bash
   terraform init
   ```

3. **Preview the changes**:

   To see the changes that Terraform will make to your infrastructure before applying them, run:

   ```bash
   terraform plan
   ```

4. **Create or update infrastructure**:

   If the plan looks good and you're ready to create or update your infrastructure, run:

   ```bash
   terraform apply
   ```

5. **Destroy infrastructure**:

   If you no longer need the infrastructure and want to tear it down, run:

   ```bash
   terraform destroy
   ```

   Note: Be cautious with this command as it will permanently delete all resources managed by Terraform.

## Notes

- Make sure you have the necessary packages installed to run Terraform.
- Customize the Terraform configuration files according to your specific requirements before running the commands.
- Ensure that your AWS credentials are properly configured on your machine to allow Terraform to interact with your AWS account.
