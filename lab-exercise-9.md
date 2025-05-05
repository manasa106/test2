Lab Exercise 9: Collaborating using Pull RequestsLab Exercise 9: Collaborating using Pull Requests
 
Objective
To understand and practice the GitHub pull request workflow, including creating branches, making changes, submitting pull requests, reviewing code, and merging changes.
 
Prerequisites
- GitHub account
- Basic understanding of Git concepts
- Web browser
 
Environment 
This lab was completed entirely through the GitHub web interface, no local Git installation was required.
 
Case 1: Created a New Repository and Branch
 
Scenario: Set up a new project repository and create a feature branch for development.
 
### Commands Used
# No local commands needed - used GitHub web interface
 
Steps Completed and Output
1. Created a new repository:
   - Navigated to GitHub.com and signed in
   - Clicked the "+" icon in the top-right corner
   - Selected "New repository"
   - Named it: "pull-request-practice"
   - Description: "Repository for practicing pull requests"
   - Visibility: Public
   - Checked "Add a README file"
   - Clicked "Create repository"
   - Output: Screenshots of the above steps
 
2. Created a new branch:
   - In the repository, clicked the "main" branch dropdown
   - Typed "feature-branch" in the search box
   - Clicked "Create branch: feature-branch from 'main'"
   - Output: Screenshots of the above steps
 
Case 2: Made Changes and Created a Pull Request
 
Scenario: Made code changes in my feature branch and created a pull request to propose merging these changes to the main branch.
 
Steps Completed and Output
1. Edited a file:
   - Navigated to the README.md file
   - Clicked the pencil icon to edit
   - Added content: "# Pull Request Practice\n\nThis repository is for practicing the GitHub pull request workflow."
   - Scrolled down and added commit message: "Update README with project description"
   - Selected "Commit directly to the feature-branch branch"
   - Clicked "Commit changes"
   - Output: Screenshots of the above steps
 
2. Created a pull request:
   - Clicked on "Pull requests" tab
   - Clicked "New pull request"
   - Set "base: main" and "compare: feature-branch"
   - Reviewed the changes
   - Clicked "Create pull request"
   - Title: "Add project description to README"
   - Description: "Updated the README file with information about the repository purpose."
   - Clicked "Create pull request"
   - Output: Screenshots of the above steps
 
Case 3: Completed the Code Review Process
 
Scenario: My pull request needed to be reviewed before merging.
 
Steps Completed and Output
1. Requested reviewers:
   - In the pull request, clicked "Reviewers" on the right sidebar
   - Searched for and selected teammates (since this was a solo project, I noted that in a team setting I would add team members here)
   - Output: Screenshots of the above steps
 
2. Added a review comment (simulated the reviewer role):
   - In the "Files changed" tab, hovered over a line
   - Clicked the "+" that appeared
   - Added comment: "Consider adding more details about what specific PR workflows we'll practice"
   - Clicked "Start a review"
   - Clicked "Finish review"
   - Selected "Request changes"
   - Clicked "Submit review"
   - Output: Screenshots of the above steps
 
3. Addressed review comments:
   - Went back to the README.md file and clicked the pencil icon
   - Added: "We will practice creating branches, making changes, creating pull requests, reviewing code, and merging changes."
   - Commit message: "Add more details as requested in the review"
   - Clicked "Commit changes"
   - Output: Screenshots of the above steps
 
4. Approved the changes (simulated the reviewer role again):
   - Went to "Files changed" tab
   - Clicked "Review changes"
   - Selected "Approve"
   - Added comment: "Changes look good now, ready to merge."
   - Clicked "Submit review"
   - Output: Screenshots of the above steps
 
Case 4: Merged Changes
 
Scenario: The pull request was approved and ready to merge.
 
Steps Completed and Output
1. Merged the pull request:
   - Went to the "Conversation" tab
   - Clicked "Merge pull request"
   - Confirmed with "Confirm merge"
   - Output: Screenshots of the above steps
 
2. Deleted the branch:
   - Clicked "Delete branch" after merge
   - Output: Screenshots of the above steps
 
Handled Potential Issues
 
Common Issue 1: Merge Conflicts
- Problem: No merge conflicts occurred during my exercise
- Knowledge Gained: I learned how to handle merge conflicts if they had occurred:
  1. Click "Resolve conflicts" button that appears
  2. Edit the file to resolve conflicts (remove conflict markers and keep desired changes)
  3. Click "Mark as resolved"
  4. Click "Commit merge"
 
Reviewers vs. Assignees - Understanding Gained
 
- Reviewers: People responsible for examining code changes and providing feedback
  - I learned that reviewers should be added when technical feedback on implementation is needed
  - Reviewers can approve or request changes
 
- Assignees: People responsible for the overall progress of the pull request
  - Usually the person who created the PR or who is currently working on it
  - Helps track ownership and responsibility for the pull request
 
Learning Outcomes Achieved
1. Understood how to create and manage branches on GitHub
2. Learned to create pull requests to propose changes
3. Understood the code review process
4. Learned how to address feedback and merge changes
5. Understood the difference between reviewers and assignees
 
Conclusion
I successfully completed the pull request workflow exercise. This process is fundamental to collaborative software development. It provides a structured way to propose, review, discuss, and merge changes, which improves code quality and team coordination. I am now comfortable with the GitHub pull request workflow and ready to apply these skills in team development environments
 
