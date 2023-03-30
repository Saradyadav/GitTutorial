# GitTutorial
Try to learn git from this repo

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial
$ git --version
git version 2.30.1.windows.1

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial
$ touch index.html

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial
$ touch myself.txt

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial
$ git init
Initialized empty Git repository in C:/Users/m_top/Documents/gitTutorial/.git/

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git config --global user.name matblck

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git config --global user.name 'matblck'

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git config --global user.email 'jcksilver7@gmail.com'

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git add index.html

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        myself.txt


m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git add myself.txt

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   myself.txt


m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git rm --cached myself.txt
rm 'myself.txt'

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        myself.txt


m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git add myself.txt

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   myself.txt


m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git add .

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ status
bash: status: command not found

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   myself.txt


m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ #hello

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git commit
hint: Waiting for your editor to close the file...
(electron) Sending uncompressed crash reports is deprecated and will be removed in a future version of Electron. Set { compress: true } to opt-in to the new behavior. Crash reports will be uploaded gzipped, which most crash reporting servers support.
[main 2021-03-04T09:48:29.749Z] update#setState idle
(node:3408) electron: The default of contextIsolation is deprecated and will be changing from false to true in a future release of Electron.  See https://github.com/electron/electron/issues/23506 for more information
(node:3408) electron: The default of contextIsolation is deprecated and will be changing from false to true in a future release of Electron.  See https://github.com/electron/electron/issues/23506 for more information
[main 2021-03-04T09:48:59.750Z] update#setState checking for updates
[main 2021-03-04T09:49:00.369Z] update#setState idle
Aborting commit due to empty commit message.

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git commit -m 'First Commit'
[main (root-commit) 1b638ae] First Commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
 create mode 100644 myself.txt

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git stautus
git: 'stautus' is not a git command. See 'git --help'.

The most similar command is
        status

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git add .

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git commit -m 'Second Commit'
[main 018691b] Second Commit
 1 file changed, 17 insertions(+)

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ git commit -m 'Second Commit html structure'
On branch main
nothing to commit, working tree clean

m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$ cat index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gitTutorial</title>
</head>
<body>
    <header>
        <h1>
            <p>Lost in Translation</p>
        </h1>
    </header>

</body>
</html>
m_top@Matt-MSI MINGW64 ~/Documents/gitTutorial (main)
$
