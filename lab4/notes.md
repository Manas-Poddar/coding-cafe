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