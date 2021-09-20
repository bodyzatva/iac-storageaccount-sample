# iac-storageaccount-sample
This example is for provisioning in azure a storage account (blobstorage)

Requirements: 
  1.  Azure Cli installed: 
    Ref: https://docs.microsoft.com/pt-pt/cli/azure/install-azure-cli-windows?tabs=azure-cli
  2.  Terraform Hasicorp installed:
  Ref: https://learn.hashicorp.com/tutorials/terraform/install-cli
  3.  Clone this repo to a folder 
  4. Subscription in azure

Run the sample

  Authentication (To run this sample, you need to autenticate in azure, ref: https://docs.microsoft.com/pt-pt/cli/azure/authenticate-azure-cli)
    Step 1 - Run command: az login (on the folder)
    Step 2 - Authenticate in portal (you will be redirected to browser login)
  
  Prepare files
    Step 3 - Edit terraform.tfvars variable: Change the subscripton id to your own.
 
  Provisioning the infraestructure:
    Step 4 - Run Command: Terraform init
    Step 5 - Run Command: Terraform plan
    Step 6 - Run Command: Terraform apply
    
  Note: Verify in azure portal that your infraestructure is there. 
  Then if you want to delete all the resources that were added just run terraform destroy. 
  
 
