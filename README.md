mkdir san
ls
cd san
git init
gedit f1.txt
git add f1.txt
git commit -m "hhh"
git --version
git checkout master
git checkout -b fb1
gedit f1.txt
git add .
git commit -m "Your commit message for feature-branch"
git checkout master
git merge fb1
git stash save "Your stash message"
git checkout fb1
git stash apply
git clone "url"
is
cd repository
gedit Readme.md

git fetch origin
git rebase origin/main
gedit Readme.md
git checkout fb1
gedit Readme.md
edit
add
commit
git rebase --continue
git push origin fb1
git checkout master
git merge feature-branch -m "Your custom commit message here"
git tag v1.0 commit I d
git show  commit id
git log -n 1 <commit-ID>
git log -n 1 abc123
git log --author="JohnDoe" --since="2023-01-01" --until="2023-12-31"
git log -n 5
git revert <commit ID>
git cherry-pick <start-commit>^..<end-commit>
git cherry-pick ABC123^..DEF456
