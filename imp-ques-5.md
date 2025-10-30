17️⃣ What is git stash used for?

Answer:
Temporarily saves uncommitted changes so you can work on something else.

git stash
git stash pop

18️⃣ What is git cherry-pick?

Answer:
Applies a specific commit from one branch to another.

git cherry-pick <commit_id>

19️⃣ What is git reflog?

Answer:
Shows all actions (commits, resets, checkouts) even those removed from log — useful to recover lost commits.

git reflog

20️⃣ What is a detached HEAD state?

Answer:
When HEAD points to a specific commit instead of a branch — you’re not on any branch.
Fix by creating a new branch:

git switch -c newbranch

21️⃣ What is git tag used for?

Answer:
Used to mark specific commits as release versions.
Example:

git tag v1.0
git push origin v1.0

22️⃣ What is the difference between git reset --soft, --mixed, and --hard?

Answer:

Option	Effect
--soft	Keeps changes staged
--mixed	Keeps changes unstaged
--hard	Deletes changes permanently
23️⃣ What is git remote -v?

Answer:
Shows all remote repositories linked to your project.

24️⃣ How do you rollback a commit in production (DevOps)?

Answer:
Use git revert <commit_id> to undo the bad commit and redeploy the stable version.

25️⃣ What is a Git branching strategy?

Answer:
Defines how branches are used for development:

GitFlow – main, develop, feature, release, hotfix

Trunk-based – developers commit directly to main branch frequently.
Used in CI/CD pipelines for smooth deployment flow.

Would you like me to send a PDF version of these Q&A (formatted cleanly for interview revision)?
Or shall I expand this list to 50+ Git interview questions (more advanced + CI/CD-based)?
