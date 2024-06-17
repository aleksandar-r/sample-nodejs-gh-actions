# sample-nodejs-gh-actions

Sample nodejs app, just for testing CI/CD with GitHub Actions

## Add Static Code Analysis with SonarCloud

Sign up for SonarCloud and create a new project.

- Add a SonarCloud token to your GitHub repository secrets.

- Update the workflow file to include SonarCloud analysis.

## Add Security Scanning with Snyk

Sign up for Snyk and create a new project.

- Add a Snyk token to your GitHub repository secrets.

- Update the workflow file to include Snyk security scans.

## Deployment to a Cloud Provider (e.g., AWS)

Set up AWS Infrastructure:

- Create an S3 bucket or an EC2 instance for deployment.
- Configure AWS credentials.
- Add AWS credentials to GitHub Secrets:

`AWS_ACCESS_KEY_ID` `AWS_SECRET_ACCESS_KEY`
