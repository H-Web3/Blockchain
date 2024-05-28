# Blockchain
This is my start of building Blockchain from scratch.
<br>
In this repository, I am going to learn and making the pure Blockchain with the use of JavaScript. Read it, learn it and make it easy to understand the working of Blockhain better. 
<br>
Now I am writing this text to show you that when we clone a repository from remote to local and then run
a command on terminal of (git status), it will show us that "branch is up to date, nothing to commit"
then we add some text, like we are writing this text and now we save it, it will show us that the
repo is modified.
<br> 
After modifing, there's a two step process, first is adding, second is commit.
<br>
As long as, we don't take these two steps, status will show us that you modified the code.
<br>
we can also create a file named like "dev". Then if we enter status command, it will show us that 
there's an untracked file, means that there's a file which is not tracked by git.
<br>
when we use git status command, generally there are four types of statuses in it. First is:
<br>
Untracked: new files that git doesn't yet track.
<br>
modified: changed
<br>
stagged: file is ready to be committed.
<br>
unmodified: unchanged 
 <br>
 Now in summary, files in first are modified or untracked then we add a file then it will show
 us that it is "stagged", then we commit, it will show us, it is "unmodified". 
 <br>
 Now to enable the git to track the file we have to add it:
 <br>
 add- adds new or changed files in your working directory o the git stagging area
 <br>
 git add <-file name->
 <br>
git add . command to add all the modified files. Also add them individually by writing file's name.
<br>
after adding, git status command will show us that files are added now changes to be committed
<br>
to commit we run a command "git commit"
<br>
Now if you go and see on github.com there is no files or modifications you do. Why?
Because all the things we do, we do in oue local sytem.
<br>
to add them into the github we have to push ut from local to remote with the "git push origin main" 
command. Push means "Upload localrepo content to remote repo".
<br>
Now the meaning of "git push origin main" ."git push" means that we want to push the git onto the github
<br>
"origin" means that default repo that we clone from the github. We want to push that git to the origin 
which we clone having a branch "main".


