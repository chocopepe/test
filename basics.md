## Clone
Cloning a remote repo named 'test' down to your local repo named 'repo'.
```
$ pwd
/Users/monyohm
$ mkdir repo
$ cd repo
$ git clone https://github.com/chocopepe/test.git
Cloning into 'test'...
remote: Counting objects: 89, done.
remote: Compressing objects: 100% (70/70), done.
remote: Total 89 (delta 16), reused 12 (delta 1)
Unpacking objects: 100% (89/89), done.
Checking connectivity... done.
$ ls                # Now 'repo' directory has a cloned 'test' directory.
test
```
Checking the cloned repo.
```
$ pwd
/Users/monyohm/repo/test
$ ls -a
.    ..    .DS_Store    .git    README.md
```
Editting that.



