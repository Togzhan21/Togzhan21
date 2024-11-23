PS C:\Users\Тогжан\OneDrive\Documents\code> cd git_pro
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git init
Initialized empty Git repository in C:/Users/Тогжан/OneDrive/Documents/code/git_pro/.git/
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git add .
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git commit -m "first commit"
Author identity unknown

Run

  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Тогжан@DESKTOP-FRNLRRB.(none)')
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git config --global user.email "tursinbekovbaurjan@gmail.com"
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git config --global user.name "Togzhan21"
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git config --list
diff.astextplain.textconv=astextplain
diff.astextplain.textconv=astextplain       
filter.lfs.clean=git-lfs clean -- %f        
diff.astextplain.textconv=astextplain       
filter.lfs.clean=git-lfs clean -- %f        
diff.astextplain.textconv=astextplain     
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt        
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=tursinbekovbaurjan@gmail.com
user.name=Togzhan21
core.repositoryformatversion=0
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git commit -m "first commit"
On branch master

Initial commit

nothing to commit (create/copy files and use "git adgit remote add origin https://github.com/Togzhan21/1-lab.gitcuments\code\git_pro>
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Togzhan21/1-lab.git'
PS C:\Users\Тогжан\OneDrive\Documents\code\git_pro> git config credential.username "Togzhan21"  
