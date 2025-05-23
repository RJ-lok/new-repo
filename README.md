#this is new file\

 ls -a
.  ..  .git
jagdish@RJ:/var/www/html/php/abc/project$ touch ab.html
jagdish@RJ:/var/www/html/php/abc/project$ git add .
jagdish@RJ:/var/www/html/php/abc/project$ git commit -m "new"
[master (root-commit) c995cb5] new
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ab.html
jagdish@RJ:/var/www/html/php/abc/project$ git status
On branch master
nothing to commit, working tree clean
jagdish@RJ:/var/www/html/php/abc/project$ git remote add origin https://github.com/RJ-lok/new-repo.git
jagdish@RJ:/var/www/html/php/abc/project$ git remote -v
origin  https://github.com/RJ-lok/new-repo.git (fetch)
origin  https://github.com/RJ-lok/new-repo.git (push)
jagdish@RJ:/var/www/html/php/abc/project$ git branch
* master
jagdish@RJ:/var/www/html/php/abc/project$ git branch -M main
jagdish@RJ:/var/www/html/php/abc/project$ git branch
* main
jagdish@RJ:/var/www/html/php/abc/project$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 210 bytes | 210.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/RJ-lok/new-repo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
jagdish@RJ:/var/www/html/php/abc/project$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
jagdish@RJ:/var/www/html/php/abc/project$ git add .
jagdish@RJ:/var/www/html/php/abc/project$ git commit -m "new"
[main 154bb6b] new
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
jagdish@RJ:/var/www/html/php/abc/project$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/RJ-lok/new-repo.git
   c995cb5..154bb6b  main -> main
jagdish@RJ:/var/www/html/php/abc/project$ get branch
Command 'get' not found, but there are 18 similar ones.
jagdish@RJ:/var/www/html/php/abc/project$ git branch
* main
jagdish@RJ:/var/www/html/php/abc/project$ git checkout -b new
Switched to a new branch 'new'
jagdish@RJ:/var/www/html/php/abc/project$ git branch
  main
* new
jagdish@RJ:/var/www/html/php/abc/project$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
jagdish@RJ:/var/www/html/php/abc/project$ git branch
* main
  new