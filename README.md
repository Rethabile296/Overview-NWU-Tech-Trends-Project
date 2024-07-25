# CMPG323-Overview---38622246

## Table of Contents
1. [Repositories](#repositories)
2. [Documentation](#documentation)
3. [Branching Strategy](#branching-strategy)
4. [.gitignore Usage](#gitignore-usage)
5. [Credentials and Sensitive Information](#credentials-and-sensitive-information)

## Repositories
I will create and use the following repositories for this project:
- **Overview Repository**: Contains the detailed planning for this project.
- **Project 2 Repository**: Holds all project-related documentation.
- **Project 3 Repository**: 
- **Project 4 Repository**: 
- **Project 5 Repository**: 
## Documentation
All project documentation is available [here]([link-to-documentation](https://github.com/Rethabile296/CMPG323-Overview---38622246/blob/main/Lean%20Technical%20Documentation%20Template.docx)).

## Branching Strategy
We will follow the Gitflow branching strategy:

- **main**: Contains production-ready code.
- **develop**: Integration branch for features and bug fixes.
- **feature/\<feature-name\>**: Used for developing new features.
- **hotfix/\<hotfix-name\>**: For urgent fixes in production.
- **release/\<release-name\>**: Prepares a new production release.

### Branching Workflow
1. Create a feature branch from `develop` for new features.
2. Merge feature branches into `develop` after code review and testing.
3. Create a release branch when preparing for a new production release.
4. Merge the release branch into `main` and `develop` after release.
5. Use hotfix branches for critical bug fixes in `main`.

## .gitignore Usage
Each repository will include a `.gitignore` file to specify which files and directories to ignore. This helps keep the repository clean and efficient. Common patterns include:

- **Temporary files**: Logs, caches, and OS-generated files.
- **Build artifacts**: Compiled code, binaries, and distribution packages.
- **Dependencies**: Files and directories managed by package managers (e.g., `node_modules` for Node.js).

Example `.gitignore`:
```plaintext
# Node.js dependencies
node_modules/

# Build artifacts
dist/
build/

# Logs
logs/
*.log

# OS-generated files
.DS_Store
Thumbs.db

# IDE files
.vscode/
.idea/

# Environment variables
.env
