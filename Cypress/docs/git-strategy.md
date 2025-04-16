# Git workflow strategy

## Branching Strategies

### Main Branch 

This is the primary branch where the source code is considered stable and ready for release.
All changes eventually get merged into this branch.

### Feature Branches

Created for developing new features or improvements.
Branch off from the main branch and merge back into it once the feature is complete and tested.
Naming convention: feature/feature-name.

## Branching Rules

### Branch Naming Conventions

Use clear and consistent naming conventions for branches to make it easy to understand their purpose.
Examples: feature/login-page, hotfix/critical-bug, release/v1.0.0.

### Commit Messages

Write meaningful commit messages that describe the changes made.
Follow a consistent format, such as type(scope): description.

### Pull Requests and Code Reviews

Use pull requests to merge changes from feature branches into the main branch.
Ensure code reviews are conducted to maintain code quality and catch potential issues.