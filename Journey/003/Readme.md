<!-- This is a template you can use for quick progress days. It removes a lot of the steps we encourage you to share in the longer template 000-DAY-ARTICLE-LONG-TEMPLATE.MD-->

# VPC Flow Logs with CloudWatch and Athena

## Cloud Research

- Used System Session Manager to connect to EC2 and review assigned logs on CloudWatch

- Created an S3 Bucket

- Created a VPC Endpoint in a private subnet in order to reach S3 without traversing internet

- Created CloudWatch Log Group and VPC Flow Log to CloudWatch

- Created Flow Logs to both CloudWatch and S3 Buckets 

- Created CloudWatch metric based on failed attempts to access port 22

- Created CloudWatch alarm based off that metric and configured automatic email notifications using Amazon SNS

- Used CloudWatch Insights to run adhoc SQL queries against the log data stored in cloudwatch logs

- Created a table in Amazon Athena for S3 log data from the vpc flow logs 

- Ran an adhoc SQL query for S3 log data stored in S3

## Next Steps

Explore Placement groups --->