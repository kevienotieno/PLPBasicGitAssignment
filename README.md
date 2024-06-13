# PLPBasicGitAssignment
## Navigate to the Home Directory:
kevie@DESKTOP-H1VVVT8 MINGW64 ~
$ cd

## List the Contents of the Home Directory:
kevie@DESKTOP-H1VVVT8 MINGW64 ~
$ ls

## Navigate to the Desktop Directory:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop
$ cd Desktop

## List the Contents of the Desktop Directory:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop
$ ls

## Navigate to the PLP Directory:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop
$ cd PLP

## List the Contents of the PLP Directory:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP
$ ls

## Create a New Directory for the Git Assignment:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP
$ mkdir PLPBasicGitAssignment

## Navigate to the New Directory:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP
$ cd PLPBasicGitAssignment

## Initialize a New Git Repository:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment
$ git init

## Rename the Default Branch to main:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (master)
$ git branch -m main

## Add the Remote Repository:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ git remote add origin "https://github.com/kevienotieno/PLPBasicGitAssignment"

## Create a New File hello.txt:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ touch hello.txt

## Edit the hello.txt File and Add Content:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ vi hello.txt

## Verify the Content of hello.txt:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ cat hello.txt
"Hello, Git!"

## Add hello.txt to the Staging Area:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ git add hello.txt

## Commit the Changes:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ git commit -m "Add hello.txt with a greeting"

## Push the Changes to the Remote Repository:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ git push -u origin main

## Fetch Updates from the Remote Repository:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ git fetch origin

## Attempt to Merge Changes:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ git merge origin/main

## Resolve the Error by Allowing Unrelated Histories:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ git pull origin main --allow-unrelated-histories

## Push the Merged Changes to the Remote Repository:
kevie@DESKTOP-H1VVVT8 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (main)
$ git push -u origin main
