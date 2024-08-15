# Contribution guidelines

## Getting Started

To contribute, features are added via PRs. The guideline for PRs are one PR per feature. Features can be a screen, backend integration or a bug fix. When creating a branch that later turns into a PR, kindly make use of the formats in **Branch Formats** below.


## How to contribute

- Clone the repository
- Make the code changes or work on a feature
- Create a new branch E.g **```git branch -b feat/auth```**
- Checkout to the branch E.g **```git checkout feat/auth```**
- Push the branch to your remote branch
- Make a PR to the *dev* branch
- Include screenshots or appetize/loom link of screens worked on in the PR description
- Request for PR review


NB: 
- Always pull from the dev branch before pushing your commits
- Don't use hardcoded strings, create or use the shared/constants/app_strings.dart
- Always check TODOs and work on them if it is assigned to you


## Branch Formats

- **```feat/<branch_name>```**
- **```chore/<branch_name>```**
- **```fix/<branch_name>```**


NB: <branch_name> here is the feature you're working on. E.g **```feat/authentication```**
