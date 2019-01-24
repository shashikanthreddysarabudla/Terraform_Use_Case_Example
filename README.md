# Terraform_Use_Case_Example
USE CASE 1:

A cloudformation/terraform script to do the following:
I have three environments: Dev, QA and Prod.
I have a lambda function that gets triggered by either a cloudwatch scheduled event or an S3 trigger. This lambda reads a CSV from S3, and saves the records in DynamoDB.

 

This Repo is an automation script to deploy this using cloudformation or terraform script. The script should provision IAM roles as appropriate.
