# class-activity

## Git Commands Along with Output

Below are the Git commands used for setting up the project along with their outputs:

```bash
Spectre@DESKTOP-U9979GL MINGW64 /d
$ git clone https://github.com/amnasalahudin/class-activity.git
Cloning into 'class-activity'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Spectre@DESKTOP-U9979GL MINGW64 /d
$ cd class-activity/

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (main)
$ git checkout -b dev
Switched to a new branch 'dev'

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (dev)
$ git push -u origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/amnasalahudin/class-activity/pull/new/dev
remote:
To https://github.com/amnasalahudin/class-activity.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (dev)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (main)
$ git checkout -b test
Switched to a new branch 'test'

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (test)
$ git push -u origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/amnasalahudin/class-activity/pull/new/test
remote:
To https://github.com/amnasalahudin/class-activity.git
 * [new branch]      test -> test
branch 'test' set up to track 'origin/test'.

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (test)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (main)
$ git checkout -b amna
Switched to a new branch 'amna'

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (amna)
$ git push -u origin amna
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'amna' on GitHub by visiting:
remote:      https://github.com/amnasalahudin/class-activity/pull/new/amna
remote:
To https://github.com/amnasalahudin/class-activity.git
 * [new branch]      amna -> amna
branch 'amna' set up to track 'origin/amna'.

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (amna)
$ git add .
warning: in the working copy of 'README.md', CRLF will be replaced by LF the next time Git touches it

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (amna)
$ git commit -m "Initial project scaffolding"
[amna c3f7f14] Initial project scaffolding
 5 files changed, 73 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 python-project/__init__.py
 create mode 100644 python-project/main.py
 create mode 100644 requirements.txt

Spectre@DESKTOP-U9979GL MINGW64 /d/class-activity (amna)
$ git push -u origin amna
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 983 bytes | 491.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/amnasalahudin/class-activity.git
   a8d8edb..c3f7f14  amna -> amna
branch 'amna' set up to track 'origin/amna'.
