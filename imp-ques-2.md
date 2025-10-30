6️⃣ What are the main areas in a Git project?

Answer:

Working directory – where you modify files.

Staging area (index) – where you prepare changes.

Repository (.git) – where commits are permanently stored.

7️⃣ What is .gitignore?

Answer:
A file that tells Git which files/folders to ignore (like logs, temp files, build outputs, etc.)
Example:

node_modules/
*.log
.env

8️⃣ What is the difference between git fetch and git pull?

Answer:

git fetch → Downloads updates from remote but doesn’t merge.

git pull → Fetches + merges changes automatically.

9️⃣ What is git add and git commit used for?

Answer:

git add → Moves changes to the staging area.

git commit → Saves those staged changes permanently in repo history.
Example:

git add .
git commit -m "Updated configuration"
