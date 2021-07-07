# list of all commits
    git log

# list of recent coomits by number
    git log -n 3

# list of commits by autor/commiter
   git log --author="John Smith"
   git log --committer="John smith"

# git by after dtae

  git log --after="2019-3-2"

# list by yesterday

  git log --before="yesterday"

# list by dates

  git log --after="2019-3-2" --before="2019-3-19"

# list by file name
  
  git log -- main.py

# list by Content

git log -S"# Introduction"


# git rollback 

git reset --hard <Commit id>


# git create branch

  git checkout -b < branch name >

# git switch to branch
  
  git checkout < branch name >

# git branch check

  git branch


# git merge
  
 git merge master amit
    
  # git config set globally

   git config --global user.name "Your Name"   
   git config --global user.email "Your Email"  

 # git config set into the repo
  
    git config  user.name "Your Name"   
   git config    user.email "Your Email"    

    
  # Create a new git tag

$ git tag <tag_name>


# Create a git tag from a commit


$ git tag <tag_name> <commit_sha>

# Git tag can also be created from the commit SHA with an annotation tag by adding “-a” and “-m” options.

$ git tag -a <tag_name> <commit_sha> -m "Your message"
 

# View available git tags

  $ git tag
  
# tag push

  git push origin v1.0
    
# git clone from a specific branch
    
    git clone -b <branch> <remote_repo>
