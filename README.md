[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/h7CYPb85)
# CMPG323-Overview---38622246

## Table of Contents
1. [Repositories](#repositories)
2. [Documentation](#documentation)
3. [Branching Strategy](#branching-strategy)
4. [.gitignore Usage](#gitignore-usage)
5. [Credentials and Sensitive Information](#credentials-and-sensitive-information)
6. [Burndown chart](#burndown-chart)

## Repositories
I will create and use the following repositories for this project:
- **Overview Repository**: "CMPG323 Overview - 38622246", contains the detailed planning for this project.
- **Project 2 Repository**: "CMPG323 Project 2 - 38622246", manages the backend services and API code.
- **Project 3 Repository**: "CMPG323 Project 3 - 38622246", contains the frontend codebase, adhering to coding standards.
- **Project 4 Repository**: "CMPG323 Project 4 - 38622246", manages RPA (Robotic Process Automation) test scripts and configurations.
- **Project 5 Repository**: "CMPG323 Project 5 - 38622246", contains code and configurations for generating project reports.
  
## Documentation
All project documentation is available here : (https://github.com/user-attachments/files/16402938/Lean.Technical.Documentation.Template.38622246.docx)

## Branching Strategy

### Planning and Analysis
For the Planning and Analysis repository:
- **main**: Contains finalized planning and analysis documents.
- **draft**: Contains drafts and working versions of documents.
- **review/\<document-name\>**: Used for document review processes.

### Web API
For the Web API repository:
- **main**: Contains production-ready code.
- **develop**: Integration branch for features and bug fixes.
- **feature/\<feature-name\>**: Used for developing new features.
- **hotfix/\<hotfix-name\>**: For urgent fixes in production.
- **release/\<release-name\>**: Prepares a new production release.

### Web App (Standards)
For the Web App repository:
- **main**: Contains production-ready code.
- **develop**: Integration branch for features and bug fixes.
- **feature/\<feature-name\>**: Used for developing new features.

- **hotfix/\<hotfix-name\>**: For urgent fixes in production.
- **release/\<release-name\>**: Prepares a new production release.

### RPA Testing
For the RPA Testing repository:
- **main**: Contains validated and approved RPA test scripts.
- **develop**: Integration branch for new or updated test scripts.
- **feature/\<feature-name\>**: Used for developing new test scripts.
- **hotfix/\<hotfix-name\>**: For urgent fixes in test scripts.
- **release/\<release-name\>**: Prepares a new set of test scripts for validation.

### Reporting
For the Reporting repository:
- **main**: Contains production-ready reports and scripts.
- **develop**: Integration branch for new or updated reports.
- **feature/\<feature-name\>**: Used for developing new reports.
- **hotfix/\<hotfix-name\>**: For urgent fixes in reports.
- **release/\<release-name\>**: Prepares a new set of reports for production.

## .gitignore Usage
Each repository will include a `.gitignore` file to specify which files and directories to ignore when I commit changes to the repository, this helps keep the repository clean and efficient. By ignoring unnecessary files, the size of the repository is reduced, making cloning and fetching faster.

## Credentials and Sensitive Information
Credentials and sensitive information should not be kept in the repository. Instead, adhere to following guidelines:
- Environment Variables: Use environment variables to store sensitive information. Use.env files for local development and make sure they're in the.gitignore file.
- Secrets Management: For production settings, use a secret management solution such as AWS Secrets Manager, Azure Key Vault, or HashiCorp Vault. 
- Configuration files: Exclude configuration files with sensitive data from the repository. Provide sample configuration files that do not include sensitive information (for example, config.sample.json).
  
By following these guidelines, I ensure that sensitive information is handled safely and ethically.

## Burndown chart
![Burndown chart](https://github.com/user-attachments/assets/7abca6f7-2a30-42aa-b703-cf8db11fd41e)

