# lambda-ssl-checker
Lambda function to check SSL certificate expiry date

# Steps:
1. Create a SNS topic which will send an email
2. Create a IAM role with SNS full access
3. Now create a Lambda function with desired nemory and execution time limit. Add the IAM role created in the previous step.
4. Copy and paste the Lambda function script, and don't forget to put the SNS ARN.
