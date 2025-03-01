# Getting started

The term for automatically testing, building, and deploying your project is Continuous Integration, or CI for short.

The configuration for CI, we commonly call a CI-workflow.

To get started creating your workflow, you need 3 things:

- A Unity project
- A Git host (GitHub, GitLab, your private server, etc.)
- A CI system (GitHub Actions, GitLab pipelines, CircleCI, TravisCI, Jenkins, etc.)

## Preparing the project

**Create a repository** on your chosen Git host and follow their instructions to commit and push your project.

Be sure to **ignore any automatically generated files**, by adding the reference [.gitignore](https://github.com/github/gitignore/blob/master/Unity.gitignore) file to the root of your project.

To **ensure large files are handled correctly** (in [LFS](https://git-lfs.github.com/)), you can add our reference [.gitattributes](https://gist.github.com/webbertakken/ff250a0d5e59a8aae961c2e509c07fbc) file to the root of your project.

You are now **ready** to create a workflow! Choose the CI system you chose in the menu on the left.
