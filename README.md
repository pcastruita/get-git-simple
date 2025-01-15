# get-git-simple

# 1. Navigate to the Cloned Repository 
Use the cd command to move into the directory where your repository is stored. For example:

```bash

cd /path/to/your/repository

```
# 2. Check the Status of the Repository

Run the following command to check if there are any local changes or if the repository is in sync with GitHub:

```bash

git status

```

# 3. Pull Changes from GitHub
Before making any changes locally, ensure you have the latest version of the repository by pulling changes from GitHub:

```bash

git pull origin main

```

# 4. Make Changes Locally
Edit files or make changes as needed. Use your preferred text editor or IDE.

# 5. Stage Changes for Commit
After making changes, stage them for commit using:

```bash

git add .

```
This stages all changed files. Alternatively, specify individual files:

```bash

git add file_name

```
# 6. Commit Changes
Commit the staged changes with a descriptive message:

```bash

git commit -m "Your descriptive commit message"

```
# 7. Push Changes to GitHub
Upload your changes to GitHub:

```bash

git push origin main

```

