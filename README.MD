commit 0:
git init
git add -a
git commit -m commit 0
commit 1;
Edit README.md
git add -A
git commit -m "commit 1"
commit 2:
Edit README.md
git add -A
git commit -m "commit 2"
commit 3:
git checkout (commit 0)
git checkout -b bugfix
git add -A
git commit -m "commit 3"
commit 4:
Edit README.MD
git add -A
git commit -m "commit 4"
commit 5:
FIX MERGE CONFLICT IN README.md
git merge bugfix -m commit 5
commit 6:
Edit README.md
git add -A
git commit -m "commit 6"
commit 7:
git checkout (commit 4)
git checkout -b bugfix_experimental
git add -A
git commit -m "commit 7"
commit 8:
Edit README.md
git add -A
git commit -m "commit 8"
commit 9:
Edit README.md
git add -A
git commit -m "commit 9"
commit 10:
git checkout master
Edit README.md
git add -A
git commit -m "commit 10"
commit 11:
git checkout bugfix
git merge bugfix_experimental -m "commit 11"
commit 12:
Edit README.md
git add -A
git commit -m "commit 12"
commit 13:
git checkout master
git merge bugfix -m "commit 13"
commit 14:
Edit README.md
git add -A
git commit -m "commit 14"


