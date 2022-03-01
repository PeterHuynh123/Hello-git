Git: version control for software development
Eg: for games, save feature, checkpoints
    - Software improves over time -> need sth to keep track  of all of the version
    -Adding new things could potentially break the current version
md = markdown

<!-- cmd -->
git init . -> initialize a respository(repo) aka project
git add * or . or git add (file name) -> add all of the file and folder in the current directory
git commit -m "the message" -> to save the current file to a version (remember to git add . after to commit after that)
git checkout (commit id) -> to bring a version to a head/branch/master to checkout
git status -> see the status of the branch
git log -> see all of the commits
git clone (git hub link end with .git) -> save a online repo to local machine


git branch (name) -> to create new branch with the name
git merge (branch name) -> to merge the branch to the master
git checkout -b <new branch name>: create and checkout new branch
git branch . M <new name>: change the current branch's name  to  new name

branch naming : feature/new feature


Merging: merge everything from new branch to another branch:
    1 gotta 
    2
        e.g
        checkout main
        git merge feeature/newfeature
        =>merge branch "feature/newfeature" into 'main'

git restore . -> to restore every file in the crrent directory
git fetch -> to download the metadata of the online repo
git status -> show the current status of the commit
git pull -> to download file from the onl repo
git push -> to upload file(s) to onl repo
