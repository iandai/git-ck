# git-ck

Use git diff and git checkout to a file with a long path is sometimes time consuming. git-ck is created to simply this process.


### Install

OSX One-liner:

```bash
$ (cd /tmp && git clone https://github.com/iandai/git-ck.git && cd git-ck && sudo cp bin/git-ck /usr/bin/)
```


### Usage
s                   Show result of git status -s.  
diff [<number>]     Show result of git diff of the files.  
ck [<number>]       Checkout the file.  
exit                Exit.  
h                   Help.  
