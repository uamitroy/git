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

# git checkout new branch

git checkout -b ＜new-branch＞
    
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
    
# git config --get remote.origin.url    
    

# Importtants Commands
    chmod 400 playa2021updated.pem
    ssh -L 8000:127.0.0.1:80 -i playa2021updated.pem bitnami@infinitereality.5edev.com
     
    <!-- import database -->
    mysql -u DB_USER_NAME -p DB_NAME < YOUR_SQL_FILE_NAME.sql

    <!-- export database -->
    mysqldump -u DB_USER_NAME -p DB_NAME > WHAT_FILE_NAME_YOU_WANT.sql
    
    <!-- commands database -->
    mysql -h ip-172-31-22-161.us-east-2.compute.internal -u sandbox_user -p dafribank_sandbox
    mysql --host=Hostname --port=3306 --user=ebdb --password=12334558393


    
 # index.php htaccess
    
    RewriteEngine on
    RewriteCond %{REQUEST_FILENAME} !-d
    RewriteCond %{REQUEST_FILENAME} !-f
    RewriteRule . index.php [L]

 # Composer Commands
   composer self-update
   composer self-update --rollback
   composer require vendor/package:version
   composer reinstall <package-name>
    
 # <a target="_blank" href="mailto:no-one@snai1mai1.com?subject=look at this website&body=Hi, I found this website and thought you might like it https://github.com/ameetroy/git">Mail</a>   
