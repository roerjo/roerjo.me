# roerjo.me
My personal site

# How I setup the auto-deployment to AWS S3
- Created an AWS IAM user to generate AWS credentials (give proper permissions to S3)
- Created `prod` and `dev` Environments in the GitHub repo settings
- Added these credentials as GitHub Environment Secrets
- Created the workflow (see .github/workflows/)
