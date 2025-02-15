Branching Strategy
main: The main branch contains the production-ready code.  Only stable and tested code is merged into this branch.
develop: The develop branch is the primary branch for development.  All new features and bug fixes are integrated into this branch.
Feature Branches: Feature branches are created for each new feature or bug fix.  They branch off from `develop` and are merged back into `develop` after review.
- Code review & PR guidelines
- Workflow
1. A new feature is started by creating a feature branch from develop: git checkout -b feature/new-feature develop
2. Changes are made in the feature branch and committed.
3. The feature branch is pushed to the remote repository: git push origin feature/new-feature
4. A pull request is created to merge the feature branch into develop.
5. The pull request is reviewed.
6. After review, the pull request is merged into develop.
7. Periodically, the develop branch is merged into "main" for releases.
![image](https://github.com/user-attachments/assets/be6ce292-187b-4e98-843b-765823d24100) - screens shot of the branches ans also i edited this line in feature branch.
