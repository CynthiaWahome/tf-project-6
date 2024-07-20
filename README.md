# Set up an AWS API Gateway to fetch data from a DynamoDB table using Terraform.

## Overview

This beginner-friendly project demonstrates how to create an AWS API Gateway to read data from a DynamoDB table using Terraform. It guides you through setting up Terraform, defining AWS resources, and managing them efficiently. Please be mindful of AWS costs associated with the resources created.

## Prerequisites

1. **Terraform Installation**

   Install Terraform on your local machine by following the official guide by HashiCorp:
   - [Install Terraform using CLI](https://learn.hashicorp.com/tutorials/terraform/install-cli)
   - [Download Terraform](https://www.terraform.io/downloads.html)

2. **Visual Studio Code Installation**

   Download and install Visual Studio Code by following this guide:
   - [Download Visual Studio Code](https://code.visualstudio.com/download)

## Task Details

1. **Sign in to AWS Management Console**

   - Access the AWS Management Console at [AWS Console](https://aws.amazon.com/console/).

2. **Setup Visual Studio Code**

   - Open Visual Studio Code and configure it for your Terraform project.

3. **Create a `variables.tf` File**

   - Define your variables in a `variables.tf` file.

4. **Create VPC Endpoint**

   - Add the VPC endpoint configuration in the `main.tf` file.

5. **Create DynamoDB Table and Items**

   - Define the DynamoDB table and add items in the `main.tf` file.

6. **Create a Lambda Function**

   - Define the Lambda function in the `main.tf` file.

7. **Create a REST API, its Resource, and Method**

   - Define the REST API, its resource, and method in the `main.tf` file.

8. **Create an `output.tf` File**

   - Specify the output variables in an `output.tf` file to obtain useful information about the deployed resources.

9. **Confirm Terraform Installation**

   - Verify the installation by checking the version:
     ```bash
     terraform version
     ```

10. **Apply Terraform Configurations**

    - Execute the Terraform commands to apply the configurations:
      ```bash
      terraform init
      terraform apply
      ```

11. **Check AWS Resources**

    - Verify the created resources in the AWS Management Console.

12. **Retrieve All Items from DynamoDB Table**

    - Use the created API Gateway to retrieve all items from the DynamoDB table.


10. **Delete AWS Resources**

   - Remove the resources by executing:
     ```bash
     terraform destroy
     ```

## Cost Considerations

Be aware that creating and running AWS resources may incur costs. Review and understand the pricing for the VPC, DynamoDB, Lambda, and API Gateway resources you are using. Always delete resources when they are no longer needed to avoid unnecessary charges.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Notes

- Ensure you follow best practices for managing AWS resources and Terraform configurations.
- For additional help, refer to the official [Terraform Documentation](https://www.terraform.io/docs) and [AWS Documentation](https://docs.aws.amazon.com/), or seek support from the community.
