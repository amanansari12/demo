"This is project 1"

"The Output for the task 2"
4dd4051 (HEAD -> master) Initial commit: add README

## For Task 3

1. "Output of  git status"

'''
    On branch master
    Changes to be committed:
    (use "git restore --staged <file>..." to unstage)
            modified:   README.md
'''

2. "Output of git diff"
'''
    diff --git a/README.md b/README.md
    index a223efc..298f15b 100644
    --- a/README.md
    +++ b/README.md
    @@ -1 +1,6 @@
    -"This is project 1"
    +"This is project 1"
    +
    +"The Output for the task 2"
    +4dd4051 (HEAD -> master) Initial commit: add README
    +
    +
'''

3. Output for "git diff --staged"

'''
diff --git a/README.md b/README.md
index a223efc..298f15b 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,6 @@
-"This is project 1"
+"This is project 1"
+
+"The Output for the task 2"
+4dd4051 (HEAD -> master) Initial commit: add README
+
+
'''

4. Output  for the "final commit hash"

'''
397ee47 (HEAD -> master) Add new section to README
4dd4051 Initial commit: add README
'''

### Task 4

1. output for git branch

'''
* feature-x
  master
'''

2. Output for "git log --oneline --graph --decorate --all"

'''
* 401e536 (HEAD -> feature-x) Add feature.txt
* 397ee47 (master) Add new section to README
* 4dd4051 Initial commit: add README
'''

### Task 5

1. Output for git status

On branch master
nothing to commit, working tree clean

2. output for 'git log --oneline --graph'

* aaa4acb (HEAD -> master, feature-x, conflict-branch) Main change to README
* 401e536 Add feature.txt
* 397ee47 Add new section to README
* 4dd4051 Initial commit: add README