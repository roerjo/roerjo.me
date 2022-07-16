[![Deploy to prod bucket](https://github.com/roerjo/roerjo.me/actions/workflows/deploy-prod.yml/badge.svg?branch=master)](https://github.com/roerjo/roerjo.me/actions/workflows/deploy-prod.yml) [![Deploy to dev bucket](https://github.com/roerjo/roerjo.me/actions/workflows/deploy-dev.yml/badge.svg?branch=develop)](https://github.com/roerjo/roerjo.me/actions/workflows/deploy-dev.yml)
# roerjo.me
My personal site

# How I setup the auto-deployment to AWS S3
- Created an AWS IAM user to generate AWS credentials (give proper permissions to S3)
- Created `prod` and `dev` Environments in the GitHub repo settings
- Added these credentials as GitHub Environment Secrets
- Created the workflow (see .github/workflows/)
