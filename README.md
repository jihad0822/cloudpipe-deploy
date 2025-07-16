# Cloudpipe Deploy
Automated deployment pipeline for static websites using AWS S3 and GitHub Actions.

## Overview
This project implements a CI/CD pipeline for deploying static websites to AWS S3 using CloudFormation for infrastructure and GitHub Actions for automation.

## Status
[![Deploy Website](https://github.com/your-username/cloudpipe-deploy/actions/workflows/deploy.yml/badge.svg)](https://github.com/your-username/cloudpipe-deploy/actions/workflows/deploy.yml)



## Setup Instructions
1. Configure AWS CLI with appropriate credentials
2. Add AWS secrets to GitHub repository
3. Push changes to main branch to trigger deployment

## Deployment Process
- Code pushed to main triggers GitHub Actions
- CloudFormation deploys/updates infrastructure
- Website files are synced to S3
- Slack notification sent on completion

## Troubleshooting
- Check GitHub Actions logs for deployment errors
- Verify AWS credentials in GitHub Secrets
- Ensure S3 bucket permissions are correct

## Architecture Diagram