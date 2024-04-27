# About
In this repository, you'll discover a VPC crafted using Terraform. The purpose behind creating this repository is to utilize certain AWS services. 😊

# Technologies
This project primarily employs **Terraform**.

> 📝 **Note:** 
> The entire project was developed on a Linux (Ubuntu) environment, so ensure that you execute it on a similar OS. Moreover, you can adjust the path provided in `main.tf` based on your OS to prevent errors.

# Prerequisites
Ensure that you have Terraform installed on your system before running the project. Follow the documentation provided below:

- [AWS Installation on Linux](https://docs.aws.amazon.com/es_es/cli/latest/userguide/getting-started-install.html)
- [Terraform Installation on Linux](https://developer.hashicorp.com/terraform/install#linux)

> 🚀 Additionally, remember to set up the entire AWS environment on your CLI by following its [documentation](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html).

# How to do
**Step 1:** Clone the repository 
```
git clone https://github.com/SebastianJimenez2/VPC-Terraform.git
```
**Step 2:** Initialize the project
```
terraform init
```
**Step 3:** Validate the configuration
```
terraform validate
```
**Step 4:** 
```
terraform plan
```
> ⚠️ **Warning:** 
> If you encounter an error while executing this command, ensure that you have the `config` and `credentials` files in the `.aws` directory. If not, refer to the [documentation](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html) for the `aws configure` command.

**Step 5:** Create or update the infrastructure
```
terraform apply
```
**Step 6:**
```
terraform destroy
```
> 📌 **Note:** 
> Make sure to destroy the infrastructure on the AWS account where you created the credentials; otherwise, you might incur charges on your bank account while the service is active.

# Contributing
If you encounter any issues within the project, suggestions and feedback for the project are greatly appreciated and welcomed! Feel free to share your ideas and recommendations to help enhance the project further. Your input is valuable in improving the overall quality and functionality. 😊