# Terraform Templates
Terraform templates for various requirements


## To run the templates
  * Install Terraform on your system (Guide: https://www.terraform.io/intro/getting-started/install.html)

  * Download the file. (**IMPORTANT: Download the variables file too and place it into same directory as the .tf file, Otherwise it will throw error.**)

  * Run **'terraform plan'** to get an idea of what is to be deployed. Put in the variable values when asked to.

  * Finally run **'terraform apply'**. Put the values when asked. This time the infrastructure would be deployed on particular provider.


#### _**WARNING:**_
  1. These things are cost incurring. Use with **Caution**.
  2. Keep a separate folder for other Terraform templates (**except variables file**). Otherwise all Terraform files would get executed at once.
