# Contributing Guidelines

Thank you for contributing to our projects!

## How to Contribute
1. Create a new branch from `develop` (or the appropriate base branch such as `hotfix/*` or `release/*`).
   - Use a clear naming convention:  
     - `feature/<short-description>`  
     - `bugfix/<short-description>`  
     - `hotfix/<short-description>`  
     - `release/<version>`
2. Commit your changes with meaningful commit messages.
3. Push your branch to the repository.
4. Open a Pull Request (PR) into the correct target branch.
   - Make sure the PR title and description explain the purpose of the change.

## Code Standards
- Follow our project coding conventions and style guides.
- Write clear, atomic commit messages (e.g., `fix:`, `feat:`, `docs:`).
- Ensure all tests are passing before submitting a PR.
- Include documentation updates if your changes affect usage, APIs, or infrastructure.

## Reviews
- At least one reviewer (or two for `main`) is required to approve before merge.
- Squash merge is preferred to keep the history clean.
- Tag your reviewer(s) explicitly if needed.

## Additional Notes
- Do **not** commit directly to `main` or `develop`. Use PRs only.
- Security issues should not be discussed in public PRs; see [SECURITY.md](SECURITY.md).
