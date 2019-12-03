# Git-Demo-by-Commandline
HOW TO

★	*GitBash at the beginning
●	cd c:
●	cd git
●	cd SMD-Assignments
●	git config --global user.name "daniyalyk"
●	git config --global user.email daniyalyk@gmail.com
●	git clone https://github.com/daniyalyk/SMD-Assignments.git
●	ls (to check connected folder)
●	git add textfile.txt (filename)
●	git status
●	git commit -m "first commit" textfile.txt
●	git push -u origin master
★	*Add Files to a Branch
●	git branch branchname
●	git checkout branchname
●	git init
●	git add file name
●	git commit -m "your message"
●	git push
★	*merging branches
●	git checkout master 
●	git checkout -b Develop
●	git merge Develop
●	git pushC
★	*More commands
●	git branch
●	git branch --list
●	git clone -b branchname https://www.github.com/SMD-Assignments.git
●	git push origin [ur branch name]
●	git push -f origin master




★	*Add Files to a Branch (MORE)
1.	git clone -b development https://www.github.com/heem42/aroms-sedb
2.	 cd aroms-sedb
3.	 git checkout -b [ur group name] e.g "git checkout titans"
4.	Now open this project in Android Studio, make all your changes. If your gradle version doesn't match with this one, you will need to upgrade your gradle. 
5.	Once, all your changes are done and your app is running, you can push it back on github following these steps
6.	 git add .
7.	  git commit -m "ur message here"
8.	git push origin [ur branch name]

★	*After conflict arrives
1.git pull --rebase origin master
2. git status
3. git mergetool
( here in mergetool the differences are shown in files where it is conflicting. To select the text press i and modify it. to save press ESC and then :wq (3 times))
4. git rebase --continue
5. git push origin master

★	Git Guide. Click Here
