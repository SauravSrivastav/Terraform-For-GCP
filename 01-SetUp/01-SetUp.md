************************************************************************************************************
                                  Installing Google SDK
************************************************************************************************************

# Run Google Cloud CLI:
docker run -it --rm -v ${PWD}:/work -w /work --entrypoint /bin/bash google/cloud-sdk:308.0.0

# Install Binaries:
apt-get update
apt-get install wget
apt-get install vim
apt-get install unzip

************************************************************************************************************
                                   Installing Terraform
************************************************************************************************************

# For Ubuntu :

> Link I followed: "https://www.howtoforge.com/how-to-install-terraform-on-ubuntu-1804/"

# Step1: Download the zip archive:
> wget https://releases.hashicorp.com/terraform/0.12.24/terraform_0.12.24_linux_amd64.zip

# Step2: Unzip the archive. The archive will extract a single binary called "terraform":
> unzip terraform_0.12.24_linux_amd64.zip


# Step3: Move the terraform binary to a directory included in your system's PATH in our case that's ~/bin directory:
> mv terraform ~/bin 
> or unzip terraform_0.12.24_linux_amd64.zip -d /usr/local/bin/

# Step4 : To check whether Terraform is installed, run:
>terraform version
# Terraform v0.13.1


# Run Google Cloud CLI
docker run -it --rm -v ${PWD}:/work -w /work --entrypoint /bin/bash google/cloud-sdk:308.0.0


