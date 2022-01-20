# Git REBASE example

Do:

1. Create a new branch and work on it
2. Do a rebase interactive from root (man git-rebase)
3. Do the next tasks:
   1. discard revert and reverted commit
   2. squash add forgotten main with previous module_a commit
   3. rewrite add_module_c commit follow conventional commit
4. End the rebase

After rebase only six commits must appear in your branch.

To restart your branch do:

    git reset --hard origin/master

