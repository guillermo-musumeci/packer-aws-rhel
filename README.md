# Create an AWS AMI for RedHat Linux using Packer

Using Packer to create a RedHat Linux Amazon Machine Images (AMI) 

## How to use:

Update the linux-variables.json with your AWS Credentials and then execute:

```
packer build -var-file=linux-variables.json rhel.json
```
