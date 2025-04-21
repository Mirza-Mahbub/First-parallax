git init

git status

git add . [For Staging All The Files]

git add app.js [For Staging Only That Specific File]

git commit -m "First Commit" [To commit][-m is optional, its for the message]

git commit -am "Your commit message here" ['-a' flag is use to a tracked file to both stage and commit at a once]

git log [Provides all log history][for every commit there is a serial number called hash(#)][Example of # 6bcd205334139cd2227]

git checkout 6bcd205334139cd2227 [Takes back to that particular commit]

git checkout master [Back to the main branch]

git branch [To view list of branch]

git branch secondary [Creation of branch. Name is secondary]

git checkout secondary [moving to secondary from master or any other branch or any other commit position]

TO MERGE WITH MASTER

git checkout master

git merge secondary
