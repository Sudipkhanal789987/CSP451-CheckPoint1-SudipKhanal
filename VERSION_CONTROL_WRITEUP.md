# Version Control Systems: Understanding Git and GitHub

## Introduction to Version Control

Version control is a system that helps developers track changes in files over time. It allows developers to save different versions of a project and restore older versions if needed.

## How Version Control Tracks Changes

Git tracks changes through commits. A commit acts as a snapshot of the project at a specific time. Each commit stores information such as the author, date, and description of changes. Git also gives every commit a unique SHA identifier.

Tracking changes helps developers understand project history and identify problems.

## Three Collaboration Benefits with Examples

### 1. Parallel Development

Different developers can work on separate branches. For example, one student creates a homepage while another creates a contact page.

### 2. Code Review

GitHub pull requests allow team members to review changes before merging.

### 3. Recovery From Errors

If a mistake happens, Git allows users to return to previous versions.

## Git's Backup and Recovery Mechanisms

Git stores all repository information inside the .git directory. Since Git is distributed, multiple copies exist on different systems.

Useful commands:

- git reflog
- git reset
- git revert
- git fsck

## Difference Between Git and GitHub

| Git | GitHub |
|------|---------|
| Local version control tool | Online hosting platform |
| Works offline | Requires internet |
| Tracks file history | Adds collaboration tools |
| Handles commits | Handles pull requests |

## Conclusion

Git and GitHub improve collaboration, project management, and recovery of previous work.
