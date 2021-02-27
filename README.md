# terraform-starter


### terraform-docker-demo
REF: https://learn.hashicorp.com/tutorials/terraform/install-cli?in=terraform/azure-get-started

cd terraform-docker-demo
terraform init
terraform apply

//localhost:8000
//docker ps
//terraform destroy

### build-infra-with-azure
REF: https://learn.hashicorp.com/tutorials/terraform/azure-build

//Install the Azure CLI tool - powershell as admin: Invoke-WebRequest -Uri https://aka.ms/installazurecliwindows -OutFile .\AzureCLI.msi; Start-Process msiexec.exe -Wait -ArgumentList '/I AzureCLI.msi /quiet'; rm .\AzureCLI.msi
//Authenticate using the Azure CLI: az login
cd learn-terraform-azure
...