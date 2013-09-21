# Utils
Here are some utilities I wrote.
You may find them usefull, you may not.

## `git-gc`
`git-gc` runs `git gc --aggressive` on all Git repositories given as arguments.

His friend, `git-gc-recursive`, uses `locate` to run `git-gc` on all Git repositories under a given prefix.

They both handle evil, evil directory names.
