# Create an AWS AMI for RedHat Linux (RHEL) 8 using Packer

Using Packer to create a RedHat Linux Amazon Machine Images (AMI) 

## How to use:

Update the linux-variables.json with your AWS Credentials and then execute:

```
packer build -var-file=variables.json rhel8.json
```

Blog post --> https://gmusumeci.medium.com/how-to-build-an-aws-ec2-redhat-8-ami-using-packer-d81dd48e6ea7
