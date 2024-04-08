# a0: Basic Tools: Part I: Command Line [10 points]

The purpose of this file is for you to demonstrate your knowledge of working with the terminal. Following each prompt below, write the line of code that you used on the terminal to accomplish the task.

```bash
# (1) Print your working directory [1 points]
pwd
chaew@SnowDesktop MINGW64 ~
$ pwd
/c/Users/chaew

# (2) List the files in your current directory [1 point]
chaew@SnowDesktop MINGW64 ~
$ ls
 -1.14-windows.xml    BrawlhallaReplays/   Documents/   Links/            'My Documents'@                                            NTUSER.DAT{051f179f-2354-11ee-aa6e-749779939f2c}.TMContainer00000000000000000001.regtrans-ms   OneDrive/   'Saved Games'/  'Start Menu'@   ansel/            ntuser.ini
 AppData/             Contacts/            Downloads/  'Local Settings'@   NTUSER.DAT                                                NTUSER.DAT{051f179f-2354-11ee-aa6e-749779939f2c}.TMContainer00000000000000000002.regtrans-ms   PrintHood@   Searches/       Templates@     ntuser.dat.LOG1
'Application Data'@   Cookies@             Favorites/   Music/             NTUSER.DAT{051f179f-2354-11ee-aa6e-749779939f2c}.TM.blf   NetHood@                                                                                       Recent@      SendTo@         Videos/        ntuser.dat.LOG2


# (3) Change your directory to a folder in which you do work for this class (if you haven't created such a folder, please do so now — perhaps titled "INFO201") [1 point]
chaew@SnowDesktop MINGW64 /c/Users
$ cd chaew

chaew@SnowDesktop MINGW64 ~
$ cd Downloads

chaew@SnowDesktop MINGW64 ~/Downloads
$ INFO201
bash: INFO201: command not found

chaew@SnowDesktop MINGW64 ~/Downloads
$ cd INFO201

# (4) Clone your assignment repository from GitHub to your machine/computer [1 point]
chaew@SnowDesktop MINGW64 ~/Downloads/INFO201
$ git clone https://github.com/info-201b-sp24/a1-basic-tools-chaewonyoo37.git
Cloning into 'a1-basic-tools-chaewonyoo37'...
remote: Enumerating objects: 14, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (13/13), done.
remote: Total 14 (delta 1), reused 12 (delta 1), pack-reused 0
Receiving objects: 100% (14/14), 689.28 KiB | 43.08 MiB/s, done.
Resolving deltas: 100% (1/1), done.

# (5) Using a *relative path*, change your directory to inside the repository you just cloned [1 point]
chaew@SnowDesktop MINGW64 ~/Downloads/INFO201
$ cd a1-basic-tools-chaewonyoo37


# (6)  What is the *absolute path* of the image file "covid-example-2.png"? (You can answer the absolute path on your own computer, or the absolute path only within the GitHub repository) [1 points]
C:\Users\chaew\Downloads\INFO201\a1-basic-tools-chaewonyoo37\images\COVID-19-Visualizations
# (7) Add all of the changes that you've made to this file with git [1 point]
chaew@SnowDesktop MINGW64 ~/Downloads/INFO201/a1-basic-tools-chaewonyoo37 (main)
$ git add .

# (8) Commit these changes, and include a *descriptive message* [2 points]
chaew@SnowDesktop MINGW64 ~/Downloads/INFO201/a1-basic-tools-chaewonyoo37 (main)
$ git commit -m "special comment made"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'chaew@SnowDesktop.(none)')


# (9) Finally, push your changes to GitHub [1 point]
chaew@SnowDesktop MINGW64 ~/Downloads/INFO201/a1-basic-tools-chaewonyoo37 (main)
$ git push
Everything up-to-date

```
