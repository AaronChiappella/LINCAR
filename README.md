# LINCAR
Practica de Git realizada mediante Git Bash


Añadiendo texto a README.me

Git Bash
aaron@DESKTOP-JCHPNIE MINGW64 ~
$ cd

aaron@DESKTOP-JCHPNIE MINGW64 ~
$ cd Desktop/

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop
$ cd IyC-Git/

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git
$ git init
Initialized empty Git repository in C:/Users/aaron/Desktop/IyC-Git/.git/

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (master)
$ git remote add origin https://github.com/AaronChiappella/LINCAR.git
aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (master)

$ git pull origin main
From https://github.com/AaronChiappella/LINCAR
 * branch            main       -> FETCH_HEAD

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (master)
$ ls
README.md

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (master)
$ git branch "ActualizarReadme"

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (master)
$ git branch --list
  ActualizarReadme
* master

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (master)
$ git checkout ActualizarReadme
Switched to branch 'ActualizarReadme'

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (ActualizarReadme)
$ git add README.md

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (ActualizarReadme)
$ git commit -m "docs(README.me): actualizando README.me"
[ActualizarReadme 803e844] docs(README.me): actualizando README.me
 1 file changed, 3 insertions(+)

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (ActualizarReadme)
$ git push origin ActualizarReadme
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 350 bytes | 350.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'ActualizarReadme' on GitHub by visiting:
remote:      https://github.com/AaronChiappella/LINCAR/pull/new/ActualizarReadme
remote:
To https://github.com/AaronChiappella/LINCAR.git
 * [new branch]      ActualizarReadme -> ActualizarReadme

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (ActualizarReadme)
$ git checkout main
Switched to a new branch 'main'
branch 'main' set up to track 'origin/main'.

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (main)
$ git merge ActualizarReadme
Updating b67ca11..803e844
Fast-forward
 README.md | 3 +++
 1 file changed, 3 insertions(+)

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (main)
$ git push origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/AaronChiappella/LINCAR.git
   b67ca11..803e844  main -> main

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (main)
$ git branch -d ActualizarReadme
Deleted branch ActualizarReadme (was 803e844).

aaron@DESKTOP-JCHPNIE MINGW64 ~/Desktop/IyC-Git (main)
$ git branch
* main
  master

