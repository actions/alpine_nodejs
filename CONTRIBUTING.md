# Contributing

## Submitting a pull request

1. Fork and clone the repository
1. Create a new branch: `git checkout -b my-branch-name`
1. Push to your fork and submit a pull request
1. Pat yourself on the back and wait for your pull request to be reviewed and merged

## Tips for working this repository:  
> - The repository is huge right now, you don't want to waste your time and disk space to get those unrelated files.
>   - Ignore LFS files during initial `git clone` the repo with `GIT_LFS_SKIP_SMUDGE=1 git clone https://mseng@dev.azure.com/mseng/AzureDevOps/_git/CIPlat.Externals`
>   - Ignore LFS files during any `git checkout` or `git fetch` operation with `GIT_LFS_SKIP_SMUDGE=1`.
>   - You do want the LFS smudge filter to run during `git add` and `git push`, make sure you don't have `GIT_LFS_SKIP_SMUDGE=1` when you run `git add` and `git push`.
> - More `Git-LFS` doc is at https://github.com/git-lfs/git-lfs/tree/main/docs

Thanks! :heart: :heart: :heart:

GitHub Actions Team :octocat:
