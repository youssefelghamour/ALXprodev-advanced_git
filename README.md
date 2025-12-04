# Git-Flow

## Overview

This project demonstrates advanced Git workflows using Git-Flow, focusing on managing features, releases, and hotfixes efficiently. It emphasizes structured branching, merging, and automation through Git hooks to maintain code stability and streamline collaboration.

## Branching Model

- **Main**: Production-ready code only.  
- **Develop**: Active development branch.  
- **Feature/***: Branches for new features.  
- **Release/***: Preparation for production releases.  
- **Hotfix/***: Urgent fixes on the main branch.

## Features

- Structured creation and management of feature branches (e.g., login and signup).  
- Release branch creation and version tagging for organized deployment.  
- Isolation of work to reduce merge conflicts and maintain stable code.  
- Automated Git hooks for pre-commit checks and post-merge logging.

## Best Practices

- Always branch from `develop` for new features.  
- Keep each feature in its own branch.  
- Merge via pull requests to ensure code review.  
- Maintain a clean `main` branch with production-ready code only.  
- Use tags to mark official release points.  
- Apply hotfixes directly to `main` and merge back to `develop`.  
- Document the workflow clearly for team collaboration.