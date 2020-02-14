**1) How to remove a big file wrongly committed**

git filter-branch --tree-filter 'rm -rf AWS/storage/.terraform/' HEAD

**2) gitignore document**

https://www.atlassian.com/git/tutorials/saving-changes/gitignore

**3) github writing and formating**

https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#headings

**4) Copy new folder/files to existing repo**

git add .

git commit -m "testing"

git remote add origin git@github.com:mehrotsh/terraformstuff.git

git pull --rebase origin master

git push origin master
