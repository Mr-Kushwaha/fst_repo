# fst_repo
This is my first reposetory.
<br>
Author: Aman😎
cast: Kushwaha


<h3> Some problumes that occur </h3>
<p>1. first is when delete some file and it's not properly deleted</p>
<p>2. Second is when we open some foalder first time then we have to config some things</p>
<h2>solution</h2>
<p>process for updating the files: git add ., git commit -m "some message", git push origin main</p>
91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)        
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    comb.csv

no changes added to commit (use "git add" and/or "git commit -a")

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ rm -f git/comb.csv

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    comb.csv

no changes added to commit (use "git add" and/or "git commit -a")

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ rm -f git/comb.csv

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git restore .

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git add .

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git commit -m "adding instruction"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got '91790@??_KushwahaJI_??.(none)')


91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git config --global user.email "amankus170@gmail.com"

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git config --global user.name "Mr-Kushwaha"

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git add .

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git commit -m "adding some instruction"
[main 0772f2a] adding some instruction
 1 file changed, 3 insertions(+)

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
$ git push origin main
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 389 bytes | 129.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Mr-Kushwaha/repoFORpandas.git
   63c0c63..0772f2a  main -> main

91790@??_KushwahaJI_?? MINGW64 ~/Documents/Add_file1by1 (main)
</p>