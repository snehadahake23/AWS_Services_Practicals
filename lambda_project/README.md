Project: AWS (Lambda) Serverless Project 

Steps Performed:

Reviewed IAM roles and permissions required for AWS Lambda.

Created a Lambda Layer to include the PyMySQL library.

Built a Data Extractor Lambda function to fetch sales data from a MySQL database.

Configured VPC, subnet, and security group for database connectivity.

Troubleshot Lambda timeout issues using CloudWatch Logs.

Created an SNS topic and subscribed an email for notifications.

Built a Report Generator Lambda function to format and send sales reports.

Tested Lambda functions manually using test events.

Scheduled automatic report execution using EventBridge (CloudWatch Events).

Verified successful email delivery of daily sales reports.

Services Used:
AWS Lambda, IAM, SNS, EventBridge, CloudWatch, EC2, Systems Manager Parameter Store
