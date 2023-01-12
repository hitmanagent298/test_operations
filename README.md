## Basic understanding of terms

Rebase: Applies commits of a whole branch over another branch.

Cherry Pick: When you want apply a commit from another branch to your current branch, just grab the commit by id.

Pull Request: These are by developers when they completed working on particular branch and now wants to merge them with main.

Stash: It is used to store the changes made in working directory temporarily but do not want to commit them.

## Commands executed for practical

mkdir test_operation

cd test_operation

touch index.html

touch about.html

touch content.html

git init

git status

git add .

git status

git commit -m "initial commit master"

git remote add origin git@github.com:hitmanagent298/test_operations.git

git remote 

git push -u origin master

git branch

git checkout -b pull_from

git status

ls

git status

git add .

git commit -m "c1 in pull_from"

git push origin pull_from

git checkout -b pull_to

git status

git push origin pull_to

git status

git add .

git commit -m  "c1 in pull_to"

git push origin pull_to

git checkout -b feature1

git status

git add .

git commmit -m "rebase branch commit1"

git commit -m "rebase branch commit1"

git push origin feature1

git status

git add .

git commit -m "rebase branch commit2"

git push origin feature1

git rebase master feature1

git checkout master

git rebase master feature1

git checkout feature1

git rebase master

git checkout master

git rebase feature1

git status

git push

git push origin master

git push -f

clear

git status

git branch

git checkout feature1 

git status

git add .

git commit -m "commit message to be changed"

git push

git push --set-upstream origin feature1

git commit -m "commit message to be changed"

git push

git commit --amend -m "commit message changed"

git push origin feature1 -f

git commit -am "cherry picked from feature1"

git push 

git checkout master

git commit -am "new commit in master"

git push 

git checkout -

git log

git checkout -

git cherry-pick b2392948cd04b2a3783c62f2098b5bb3d64eaa79

git cherry-pick --skip

git status

git checkout feature1

git status

git checkout feature1

git log

git checkout -

git checkout master

git cherry-pick af975c71d54026b004550f789f8060915baffbb5

git commit -m  "cherry-picked from feature1"

git commit -am  "cherry-picked from feature1"

git branch

git push

git checkout -

git status

git add .

git status

git commit -m "commit to be dropped"

git push

git status

git reset --hard HEAD^

git status

git commit -m "commit dropped"

git push

git push -f
