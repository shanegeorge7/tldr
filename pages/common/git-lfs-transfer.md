# git-lfs-transfer

> Transfer Git LFS objects between repositories.
> A Charm tool for managing Git Large File Storage transfers.
> More information: <https://github.com/charmbracelet/git-lfs-transfer>.

- Transfer LFS objects from source to destination repository:

`git-lfs-transfer {{source_repo}} {{destination_repo}}`

- Transfer specific LFS objects by ref:

`git-lfs-transfer {{source_repo}} {{destination_repo}} --ref {{branch_name}}`

- Display version information:

`git-lfs-transfer --version`

- Display help:

`git-lfs-transfer --help`
