1) Git and GitHub me kya difference hai?

Git ek distributed version control system hai — code local machine par track karta hai.
GitHub ek cloud-based hosting platform hai jaha Git repositories remotely store, collaborate & review hote.

2) git pull aur git fetch me difference?

git fetch → sirf remote se latest metadata (commits/branches) lane ka kaam karta, merge nahi karta

git pull → fetch + auto merge, yani changes local branch me apply bhi ho jate

Safe way: git fetch → review → manually merge

3) git merge vs git rebase ?

merge → history ko preserve karte hue ek naya merge commit create karta

rebase → history rewrite karta, linear history bana deta (clean but destructive)

Teams: shared repo par merge
Local cleanup ke liye rebase

4) git reset vs git revert ?

reset → history modify karta (unsafe for shared branches)

revert → ek new opposite commit add karta (safe for shared branches)

Shared repo = revert
Local fix = reset

5) Git conflict kyu aata aur resolve kaise kare?

Conflict tab aata jab same file ke same lines do jagah se change ho aur Git decide na kar paaye kaun sa rakhe.

Resolve steps:

File open karo → conflict markers ke beech code fix karo

git add <file>

git commit (ya merge complete)
