# class-activity

## git commands along with output

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

git add .
git commit -m "Initial project scaffolding"
git push -u origin amna
