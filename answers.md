1) git --version
    git version 2.39.5 (Apple Git-154)
2) git config --list
    credential.helper=osxkeychain
init.defaultbranch=main
user.name=JayantJayakumar
user.email=jj483124@ohio.edu
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
3) git --help?
    it provided all the common Git commands used in various situations
4) git status (Before adding README.md and answer.md)
    No commits yet

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
            README.md
            answers.md
5) git status (after adding README.md)
    On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
6) git status (after adding answer.md)
    No commits yet

    Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
            new file:   README.md
            new file:   answers.md
7) git status (after using "Initial commit")
    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
            modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")
