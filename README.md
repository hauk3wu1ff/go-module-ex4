# go-module-ex4
go module for exercise 4

# Steps to create module for exercise
```
>:~/repos/udemy$ git clone https://github.com/hauk3wu1ff/go-module-ex4.git
Cloning into 'go-module-ex4'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (5/5), done.
>:~/repos/udemy$ cd go-module-ex4
>:~/repos/udemy/go-module-ex4$ mkdir quotes
>:~/repos/udemy/go-module-ex4$ go mod init github.com/hauk3wu1ff/go-module-ex4
go: creating new go.mod: module github.com/hauk3wu1ff/go-module-ex4
>:~/repos/udemy/go-module-ex4$ vi quotes/quotes.go 
>:~/repos/udemy/go-module-ex4$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        go.mod
        quotes/

no changes added to commit (use "git add" and/or "git commit -a")
>:~/repos/udemy/go-module-ex4$ cat go.mod 
module github.com/hauk3wu1ff/go-module-ex4

go 1.14
>:~/repos/udemy/go-module-ex4$ git add -A
>:~/repos/udemy/go-module-ex4$ git commit -m "Module for exercise 4 complete" 
[main 60ccc5e] Module for exercise 4 complete
 3 files changed, 26 insertions(+), 2 deletions(-)
 rewrite README.md (61%)
>:~/repos/udemy/go-module-ex4$# push only one tag to git
>:~/repos/udemy/go-module-ex4$git push origin v0.1.0
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/hauk3wu1ff/go-module-ex4.git
 * [new tag]         v0.1.0 -> v0.1.0

```
