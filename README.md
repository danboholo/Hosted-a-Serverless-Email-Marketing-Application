# Serverless Email Marketing Application

Welcome to my step-by-step tutorial on building a serverless email marketing application using AWS services.

## Project Structure

serverless-email-marketing-application/

# Services I Used
- Amazon Simple Email Service (SES)
- AWS Lambda
- Amazon S3
- Amazon EventBridge
- AWS Identity and Access Management (IAM)

# Requirements
- Valid email addresses to send to
- An email address from your own domain to send from
- Basic knowledge of AWS
- A text editor for HTML code

# Files Included
- `email_template.html`: The HTML email template used for sending emails.
- `contacts.csv`: The CSV file containing contact information.
- `lambda_function.py`: The Python code for the Lambda function to send personalized emails.
- `lambda_policy.json`: The IAM policy for the Lambda execution role.

## Steps I Followed
1. Created an S3 Bucket:
    - I stored the email templates and contact lists in the S3 bucket.

2. Uploaded Files to S3:
    - I uploaded `email_template.html` and `contacts.csv` to the S3 bucket.

3. Set Up Amazon SES:
    - I verified my email address and domain with SES.
    - I moved SES out of the sandbox for production use.

4. Created the Lambda Function:
    - I wrote a Python function to handle the email logic.
    - I configured the Lambda execution role with the necessary permissions.

5. Set Up EventBridge:
    - I created a schedule to trigger the Lambda function for sending emails.

6. Testing:
    - I sent test emails and validated email addresses.
    - I ensured the Lambda function had the correct permissions and configurations.

# Enhancements
- I included some suggestions for improving the application.






