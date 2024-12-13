## Task - 1

# This task aims to practice Git commands `git revert` and `git reset` to understand their usage and implications in managing commit history. Additionally, it includes a scenario where multiple commits on a branch need to be consolidated into one commit.

# Acceptance Criteria:

- Identify a branch in the project repository that contains multiple commits.
- Determine the commits that need to be reverted or reset to consolidate them into one commit.
- Use `git revert` to create a new commit that undoes the changes introduced by a specific commit without modifying the commit history.
- Verify that the changes are successfully reverted and reflected in the commit history.
- If necessary, use `git reset` to move the branch pointer to a previous commit and consolidate multiple commits into one.
- Confirm that the commit history has been consolidated, and only one commit represents the changes previously spread across multiple commits.
- Push the changes to the branch in the remote repository.
- Create a pull request from the updated branch to the main repository's master branch for review.
