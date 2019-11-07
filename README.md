# This is gonna be my Git cheat-sheet for now

# Mask/unmask changes:
#   this is how it used to be:
- `git update-index --assume-unchanged <file>`
- `git update-index --no-assume-unchanged <file>`
#   but later on:
- `git update-index --skip-worktree …`
# "assume" is said to be for large files so Git won't check
# them for changes. Also, on theirs every change in upstream they
# will be tracked again (which might be good but not always).

# change current branch w/o checkout:
- `git symbolic-ref HEAD refs/heads/otherbranch`
