【1】or create a new repository on the command line

echo "# Design-Pattern" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:github用户名/Design-Pattern.git
git push -u origin master

【2】or push an existing repository from the command line

git remote add origin git@github.com:github用户名/Design-Pattern.git
git push -u origin master


【3】or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project
