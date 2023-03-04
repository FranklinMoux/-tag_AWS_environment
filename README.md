# How to tag your AWS environment

### (1) imports the boto3 library, which is the AWS SDK for Python, and then connects to the EC2 service
### (2) defines the tag key and value that you want to apply to your environment, in this case "Environment" and "Production" respectively
### (3) defines the resources you want to tag, in this case all instances in the AWS account, and creates a dictionary containing the tag key and value
### (4) tags the resources by calling the create_tags() method of the EC2 service, passing in the resources and the tag as arguments
### You can adjust this code to target different resources and apply different tags, depending on your specific needs.
### Note that you need to setup the credentials and the region before running this script. You can follow this guide to set it up
