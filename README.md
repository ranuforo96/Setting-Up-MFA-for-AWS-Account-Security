# Setting-Up-MFA-for-AWS-Account-Security
Documentation and best practices for implementing Multi-Factor Authentication to secure your AWS root and IAM users

The first line of defense in securing an AWS account is defining a robust account-wide password policy. This process is managed directly from the AWS IAM Console by following these steps:

Navigate to Account Settings: On the left-hand navigation pane of the IAM dashboard, click on Account settings

<img width="1916" height="765" alt="image" src="https://github.com/user-attachments/assets/0732e4ac-319f-4030-b515-6f01823d2e52" />

Modify the Policy: Locate the Password policy section and select the option to edit your configuration

You should then be prompted to choose between two policy types:

IAM Default: You can choose to enforce the standard, pre-configured security requirements provided out-of-the-box by AWS

<img width="1886" height="932" alt="image" src="https://github.com/user-attachments/assets/2865c22a-f348-4631-9c36-4bc422b49852" />

Custom: Alternatively, you can build a tailored policy to enforce stricter compliance rules, including:

Complexity Requirements: Mandating a minimum character length and requiring a mix of uppercase letters, lowercase letters, numerical digits, and non-alphanumeric (special) characters

Expiration Limits: Setting passwords to automatically expire after a specific timeframe (e.g., 90 days), and deciding whether expiration requires an administrative reset

User Permissions: Choosing whether to permit users to self-change their passwords

Prevention of Reuse: Restricting users from recycling old passwords

<img width="893" height="665" alt="image" src="https://github.com/user-attachments/assets/b3043c0b-0547-4157-b8c8-0178be1f4cb5" />

Once password complexity requirements are applied, proceed to the next section to configure Multi-Factor Authentication (MFA)

On the same screen, click on your account name in the top right corner and select Security credentials

<img width="958" height="1028" alt="image" src="https://github.com/user-attachments/assets/fe84e1ca-c0a5-4625-8c38-937760a12848" />

Once the page has loaded click on Assign MFA

<img width="953" height="624" alt="image" src="https://github.com/user-attachments/assets/e0940da3-cb8d-49b5-a7ee-cced75d8b888" />

