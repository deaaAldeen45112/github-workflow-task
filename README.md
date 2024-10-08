# Collaborative Development using Gitflow

## Objective

This project demonstrates the practical application of the Gitflow workflow in a collaborative development environment. The goal is to understand and implement the fundamentals of version control using Git and GitHub, simulating a real-world team setting.

## Project Overview

The project is a simple example created to illustrate the Gitflow workflow. It includes basic [text files or Java code examples] and showcases the development, release, and hotfix processes. 

## Gitflow Workflow

### Branches

- **Main Branch (`main`)**: The primary branch containing the production-ready code. This is where the stable version of the project resides.
- **Development Branch (`develop`)**: The branch where ongoing development occurs. This branch integrates features and prepares for the next release.
- **Feature Branches (`feature/branch-name`)**: Created from the `develop` branch to work on new features. Merged back into `develop` once the feature is complete.
- **Release Branches (`release/branch-name`)**: Created from the `develop` branch to prepare for a new release. Includes final fixes and adjustments before merging into `main` and `develop`.
- **Hotfix Branches (`hotfix/branch-name`)**: Created from the `main` branch to address critical issues in the production code. Merged back into both `main` and `develop` after the fix is applied.

## Gitflow Workflow Simulation
This repository is a simulation of the Gitflow branching model:
[Simulation Repository](https://github.com/deya-123/gitflow-task)

## Documentation
A full project report is available in `gitflow_report.pdf`. 

## Video Presentation
A video presentation demonstration of the project setup is available on YouTube:  
[Watch the Video Presentation](https://www.youtube.com/watch?v=xa8OYlIk3tQ&t=1s)
