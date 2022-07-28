Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~
$ mkdir git-basic

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~
$ cd git-basic

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic
$ touch first.txt

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic
$ git init .
Initialized empty Git repository in C:/Users/Lenovo Ideapad 320/git-basic/.git/

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ git add .

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ git commit -m "adding first.txt"
[master (root-commit) 392733f] adding first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 first.txt

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ git log
commit 392733fed7422bfbdb354817bae88dc7b1225d2e (HEAD -> master)
Author: haikalganteng <haikalganteng123@gmail.com>
Date:   Thu Jul 28 08:42:04 2022 +0700

    adding first.txt

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ touch second.txt

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ git add second.txt

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ git commit -m "adding second.txt"
[master d2cf056] adding second.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 second.txt

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ rm first.txt

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ git add .

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ git commit -m "removing first.txt"
[master 905a6f5] removing first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 first.txt

Lenovo Ideapad 320@DESKTOP-E6G4S2P MINGW32 ~/git-basic (master)
$ git log
commit 905a6f5388a7f62d6fc42039d8791546e349bf21 (HEAD -> master)
Author: haikalganteng <haikalganteng123@gmail.com>
Date:   Thu Jul 28 08:46:44 2022 +0700

    removing first.txt

commit d2cf056d7762d6df644f25116588643548e9da52
Author: haikalganteng <haikalganteng123@gmail.com>
Date:   Thu Jul 28 08:45:04 2022 +0700

    adding second.txt

commit 392733fed7422bfbdb354817bae88dc7b1225d2e
Author: haikalganteng <haikalganteng123@gmail.com>
Date:   Thu Jul 28 08:42:04 2022 +0700

    adding first.txt

