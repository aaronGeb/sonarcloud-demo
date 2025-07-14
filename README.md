# SonarCloud Demo Project: Salesforce + MuleSoft

## 🔧 What’s Included
- Salesforce SFDX code with static analysis via SFDX Scanner and SonarCloud
- MuleSoft API project with Maven build and Sonar analysis
- Azure DevOps YAML pipelines for CI
- PR decoration and quality gate checks

## 🚀 Setup Instructions

### 1. Prerequisites
- Azure DevOps Project
- SonarCloud Account
- Salesforce CLI
- Maven 3.x

### 2. Connect Azure DevOps to SonarCloud
- Create a new service connection to SonarCloud
- Add `SonarToken` as a secure variable in the pipeline

### 3. Run the Pipeline
Commit code to any branch or open a PR. The pipeline will:
- Run static analysis on Salesforce and MuleSoft code
- Publish results to SonarCloud
- Decorate pull requests with issues and quality gate status

### 4. Analyze Results
Go to [SonarCloud](https://sonarcloud.io) and review:
- Code smells
- Bugs
- Coverage
- Quality gate status

## 📂 Folder Structure
See top-level README or repo layout

## 🛠 Tools Used
- Azure DevOps Pipelines
- SonarCloud
- Salesforce SFDX CLI
- MuleSoft (via Maven)
