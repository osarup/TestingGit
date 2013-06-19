TestingGit
==========

Test all your git actions against this repository. 

All the R&D members, just follow these simple steps on how to git.

1) Open your terminal (If on windows, use GUI -> For that refer to commiting and cloning part in -> http://thespl.in/?q=content/github-impressive-github-profile-your-new-resume )

2) First of all you have to fork this repository to your own profile. Look at the fork button on the repository page or as shown in the above tutorial.

3) Now go to your own profile and you will find this repository has been added to your profile.

 Now the real thing begins.

4) If using shell, type "git clone [repository-url]" For example, repository-url in this case is "https://github.com/Society-of-Programming-Languages/TestingGit.git" & in your case it will be "https://github.com/[Your Github Username]/TestingGit.git".

5) Once you have cloned your forked repo, it will create a local directory on your hard disk starting with the name of the repo you just cloned.

6) Now go to above cloned directory, and update this README file by adding your name in it. (There is a section below that says "Contributors". Update there and no where else) 

7) Now comes commiting these changes to your forked repository. Simply use these sequence of commands in git shell.
-> "git add ."  This adds the files to the staging area.
-> "git commit -m "Your message relating to the changes you have made"
-> "git push -u origin master" This command pushes your changes to the repo server with remote as "origin" and branch as "master"

8) Now to finally make me accept the changes you have made, go to the github.com website and on the repo there is a tab called "Pull Request". As soon as you make changes, you will see a tab under "Pull Request" something saying like "Create Pull Request".
   This means that you have made some changes in your forked repository, and you want me to incorporate those changes to my original repository. (Often known as patches if they fix some issue).

9) That's all. If you followed each step carefully, you have got the whole idea behind git. There is "Issues" tab for creating issues regarding a particular code. You can create issues and a discussion can be held right there with everyone being notified about it.

VERY VERY IMPORTANT NOTE: If you see some message saying that your "branch is behind something something", all it means is that you have not incorporated changes made by someone else. To do that simply open shell and go typing the following commands.

"git remote -v" //Lists the names of remotes for a repository.

"git remote add upstream https://github.com/Society-of-Programming-Languages/TestingGit.git" //Adds a new remote named "upstream". You can name it anything.

"git remote -v" //Check if upstream has been added.

"git fetch upstream" //Fetch all the branches of that remote into remote-tracking branches, such as upstream/master

"git checkout master" //Very important in order to switch to master branch of upstream


 Rewrite your master branch so that any commits of yours that
 aren't already in upstream/master are replayed on top of that
 other branch:

"git marge upstream/master"


That's it. Now you can carry on with "git push -u origin master", to make all the updated changes to you repo on github.

CONTRIBUTORS (Update your names below)
============
- Bhavyanshu
