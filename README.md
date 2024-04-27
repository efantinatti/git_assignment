# Git Assignment - efantinatti

a. What is an issue?

	A: In Git, an issue is a tracked problem, task, or feature request within a project, typically consisting of a description, labels, assignees, comments, status, and references.

b. What is a pull request?

	A: A pull request is a way to initiate and, of course, discuss changes before they are merged into the main branch of a repository.

c. How do I open up a pull request?

	A:
	> Create a Branch: Create a new branch in your local repo.
	> Make Changes: Edit or add new files to your local repo.
	> Commit Changes: Use git add and git commit to commit your changes locally.
	> Push Changes: git push your local branch to the remote repository.
	> Open Pull Request: Navigate to the repository on GitHub and click on the "Pull Request" button.
	> Review Changes: Provide a title, description, and review your changes on the pull request page.
	> Submit Pull Request: Click on the "Create Pull Request" button to open the pull request for review and potential merging.

d. Give me a step by step guide on how to add someone to your repository.

	A:
	1 - Go to your repo, where you want to add a collaborator.
	2 - Go to your repo's settings and click om Collaborators (under General).
	3 - In the Manager acces (middle botton screen) click over Add people and invite your new Collaborator by typing her/his username (name should also me resolved) and them click add.
	4 - The new Collaborator should receive an invite link by email and the pending invite notification on your manage access should change, which means confirmed.
	

e. What is the difference between git and GitHub?

	A:
	> git: Is a distributed version control system (DVCS) that allow us as developers or not to track changes in the source code during software development, and of couse, work collaboratively. Git operates locally in the developer's machine, allowing to work offline.

	> Github: Is a web-based platfor to host Git repositories as well as offering features such as issue tracking and pull requests, to name a few. Nonetheless, it allows developers or not to share code / documents publicly or privately according to their repository's settings.


f. What does git diff do?
	
	A: It allows us to display contents differences between the changes in our current repo / branch in the local directory or in the staging area or between commits.

g. What is the main branch?
	
	A: main (master) branch is the primary branch in a repository. In a nutshell, it is where (supposedly)  your code is to be delivered as final.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

	A: It isn't the best practice, specially when working on a collaborative environment. Code must follow a review process before being posted as final, that being said, tesing / isolation of changes / CI and etc are common methods to work on code development prior giving the fina status of it.