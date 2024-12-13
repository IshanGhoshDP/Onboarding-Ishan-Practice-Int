## Task - 1

# This task focuses on using the Git squash concept to combine multiple commits into a single, cohesive commit for better commit history management.

# Acceptance Criteria 

- Identify a branch in the project repository that contains multiple commits related to a specific feature or bug fix. 
OR 
If there are no existing PR open new branch. Identify the Accessibility issues on website,  fix every issue in a different commit and then squash them into single commit.
- Determine the range of commits that need to be squashed into a single commit.
- Use `git rebase -i HEAD~n` (where n is the number of commits to squash) to initiate an interactive rebase session.
- Squash the selected commits into one by marking them with "squash" or "s" in the interactive rebase editor.
- Provide a meaningful commit message that summarizes the changes introduced by the squashed commits.
- Ensure that the squashed commit is clear, concise, and follows the project's commit message conventions.
- Verify that the commit history has been updated, and only one commit represents the changes previously spread across multiple commits.
- Push the changes to the branch in the remote repository.
- Create a pull request from the updated branch to the main repository's master branch for review.
