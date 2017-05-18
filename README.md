# phase-0-gps-1

devbootcamp :> mkdir phase-0-gps-1 #create gps directory

devbootcamp :> cd phase-9-gps-1 #error
-bash: cd: phase-9-gps-1: No such file or directory

devbootcamp :> cd phase-0-gps-1 #navigate to gps directory

phase-0-gps-1 :> ls #list directories 

phase-0-gps-1 :> git clone https://github.com/peanutenthusiast/phase-0-gps-1
Cloning into 'phase-0-gps-1'... #clone directories
























GIT-CHECKOUT(1)                   Git Manual                   GIT-CHECKOUT(1)

NAME
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.

phase-0-gps-1 :> touch awesome_page.md create awesome_page markdown

phase-0-gps-1 :> git push origin master update Github repository
fatal: Not a git repository (or any of the parent directories): .git

phase-0-gps-1 :> ls list content
awesome_page.md phase-0-gps-1

phase-0-gps-1 :> cd phase-0-gps-1 

phase-0-gps-1 (master) :> touch awesome_page.md

phase-0-gps-1 (master) :> git push origin master update Github repository
Everything up-to-date

phase-0-gps-1 (master) :> git checkout -b add-command-log create new branch
Switched to a new branch 'add-command-log'

phase-0-gps-1 (add-command-log) :> git checkout --help check for command syntax/explanation

phase-0-gps-1 (add-command-log) :> ls
LICENSE         README.md       awesome_page.md

phase-0-gps-1 (add-command-log) :> git
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

phase-0-gps-1 (add-command-log) :> subl README.md open readme.md in sublime

phase-0-gps-1 (add-command-log) :>