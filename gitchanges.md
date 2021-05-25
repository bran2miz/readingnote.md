Last login: Tue May 25 09:51:21 on ttys001

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
Wesleys-MacBook-Pro-2:~ wesleymizutani$ ls
Applications	Downloads	Movies		Public
Desktop		Dropbox		Music		Sites
Documents	Library		Pictures	projects
Wesleys-MacBook-Pro-2:~ wesleymizutani$ cd
Wesleys-MacBook-Pro-2:~ wesleymizutani$ pwd
/Users/wesleymizutani
Wesleys-MacBook-Pro-2:~ wesleymizutani$ cd
Wesleys-MacBook-Pro-2:~ wesleymizutani$ ls
Applications	Downloads	Movies		Public
Desktop		Dropbox		Music		Sites
Documents	Library		Pictures	projects
Wesleys-MacBook-Pro-2:~ wesleymizutani$ cd projects
Wesleys-MacBook-Pro-2:projects wesleymizutani$ ls
codefellows
Wesleys-MacBook-Pro-2:projects wesleymizutani$ cd codefellows
Wesleys-MacBook-Pro-2:codefellows wesleymizutani$ ls
code102
Wesleys-MacBook-Pro-2:codefellows wesleymizutani$ cd code102
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ ls
hello_world	reading-notes
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ https://github.com/bran2miz/readingnote.md.gi
-bash: https://github.com/bran2miz/readingnote.md.gi: No such file or directory
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ git clone https://github.com/bran2miz/readingnote.md.git
Cloning into 'readingnote.md'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ code .
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ pwd
/Users/wesleymizutani/projects/codefellows/code102
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ cd code102
-bash: cd: code102: No such file or directory
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ ls
hello_world	reading-notes	readingnote.md
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ cd readingnote.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git clone https://github.com/bran2miz/readingnote.md.git
Cloning into 'readingnote.md'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ code .
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ ls
README.md	readingnote.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ cd ..
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ ls
hello_world	reading-notes	readingnote.md
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ cod. v
-bash: cod.: command not found
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ code .
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ ls
hello_world	reading-notes	readingnote.md
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ git add https://github.com/bran2miz/readingnote.md.git
fatal: not a git repository (or any of the parent directories): .git
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ git clone https://github.com/bran2miz/readingnote.md.git
fatal: destination path 'readingnote.md' already exists and is not an empty directory.
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ git clone https://github.com/bran2miz/readingnote.md.git
Cloning into 'readingnote.md'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 12 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (12/12), 5.73 KiB | 5.73 MiB/s, done.
Resolving deltas: 100% (1/1), done.
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ code .
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ git status
fatal: not a git repository (or any of the parent directories): .git
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ ls
hello_world	reading-notes	readingnote.md
Wesleys-MacBook-Pro-2:code102 wesleymizutani$ cd readingnote.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ ls
README.md		codercomputer.md	markdown.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add .
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git commit -m "Added a table of contents, links to and from pages"
[main df20fac] Added a table of contents, links to and from pages
 1 file changed, 6 insertions(+), 1 deletion(-)
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 460 bytes | 460.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/bran2miz/readingnote.md.git
   e61ea0b..df20fac  main -> main
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add markdown.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git commit "Added a link back to the main page"
error: pathspec 'Added a link back to the main page' did not match any file(s) known to git
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git push origin main
Everything up-to-date
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add codercomputer
fatal: pathspec 'codercomputer' did not match any files
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add codercomputer.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git commit -m "added a link back to the main page"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git push origin main
Everything up-to-date
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add markdown.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git commit -m"Added a link back to the main page"
[main a40b2ce] Added a link back to the main page
 1 file changed, 2 insertions(+)
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 317 bytes | 317.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/bran2miz/readingnote.md.git
   df20fac..a40b2ce  main -> main
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add markdown.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git commit -m"Deleted the <symbol"
[main 89ba677] Deleted the <symbol
 1 file changed, 1 insertion(+), 1 deletion(-)
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/bran2miz/readingnote.md.git
   a40b2ce..89ba677  main -> main
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add codercomputer.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git commit -m "deleted the less than symbol"
[main d2bd5c5] deleted the less than symbol
 1 file changed, 2 insertions(+)
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 315 bytes | 315.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/bran2miz/readingnote.md.git
   89ba677..d2bd5c5  main -> main
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	gitchanges.md
	revisionsandcloud.md

no changes added to commit (use "git add" and/or "git commit -a")
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add README.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	gitchanges.md
	revisionsandcloud.md

Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git commit -m"Add the link to revision and cloud reading notes"
[main 4ff716d] Add the link to revision and cloud reading notes
 1 file changed, 3 insertions(+), 2 deletions(-)
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 431 bytes | 431.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/bran2miz/readingnote.md.git
   d2bd5c5..4ff716d  main -> main
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git add revisionsandcloud.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   revisionsandcloud.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	gitchanges.md

Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git commit -m"Add new reading notes"
[main a63d9b5] Add new reading notes
 1 file changed, 97 insertions(+)
 create mode 100644 revisionsandcloud.md
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.79 KiB | 1.79 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/bran2miz/readingnote.md.git
   4ff716d..a63d9b5  main -> main
Wesleys-MacBook-Pro-2:readingnote.md wesleymizutani$ 