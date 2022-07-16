# TODO
- Setup auto deployment to S3 bucket
  - Possible methods:
    - GitHub Actions
    - AWS CodePipeline
  - Create a `develop` branch that should deploy to the dev S3 bucket after commit or PR merge
  - `master` branch should deploy to prod S3 bucket after commit or PR merge
  - test
