Daftar tugas / branch

1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT


ThinkPad@DESKTOP-PMKV5UP MINGW64 ~
$ git--global user.email "feykhana@gmail.com"
bash: git--global: command not found

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~
$ cd "C:\Users\ThinkPad\Git"

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git
$ git clone https://github.com/FeykhaKoem/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git
$ cd "C:\Users\ThinkPad\Git\belajarGIT"

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git branch Tugas-git

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git branch Tugas-html

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git branch Tugas-css

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git branch Tugas-js

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git branch Tugas-midProject

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git branch Tugas-php

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git branch Tugas-finalProject

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git switch Tugas-git
Switched to branch 'Tugas-git'

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-git)
$ git commit -m "Success"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ThinkPad@DESKTOP-PMKV5UP.(none)')

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-git)
$ git config --global user.email feykhana@gmail.com

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-git)
$ git config --global user.name FeykhaKoem

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-git)
$ git commit -m "Success"
[Tugas-git f7b139e] Success
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-git)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git merge Tugas-git
Updating d3a8981..f7b139e
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/FeykhaKoem/belajarGIT.git
   d3a8981..f7b139e  main -> main

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git switch Tugas-html
Switched to branch 'Tugas-html'

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-html)
$ git commit -m "Terserah"
[Tugas-html 83a9510] Terserah
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-html)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git merge Tugas-html
Merge made by the 'ort' strategy.
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 531 bytes | 531.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/FeykhaKoem/belajarGIT.git
   f7b139e..af82114  main -> main

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git switch Tugas-css
Switched to branch 'Tugas-css'

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-css)
$ git commit -m "Tugas"
[Tugas-css 4f1788f] Tugas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-css)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git merge Tugas-css
Merge made by the 'ort' strategy.
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 556 bytes | 556.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/FeykhaKoem/belajarGIT.git
   af82114..451e0d1  main -> main

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git switch Tugas-js
Switched to branch 'Tugas-js'

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-js)
$ git commit -m "ngoding"
[Tugas-js c58233d] ngoding
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-js)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git merge Tugas-js
Merge made by the 'ort' strategy.
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 489 bytes | 489.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/FeykhaKoem/belajarGIT.git
   451e0d1..9439948  main -> main

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git switch Tugas-midProject
Switched to branch 'Tugas-midProject'

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-midProject)
$ git commit -m "Mid Project"
[Tugas-midProject 40c39b7] Mid Project
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-midProject)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git merge Tugas-midProject
Merge made by the 'ort' strategy.
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 519 bytes | 519.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/FeykhaKoem/belajarGIT.git
   9439948..0ff177c  main -> main

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git switch Tugas-php
Switched to branch 'Tugas-php'

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-php)
$ git commit -m "PHP"
[Tugas-php f1a3aea] PHP
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-php)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git merge Tugas-php
Merge made by the 'ort' strategy.
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 497 bytes | 497.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/FeykhaKoem/belajarGIT.git
   0ff177c..dd094e8  main -> main

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git switch Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-finalProject)
$ git commit -m "Tugas Akhir"
[Tugas-finalProject a06b2ea] Tugas Akhir
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (Tugas-finalProject)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git merge Tugas-finalProject
Merge made by the 'ort' strategy.
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 512 bytes | 512.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/FeykhaKoem/belajarGIT.git
   dd094e8..2c9102b  main -> main

ThinkPad@DESKTOP-PMKV5UP MINGW64 ~/Git/belajarGIT (main)
$
