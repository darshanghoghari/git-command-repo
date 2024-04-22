# git-command-repo
Github Command

==========================================Git Basic Commands======================================================

============================================================================================
**********************git clone command*************************
============================================================================================

->clone project in local system from github
command:-
	git clone <git repo link>

============================================================================================
**********************git remote access command*************************
============================================================================================

1)first initilize git in local system folder 
command :- 
	git init 

2)after add remote access 
command :-
	git remote add origin <git repo link>

3)take single pull from main 
command :- 
	git pull origin main 

============================================================================================
**********************git create branch command*************************
============================================================================================

1)new branch name 
command:-
	git branch <new-branch-name> 

2)switch on new branch 
command:-
	git checkout <new-branch-name>

3)create file or pull from main branch

4)tracking relationship between the local branch and the remote branch. This relationship allows you to easily synchronize the local and remote branches using commands like git pull and git push.
command:-
	git push --set-upstream origin <new-branch-name>

============================================================================================
**********************git push command*************************
============================================================================================

1)first staged all file for git 
command:-
	-> git add . (all untracked file staged )
	-> git add <file1> <file2> <file3>(for some file)

2)after commit them 
command:-
	-> git commit -m "add your commit message"

3)push in git hub
command:-
	-> git push

============================================================================================
**********************git push command*************************
============================================================================================

*)pull from cuurent branch (means working in dev branch in local and take pull from also dev branch)
command:-
	-> git pull

*)pull from another branch 
command:-
	-> git pull origin <branch-name>

============================================================================================



