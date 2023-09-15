# GitHub Alpine NodeJS

[![Actions Status](https://github.com/actions/alpine_nodejs/workflows/Build%20Alpine%20Node.js/badge.svg)](https://github.com/actions/alpine_nodejs/actions)

The Alpine NodeJS repo houses a redistribution of NodeJS builds that are used within the [GitHub Actions Runner](https://github.com/actions/runner/blob/main/src/Misc/externals.sh).

## Getting Started
The [workflow](https://github.com/actions/alpine_nodejs/actions/workflows/docker-image.yml) in this repository can compile a partial-static node.js for alpine and create a [GitHub release](https://github.com/actions/alpine_nodejs/releases) for it.

- Queue workflow using `workflow_dispatch` trigger and set the `node` version you want to compile as input, ex: `v12.22.7`
![queue workflow](./res/queueWorkflow.png)

- Wait for the run to complete
![succeed run](./res/succeedRun.png)

- There should be a newly created release that matches the version you want for `node`, and it is able to run on alpine.
![new release](./res/createdRelease.png)

