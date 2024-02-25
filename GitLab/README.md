# GitLab CI Configuration Examples

This repository contains a collection of `gitlab-ci.yml` examples for various use cases and project environments. These examples are designed to help you get started with GitLab CI/CD pipelines, showcasing different strategies for building, testing, and deploying your applications.

## Getting Started

To use these examples, you'll need a GitLab account and a project where you can set up CI/CD pipelines. If you're new to GitLab CI/CD, it's recommended to read through [GitLab's CI/CD documentation](https://docs.gitlab.com/ee/ci/) to get familiar with the basics.

## Examples Overview

Below is a brief overview of each example included in this repository. For more detailed information, please refer to the specific configuration files and their comments.

- **tf complete pipeline**: pipeline automates Terraform workflows across development, staging, QA, and production environments.
  - [GitLab/tf-gitlab-ci.yml](tf-complete-gitlab-ci.yml)
- **multi-env pipeline**: pipeline configures a CI/CD workflow, including build, test, deploy, and promotion across environments.
  - [GitLab/multi-env-gitlab-ci.yml](multi-env-gitlab-ci.yml)
- **multi-build pipeline**: pipeline configures a CI/CD workflow, with multiple build/publish/deploy steps, for each environment.
  - [GitLab/multi-build-gitlab-ci.yml](multi-build-gitlab-ci.yml)
- **tf single env pipeline**: pipeline automates Terraform workflows for a single environment.
  - [GitLab/tf-single-env-gitlab-ci.yml](tf-single-env-gitlab-ci.yml)


## How to Use

To use an example in your project:

1. Copy the gitlab-ci file that you want to use from the example directory to the root of your GitLab project. And then rename it to `.gitlab-ci.yml` 
2. Customize the file as needed for your project's specific requirements.
3. Commit and push the `.gitlab-ci.yml` file to your GitLab repository.
4. GitLab will automatically detect the file and start running your CI/CD pipeline based on the configurations provided.

---