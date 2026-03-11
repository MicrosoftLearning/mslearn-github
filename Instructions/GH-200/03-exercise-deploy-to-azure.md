---
lab:
  topic: GH-200
  title: Exercise - Create a workflow that deploys a web app to Azure
  description: Learn how to create a Continuous Deployment (CD) workflow that automatically
    deploys your web application to Azure.
  duration: 26 minutes
  level: 300
  islab: true
  primarytopics:
  - Azure
---

# Exercise - Create a workflow that deploys a web app to Azure

In this lab, you will learn how to create a Continuous Deployment (CD) workflow using GitHub Actions to automatically deploy your web application to Azure. CD extends CI by automatically deploying code changes to production or staging environments after passing all tests. This enables faster delivery of features and bug fixes to users.

You will learn how to:

- Understand Continuous Deployment concepts
- Create a deployment workflow for Azure
- Use repository secrets for authentication
- Configure Azure credentials
- Deploy web applications automatically
- Monitor deployment status and logs

This lab takes approximately **45-60** minutes to complete.

## Before you start

To complete the lab, you need:

- A GitHub user account. If you don't have one, you can [create a new account](https://github.com/join). If you need instructions on how to create a GitHub account, refer to the article [Creating an account on GitHub](https://docs.github.com/get-started/quickstart/creating-an-account-on-github).
- An Azure account (free tier available).
- Basic understanding of GitHub Actions and repository secrets.
- A web browser with access to the internet.

## Complete the exercise on GitHub

In this exercise, you'll create a deployment workflow through a hands-on GitHub Skills exercise.

> **Note:** This exercise is hosted on GitHub Skills and provides an interactive learning experience. You'll configure Azure resources, set up secrets, and create a workflow that automatically deploys your application to Azure.

The exercise consists of the following activities:

1. Start a web browser and navigate to the exercise repository: [https://github.com/skills/deploy-to-azure](https://github.com/skills/deploy-to-azure)

1. On the exercise page, select the **Use this template** button to copy the exercise to your GitHub account.

   > **Note:** Simply copy the exercise to your account, then give GitHub about 20 seconds to prepare the first lesson, then refresh the page.

1. Follow the instructions on the repository's README to complete all the challenges, which include:

   - **Understanding CD concepts** and deployment strategies
   - **Setting up Azure resources** for hosting your application
   - **Creating Azure credentials** for GitHub Actions
   - **Storing credentials as secrets** in your repository
   - **Creating a deployment workflow** with Azure actions
   - **Configuring deployment triggers** (e.g., on merge to main)
   - **Deploying your application** to Azure App Service
   - **Monitoring deployment progress** and troubleshooting issues
   - **Verifying the deployed application** in Azure

1. Work through each step in the exercise, following the prompts and instructions provided.

   > **Note:** The exercise uses Azure App Service, but the concepts apply to other Azure services like Container Apps, Static Web Apps, or Functions.

1. When you finish all the challenges, you'll have a complete CI/CD pipeline that automatically deploys your application to Azure.

## What you've learned

After completing this exercise, you should be able to:

- Understand Continuous Deployment principles
- Create deployment workflows with GitHub Actions
- Configure Azure for automated deployments
- Use repository secrets securely for authentication
- Deploy web applications to Azure App Service
- Monitor deployment status and troubleshoot issues
- Implement deployment best practices
- Set up complete CI/CD pipelines
- Automate the entire software delivery process

Congratulations! You've completed the "Create a workflow that deploys a web app to Azure" exercise and learned how to implement Continuous Deployment to Azure!
