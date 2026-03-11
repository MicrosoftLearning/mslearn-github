---
lab:
  topic: GH-100
  title: Exercise - Use a repository secret in a GitHub Actions workflow
  description: Learn how to securely store and use sensitive information in GitHub
    Actions workflows using repository secrets.
  duration: 26 minutes
  level: 300
  islab: true
  primarytopics:
  - GitHub
---

# Exercise - Use a repository secret in a GitHub Actions workflow

In this lab, you will learn how to securely store and use sensitive information in GitHub Actions workflows using repository secrets. When deploying applications or interacting with external services, you often need to use API keys, passwords, or tokens. GitHub secrets provide a secure way to store this sensitive information and use it in your workflows.

You will learn how to:

- Understand what repository secrets are and why they're important
- Create and manage repository secrets
- Reference secrets in GitHub Actions workflows
- Use secrets to deploy to Azure
- Implement security best practices for secrets
- Understand secret scoping and permissions

This lab takes approximately **30-45** minutes to complete.

## Before you start

To complete the lab, you need:

- A GitHub user account. If you don't have one, you can [create a new account](https://github.com/join). If you need instructions on how to create a GitHub account, refer to the article [Creating an account on GitHub](https://docs.github.com/get-started/quickstart/creating-an-account-on-github).
- Basic understanding of GitHub Actions workflows.
- A web browser with access to the internet.

## Complete the exercise on GitHub

In this exercise, you'll learn to work with repository secrets through a hands-on GitHub Skills exercise that demonstrates deploying to Azure.

> **Note:** This exercise is hosted on GitHub Skills and provides an interactive learning experience. You'll create secrets, configure a workflow to use them, and deploy an application securely.

The exercise consists of the following activities:

1. Start a web browser and navigate to the exercise repository: [https://github.com/skills/deploy-to-azure](https://github.com/skills/deploy-to-azure)

1. On the exercise page, select the **Use this template** button to copy the exercise to your GitHub account.

   > **Note:** Simply copy the exercise to your account, then give GitHub about 20 seconds to prepare the first lesson, then refresh the page.

1. Follow the instructions on the repository's README to complete all the challenges, which include:

   - **Understanding repository secrets** and their importance for security
   - **Creating secrets** in repository settings
   - **Referencing secrets** in workflow files using `${{ secrets.SECRET_NAME }}`
   - **Using secrets for deployment** to external services like Azure
   - **Understanding secret security** and best practices
   - **Managing secret access** and permissions
   - **Testing workflows** that use secrets

1. Work through each step in the exercise, following the prompts and instructions provided.

   > **Note:** Secrets are encrypted and not visible once created. They can only be used in workflows and cannot be retrieved through the UI after creation.

1. When you finish all the challenges, you'll understand how to securely manage sensitive information in your CI/CD workflows.

## What you've learned

After completing this exercise, you should be able to:

- Understand the importance of secrets in CI/CD pipelines
- Create and manage repository secrets in GitHub
- Reference secrets in GitHub Actions workflows
- Use secrets securely in deployment workflows
- Implement security best practices for secret management
- Understand secret scoping (repository, environment, organization)
- Deploy applications to Azure using secrets
- Protect sensitive information in automated workflows

Congratulations! You've completed the "Use a repository secret in a GitHub Actions workflow" exercise and learned how to securely manage sensitive information in your workflows!
