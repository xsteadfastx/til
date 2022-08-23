# Clone to worktree

Git branches is like an antipattern.
Its best to use `git worktree` to have already checked out git branches.

## Cloning

    git clone https://git.xsfx.dev/xsteadfastx/til.git til/main

This will create the directory `til` and clones the branch `main` into it.

## Create new worktree

    cd til/main
    git worktree add ../foo main

This will create the worktree `foo` in `til/foo`.