Objective
To understand and practice the GitHub pull request workflow, including creating branches, making changes, submitting pull requests, reviewing code, and merging changes.
 
Prerequisites
- GitHub account
- Basic understanding of Git concepts
- Web browser
 
Environment 
This lab was completed entirely through the GitHub web interface, no local Git installation was required.
 
Case 1: Created a New Repository and Branch
 
Scenario: Set up a new project repository and create a feature branch for development.
 
### Commands Used
# No local commands needed - used GitHub web interface
 
Steps Completed and Output
1. Created a new repository:
   - Navigated to GitHub.com and signed in
   - Clicked the "+" icon in the top-right corner
   - Selected "New repository"
   - Named it: "pull-request-practice"
   - Description: "Repository for practicing pull requests"
   - Visibility: Public
   - Checked "Add a README file"
   - Clicked "Create repository"
   - Output: Screenshots of the above steps
 
2. Created a new branch:
   - In the repository, clicked the "main" branch dropdown
   - Typed "feature-branch" in the search box
   - Clicked "Create branch: feature-branch from 'main'"
   - Output: Screenshots of the above steps
 
Case 2: Made Changes and Created a Pull Request
 
Scenario: Made code changes in my feature branch and created a pull request to propose merging these changes to the main branch.
 
Steps Completed and Output
1. Edited a file:
   - Navigated to the README.md file
   - Clicked the pencil icon to edit
   - Added content: "# Pull Request Practice\n\nThis repository is for practicing the GitHub pull request workflow."
   - Scrolled down and added commit message: "Update README with project description"
   - Selected "Commit directly to the feature-branch branch"
   - Clicked "Commit changes"
   - Output: Screenshots of the above steps
 
2. Created a pull request:
   - Clicked on "Pull requests" tab
   - Clicked "New pull request"
   - Set "base: main" and "compare: feature-branch"
   - Reviewed the changes
   - Clicked "Create pull request"
   - Title: "Add project description to README"
   - Description: "Updated the README file with information about the repository purpose."
   - Clicked "Create pull request"
   - Output: Screenshots of the above steps
 
Case 3: Completed the Code Review Process
 
Scenario: My pull request needed to be reviewed before merging.
 
Steps Completed and Output
1. Requested reviewers:
   - In the pull request, clicked "Reviewers" on the right sidebar
   - Searched for and selected teammates (since this was a solo project, I noted that in a team setting I would add team members here)
   - Output: Screenshots of the above steps
 
2. Added a review comment (simulated the reviewer role):
   - In the "Files changed" tab, hovered over a line
   - Clicked the "+" that appeared
   - Added comment: "Consider adding more details about what specific PR workflows we'll practice"
   - Clicked "Start a review"
   - Clicked "Finish review"
   - Selected "Request changes"
   - Clicked "Submit review"
   - Output: Screenshots of the above steps
 
3. Addressed review comments:
   - Went back to the README.md file and clicked the pencil icon
   - Added: "We will practice creating branches, making changes, creating pull requests, reviewing code, and merging changes."
   - Commit message: "Add more details as requested in the review"
   - Clicked "Commit changes"
   - Output: Screenshots of the above steps
 
4. Approved the changes (simulated the reviewer role again):
   - Went to "Files changed" tab
   - Clicked "Review changes"
   - Selected "Approve"
   - Added comment: "Changes look good now, ready to merge."
   - Clicked "Submit review"
   - Output: Screenshots of the above steps
 
Case 4: Merged Changes
 
Scenario: The pull request was approved and ready to merge.
 
Steps Completed and Output
1. Merged the pull request:
   - Went to the "Conversation" tab
   - Clicked "Merge pull request"
   - Confirmed with "Confirm merge"
   - Output: Screenshots of the above steps
 
2. Deleted the branch:
   - Clicked "Delete branch" after merge
   - Output: Screenshots of the above steps
 
Handled Potential Issues
 
Common Issue 1: Merge Conflicts
- Problem: No merge conflicts occurred during my exercise
- Knowledge Gained: I learned how to handle merge conflicts if they had occurred:
  1. Click "Resolve conflicts" button that appears
  2. Edit the file to resolve conflicts (remove conflict markers and keep desired changes)
  3. Click "Mark as resolved"
  4. Click "Commit merge"
 
Reviewers vs. Assignees - Understanding Gained
 
- Reviewers: People responsible for examining code changes and providing feedback
  - I learned that reviewers should be added when technical feedback on implementation is needed
  - Reviewers can approve or request changes
 
- Assignees: People responsible for the overall progress of the pull request
  - Usually the person who created the PR or who is currently working on it
  - Helps track ownership and responsibility for the pull request
 
Learning Outcomes Achieved
1. Understood how to create and manage branches on GitHub
2. Learned to create pull requests to propose changes
3. Understood the code review process
4. Learned how to address feedback and merge changes
5. Understood the difference between reviewers and assignees
 
Conclusion
I successfully completed the pull request workflow exercise. This process is fundamental to collaborative software development. It provides a structured way to propose, review, discuss, and merge changes, which improves code quality and team coordination. I am now comfortable with the GitHub pull request workflow and ready to apply these skills in team development environments
