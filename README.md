# GitHub Alpine NodeJS

[![Actions Status](https://github.com/actions/alpine_nodejs/workflows/Build%20Alpine%20Node.js/badge.svg)](https://github.com/actions/alpine_nodejs/actions)

The Alpine NodeJS repo houses a redistribution of NodeJS builds that are used within the [GitHub Actions Runner](https://github.com/actions/runner/blob/main/src/Misc/externals.sh).

### Note

Thank you for your interest in this GitHub action, however, right now we are not taking contributions. Add commentMore actions

We continue to focus our resources on strategic areas that help our customers be successful while making developers' lives easier. While GitHub Actions remains a key part of this vision, we are allocating resources towards other areas of Actions and are not taking contributions to this repository at this time. The GitHub public roadmap is the best place to follow along for any updates on features we’re working on and what stage they’re in.

We are taking the following steps to better direct requests related to GitHub Actions, including:

1. We will be directing questions and support requests to our [Community Discussions area](https://github.com/orgs/community/discussions/categories/actions)

2. High Priority bugs can be reported through Community Discussions or you can report these to our support team https://support.github.com/contact/bug-report.

3. Security Issues should be handled as per our [security.md](security.md)

We will still provide security updates for this project and fix major breaking changes during this time.

You are welcome to still raise bugs in this repo.

## Getting Started
The [workflow](https://github.com/actions/alpine_nodejs/actions/workflows/docker-image.yml) in this repository can compile a partial-static node.js for alpine and create a [GitHub release](https://github.com/actions/alpine_nodejs/releases) for it.

- Queue workflow using `workflow_dispatch` trigger and set the `node` version you want to compile as input, ex: `v12.22.7`
![queue workflow](./res/queueWorkflow.png)

- Wait for the run to complete
![succeed run](./res/succeedRun.png)

- There should be a newly created release that matches the version you want for `node`, and it is able to run on alpine.
![new release](./res/createdRelease.png)

