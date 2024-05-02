2

git clone <url>
ls
cd <repo name>
git status
git status
git add -A
git commit -m"adding new file"
git push origin main

3
git status
git checkout -b fix
git status
git add -A
git status
git commit -m"update"
git push origin fix

git checkout main
git status
git merge fix main
git push origin main


6

git init
git clone<URL>
cd <REPO NAME>
git submodule add <URL>
git status
git add -A
git commit -m"submodule"
git push -u origin main
git submodule dinit --all
git status
git config --global alias.st status
git st
git config --global alais.br branch
git br
