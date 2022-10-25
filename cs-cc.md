# Pairing-Activity
- A pairing activity for LEARN's Golf Cohort 2022. Copy this markdown to a file with your name and your parnters name as the file name. 
    ex. austin-elyse.md
- Fill out the sections with the help of your partner to create notes for your git flow
    ex. clone command `$ git clone https://...`


# Partner 1
## Clone down the repository 
- open github
- click on profile dropdown
  -click on learn academy org
  -click view organization
   -click on repositories tab
 - find the pairing-activity repository
 -click on the green code button in the middle of the page
 -copy code link under https  "https://github.com/learn-academy-2022-golf/Pairing-Activity.git"
 open terminal
 type in terminal commands:
  -$ pwd
  -$ ls
 find folder to input file
 input command:
  -$ git clone  https://github.com/learn-academy-2022-golf/Pairing-Activity.git
To verify the status of the clone use command
  -$ git status
Access repository using command:
  -$ cd Pairing-Activity



## Create a new Branch 
Verify location
  -$ pwd
  -$ ls
Create new branch with command:
  -$ checkout -b "gitflow-cs-cc"
Verify new branch created with command:
  -$ git status
Open code editor with command:
  -$ code .

## Make changes to the files / structure
To create a new file:
 -Above the "README.md" file name 
  -click on the page + icon
    -name the new file "cs-cc.md"
Copy the content on the "README.md" file on to "cs-cc.md"

In the appropriate spaces type actions taken to complete each step
  -save file on vs code utilizing "command+s"

  
## Check the branch status and work through the git push flow
Return to terminal
verify status of your branch using command:
  -$ git status
Add updated file into the terminal using command:
  -$ git add cs-cc.md
Verify changes are saved using command:
  -$ git status
Commit the file with corresponding message to partner with command:
  -$ git commit -m "first part done"
Upload file to Github using command:
  -$ git push origin gitflow-cs-cc

# Partner 2
## Fetches the branch and views changes
  To find current updated branch file:
 - open github
 - find Learn-Academy-2022-Golf
 - find Pairing-Activity repo
 - click branch tab
 - click gitflow-cs-cc
 - pull code from the code button and copying link from HTTPS "https://github.com/learn-academy-2022-golf/Pairing-Activity.git"
  type in terminal commands:
  -$ pwd
  -$ ls
 find folder to input file
 input command:
  -$ git clone  https://github.com/learn-academy-2022-golf/Pairing-Activity.git
To verify the status of the clone use command
  -$ git status
Access repository using command:
  -$ cd Pairing-Activity
  To find file on GitHub:
 - $ git fetch origin gitflow-cs-cc
  To verify retrieval of branch:
  - $ git checkout gitflow-cs-cc
  To pull the file:
  - $ git pull origin gitflow-cs-cc
  
  - $ code .

##  Make changes to the files / structure
 - Input changes made to code
 - save file

## Check the branch status and work through the git push flow
 - $ git status
 - $ git add cs-cc.md
  $ git status
  $ git status
  $ git add cs-cc.md
  $ git status
  $ git commit -m "second part done"
  $ git push origin gitflow-cs-cc
# Partner 1
## Pull down the changes 
 - $ git fetch origin gitflow-cs-cc
  - $ git checkout gitflow-cs-cc
  - $ git pull origin gitflow-cs-cc
  - $ code .

## Make changes to the files / structure
 - make changes to the file
 - save file

## Check the branch status and work through the git push flow
 -  - $ git status
 - $ git add cs-cc.md
  $ git status
  $ git status
  $ git add cs-cc.md
  $ git status
  $ git commit -m "third part done"
  $ git push origin gitflow-cs-cc

# Partner 2
## Pull down the changes 
 - $ git fetch origin gitflow-cs-cc
  - $ git checkout gitflow-cs-cc
  - $ git pull origin gitflow-cs-cc
  - $ code .

##  Make changes to the files / structure
 - Input changes made to code
 - save file

## Check the branch status and work through the git push flow
 -$ git status
 - $ git add cs-cc.md
  $ git status
  $ git status
  $ git add cs-cc.md
  $ git status
  $ git commit -m "complete"
  $ git push origin gitflow-cs-cc

## Create a Pull Request (PR) to Main
 - Go onto Github
 - Inside your repository you will see a message
 - click "Compare and Pull Request"
 - click "Merge Pull Request"
 - A message will pop up that says "Pull Request successfully merged and closed
