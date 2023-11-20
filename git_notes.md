# bash script for github

- to clone the repository (download it) and make a new branch
git clone [link]
git checkout -b [branch_name]

- to clone into an existing branch
git clone [url] --branch [branch] --single-branch

- get status of repository (will compare your local files to main)
git status

- merge request
git add [path]
git commit -m "type message"
git push origin [branch_name]