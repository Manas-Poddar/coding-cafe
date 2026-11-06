# Lab 4 – Git and GitHub

# Question 1
The `--global` flag applies Git configuration to all repositories for the current user. Without it, the configuration applies only to the current repository.

# Question 2
The `.git` directory appeared in `ls -a` but not in `ls`. It contains Git's internal data, including configuration, commit history and information required to track changes.

# Question 3
Git initially showed two untracked entries: `README.md` and the `week02/` directory. The directory may contain files created during previous labs.

# Question 4
The `.gitignore` file instructs Git to ignore virtual environments, Python cache folders, compiled Python files and operating system metadata. In my case, no additional files disappeared because `.venv` was not listed initially.

# Question 5
The `.gitignore` file should be committed because it contains instructions about which files Git should ignore. Committing it ensures that everyone working on the repository follows the same rules.

# Question 6
README.md moved from Untracked files to Changes to be committed. This happened because `git add README.md` moved the file from the working directory to the staging area.

# Question 7
Git reported that 4 files changed in the first commit. It also displayed the number of insertions and deletions.

# Question 8
The first seven characters of a commit hash form an abbreviated commit identifier. They allow us to identify and reference a particular commit without using its full hash.

# Question 9
The four steps of the Git workflow are making changes to files, checking the status, staging the changes using `git add`, and committing them using `git commit`.

# Question 10
README.md has a special name because GitHub automatically displays it on the repository's front page. It provides visitors with an introduction to the project, its purpose and its contents.

# Question 11
`gh auth login` authenticates the GitHub CLI with my GitHub account and stores the authentication credentials. This allows Git to perform future operations without repeatedly asking for my password.

# Question 12
The README.md file is displayed on the GitHub repository's front page because GitHub automatically renders it as formatted Markdown. It helps visitors understand the repository.

# Question 13
No, pushing did not change my local commit history. It simply uploaded my existing commits to the remote GitHub repository.

# Question 14
A private repository exists on GitHub but can only be accessed by its owner and authorised collaborators. A repository that does not exist on GitHub has no online presence and cannot be accessed there.