# Setting-Up-MFA-for-AWS-Account-Security
Documentation and best practices for implementing Multi-Factor Authentication to secure your AWS root and IAM users

The first line of defense in securing an AWS account is defining a robust account-wide password policy. This process is managed directly from the AWS IAM Console by following these steps:

Navigate to Account Settings: On the left-hand navigation pane of the IAM dashboard, click on Account settings

<img width="1916" height="765" alt="image" src="https://github.com/user-attachments/assets/0732e4ac-319f-4030-b515-6f01823d2e52" />

Modify the Policy: Locate the Password policy section and select the option to edit your configuration

You should then be prompted to choose between two policy types:

<img width="1886" height="932" alt="image" src="https://github.com/user-attachments/assets/2865c22a-f348-4631-9c36-4bc422b49852" />

AWS Default Policy: You can choose to enforce the standard, pre-configured security requirements provided out-of-the-box by AWS

<img width="1886" height="932" alt="image" src="https://github.com/user-attachments/assets/07745d8e-33e9-4d1d-a79e-ba6f23747bc6" />

Custom Password Policy: Alternatively, you can build a tailored policy to enforce stricter compliance rules

<img width="893" height="665" alt="image" src="https://github.com/user-attachments/assets/b3043c0b-0547-4157-b8c8-0178be1f4cb5" />


