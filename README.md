Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
brill@BRILLIANIJESHIA MINGW64 ~
$ cd Documents

brill@BRILLIANIJESHIA MINGW64 ~/Documents
$ git clone https://github.com/rillyy/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

brill@BRILLIANIJESHIA MINGW64 ~/Documents
$ cd belajarGIT

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git 5789635] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 030b2bf..5789635
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 321 bytes | 321.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/rillyy/belajarGIT.git
   030b2bf..5789635  main -> main

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html 4d31e80] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating 5789635..4d31e80
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 350 bytes | 350.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/rillyy/belajarGIT.git
   5789635..4d31e80  main -> main

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css 7d8a5ac] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating 4d31e80..7d8a5ac
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 371 bytes | 371.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/rillyy/belajarGIT.git
   4d31e80..7d8a5ac  main -> main

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-js.txt"
[Tugas-js ee59205] Menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating 7d8a5ac..ee59205
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/rillyy/belajarGIT.git
   7d8a5ac..ee59205  main -> main

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject 450d1d0] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating ee59205..450d1d0
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/rillyy/belajarGIT.git
   ee59205..450d1d0  main -> main

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php b06950e] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating 450d1d0..b06950e
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/rillyy/belajarGIT.git
   450d1d0..b06950e  main -> main

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject 75855e6] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Updating b06950e..75855e6
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

brill@BRILLIANIJESHIA MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/rillyy/belajarGIT.git
   b06950e..75855e6  main -> main
