13️⃣ How to resolve merge conflicts?

Answer:

Open conflicting files.

Manually fix conflicts (remove <<<<<<<, =======, >>>>>>>).

Then run:

git add .
git commit

14️⃣ How do you delete a branch?

Answer:

Local: git branch -d branchname

Remote: git push origin --delete branchname

15️⃣ How do you view commit history?

Answer:

git log
git log --oneline

16️⃣ What is the difference between git reset and git revert?

Answer:

git reset → Removes commits (rewrites history).

git revert → Creates a new commit that undoes changes safely (used in shared repos).
