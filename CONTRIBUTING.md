Thank you for considering to contribute to "SENIOR PROJECT"

The following guidlines will deliver upon the following information 
"repository workflow standards, branch naming conventions, pull request procedures, code review requirements, and commit message formats."

## Repository Workflow Standards ##
The repository will follow a consistent workflow for making and integrating changes. The general process will be Issue → Create Branch → Make Changes → Commit → Push → Pull Request → Code Review → Merge. Following this order allows the team to document changes efficiently and provides a clear history of how the project has developed. This workflow also makes troubleshooting and bug fixes easier because changes can be traced back to the issue and commits associated with them.

Whenever possible, development work should be associated with an existing issue. If an issue does not already exist for the planned work, a new issue should be created before development begins. This allows the team to keep track of what work is being completed and why the change is necessary.

## Branch Naming Conventions ##
Branches should use short, simple, lowercase names that clearly describe the work being completed. Branch names should avoid unnecessary words or characters while still providing enough information for another contributor to understand the purpose of the branch. Examples of acceptable branch names include login-page, fix-navbar, database-setup, and parental-controls.
The purpose of this convention is to make the repository easier to navigate and allow contributors to quickly identify what work is associated with each branch.


## Pull Request Procedures ##
All changes should be submitted through a Pull Request before being merged into the main branch. A Pull Request should clearly explain what was changed or added, why the change was made, and the current completion status of the work. Any known bugs, limitations, or features that may be affected by the changes should also be documented in the Pull Request. 

Pull Requests must be reviewed and tested by at least one other contributor. Any functionality affected by the changes should be checked before the Pull Request is accepted. Contributors should also verify that existing functionality has not been broken by the new changes. Once the Pull Request has been reviewed, tested, and any necessary issues have been addressed, the author may merge their own Pull Request.

## Code Review Requirements ##
Code reviews are intended to ensure that contributions are readable, maintainable, functional, and consistent with the coding standards. Reviewers should verify that variables have clear and descriptive names that describe its function. Classes, functions, loops, and conditional statements are properly whitespaced with indents, and brackets are given their own line for readability.

Comments should provide useful information and should not simply repeat what the code is already communicating. Code should be written in a way that allows other contributors to understand and maintain it. Reviewers should also verify that tests have been added, modified, or removed when appropriate and that existing functionality has not been affected unintentionally. Documentation should be updated when necessary, and any known bugs or problems should be identified before the Pull Request is merged.

## Commit Message Formats ##
Commit messages should use standardized keywords to identify the type of change being made. The project will use “feat:” for new features, “fix:” for bug fixes, “docs:” for documentation changes, “refactor:” for restructuring existing code, “test:” for changes involving tests, and “chore:” for maintenance or configuration changes and “log:” for logging in logs.

Commit messages should provide a short and clear description of the change being made. For example, a commit adding a parental control feature could use feat: add parental control settings, while a commit fixing a login problem could use fix: correct login validation. When useful, commit messages may also include additional information such as the relevant file, function, or code section. Larger changes should provide enough information for another contributor to understand what was changed without having to inspect the entire commit.


## Testing ##
Contributors are responsible for testing their own changes before submitting a Pull Request. Testing should verify that the new or modified functionality works as intended and that existing functionality has not been negatively affected.

In addition to testing their own work, contributors are expected to test changes made by other team members during the Pull Request review process. Having another contributor test a change provides a second perspective and increases the likelihood of identifying bugs or unexpected behavior before the change is merged.

