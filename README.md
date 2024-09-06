# AWS-S3-File-uploading-notification-system
#STEPS FOR DOING THE PROJECT 

1. Create a jupyter/python file
2. LOGIN USING YOUR ROOT ID PASSWORD OF AWS MANAGEMENT CONSOLE
3. install the  boto3 
4. Create an s3 bucket using the aws services 
5. Do the updation upload using the code file

#Steps for creation of S3 bucket using the AWS CLI 

1. Install the awscli on your device through command prompt
2. Create IAM USER FROM YOUR ROOT ACCOUNT
3. GIVE S3 PERMISSIONS TO IAM USER 
4. USE aws config command
5. give your access key and secret key
6. provide your default region
7. After your configuration of IAM USER USE THE CODE GIVEN IN CREATEBUCKET.IPYNB

#Steps for the Simple Notification service on aws console 

1. GO TO SNS SERVICE FROM AWS MANAGEMENT CONSOLE DASHBOARD
2. CREATE NEW SNS TOPIC BY FOLLOWING THE STEPS
3. CREATE THE SUBSCRIPTION OF YOUR EMAIL IN THE TOPIC CREATED BY USER
4. VERIFY THE EMAIL SENT BY THE AWS.
5. SELECT THE S3 BUCKET FOR WHICH YOU NEED SNS FOR THE FILE UPLOADED ANYTIME
6. SELECT THE PERMISSIONS TAB.
7. GO TO THE EVENT.
8. CREATE AN EVENT FOR THE S3 BUCKET AND ATTACH THE SERVICE FOR WHICH YOU NEED NOTIFICATION.
9. VERIFY BY UPLOADING THE FILE IN THE S3 BUCKET USER WILL GET THE NOTIFICATION FOR THE SAME.
