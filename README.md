# git_tutorial

# globaly set git account
git init 
git config --global user.name "Username" </br>
git config --global user.email "<Email@gmail.com>"

# check your current username and email
git config --globle --list

# for Add all file
add = git add . </br>

commit = a snapshot of repo at specific point in time </br>
commit = git commit -m "name of update"


# Branch

create a new branch = git checkout -b <branch_name> </br>
switch branch = git checkout <branch_name> </br>
check current branch = git branch </br>
delete a exist branch = git branch -d <branch_name> </br>

# pull another branch in main branch 
git pull origin <branch_name> </br>
git push origin main <current_branch_name> </br>
git status = for check the status(update commit or add) </br>

# gitignore
git rm -r --cached </br>
git add . </br>
git commit -m <commit_message>

# conflicts

# SSH key

# step - 1 generate key
command - ssh-keygen -> enter -> overwrite = y -> enter -> enter -> now we get the id and path 

#  step-2 
cat ~/.ssh/<id.pub>

# step -3
Add key in github , Open_github_profile -> setting -> ssh and gpg key -> new key -> title and <addyourkey_ssh-rsa>


# git ssh doc 
https://www.geeksforgeeks.org/how-to-generate-public-ssh-or-gpg-keys-using-git-commands/

# test ssh key
ssh -T git@github.com
Hi <name>! You've successfully authenticated, but GitHub does not provide shell access 

# check the doc for test ssh
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection
