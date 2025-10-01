
git config --global user.name "Rei"
git config --global user.email "pulajrei6@gmail.com"


mkdir my-project
cd my-project

git init

echo "Author: Rei > author.txt
echo "Email:pulajrei6@gmail.com >> author.txt
echo "Project: My Project" >> author.txt

git add .
git commit -m "Initial commit with author info

Name:Rei
Email:pulajrei6@gmail.com"

git log --oneline

git config --global user.name
git config --global user.email

git status

git log --pretty=format:"%C(yellow)%h %C(blue)%ad %C(red)%d %C(reset)%s %C(green)[%an]%C(reset)" --date=short

 git add .
    git commit -m "Initial commit: $project_name
