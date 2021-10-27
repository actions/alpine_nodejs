# alpine_nodejs

[GitHub Actions Runner](https://github.com/actions/runner/blob/main/src/Misc/externals.sh) download alpine node.js from https://vstsagenttools.blob.core.windows.net/tools/nodejs

The [workflow](https://github.com/TingluoHuang/alpine_nodejs/actions/workflows/docker-image.yml) in this repository can compile a partial-static node.js for alpine and create a [GitHub release](https://github.com/TingluoHuang/alpine_nodejs/releases) for it.

Follow instruction on https://dev.azure.com/mseng/AzureDevOps/_git/CIPlat.Externals to upload the compiled alpine node.js into https://vstsagenttools.blob.core.windows.net/tools/nodejs
