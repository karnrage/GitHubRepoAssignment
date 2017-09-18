Microsoft Windows [Version 6.3.9600]
(c) 2013 Microsoft Corporation. All rights reserved.

C:\Users\kkps>dir
 Volume in drive C is Windows
 Volume Serial Number is 4045-B750

 Directory of C:\Users\kkps

09/18/2017  05:07 PM    <DIR>          .
09/18/2017  05:07 PM    <DIR>          ..
03/14/2016  08:42 PM    <DIR>          .android
03/06/2016  02:10 AM    <DIR>          .AndroidStudio1.5
09/04/2017  06:26 PM             1,524 .bash_history
09/12/2015  05:10 PM             2,507 .enstaller4rc
09/18/2017  04:59 PM               158 .gitconfig
09/08/2015  09:53 PM    <DIR>          .ipython
09/19/2015  05:03 PM    <DIR>          .matplotlib
09/18/2017  11:09 AM                 0 .node_repl_history
01/22/2016  11:54 PM    <DIR>          .oracle_jre_usage
09/01/2017  05:02 PM    <DIR>          .rssowl2
09/04/2017  05:53 PM    <DIR>          .ssh
08/14/2017  04:38 PM             1,180 .viminfo
08/14/2017  09:59 AM    <DIR>          .vscode
09/08/2015  09:52 PM    <DIR>          Canopy
07/29/2017  02:18 PM    <DIR>          Contacts
03/26/2017  03:51 PM                 0 delete this
09/18/2017  05:59 PM    <DIR>          Desktop
09/16/2017  12:59 PM    <DIR>          Documents
09/18/2017  11:45 AM    <DIR>          Downloads
07/29/2017  02:18 PM    <DIR>          Favorites
07/29/2017  02:18 PM    <DIR>          Links
09/04/2017  06:25 PM    <DIR>          Music
09/08/2015  10:10 PM    <DIR>          newest directory
09/18/2017  05:17 PM    <DIR>          new_project
09/16/2017  01:07 PM    <DIR>          OneDrive
07/29/2017  02:18 PM    <DIR>          Pictures
07/29/2017  02:18 PM    <DIR>          Saved Games
07/29/2017  02:18 PM    <DIR>          Searches
10/12/2016  08:12 PM                 0 Sti_Trace.log
11/23/2016  10:01 AM    <DIR>          Tracing
08/18/2017  02:18 PM    <DIR>          Videos
               7 File(s)          5,369 bytes
              26 Dir(s)  159,714,263,040 bytes free

C:\Users\kkps>cd desktop

C:\Users\kkps\Desktop>mkdir GitHubRepoAssignment

C:\Users\kkps\Desktop>cd GitHubRepoAssignment

C:\Users\kkps\Desktop\GitHubRepoAssignment>git init
Initialized empty Git repository in C:/Users/kkps/Desktop/GitHubRepoAssignment/.
git/

C:\Users\kkps\Desktop\GitHubRepoAssignment>copy nul readme.md
        1 file(s) copied.

C:\Users\kkps\Desktop\GitHubRepoAssignment>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.md

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\kkps\Desktop\GitHubRepoAssignment>git add .

C:\Users\kkps\Desktop\GitHubRepoAssignment>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.md


C:\Users\kkps\Desktop\GitHubRepoAssignment>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   readme.md


C:\Users\kkps\Desktop\GitHubRepoAssignment>git commit -m "added copy/paste of co
mmand prompt with steps to complete assignenment"
[master (root-commit) cd8aafc] added copy/paste of command prompt with steps to
complete assignenment
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md

C:\Users\kkps\Desktop\GitHubRepoAssignment>