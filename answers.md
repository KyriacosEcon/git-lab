PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git --version
git version 2.30.0.windows.2

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=ke020019@ohio.edu
user.name=Kyriacos Economides
core.repositoryformatversion=0

PS C:\Users\kyria\OneDrive\Desktop\cs2400\hw\labs> git add --helpls
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git add answers.md
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git commit -m "Initial commit"
[master (root-commit) def3fa1] Initial commit
 2 files changed, 23 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md

 PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git log
commit def3fa17d52803d1ed9c1a7903d96859d0dfa4b3 (HEAD -> master)
Author: Kyriacos Economides <ke020019@ohio.edu>
Date:   Tue Jan 26 19:42:44 2021 -0500

       Initial commit
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git remote add origin https://github.com/KyriacosEcon/git-lab.git
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git branch -M main
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push -u origin main
info: please complete authentication in your browser...
fatal: Application not found
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/KyriacosEcon/git-lab.git/'





...
    

Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.
Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\kyria\OneDrive\Desktop\cs2400\hw\labs> git add --help
PS C:\Users\kyria\OneDrive\Desktop\cs2400\hw\labs> ls


    Directory: C:\Users\kyria\OneDrive\Desktop\cs2400\hw\labs


Mode                 LastWriteTime         Length Name                                                                                                                           
----                 -------------         ------ ----                                                                                                                           
d-----         1/19/2021   7:40 PM                .vscode                                                                                                                        
d-----         1/26/2021   6:48 PM                git-lab                                                                                                                        


PS C:\Users\kyria\OneDrive\Desktop\cs2400\hw\labs> ls 


    Directory: C:\Users\kyria\OneDrive\Desktop\cs2400\hw\labs
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
init.defaultbranch=master
user.email=ke020019@ohio.edu
user.name=Kyriacos Economides
PS C:\Users\kyria\OneDrive\Desktop\cs2400\hw\labs> git add --help
PS C:\Users\kyria\OneDrive\Desktop\cs2400\hw\labs> cd ~/OneDrive/Desktop/cs2400/labs/git-lab
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> dir   


    Directory: C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         1/26/2021   7:10 PM              6 README.md


PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> ls


    Directory: C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab


----                 -------------         ------ ----
-a----         1/26/2021   7:10 PM              6 README.md


PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> ls


    Directory: C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab


Mode                 LastWriteTime         Length Name
-a----         1/26/2021   7:31 PM            807 answers.md


PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> dir  


    Directory: C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         1/26/2021   7:10 PM              6 README.md


PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git init
Initialized empty Git repository in C:/Users/kyria/OneDrive/Desktop/cs2400/labs/git-lab/.git/
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git status
On branch master


Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git-lab
git-lab : The term 'git-lab' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included,   
verify that the path is correct and try again.
    + CategoryInfo          : ObjectNotFound: (git-lab:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab>
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git add README.md
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git add answers.md
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git status
On branch mast
No commits yet
        new file:   README.md
        new file:   answers.md

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git commit -m "Initial commit"
 create mode 100644 README.md
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git log
commit def3fa17d52803d1ed9c1a7903d96859d0dfa4b3 (HEAD -> master)
Author: Kyriacos Economides <ke020019@ohio.edu>
Date:   Tue Jan 26 19:42:44 2021 -0500

    Initial commit
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git remote add origin https://github.com/KyriacosEcon/git-lab.git
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push -u origin main
info: please complete authentication in your browser...
fatal: Application not found
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/KyriacosEcon/git-lab.git/'
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab>
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git add READ,md
fatal: pathspec 'READ,md' did not match any files
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git commit -m "Hello"
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use


PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> echo "# git-lab" >> README.md
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git init
Reinitialized existing Git repository in C:/Users/kyria/OneDrive/Desktop/cs2400/labs/git-lab/.git/
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git add README.md
[main 066e9af] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git branch -M main
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git remote add origin https://github.com/KyriacosEcon/git-lab.git
error: remote origin already exists.
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push -u origin main
info: please complete authentication in your browser...
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/KyriacosEcon/git-lab.git/'
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git commit -m "Hi"
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
        modified:   answers.md

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git branch -M main
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push -u origin main
info: please complete authentication in your browser...
fatal: Application not found
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push -u origin main
info: please complete authentication in your browser...
fatal: Application not found
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push -u origin main
info: please complete authentication in your browser...
fatal: Application not found
PS C:\Users\kyria\OneDrive\Desktop\cs2400\labs\git-lab> git push -u origin main
8b55948b32382f3987727d923a0000f748aeef8f