1.git version 2.37.3.windows.1
2.diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Your name
user.email=bc185420@ohio.edu
user.name=Bradley
PS C:\Users\bcamp\git-lab>
3.It took me to a website file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-add.html
4.On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md
5.a new file named README.md was added and turned green.
6.a new file named answers.md was added and turned green.
7.On branch master
nothing to commit, working tree clean
8.commit 4acdc88c4ebe8af672d2801b1e7e3bd2e260cd67 (HEAD -> master)
Author: Bradley <bc185420@ohio.edu>
Date:   Fri Sep 9 20:27:25 2022 -0400

    Initial commit
9.I see README.md and answers.md
10.No the changes you made online reflected in your local copy.
11.It gave me an error
12.Yes changes were made to my local copy.
13.Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible matches include:
-Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4
+ ls -a
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand
